# Header Text in New Button Callout
#### Description
#### Before
![Before - Header Text in New Button Callout](NewButtonCalloutHeaderText-Before.PNG)
#### After
![After - Header Text in New Button Callout](NewButtonCalloutHeaderText-After.PNG)
#### Snippet
```css
h2[id^="cojs-newdocWOPI"].js-callout-title {
	visibility: hidden;
}

h2[id^="cojs-newdocWOPI"].js-callout-title:after {
	content: "Create a new folder";
	visibility: visible;
	position: absolute;
    left: 0;
    margin-left: 20px;
}
```
#### Applies To
SharePoint Online