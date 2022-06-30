# Chapters 3 and 4
1. There are three main types of lists in HTML: ordered, unordered, and definition. What are their differences?
Ordered lists are numbered lists.
Unordered lists are bulleted lists.
Definition lists are used to define terms.  Terms are listed out and below each term/terms is a definition/s.
2. What is the basic structure of an element used to link to another website?
The <a> tag with and href attribute is used to link out to another website.  An example would be <a href="www.google.com">Google</a>
3. What attribute should you include in a link to open a new tab when the link is clicked?
To open a new tab, use the attribute target="_blank" after the href attribute, separated by a space.
4. How do you link to a specific part of the same page?
To link to a specific part of a page, do two things: (1) add an id attribute to the tag you want to link to, for example: id="top".  (2) The link the user will click on will use the <a> tag with the same href attribute, using a #.  For example <a href="#top">Top</a>

#Codepen
https://codepen.io/logkatwya3/pen/oNqNwdK

Two lists: ordered and unordered.
A link to your GitHub account.
A link to the Turing website.

# Chapters 10, 11, 12:

1. What is the purpose of CSS?
CSS allows a user to create rules to describe how a page should look.  It allows the user to make the page more interesting by adding colors, styles and padding rules that in turn will make it look nicer and more appealing.
2. What does CSS stand for? What does cascading mean in this case?
CSS = Cascading Style Sheets.  Most rules will apply to elements on the page.  However, you can override individual elements if you don't want the style applied to all elements the same way.  
3. What is the basic structure of a CSS rule?
The basic structure includes a Selector and a declartion.  The Selector applies to the html element.  The Declarion is made up of a Property and Value.  The Property indicates the what you want to change on the element.  The Value is what you want the Element to change to, for example the color yellow. An example is: h1 { color: yellow;}
4. How do you link a CSS stylesheet to your HTML document?
Within the <head> tag add an empty <link> tag.  It should consist of three attributes: href with a path to the css file, type with a value of text/css, and rel which specifies the link between an HTML doc and css doc.  <link href="css/styles.css" type="text/css" rel="stylesheet" />
5. When is it useful to use external stylesheets as opposed to using internal CSS?
It is useful to use an external stylesheet when making more than one page on a website.
6. Describe what a color hex code is.
Hex codes represent a color made up of red, blue and green, made up of 6 digits and preceded by a hashtag.  #ee3e80
7. What are the three parts of an HSL color property?
Hue, Saturation and Lightness.  Hue is a color circle represented by an angle between 0-360 degrees. Saturation is the amount of grey in a color.  Lightness is the amount of white or black in a color.  
8. In the world of typeface, what are the three main categories of fonts? What are the differences between them?
Serif: serif fonts have extra details on the end of letters, making it easier to read for long passages.
Sans-serif:  sans-serif have straight ends to the letters, making for a clean look.
Monospace: monospace letters have a fixed width, and are commonly used for code because it makes alignment easier.
9. When specifying font-size, what are the main three units used?
Pixels: the most common and flexible method.  The number of pixels is followed by px.
Percentages: The default size of text in a browser is 16px.  If using percentage for font-size, 75% would be 12px.
EMS: An em is equivalent to the width of the letter m.

#Codepen
https://codepen.io/logkatwya3/pen/oNqNwdK

Add a color to the text of all of your headings (using hex codes).
For your h1 heading, add a background color.
Make your headings a serif font, and make the paragraph text a sans-serif font.
Change a snippet of paragraph text to be italic using the font-style property (do not use the <i></i> in this case).
