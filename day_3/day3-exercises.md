# Chapter 7
1. If you're using an input element in a form, what attribute controls the behavior of that input?
The Type attribute controls the behavior, example: type="text" or type="password" or type="checkbox"
2. What element is used to create a dropdown list?
The <select> element.  
3. If you're using an input element to send form data to a server, what should the type attribute be set to?
The name and the value attribute should be set to send the name/value pair to the server.
4. What element is used to group similar form items together?
The <fieldset> element.

#Codepen:
https://codepen.io/logkatwya3/pen/oNqNwdK

Text boxes for each artist (three artists total).
Labels for each text box.
Dropdowns for the genre of each artist.
Submit button.

#Chapter 13 and 15

1. Describe the differences between border, margin, and padding.
Border: a border separates one box from another.  Borders are always there, even if you can't see them.
Margin: is the spacing outside of borders lines.  Increasing margins increases the space between two border boxes.
Padding: is the spacing between the content within a box and it's border.  Increasing the padding can make the text easier to read.
2. For a CSS rule padding: 1px 2px 5px 10px, what sides of the content box does each pixel value correspond to?
Clockwise from the top: top, right, bottom, left
3. Describe the difference between block-level and inline elements.
Inline elements flow horizontally between surrounding text (examples: img, b, i).  Block-level boxes start on a new line (examples: h1, p, ul, li).
4. What is the role of fixed positioning, and why is z-index important in the scenario of using fixed positioning?
Fixed positioning sets an element to an absolute fixed position.  It positions the element in relation to the browser window.  For example, a heading may have a fixed position, which allows the paragraph text to flow behind it as the user scrolls.  Note: the user will have to adjust the positioning of the paragraph text once the header is given a fixed position, because it no longer responds to the position of the paragraph text, but is no fixed based off the browser.  When using fixed positioning (and absolute and relative) boxes can overlap.  The z-index sets what boxes should be in the forefront using a number.  The higher the number, the closer that element is to the forefront.
5. What is the difference between a fixed and liquid layout?
Fixed layouts do not change size as the user changes the browser/device size.  They tend to use pixels in this layout design.  
Liquid layout expands and contracts if the browser/device size changes.  The tend to use percentages in this layout.  

#CodePen
https://codepen.io/logkatwya3/pen/oNqNwdK

Add a border and background color to your headings. Pay attention to the contrast between the text and background colors.
Divide your paragraph text into two vertical columns.
