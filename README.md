# HTML_CSS_Targeted_CSS
### Learner Instructions
Goal
Create a menu that will render a menu for the Little Lemon restaurant with the help of the styling that you will add for the HTML page provided.

Objectives
Add styling to the CSS page with the help of different combinator selectors along with other CSS rules you have leared so far.

While reviewing the code, note the following:

For div elements that follow the h3 element, the child combinator is defined as div > h3

For elements using the CSS class low that follow the label CSS class, the adjacent sibling combinator is defined as .label + .low

For div elements that follow other div elements, the general sibling combinator is defined as div ~ div



**Step 1:**  Add padding of 10px to the section class

```
.section {
	padding: 10px;
}
```

**Step 2:**  Change the weight of the font to bold for the label class

```
.label {  
	font-weight: bold;
}
```

**Step 3:**  For the description class, change styling of the font to italics.

```
.description {
    font-style: italic;
}
```

**Step 4:**  Additionally add a border on the top side of 2px that is solid and has a color code of '#495E57'

```
border-top: 2px solid #495E57;
```

**Step 5:**  In the class item-name, change the margin to 25 pixels and font-size to 12 pixels.

```
.item-name {
	margin: 25px;
	font-size: 12px;
}
```

**Step 6:**  Float the contents of the element b to the right.

```
b {
    float: right;
}
```

**Step 7:**  Add a margin to the top of -15px.

```
margin-top: -15px; /* Inside b */
```

**Step 8:**  Change the color of the element to darkcyan
```
color: darkcyan; /* Inside b */
```

**Step 9:**  Add a child combinator for h3 tags that follow the div tag and assign them rules as follows:

**Step 9.a** change the font size as well as margin to 20px
```
div > h3 {
    font-size: 20px;
    margin: 20px;
}
```

**Step 9.b:**  Change the alignment of text to center
```
    text-align: center;
```

**Step 9.c:**  Assign it a color code of '#495E57'

```
    color: #495E57;
```

**Step 10:**  Add an adjacent sibling combinator for items of class low that follow class label and change their color to brown

```
.label + .low {
  color: brown; 
}
```

**Step 11:**  Add a general sibling combinator for div tags that follow other div tags and change their color to RGB values of 90,90,90.

```
div ~ div {
  color: rgb(90, 90, 90);
}
```
