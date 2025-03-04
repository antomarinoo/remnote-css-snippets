# remnote-css-snippets
A collection of my favourite css snippets for RemNote.

## Cloze gray background and remove bottom underline
```
/* Cloze gray background and remove bottom underline */

.cloze {
    background-color: #E6EAEE !important;
    border-color: gray !important;
    padding: 1px 7px;
    text-decoration: none;
    border-radius: 4px;
    border: none !important;
    color: black !important;
}
```
## Underlined blue cloze
```
/* Underlined blue cloze */

.cloze {
    background-color: transparent !important;
    padding: 0px 0px;
    text-decoration: none;
    border-radius: 0px;
    border-bottom: 2px; !important;
    border-color: blue !important;
    font-weight: 400 !important;
    color: blue !important;
}
```
## Default content zoom 
```
/* Default content zoom */
#content {
  zoom: 90%;
}
```
## Smaller and thinner headings
```
/* Smaller and thinner headings */
.rem-text.rem-header--1 {
	font-size: 22px;
	font-weight: 600;
}

.rem-text.rem-header--2 {

	font-size: 20px;
	font-weight: 500;
}

.rem-text.rem-header--3 {
	font-size: 18px;
	font-weight: 500;
}
```
