# 100 Days Of Frontend Interview Questions

This repo will contain 500 frontend interview questions which will have HTML, CSS, Javascript & React questions. I will add not any problems or long questions for now, just theory questions.

I will add 5 questions a day in this repo till day 100 days and after this, I am also planning to do 100 days of javascript questions too.

If you want to see the 5 questions daily in your social media feed, connect with me on [Twitter](https://twitter.com/saran_pariyar1) and [LinkedIn](https://www.linkedin.com/in/saran-pariyar-5078b5217/) cause I will be posting them on my social media accounts too.

<b>I've also added some tables, no need to memorize them, just take a look at them once a day or few times and you'll able to understand those concepts easily</b>

`Source of the questions: Google, ChatGPT, Github repos, etc`

---

## Tables of content

| Techs      | No. of Questions |  Range  |
| ---------- | :--------------: | :-----: |
| HTML       |        50        |  0-50   |
| CSS        |       100        | 51-150  |
| Javascript |       200        | 151-350 |
| React      |       150        | 351-500 |

## <br />

# HTML

## Day 1

1. ### What is HTML and what are it's basic components?

   HTML (Hyper Text Markup Language) is the standard markup language for creating web pages. It's basics components includes element, tags and attribute.

2. ### What is the purpose of Doctype in HTML?

   The Doctype declaration specifies the type of document being used and tell the web browser how to interpret the pages content. It is located at the top of the HTML document.

3. ### What is semantic HTML?

   Semantic HTML uses specific HTML elements to provide additional information about the structure and content of the page, making it more accessible and easy to read.

4. ### What are different types of list in HTML?

   There are 3 types of list in HTML. They are Ordered list, unordered list and definition list.

5. ### What is the difference between div element and span element?
   The div element is a block-level element that is used to group and organize other HTML elements while span element is an inline-element that is used to apply style or attribute to a specific part of a block-level element.

## Day 2

6. ### What is the difference between \<b> and \<strong> tags in HTML?

   The \<B> tag is used to apply bold formatting to text, while the \<strong> tag is used to indicate that the text is important and carries stronger semantic meaning than \<b>.

7. ### What are the different types of input field in HTML?

   There are several types of input field in HTML including text, password, checkbox, radio, button, submit, file and reset.

8. ### What is the difference between a GET request and POST request?

   The GET request is used to retrieve data from a web server, while a POST request is used to submit data to a web server. GET requests are less secure and have limit on the amount of data that can be sent while POST request have no limit and are more secure.

9. ### How do you create a hyperlink in HTML?

   Hyperlinks are created using \<a>(anchor) tag, which contains the URL of the link and the text to be displayed.

10. ### What is the purpose of the alt attribute in HTML?
    The alt attribute is used to provide a text description of an image for users who are unable in to see the image, such as those who use screen readers.

## Day 3

11. ### What are void elements in HTML?

    Void elements are those elements in HTML which do not have closing tag or do not need to be closed. Example: \<br />, \<img />, etc.

12. ### Can we display web page inside a webpage or is nesting of webpage possible?

    Yes, we can display a web page inside another HTML web page. HTML provides \<iframe> tag using which we can achieve this functionality.

13. ### What is the difference between \<link> tag and \<a> tag?

    The anchor tag \<a> is used to create a hyperlink to another web page or to a certain part of a web page and these links are clickable, whereas, link tag \<link> defines a link between a document and external resource and these are not clickable.

14. ### What are some of the advantages of HTML5 over its previous versions?

    Some advantages of HTML5 are:

    1. It has multi media support
    2. Improved performance (faster loading)
    3. Better accessibility

15. ### What is the canvas element in HTML5?
    The \<canvas> element is a container that is used to draw graphics on the web page using scripting language like javascript.

## Day 4

16. ### What is an HTML form?

    HTML form is a section of a web page that allows users to input and submit data to the server.

17. ### What is the difference between HTML form's "action" and "method" attributes?

    The "action" attribute specifies the URL to which the form data is submitted, while the "method" attribute specifies the HTTP method when submitting the form data(either "GET" or "POST").

18. ### What would happen if there is no text between the HTML tags?

    There would be nothing to format if there is not text present between the tags. Therefore, nothing will appear on the screen. Tags without closing tag like \<img> do not require any text between them.

19. ### What is the purpose of \<head> tag?

    The \<head> tag in HTML is used to provide metadata about document, such as title of page, links and other information that is not directly displayed on the web page. This information is used by browser and search engine to understand the content and structure of the web page.

20. ### What is the purpose of the \<meta> tag in HTML?
    The \<meta> tag is used to provide additional information about the webpage, such as author, keywords, description which is used by search engines to understand the content of the page.

## Day 5

21. ### What is the purpose of the \<script> tag in HTML?

    The \<script> tag is either used to embed client-side script(Javascript), or it points to an external script file through the src attribute.

22. ### What is the purpose of the viewport meta tag?

    Viewport meta tag lets us control the width and scaling of the viewport so that it's sized correctly on all devices.

23. ### What is the purpose of the \<noscript> tag in HTML?

    The \<noscript> tag in used to display text for those browsers which does not support script tag or the browser disabled the script by user.

24. ### What is the purpose of the \<fieldset> tag in HTML?

    Fieldset is used to group related elements in a form. The \<fieldset> tag draws a box around the related elements.

25. ### what is the difference between HTML tag and HTML element?
    HTML tag is just opening or closing entity. For example \<p> and \</p> are called HTML tags. <br />
    HTML element consists of opening tag, closing tag and content(optional for content-less tags). For example: \<p> This is the content \</p>, this complete thing is called HTML element.

## Day 6

26. ### How do you change the color of bullets?

    The color of the bullet is always the color of the first text of the list. So, if we can change the color of the bullets by changing the color of the text.

27. ### What will happen if we don't put \<!Doctype HTML> tag?

    If we don't put \<!Doctype HTML> tag, the browser will not be able to identify that it is an HTML document and HTML5 tags will not function properly.

28. ### What is HTML5 web storage?

    HTML5 Web Storage is a mechanism in modern web browsers that allows web applications to store data locally within the user's browser. It provides two storage options: Local Storage and Session Storage.

29. ### What is the use of "target" attribute in HTML?

    The "target" attribute is used to specify where to open the linked document when the user clicks on the hyperlink.

30. ### What is the use of "em" tag?
    The "em" tag is a semantic tag which is used to apply emphasis to a word or phrase within a paragraph. <br />
    Example: The sentence "I really enjoyed cycling" could be written using the "em" tag to emphasize the word "really": "I \<em>really \</em> enjoyed the concert last night."

## Day 7

31. ### What is the purpose of \<header> tag?

    The \<header> tag is used to defined the header section of a webpage which includes site logo, navigation menu, and other introductory content.

32. ### What is the purpose of \<nav> tag?

    The \<nav> tag used to define a section of a webpage that contains links to other pages or sections of the current page.

33. ### What is the purpose of \<main> tag?

    The \<main> tag is used to define the main content of a webpage, where the most important information is displayed.

34. ### What is the purpose of \<article> tag?

    The \<article> tag is used to define a self-contained piece of content, such as a blog post, news article, or product review.

35. ### What is the purpose of \<section> tag?
    The \<section> tag is used to group together related content and can be thought of as a container for content.

## Day 8

36. ### What is the purpose of \<aside> tag?

    The \<aside> tag is used to define content that is related to the main content of a webpage, but is not directly part of it. It is often used to provide additional information to the main content.

37. ### What is the purpose of \<footer> tag?

    The \<footer> tag is used to define the footer section of a webpage which contains copyright information, contact details, and other legal content.

38. ### What is the purpose of \<figure> tag?

    The \<figure> tag is used to group together media content, such as images or video with their associated captions or explanatory text.

39. ### What is the purpose of \<figcaption> tag?

    The \<figcaption> is used to define the caption or description of a media that is contained within a \<figure> tag.

40. ### What is the purpose of \<blockquote> tag?
    The \<blockquote> tag is used to indicate that a section of text is being quoted from another source. It is used to highlight a particularly important quote.

## Day 9

41. ### What is \<datalist> tag?

    The \<datalist> tag is new addition to HTML5, and it is used to provide a list of pre-defined options for an input field. It allows us to create dropdown list of options.

42. ### What is the use of \<option> tag?

    The \<option> tag is used to define an option in a dropdown list. The 'value' attribute in \<option> tag is specifies the value of the option that will be submitted when the form is submitted.

43. ### How can you make an image clickable in html?

    To make an image clickable, we have to use anchor tag with the image tag nested inside it and specify where we want to be directed to in "href" attribute when image in click.

44. ### Details about all tags used in HTML table.

    | Tag Name    | Definition                                                     |
    | ----------- | -------------------------------------------------------------- |
    | \<table>    | Defines a table                                                |
    | \<caption>  | Defines a title or caption for a table                         |
    | \<thead>    | Defines the header of a table                                  |
    | \<tbody>    | Defines the body of a table                                    |
    | \<tfoot>    | Defines the footer of a table                                  |
    | \<tr>       | Defines a row in a table                                       |
    | \<th>       | Defines a header cell in a table                               |
    | \<td>       | Defines a standard cell in a table                             |
    | \<colgroup> | Defines a group of columns in a table                          |
    | \<col>      | Specifies column properties for each column within \<colgroup> |
    | \<caption>  | Defines a title or caption for a table                         |

45. ### HTML table attributes.
    | Attribute         | Description                                                                                                                                                                    |
    | ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
    | `border`          | Specifies the width of the border around the table.                                                                                                                            |
    | `cellpadding`     | Specifies the amount of padding to be added to the cells in the table.                                                                                                         |
    | `cellspacing`     | Specifies the amount of space to be added between cells in the table.                                                                                                          |
    | `width`           | Specifies the width of the table.                                                                                                                                              |
    | `height`          | Specifies the height of the table.                                                                                                                                             |
    | `align`           | Specifies the horizontal alignment of the table within its containing element. Possible values are `left`, `center`, `right`, and `justify`.                                   |
    | `valign`          | Specifies the vertical alignment of the table within its containing element. Possible values are `top`, `middle`, `bottom`, and `baseline`.                                    |
    | `bgcolor`         | Specifies the background color of the table.                                                                                                                                   |
    | `bordercolor`     | Specifies the color of the border around the table.                                                                                                                            |
    | `border-collapse` | Specifies whether the borders of the cells in the table should be collapsed into a single border or not. Possible values are `collapse` and `separate`. Default is `separate`. |
    | `border-spacing`  | Specifies the amount of space to be added between the cells in the table when the `border-collapse` property is set to `separate`.                                             |
    | `caption`         | Specifies the title or caption of the table.                                                                                                                                   |
    | `caption-side`    | Specifies the side of the table on which to place the caption. Possible values are `top`, `bottom`, `left`, and `right`. Default is `top`.                                     |
    | `empty-cells`     | Specifies whether or not to display borders around empty cells in the table. Possible values are `show` and `hide`. Default is `show`.                                         |
    | `frame`           | Specifies which sides of the table should have borders. Possible values are `void`, `above`, `below`, `hsides`, `vsides`, `lhs`, `rhs`, and `box`.                             |
    | `rules`           | Specifies which parts of the table's border should be shown. Possible values are `none`, `groups`, `rows`, `cols`, and `all`. Default is `none`.                               |
    | `summary`         | Specifies a summary of the contents of the table.                                                                                                                              |
    | `dir`             | Specifies the direction of the table's text. Possible values are `ltr` (left-to-right) and `rtl` (right-to-left).                                                              |

## Day 10

46. ### What is the purpose of the "data-\*" attribute in HTML?

    The data=\* attribute allows us to store additional information about an HTML element that is not otherwise displayed on the page, but may be useful to scripts that interact with the page.

47. ### What is the purpose of \<legend> tag?

    The \<legend> tag provides semantic caption or title for a \<fieldset> element. It is optional but better for better to have for accessibility.

48. ### What are HTML entities?

    HTML entities are codes used to represent special characters in HTML that cannot be easily typed or displayed. Example: `&amp` represents (`&`)

49. ### What is the purpose of the \<picture> element in HTML5, and how is it used to optimize images?

    The \<picture> element in HTML5 is used to provide multiple versions of an image at different resolutions or sizes, and allows the browser to choose the best version to display based on the user's device and viewport size.

50. ### HTML ARIA attributes.
    | Attribute          | Description                                                                                                                                   | Example                                                                                           |
    | ------------------ | --------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
    | `aria-label`       | Provides a short, descriptive label for an element that isn't already provided by its text content or associated label element.               | `<button aria-label="Search">🔍</button>`                                                         |
    | `aria-describedby` | References another element that provides additional information about the current element, such as instructions or help text.                 | `<input type="text" aria-describedby="name-help"> <div id="name-help">Enter your full name</div>` |
    | `aria-required`    | Indicates which form fields are mandatory and must be filled out before the form can be submitted.                                            | `<input type="text" aria-required="true">`                                                        |
    | `aria-expanded`    | Indicates whether a collapsible element like an accordion or dropdown menu is currently expanded or collapsed.                                | `<button aria-expanded="true" aria-controls="menu">Menu</button> <div id="menu">...</div>`        |
    | `aria-disabled`    | Indicates whether an element is currently disabled or not, such as a disabled button.                                                         | `<button aria-disabled="true">Submit</button>`                                                    |
    | `aria-checked`     | Indicates whether a checkbox or radio button is currently checked or not.                                                                     | `<input type="checkbox" aria-checked="true">`                                                     |
    | `aria-haspopup`    | Indicates that an element has a pop-up or dropdown menu associated with it.                                                                   | `<button aria-haspopup="true" aria-controls="menu">Menu</button> <div id="menu">...</div>`        |
    | `aria-selected`    | Indicates that an element is currently selected or highlighted, such as a selected item in a list                                             | `<li aria-selected="true">Item 1</li>`                                                            |
    | `aria-hidden`      | Indicates that an element is currently hidden or not visible to users, such as content that is only revealed when certain conditions are met. | `<div aria-hidden="true">Hidden content</div>`                                                    |

<br />

---

# CSS

## Day 11

51. ### What is CSS?

    CSS stands for Cascading Style Sheets. CSS is used to define styles for web pages, including the design, layout and variations in display for different devices and screen sizes.

52. ### What are the possible ways to apply CSS styles to a web page?

    There are 3 ways to apply CSS styles to a web page. They are:

    1. Inline CSS
    2. Internal CSS
    3. External CSs

53. ### What are some new features in CSS3?

    Some new features of CSS3 are:

    1. New selectors.
    2. Pseudo-classes
    3. Rounded Corners(Border-radius)
    4. Text shadow
    5. Gradient, etc

54. ### What are the css selectors?

    CSS selector is a part of css rule which is used to apply styles to a target specific HTML element or group of elements.

55. ### What is universal selector in css?
    The universal selector is a css selector that can be used to apply styles to all elements on a page or to reset styles for all elements to their default values

## Day 12

56. ### Explain the difference between classes and IDs in CSS.

    Classes are used to group together elements with similar styles, while IDs are used to target specific elements on a page. IDs must be unique, while classes can be used multiple times on a page.

57. ### Explain box model in CSS.

    The box model in CSS is a way of representing elements as boxes with content, padding, borders, and margins. The content area is the actual content of the element, the padding is the space between the content and the border, the border is a line around the element, and the margin is the space between the border and the surrounding elements.

58. ### What is the difference between margin and padding in CSS?

    Margin is the space between the border of an element and the surrounding elements, while padding is the space between the content of an element and its border.

59. ### Explain the CSS display property and its values.

    The CSS display property controls how an element is displayed on a page. The possible values are block, inline, inline-block, none, and others.

60. ### What is the CSS position property and its values?
    The CSS position property controls how an element is positioned on a page. The possible values are static, relative, absolute, fixed, and sticky

## Day 13

61. ### What is the difference between absolute and relative positioning in CSS?

    Relative positioning moves an element relative to its current position without affecting the position of other elements, while absolute positioning positions an element relative to its closest parent element, potentially affecting the position of other elements.

62. ### Explain the CSS float property and its values.

    The CSS float property controls the alignment of an element in a page layout. The possible values include left, right, none, and inherit. When an element is floated left or right, other elements will flow around it.

63. ### What is the CSS clear property?

    The CSS clear property controls whether an element is allowed to float next to another element or not. The possible values include left, right, both, and none. When an element is cleared, it will be moved below any floated elements.

64. ### What is the CSS z-index property?

    The CSS z-index property controls the stacking order of elements on a page. Elements with a higher z-index value are displayed on top of elements with a lower z-index value. The default value of z-index is auto.

65. ### What are CSS pseudo-classes? Give some examples.
    CSS pseudo-classes are selectors that target elements based on their state or position in the document. Some examples include :hover, :active, :focus, :first-child, :last-child, and :nth-child.

## Day 14

66. ### What is CSS animation?

    CSS animation is a way to add movement and dynamism to the HTML element on a web pages using CSS. It is used to enhance users experience.

67. ### How do you define a CSS animation?

    We can define CSS animation by creating a set of keyframes that specify the start and end states of an animation. We can apply the animation to an element using the animation property in css.

68. ### How do you trigger a CSS animation to start and stop?

    You can trigger a CSS animation to start and stop using various CSS selectors and events. For example, you can use the :hover pseudo-class to start an animation when a user hovers over an element.

69. ### How do you create a responsive CSS animation?

    We can create responsive CSS animation by using relative units like percentages instead of fixed units like pixels. We can also use media queries to adjust the animation properties based on the size of the viewport.

70. ### How do you optimize CSS animations for performance?
    We can optimize CSS animation for performance by using techniques like reducing the number of elements being animated, minimizing the use of box-shadow and text-shadow, and using transform and opacity instead of top, left, bottom, and right.

## Day 15

71. ### How do you debug CSS animations and troubleshoot common issues, such as animations not playing or playing too quickly?

    We can debug CSS animations by checking for typos or syntax errors, checking browser's compatibility if it supports the property or not, checking for code that may override the animation.

72. ### What is transition in CSS?

    A transition in CSS is a way to create animation effects when a property of an HTML element changes, allowing developers to smoothly animate changes to an element's style over a specified duration.

73. ### Can you specify multiple CSS transitions for an element?

    Yes, you can specify multiple CSS transitions for an element by separating them with commas in the "transition" property.

74. ### What are gradients in CSS?

    It is a property of CSS which allows you to display a smooth transformation between two or more than two specified colors. There are two types of gradients in CSS. They are: Linear gradient and radial gradient.

75. ### What is the difference between linear and radial gradient in CSS?
    A linear gradient creates a smooth transition between two or more colors in a straight line while the radial gradient creates a smooth transition between two or more colors in a circular shape.

## Day 16

76. ### What is flexbox?

    Flexbox is a CSS3 layout module which provides more flexible and efficient way to align arrange and align the elements within the container. It is widely supported by the modern web browser.

77. ### What is the difference between flex-grow and flex-shrink properties in Flexbox?

    `flex-grow` is a property in Flexbox that specifies how much a flex item should grow relative to the other items in the container, while `flex-shrink` specifies how much a flex item should shrink relative to the other items when there is not enough space available in the container.

78. ### What is the difference between flex-wrap: nowrap and overflow: hidden in CSS?

    `flex-wrap: nowrap` prevents flex items from wrapping to the next line when they overflow the container, while `overflow: hidden` hides any content that overflows the container's boundaries.

79. ### What is the `gap` property in Flexbox, and how is it used to add spacing between flex items?

    The `gap` property in Flexbox sets the spacing between flex items, both horizontally and vertically. It is a shorthand for `row-gap` and `column-gap`.

80. ### How do you center an element using flexbox?
    To center an element using flexbox, we need to set the parent container's display property to `flex` and use the `justify-content` & `align-items` properties with the value of `center`.

## Day 17

81. ### What is CSS grid?

    CSS grid is a layout system in CSS that allows you to create complex, multi-dimensional grid layouts for web pages.

82. ### How do you use the grid-template-columns and grid-template-rows properties to define the size and number of columns and rows in a grid?

    You can use the grid-template-columns and grid-template-rows properties to define the size and number of columns and rows in a grid. For example, you might define a grid with three columns, where the first column is 100 pixels wide, the second column is 50% of the available width, and the third column takes up the remaining space, with the following CSS:

    ```
    grid-template-columns: 100px 50% 1fr;
    ```

83. ### How do you specify the number of columns in a grid using CSS?

    You can specify the number of columns in a grid by using the `grid-template-columns` property. For example, `grid-template-columns: repeat(3, 1fr)` will create a grid with three columns that are each one fraction of the available space.

84. ### How do you align items within a grid using CSS?

    You can align items within a grid using the `justify-items` and `align-items` properties. justify-items aligns items horizontally within a grid, while `align-items` aligns items vertically.

85. ### What is the difference between grid-row and grid-column in CSS Grid?
    `grid-row` is used to position an item within a row, while `grid-column` is used to position an item within a column. Both properties can take a value of either a number or a named grid line.

# Day 18

86. ### What is a CSS transition?

    A CSS transition is a way to add a gradual animation effect to an element when its CSS properties change.

87. ### What is the purpose of the `transition-property` property in CSS transitions?

    The `transition-property` property specifies which CSS property or properties should be transitioned when a change occurs.

88. ### What is the function of the `transition-timing-function` property in CSS transitions?

    The `transition-timing-function` property specifies the rate of change of the transition over time. This can be used to control the speed of the transition and how it accelerates and decelerates. Example: `ease-in`, `ease`, `ease-out`.

89. ### How do you delay the start of a CSS transition?

    You can delay the start of a CSS transition using the transition-delay property. This property specifies the amount of time to wait before starting the transition, in seconds or milliseconds. Example: `transition-delay: 1s;`

90. ### How do you apply a transition to multiple properties at once?
    You can apply a transition to multiple properties at once by separating the property names with commas in the `transition-property` property. example, `transition-property: background-color, color, opacity;`

# Day 19

91. ### What are CSS 2D Transforms?

    CSS 2D Transforms are a set of properties that allow you to transform the position, rotation, scaling, and skewing of an element in two dimensions, without affecting the surrounding elements.

92. ### Can you use negative values with CSS 2D transforms? If so, what effect do they have?

    Yes, you can use negative values with CSS 2D transforms. The effect of negative values depends on the function being used. For example, a negative value for the `rotate()` function will rotate the element counterclockwise instead of clockwise.

93. ### What are the properties of CSS 2D transform?

    The properties of CSS 2D Transforms are:

    1. transform: specifies the transformation functions to be applied to an element
    2. transform-origin: specifies the point around which the transformation should occur
    3. translate: moves an element along the x-axis and/or y-axis
    4. rotate: rotates an element clockwise or counterclockwise around a given point
    5. scale: increases or decreases the size of an element
    6. skew: skews an element along the x-axis and/or y-axis

94. ### Can you apply multiple transformations to the same element using CSS 2D transforms?

    Yes, you can apply multiple transformations to the same element using CSS 2D transforms. You can do this by separating each transformation function with a space in the `transform` property.

95. ### What is the difference between the `translate()` and `rotate()` functions?
    The `translate()` function is used to move an element along the x-axis and/or y-axis, while the `rotate()` function is used to rotate an element clockwise or counterclockwise around a given point.

# Day 20

96. ### What are the properties of CSS 3D transform?

    The properties of CSS 3D Transforms are:

    1. transform-style: determines whether an element's children are transformed in 3D space
    2. perspective: determines the distance between the viewer and the element, affecting the appearance of 3D transforms
    3. perspective-origin: specifies the origin point of the perspective
    4. transform: applies a 3D transformation to an element, such as rotateX(), rotateY(), rotateZ(), translateX(), translateY(),translateZ(), scale(), and skew()
    5. transform-origin: specifies the origin point of the transformation
    6. backface-visibility: determines whether or not the back face of an element should be visible when the element is rotated.

97. ### What is the difference between RGB and RGBA colors?

    RGBA is similar to RGB, but it includes an additional alpha value that represents the opacity of the color. The alpha value is a number between 0 and 1, with 0 being completely transparent and 1 being completely opaque.

98. ### What is color contrast?

    Color contrast is how much the colors of the text and the background of a website stand out from each other.

99. ### How does color contrast applies to accessibility in web design?

    It is important because people with visual impairments or color blindness may have trouble seeing things if there is not enough contrast. There are guidelines for making sure there is enough contrast which makes the website content more accessible to the people.

100.  ### what is css filter?
      CSS filters are a set of visual effects that can be applied to HTML elements using CSS. Filters can be used to adjust the appearance of an element in various ways, such as changing its color, blurring or sharpening it, adjusting its brightness or contrast, and more.

# Day 21

101. ### What are some important considerations when using text effects?

     Important considerations include making sure the text remains readable and legible, ensuring the effect is appropriate for the overall design, and avoiding overuse of effects.

102. ### What is a CSS sprite?

     A CSS sprite is a technique used to combine multiple images into a single image file, reducing the number of HTTP requests required to load the page and improving loading times.

103. ### What is the :not() pseudo-class used for in CSS?

     The :not() pseudo-class is used to select all elements that do not match the specified selector.

104. ### How do you target all even or odd elements using a pseudo-selector in CSS?

     The :nth-child() pseudo-selector can be used with the "even" or "odd" keyword to target all even or odd elements of a parent element.

105. ### What is the :visited pseudo-class used for in CSS?
     The :visited pseudo-class is used to target a link that has been visited by the user.

# Day 22

106. ### How do you target the first letter of a text element using a pseudo-selector in CSS?

     The ::first-letter pseudo-element is used to target the first letter of a text element.

107. ### What is the :active pseudo-class used for in CSS?

     The :active pseudo-class is used to target an element when it is in an active state, such as when a user clicks on it.

108. ### What is the :lang() pseudo-class used for in CSS?

     The lang() pseudo-class is used to target elements based on the language attribute of the HTML document. For example, you can use :lang(en) to target all elements in English, or :lang(fr) to target all elements in French.

109. ### What is the :checked pseudo-class used for in CSS?

     The :checked pseudo-class is used to target form elements that have been selected by the user, such as checkboxes or radio buttons. This can be used to change the appearance or behavior of the selected element.

110. ### What is the @media rule in CSS?
     The @media rule in CSS allows developers to apply styles to a web page based on the size of the device or screen being used to view it, making it more responsive.

# Day 23

111. ### What is the difference between fluid and fixed layouts in CSS?

     A fluid layout in CSS adjusts its width and height based on the size of the screen, while a fixed layout has a set width and height. Fluid layouts use percentages to set their dimensions, while fixed layouts use pixels.

112. ### How do you make images responsive in CSS?

     To make images responsive in CSS, you can use the max-width: 100% property, which will make the image scale down proportionally to fit the width of its container while maintaining its aspect ratio.

113. ### What is the difference between min-width and max-width in CSS media queries?

     In CSS media queries, min-width sets the minimum screen width at which a set of styles will be applied, while max-width sets the maximum screen width at which a set of styles will be applied. For example, if you use min-width: 768px, the styles will only be applied to screens that are 768 pixels wide or larger, while if you use max-width: 768px, the styles will only be applied to screens that are 768 pixels wide or smaller.

114. ### What is the difference between responsive and adaptive design in CSS?

     Responsive design in CSS adapts to different screen sizes and devices by using flexible grids, fluid images, and media queries to adjust the layout and content of the website. Adaptive design in CSS, on the other hand, uses predefined layout sizes and breakpoints to adjust the layout and content based on the screen size and device being used.

115. ### How do you optimize responsive images for faster loading in CSS?
     To optimize responsive images for faster loading in CSS, you can use smaller file formats like JPEG and PNG, reduce the image size and resolution, and use lazy loading to only load images when they are needed.

# Day 24

116.  ### How does calc() work in css?

      The CSS3 calc() function allows us to perform mathematical operations on property values.
      Example: `div{width: calc(100px + 50px)}`

117.  ### What is the overflow property in CSS used for?

      The overflow property specifies what should happen if content overflows an element’s box. It's possible values are: auto, none, scroll, visible.

118.  ### What is the difference between `visibility:hidden` and `display:none`?

      `visibility:hidden` means the tag is not visible, but the space is allocated for it on the page. `display:none` means the tag will not appear at all and there will be no space allocated for it between the other tags.

119.  ### Are quotes mandatory in URL’s?

      Quotes are optional in URL’s, and it can be single or double.

120.  ### Explain what are web-safe fonts and fallback fonts.
      Web-safe fonts are fonts that are commonly installed on most devices and web browsers. Fallback fonts are alternative fonts specified in case the primary font is not available on the user's device.

# Day 25

121. ### What is the purpose of CSS content property?

     The CSS content property is used to insert content before or after an HTML element using the ::before and ::after pseudo-elements.

122. ### How can we create custom cursor in CSS?

     To create a custom cursor in CSS, you can use the "cursor" property and set it to "url" with the path to the image file that you want to use as the cursor.

123. ### What is the "line-height" property in CSS?

     The "line-height" property in CSS is used to control the spacing between lines of text within an element.

124. ### What is specificity in CSS?

     Specificity in CSS is a way of determining which CSS rule applies to an element. It is based on the number of selectors and their types in a CSS rule. Specificity is calculated using a formula: inline styles have the highest specificity, followed by IDs, classes, and then elements.

125. ### Which property is used to control the scrolling of an image in the background?
     The `background-attachment` property is used to control the scrolling of an image in the background.

# Day 26

126. ### Which CSS property is used to capitalize text or convert text to uppercase or lowercase letters?

     The text-transform property is used to capitalize text or convert text to uppercase or lowercase letters.

127. ### What is word-wrap property in CSS3?

     The word-wrap property allows long words to be able to be broken in order to prevent overflow and wrap onto the next line.

128. ### Describe ‘rule set’ in CSS?

     It is an instruction that tells browser on how to render a specific element on the HTML page. It consists of a selector with a declaration block that follows.

129. ### How can you create a CSS-only dropdown menu?

     A CSS-only dropdown menu can be created by using the "hover" pseudo-class and the "display" property. When the user hovers over a parent element, the "display" property of the child element can be set to "block" or "inline-block" to reveal the dropdown menu.

130. ### What are the potential drawbacks of using CSS frameworks such as Bootstrap?
     Using CSS frameworks like Bootstrap can lead to bloated code, difficulties in customizing the design, and unoriginal or generic looks

# Day 27

131. ### What is Tailwind CSS?

     TailwindCSS is a utility-first CSS framework that provides pre-defined CSS classes that can be used to rapidly build custom user interfaces.

132. ### How do you customize TailwindCSS to match a specific design system or brand guidelines?

     TailwindCSS provides a configuration file that can be customized to match a specific design system or brand guidelines. This file includes variables for colors, fonts, spacing, and more, which can be adjusted to match the project's needs.

133. ### Can you explain the difference between utility classes and component classes in TailwindCSS?

     Utility classes in TailwindCSS are small, single-purpose classes that provide a specific styling utility, such as padding, margin, or text alignment. Component classes, on the other hand, are larger classes that provide a collection of styles for a specific component, such as a button or card.

134. ### How do you optimize the file size of TailwindCSS in a production environment?

     TailwindCSS provides a purge option that removes any unused classes from the final CSS file, reducing its size. This option should be enabled in a production environment to minimize the CSS file size.

135. ### What are some common performance issues with TailwindCSS, and how do you optimize performance in your projects?
     Common performance issues with TailwindCSS include the size of the CSS file and the number of classes being generated. To optimize performance, it is important to enable the purge option in a production environment, use a caching mechanism to speed up builds, and avoid generating unnecessary classes.

# Day 28

136. ### What is CSS preprocessor?

     A CSS preprocessor is a scripting language that extends the capabilities of CSS which makes it easier and more efficient to write CSS code.

137. ### What is the difference between a CSS preprocessor and a post-processor?

     A CSS preprocessor generates CSS code from source code written in a higher-level scripting language, whereas a post-processor takes existing CSS code and applies transformations or optimizations to it. In other words, a preprocessor is used during development, while a post-processor is used after development to optimize performance.

138. ### What is SASS?

     Sass is a CSS preprocessor that adds functionality to CSS, such as variables, nesting, and more. It allows us to write more efficient code and simplifies task like browser compatibility.

139. ### what is the difference between sass and scss?

     Sass and SCSS are both CSS pre-processors and are very similar, but they have different syntax. Sass has a more concise and less verbose syntax, with no curly braces and no semicolon whereas SCSS has a syntax that is almost identical to standard CSS, with curly braces and semicolons

140. ### Can you describe a situation where you would choose not to use Sass?
     A developer might choose not to use Sass if they prefer to stick with standard CSS for simplicity or if they are working on a small project where the added features of Sass may not be necessary.

# Day 29

141. ### What is SASS nesting?

     Sass nesting is a feature that allows us to write CSS selectors that are nested within one another which makes our code easier to read and understand.

142. ### What are variables in Sass?

     Variables in Sass allow you to assign values to a variable name, which can then be used throughout your stylesheet.

143. ### What are mixins in Sass?

     A mixin is a feature in Sass that allows you to define a set of CSS styles that can be reused throughout your stylesheet. Example:

     ```
     @mixin my-text-style {
      font-size: 16px;
      font-weight: bold;
     }

     /* we can use the whole style like this now */

     h1 {
      @include my-text-style;
     }
     ```

144. ### What is Sass inheritance?

     Inheritance allows us to define a set of styles in one selector, called a "parent", and then extend those styles to another selector, called a "child". Example:

     ```
     @mixin button-style($bg-color, $text-color) {
         background-color: $bg-color;
         color: $text-color;
         display: inline-block;
         padding: 8px 16px;
     }

     // Use the mixin to create different button styles

     .button-primary {
         @include button-style(#007bff, #fff);
     }

     .button-secondary {
         @include button-style(#6c757d, #fff);
     }
     ```

145. ### How do you use 'if' statements in SCSS?

     In SCSS, you can use the @if directive to add conditional logic to your styles. Example:

     ```
     //declaring variable
     $background-color: #333;

     body {

     @if $background-color == #333 {
     background-color: $background-color;

     } @else {

     background-color: #fff;
         }
     }
     ```

# Day 30

146. ### What are some common mistakes that developers make when writing CSS, and how do you avoid them?

     Common mistakes in CSS include over-reliance on frameworks, lack of organization, and using non-semantic HTML

147. ### How do you balance the need for visual aesthetics with the need for website or application functionality?

     I balance the need for visual aesthetics with the need for functionality by designing with the user in mind, testing designs with real users, and incorporating feedback and data into the design process.

148. ### How do you ensure that your CSS is optimized for search engine optimization (SEO)?

     We can ensure CSS is optimized for SEO by minimizing code bloat to improve load time, use relevant class names, avoiding inline styles, etc.

149. ### How do you ensure that your CSS is scalable and maintainable for large projects?

     We can ensure that our CSS is scalable and maintainable for large project by:

     1. Using proper naming convection for ID and classes.
     2. Using preprocessor like sass, less, etc.
     3. Using performance enhancing techniques like lazy-loading, etc.

150. ### How do you use CSS variables to create more flexible and dynamic designs, and what are some use cases where variables are particularly useful?
     CSS variables can improve maintainability and reduce repetition. Variables are particularly useful for theming, creating responsive designs, and making changes to global styles.

# Day 31

151. ### What is javascript?

     JavaScript is a programming language used to create interactive and dynamic web pages, as well as to create more complex applications on the client and server side.

152. ### What is the difference between null and undefined in JavaScript?

     Null represents a deliberate non-value or absence of any object value, while undefined represents a lack of value or an uninitialized variable.

153. ### What is the difference between == and === in JavaScript?

     The double equals (==) compares the value of two variables, while the triple equals (===) compares both the value and the data type of two variables.

154. ### What is the difference between let, const, and var in JavaScript?

     The var keyword is used for variable declaration in older versions of JavaScript, while let and const were introduced in ES6. Var has a function-level scope, while let and const have block-level scope. Additionally, const variables cannot be reassigned after being declared, while let variables can be.

155. ### How do you convert a string to a number in JavaScript?
     You can use the `Number()` or `parseFloat()` functions to convert a string to a number in JavaScript.

# Day 32

156. ### What is the purpose of the array slice method?

     The `slice()` method returns the selected elements in an array as a new array object. It selects the elements starting at the given start argument, and ends at the given optional end argument without including the last element.

157. ### What is the purpose of the array splice method?

     The `splice()` is an array method in JavaScript that allows you to modify an array by adding, removing, or replacing elements. It takes two required parameters: the index at which to start making changes to the array, and the number of elements to remove. It also has an optional parameter for adding one or more elements to the array.

158. ### What is the difference between slice and splice?

     | slice                                        |                     splice                      |
     | -------------------------------------------- | :---------------------------------------------: |
     | Doesn't modify the original array(immutable) |      Modifies the original array(mutable)       |
     | Returns the subset of original array         |      Returns the deleted elements as array      |
     | Used to pick the elements from array         | Used to insert or delete elements to/from array |

159. ### What are arrow function?

     Arrow functions are a shorthand syntax for writing function expressions in JavaScript. They use the `=>` syntax to separate the function parameters from the function body and have a concise syntax that makes them ideal for writing short, one-liner functions.

160. ### What are first class function?
     First-class functions means when functions in that language are treated like any other variable. This means that functions can be assigned to variables, passed as arguments to other functions, and returned from functions.

# Day 33

161. ### What is a pure function?

     A pure function is a function that, given the same input, will always return the same output and does not have any observable side effect.

162. ### What is the scope chain in JavaScript?

     The scope chain is how Javascript looks for variables. When looking for variables through the nested scope, the inner scope first looks at its own scope.

163. ### What is a higher order function?

     A higher-order function is a function that takes one or more functions as arguments and/or returns a function as its result.

164. ### What is hoisting?

     Hoisting is a behavior in JavaScript where variable and function declarations are moved to the top of their respective scopes during compilation or interpretation, before the code is actually executed. This means that you can use a variable or function before it has been declared, but only if it is declared using the `var` or `function` keywords. However, only the declarations themselves are hoisted, not their values or assignments.

165. ### What are modules in javascript?
     modules are a way of organizing code into separate files or components that can be reused in different parts of an application. Modules allow you to encapsulate data and functionality, making your code more organized and easier to maintain

# Day 34

166. ### What is a closure in JavaScript?

     In JavaScript, a closure is created when a function is defined inside another function and the inner function is returned from the outer function. The inner function has access to the variables in the outer function, even after the outer function has returned.

     ```
     function outer() {
       var name = "John";
       function inner() {
         console.log("Hello " + name);
       }
       return inner;
     }

     var greeting = outer();
     greeting(); // Output: "Hello John"
     ```

167. ### What is callback in JavaScript?

     A callback is a function that is passed as an argument to another function and is intended to be called when the first function has completed its task. The primary use of callbacks in JavaScript is to handle asynchronous operations, such as making an AJAX request or waiting for a user to click a button.

168. ### What is a callback hell in javascript?

     Callback hell is a term used to describe a situation where multiple callbacks are nested within one another, making the code difficult to read, debug, and maintain. It often arises when dealing with asynchronous operations, such as making HTTP requests or working with databases.

169. ### What is memoization?

     Memoization is a technique used in computer science to speed up the execution of functions by caching the results of expensive function calls and returning the cached result when the same inputs occur again.

170. ### What is the purpose of the "use strict" statement in JavaScript?
     The "use strict" statement is used to enable strict mode in JavaScript, which helps to prevent common errors and make the code more secure. It prevents things like use of undeclared variable, use of keywords as variable name, using duplicate property names in objects, etc.

# Day 35

171.  ### What is a cookie in javascript?

      A cookie is a small data file that a website stores on a user's computer or device. Cookies are commonly used to remember user preferences and login information, and to track user activity on a website. Cookies can also have an expiration date, after which they are automatically deleted.

172.  ### What are the differences between cookie, local storage and session storage?

      | Feature                           | Cookie                             | Local storage    | Session storage     |
      | --------------------------------- | ---------------------------------- | ---------------- | ------------------- |
      | Accessed on client or server side | Both server-side & client-side     | client-side only | client-side only    |
      | Lifetime                          | As configured using Expires option | until deleted    | until tab is closed |
      | SSL support                       | Supported                          | Not supported    | Not supported       |
      | Maximum data size                 | 4KB                                | 5 MB             | 5MB                 |

173.  ### What is AJAX?

      AJAX (Asynchronous JavaScript and XML) is a technique to create more dynamic and interactive web pages. It allows a web page to update content without requiring the page to reload. With AJAX, data is sent to and from the server in the background, using JavaScript and other data formats like JSON. This makes web applications more seamless and responsive, providing users with a faster and more engaging browsing experience.

174.  ### What is the difference between synchronous and asynchronous code in JavaScript?

      Synchronous code executes tasks in sequence and waits for each task to complete before moving on, while asynchronous code can execute multiple tasks simultaneously and doesn't wait for them to complete before moving on to the next task.

175.  ### What are promises in JavaScript?
      Promises in JavaScript are a way of handling async operations. They help us write async code that looks and behaves like sync code, making it easier to read and maintain. Promises have three states: pending, fulfilled, and rejected.

# Day 36

176. ### Who created Javascript?

     JavaScript was created by Brendan Eich in 1995.

177. ### What is the difference between async/await and promises in JavaScript?

     Both async/await and Promises are used to handle asynchronous operations in JavaScript. However, async/await is built on top of Promises which makes asynchronous code more readable, easier to write and reason about.

178. ### How do you handle errors in javascript?

     In JavaScript, errors can be handled using try-catch blocks. The code that might generate an error is enclosed in a try block, and if an error occurs, the catch block is executed. The catch block can then handle the error, such as by logging it to the console or displaying an error message to the user.

179. ### What is NaN in javascript?

     NaN (Not A Number) is a special value in JavaScript that represents a situation where a value is not a valid number. One important thing to note is that NaN is not equal to any value, including itself. We can use the `isNaN()` function to check whether a value is NaN or not.

180. ### How do you find operating system details in javascript?
     In JavaScript, you can find the operating system details of the user by accessing the `navigator` object, which contains information about the user's browser and environment.

# Day 37

181. ### What is the Document Object Model (DOM)?

     The DOM (Document Object Model) is a programming interface that represents the structure and content of an HTML document as a tree-like structure of nodes. It allows developers to access and manipulate the content and structure of a web page using programming languages like JavaScript.

182. ### What is the difference between the DOM and HTML?

     HTML is a markup language used to define the structure and content of a web page, while the DOM is an interface that represents that structure and content as a tree-like structure. The DOM provides a way to access and manipulate the content and structure of a web page, while HTML is simply a static markup language.

183. ### What is the difference between the DOMContentLoaded event and the load event?

     The DOMContentLoaded event is fired when the initial HTML document has been completely loaded and parsed, while the load event is fired when all resources on the page, including images and scripts, have finished loading.

184. ### What is the difference between innerHTML and innerText?

     The main difference between `innerText` and `innerHTML` in the DOM is that `innerText` returns only the visible text content of an element, excluding any HTML tags, while `innerHTML` returns the complete HTML content of an element, including any nested elements and tags.

185. ### What is the role of the Window object in the DOM?
     The Window object in the DOM represents the browser window or tab that displays the web page. It provides methods and properties for controlling and manipulating the browser window.

# Day 38

186. ### What is a DOM node in JavaScript?

     A node in the DOM is a fundamental unit that represents an element, attribute, or text content in a web page. Every node has a relationship with other nodes, such as a parent, child, or sibling. The parent node contains the child nodes, and the child nodes can have siblings that share the same parent

187. ### How do you prevent default behavior of an event in the DOM using JavaScript?

     To prevent the default behavior of an event in the DOM using JavaScript, you can use the preventDefault() method. This method is called on the event object that is passed to the event handler function

188. ### What is event propagation?

     Event propagation in the DOM refers to how events move or flow through different elements on a webpage. When an event happens on an element, like a click, it can travel to its parent elements and eventually to the whole document. This is called event bubbling. Alternatively, events can also travel from the document to the element that triggered the event, which is called event capturing.

189. ### What is call stack in javascript?

     The call stack in JavaScript is a data structure that stores information about the currently executing functions. When a function is called, a new frame is added to the top of the stack, and when the function completes, its frame is removed from the stack. This helps the JavaScript engine keep track of where it is in the execution of a script and manage the order in which functions are called.

190. ### What is an event loop?
     The event loop in JavaScript handles asynchronous operations by queuing them up and processing them one by one in a non-blocking way. It checks the event queue continuously and processes the oldest operation first. When an operation is completed, its callback function is executed.

# Day 39

191. ### What is BOM?

     BOM stands for Browser Object Model. It is a set of APIs provided by the browser that allow JavaScript to interact with the browser window.

192. ### What is the use of `setTimeOut()` in javascript?

     `setTimeout()` is a built-in function in JavaScript that allows you to schedule a function to be executed after a specified amount of time has elapsed.

193. ### What is the use of `setInterval()` in javascript?

     `setInterval()` is a function in JavaScript that allows you to repeatedly execute a given function at a specified interval. It works by calling the function repeatedly with a specified time delay between each call, until the interval is cancelled.

194. ### What is the purpose of clearTimeout method and clearInterval?

     The clearTimeout method is a built-in function in JavaScript that is used to cancel a timer created by the setTimeout function and clearInterval method is a built-in function in JavaScript that is used to cancel a recurring timer created by the setInterval function.

195. ### How do you redirect new page in javascript?

     To redirect to a new page using JavaScript, you can use the `window.location` object's `assign` or `replace` methods.
     Example:

     ```
     // Redirect to a new page
     window.location.assign("https://www.example.com");

     // Redirect to a new page and replace the current page in the browser history
     window.location.replace("https://www.example.com");
     ```

# Day 40

196. ### What is a JavaScript object?

     JavaScript object is a non-primitive data-type that allows you to store multiple collections of data. It is a container of key-value pairs in which value may be a variable, function or object itself.

197. ### What is the difference between dot notation and bracket notation when accessing properties of an object?

     Dot Notation only allows static keys while Bracket Notation accepts dynamic keys. Static key here means that the key is typed directly, while Dynamic key here means that the key is evaluated from an expression.

198. ### What is an object literal in javascript?

     Object literal is a syntax for creating object in javascript in which property and method are inside of curly braces separated by comma. We assign a variable to an object in object literal.

199. ### How would you clone an object in JavaScript?

     There are four ways to clone an object in javascript. They are:

     1. Use the spread operator.
     2. Call the Object.assign() function.
     3. Use JSON parsing.
     4. Use the structuredClone() function.

     ```
     const data = { name: "Alice", age: 26 }
     // 1
     const copy1 = { ...data }
     // 2
     const copy2 = Object.assign({}, data)
     // 3
     const copy3 = JSON.parse(JSON.stringify(data))
     // 4
     const copy4 = structuredClone(data)
     ```

200. ### What is a JSON?
     JavaScript Object Notation (JSON) is a standard text-based format for representing structured data based on JavaScript object syntax. It is commonly used for transmitting data in web applications .

# Day 41

201. ### What is Class in JavaScript?

     Class is a template that can be used to create objects that share the same properties and methods. When an object is created from a class, it is called an instance of that class. Class was introduced in ECMAScript(ES6).

202. ### What is a constructor in javascript?

     In JavaScript, a constructor is a special method that is used to create and initialize objects that are based on a class. It's like a blueprint for creating new objects.The constructor method is called automatically when a new object is created from a class, using the new keyword. It's used to set the initial state of the object by assigning values to its properties.

203. ### What is the difference between a static method and an instance method in a class?

     An instance method is a method that can be called on an instance of a class, and it can access and modify instance-specific data, like properties of the object. A static method, on the other hand, is a method that belongs to the class itself, not to any instance of the class. It can only access class-level data and can be called on the class itself, rather than on an instance of the class.

204. ### What is "this" in javascript Classes?

     In JavaScript classes, `this` refers to the current object that is being worked on. It's like a placeholder for the object. For example, if you have a class that creates `Person` objects, and you want to give each person a `name`, you can use `this.name` to refer to the `name` property of the current `Person` object that is being created or accessed. So, `this` is just a way to access the current object's properties and methods inside a class.

205. ### What are the benefits of using classes in JavaScript?

     There are several benefits of using classes in javascript. Some of them are:

     1. Encapsulation: Classes allow you to encapsulate related data and behavior into a single object, making it easier to manage and organize your code.

     2. Inheritance: Classes support inheritance, which allows you to create subclasses that inherit properties and methods from a parent class. This can help you avoid duplicating code and make your code more modular and reusable.

     3. Code Reusability: With classes, you can create objects that share common properties and behavior. This can help you avoid writing the same code over and over again, making your code more efficient and easier to maintain.

     4. Readability: Classes provide a clean and organized way to structure your code, which can make it easier to read and understand.

# Day 42

206.  ### Can you explain the concept of method overriding in a class in JavaScript?

      Method overriding is a concept in JavaScript where a subclass can provide its own implementation of a method that is already defined in the parent class. To override a method in a subclass, you simply define a method with the same name as the method in the parent class

207.  ### What is composition in classes in JavaScript?

      Composition in class JS is a technique of building complex classes by combining smaller, more focused classes that represent specific behaviors or properties.Composition is a flexible and powerful technique for creating modular, reusable code in JavaScript.

208.  ### What is inheritance in classes in javascript?

      Inheritance in classes in JavaScript is the ability to create a new class based on an existing class. The new class inherits all the properties and methods of the existing class, and can also add new properties and methods or override existing ones.

209.  ### What is the `extends` keyword in JavaScript, and how is it used for inheritance?
      The `extends` keyword is used in JavaScript to create a new class that inherits from an existing class. It is used in the class declaration syntax, like this:
      ```
      class ChildClass extends ParentClass {
       // ChildClass methods and properties
      }
      ```
210.  ### what is the purpose of `super()` in javascript classes?
      The `super()` keyword in JavaScript is used to call a method or constructor of a parent class from within a subclass. It allows a subclass to inherit and use functionality from the parent class, while also adding its own functionality.

# Day 43

211. ### What is a private class field in JavaScript?

     A private class field in JavaScript refers to a class field that is only accessible within the class in which it is defined. It cannot be accessed or modified from outside the class, not even by instances of the class.

212. ### Can you explain the concept of encapsulation in JavaScript classes?

     Encapsulation is a concept in object-oriented programming that refers to bundling data and methods within a single unit, such as a class, and hiding the internal details of the class from the outside world. This makes the code more secure and maintainable.

213. ### What is `get` keyword in javascript classes?

     The `get` keyword is used to define a method that retrieves the value of a property. When the property is accessed, the `get` method is automatically called, and its return value is used as the property's value.

214. ### What is `set` keyword in javascript classes?

     The `set` keyword is used to define a method that sets the value of a property. When the property is assigned a value, the `set` method is automatically called, and it can perform any necessary validation or processing before setting the property's value.

215. ### Can you explain the concept of instance variables in a class in JavaScript?
     In JavaScript, instance variables are properties of an object that are specific to an instance of a class. When we create a new instance of a class using the `new` keyword, each instance has its own set of instance variables that are separate from other instances.

# Day 44

216. ### What is the difference between a class and a function in JavaScript?

     functions and classes are both important tools in JavaScript for defining reusable code, but they serve different purposes. Functions are used to encapsulate logic and perform specific tasks, while classes are used to create objects with shared properties and methods. Knowing when to use each one depends on the specific problem being solved and the design of the application.

217. ### What is abstract class in javascript?

     In JavaScript, an abstract class is a blueprint for creating other classes that share some common properties and methods. However, unlike regular classes, abstract classes cannot be directly instantiated. Instead, they are meant to be extended or subclassed by other classes.

218. ### How would you convert an object to a JSON string in JavaScript, and vice versa?

     In JavaScript, you can convert an object to a JSON string using the `JSON.stringify()` method, and you can convert a JSON string back to an object using the `JSON.parse()` method.

219. ### What is the difference between a class and an interface in JavaScript?

     Classes and interfaces are both used in JavaScript to define object types, but serve different purposes. A class defines a blueprint for creating objects that have properties and methods, while an interface describes the shape of an object and enforces a contract between different parts of a program. Classes define what an object is, while interfaces define what an object can do.

220. ### Can you explain the concept of polymorphism in classes in JavaScript?
     Polymorphism in JavaScript classes means that different objects can share the same methods, even if they belong to different classes. This allows us to reuse code across multiple classes and write more flexible, maintainable code.

# Day 45

221.  ### What is prototype in javascript?

      In JavaScript, a prototype is an object that contains properties and methods that can be shared by all objects created with the same constructor function. It helps to reduce code duplication and makes your code more efficient.

222.  ### What is prototype chain?

      Every object in JavaScript has a built-in property, which is called its prototype. The prototype is itself an object, so the prototype will have its own prototype, making what's called a prototype chain. The chain ends when we reach a prototype that has null for its own prototype.

223.  ### How does prototypal inheritance work in JavaScript?

      Prototypal inheritance allows objects to inherit properties and methods from their parent objects. When an object is created with a constructor function, its prototype is automatically set to the prototype object associated with that constructor function. Any properties or methods defined in the prototype object are shared by all objects created with that constructor function. When an object tries to access a property or method, JavaScript first looks for it in the object itself. If it's not found, it looks up the prototype chain until it finds the property or method.

224.  ### What is the difference between prototypal inheritance and classical inheritance?

      The main difference between prototypal and classical inheritance is that prototypal inheritance allows objects to inherit properties and methods directly from other objects, without the need for classes or constructors. This makes the code more flexible and easier to maintain. Classical inheritance relies on classes and constructors to define the inheritance hierarchy, which can provide better organization and structure but is more rigid and requires more upfront planning.

225.  ### What is the difference between an object's prototype and its constructor function?
      | Prototype                                                                         | Constructor Function                                                   |
      | --------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
      | An object that is shared by all instances created by the constructor function     | A function that is used to create new objects                          |
      | Used to define properties and methods that are shared by all instances            | Used to define properties and methods that are unique to each instance |
      | Accessed using the `prototype` property of the constructor function               | Accessed using the `new` keyword followed by the constructor function  |
      | Modifying the prototype affects all instances created by the constructor function | Modifying the constructor function does not affect existing instances  |

### Day 46

226. ### How do you add properties and methods to an object's prototype in JavaScript?

     We can add properties and methods to an object's prototype by using the constructor function's prototype property. To add a property, simply assign a value to a property on the prototype object. To add a method, define a function and assign it to a property on the prototype object.

     ```
     MyConstructor.prototype.myProperty = "some value";
     ```

227. ### What is the difference between `Object.prototype` and `Object.__proto__` in JavaScript?

     In other words, `Object.prototype` is the object that provides default properties and methods that all objects in JavaScript inherit from. On the other hand, `Object.__proto__` is the object that the `Object` constructor itself inherits from, and it provides the properties and methods that are specific to the `Object` constructor.

228. ### How do you check if an object inherits from a specific prototype in JavaScript?

     We can check if an object inherits from a specific prototype by using the `isPrototypeOf()` method. This method can be called on a prototype object to check if it appears anywhere in the prototype chain of another object. If the prototype object does appear in the prototype chain of the other object, `isPrototypeOf()` will return `true`. Otherwise, it will return `false`.

     ```
     // Check if person inherits from the Object.prototype
     console.log(Object.prototype.isPrototypeOf(person)); // Outputs true if it inherits or else false
     ```

229. ### How do you override a method in an object's prototype in JavaScript?

     We can override a method in an object's prototype by redefining the method on the prototype. To do this, you simply assign a new function to the existing property on the prototype. When you do this, any objects that were created using the constructor function whose prototype you are modifying will now have the new version of the method available to them.

230. ### What is the difference between Object.create() and new Object() in JavaScript?
     The main difference between `new Object()` and `Object.create()` is that `new Object()` creates a new object from scratch, while `Object.create()` creates a new object that inherits from an existing object.

# Day 47

231. ### What is a regular expression(regex)?

     A regular expression, or regex for short, is a set of characters that form a pattern. This pattern is used to search for and match specific sequences of text.

232. ### What is the difference between a regular expression and a string?

     A regular expression is a pattern used to match against a string. A string is simply a sequence of characters.

233. ### What is the syntax for creating a regular expression pattern?

     The syntax for creating a regular expression pattern consists of a combination of characters, special characters, and operators that define the pattern to match.

     ```
     // Define the regex pattern
     const pattern = /\b[A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\.[A-Z|a-z]{2,}\b/;
     ```

234. ### What is a character class in regular expressions?

     A character class in regular expressions is a set of characters that can be matched in a single position in the text. It is denoted by enclosing the characters in square brackets [].

     ```
     // Define the regex pattern using a character class
     const pattern = /[aeiou]/;
     ```

235. ### What is the difference between the asterisk () and the plus sign (+) in regular expressions?

     In regular expressions, the asterisk (\*) matches zero or more occurrences of the preceding character, while the plus sign (+) matches one or more occurrences of the preceding character.

     For example, if we want to match the letter "a" followed by zero or more "b" characters, we would use the asterisk in our regular expression like this: /ab\*/. This would match strings like "a", "ab", "abb", "abbb", and so on.

     On the other hand, if we want to match the letter "a" followed by one or more "b" characters, we would use the plus sign in our regular expression like this: /ab+/

# Day 48

236. ### How do you use the question mark (?) in regular expressions?

     The question mark (?) is a metacharacter used in regular expressions to indicate that the preceding character or group of characters is optional. It means that the preceding character or group of characters may appear zero or one time. For example, the regular expression "colou?r" will match both "color" and "colour".

237. ### What is the purpose of backslashes () in regular expressions?

     Backslashes () are used in regular expressions to indicate that the following character has a special meaning. For example, the regular expression "\d" matches any digit character, while the regular expression "\s" matches any whitespace character. If you want to match a literal backslash character, you need to escape it by using two backslashes (\).

238. ### How do you specify a range of characters in a character class?

     In a character class, you can specify a range of characters by using a hyphen (-) between two characters. For example, the regular expression "[a-z]" matches any lowercase letter from "a" to "z". Similarly, the regular expression "[0-9]" matches any digit character from "0" to "9". Note that the range is inclusive, so the characters at both ends are included in the match.

239. ### What is the difference between a greedy and a non-greedy match in regular expressions?

     In regular expressions, a greedy match will match as much as possible while still allowing the overall pattern to match. A non-greedy match, on the other hand, will match as little as possible while still allowing the overall pattern to match. Greedy matching is the default behavior in most regex engines. To make a match non-greedy, you can use the question mark (?) after the quantifier. For example, the regular expression ".\*?" will match as few characters as possible.

240. ### How do you use the pipe (|) operator in regular expressions?
     The pipe (|) operator is used in regular expressions to match either one pattern or another. For example, the regular expression "cat|dog" will match either "cat" or "dog". You can also use parentheses to group patterns together when using the pipe operator. For example, the regular expression "(red|green|blue) car" will match "red car", "green car", or "blue car".

# Day 49

241. ### What is the purpose of the caret (^) and dollar sign ($) characters in regular expressions?

     The caret (^) and dollar sign ($) characters in regular expressions are used to match the beginning and end of a string, respectively.

242. ### What are some common use cases for regular expressions?

     Common use cases for regular expressions include text parsing, search and replace operations, and input validation.

243. ### How do you match a specific number of characters in a regular expression?

     To match a specific number of characters in a regular expression, you can use quantifiers such as {n} to match exactly n occurrences of a pattern, or {n,m} to match between n and m occurrences.

244. ### How do you match a specific character that has a special meaning in a regular expression?

     To match a specific character that has a special meaning in a regular expression, you can use an escape character () before the special character.

245. ### How do you use lookarounds in regular expressions?

     Lookarounds in regular expressions allow you to look ahead or behind the current position in the string without including the matched text in the result. Positive lookaheads (?=) and negative lookaheads (?!), as well as positive lookbehinds (?<=) and negative lookbehinds (?<!), are the four types of lookarounds that can be used.

# Day 50

246. ### What is the `window.location` object in JavaScript?
     The `window.location` object is a built-in object in JavaScript that contains information about the current URL of the webpage. It is a property of the global `window` object and provides several properties and methods to work with URLs.

247. ### What are the properties of the `window.location` object?
     Some of the properties of the window.location object are:

     `href` : returns the entire URL of the current page <br/>
     `protocol` : returns the protocol of the URL (http:, https:, etc.) <br/>
     `host` : returns the hostname and port number of the URL <br/>
     `hostname` : returns the hostname of the URL <br/>
     `port` : returns the port number of the URL <br/>
     `pathname` : returns the path and filename of the URL <br/>
     `search` : returns the query string of the URL <br/>
     `hash` : returns the anchor part of the URL <br/>

248. ### How do you redirect to another page using JavaScript's `window.location` object?
     We can redirect to another page using the `assign()` method of the `window.location` object.
     ```
          window.location.assign("https://www.google.com");
     ```

249. ### How do you reload the current page using JavaScript's `window.location` object?
     You can reload the current page using the reload() method of the window.location object.
     ```
     window.location.reload();
     ```

250. ### How do you get the value of a query parameter from the URL using JavaScript's `window.location` object?
     You can get the value of a query parameter from the URL using the `searchParams` property of the `window.location ` object. For example, to get the value of a query parameter named `id`.
     ```
     const id = new URLSearchParams(window.location.search).get("id");
     ```

# Day 51

251. ### What is the Date object in JavaScript?
     The Date object in JavaScript represents a date and time value, which can be used to perform various operations on dates and times.

252. ### How do you format a date in JavaScript?
     You can format a date in JavaScript using the toLocaleDateString() method of the Date object, which returns a string representation of the date in the specified locale.
     ```
     var date = new Date();
     var formattedDate = date.toLocaleDateString('en-US', { month: '2-digit', day: '2-digit', year: 'numeric' });
     console.log(formattedDate); // Output: "05/14/2023"
     ```

253. ### How do you compare two dates in JavaScript?
     You can compare two dates in JavaScript using the <, >, <=, >=, ==, and != operators, which compare the numeric values of the Date objects (i.e., their timestamps).
     ```
     var date1 = new Date('2023-05-14');
     var date2 = new Date('2023-05-15');

     if (date1 < date2) {
       console.log('date1 is earlier than date2');
     } else {
       console.log('date1 and date2 are equal');
     }
     ```
254. ### How do you get the current timestamp in JavaScript?
     You can get the current timestamp in JavaScript using the `getTime()` method of the Date object, which returns the number of milliseconds since January 1, 1970, 00:00:00 UTC.

255. ### How do you add or subtract days to a date in JavaScript?
     You can add or subtract days to a date in JavaScript using the `setDate()` method of the Date object, which allows you to set the day of the month for a given date.
     ```
     var date = new Date();
     date.setDate(date.getDate() + 3);
     console.log(date); // Output: the date 3 days from now
     ```

# Day 52

256. ### what is iterator in javascript?
     In JavaScript, an iterator is an object that provides a way to access elements of a collection or a custom data structure in a sequential manner. It allows you to loop over the elements one at a time, retrieving them on demand.

     The most important method is next(), which is responsible for returning the next element in the sequence. When you call next() on an iterator, it returns an object with two properties: value, representing the current element, and done, indicating whether there are more elements or if the iteration is complete.

257. ### What is decorator in javascript?
     In JavaScript, a decorator is a design pattern that allows you to modify the behavior of an object or a function by wrapping it with another function. It provides a way to add new functionality or modify existing functionality dynamically, without changing the original code.

258. ### What is babel?
      Babel is a tool that helps you write modern JavaScript code while ensuring compatibility with older environments by transforming or transpiling that code into an older JavaScript version. It allows developers to take advantage of new language features without worrying about browser compatibility issues.

259. ### What is optional chaining?
     Optional chaining is a js feature by which using the `?.` operator, you can directly access nested properties or call nested functions, and if any part of the chain is null or undefined, the expression short-circuits and returns undefined instead of throwing an error. 

260. ### What is throttling?
     Throttling is a technique used in JavaScript to control the rate at which a particular function or code block is executed. It ensures that the function is called at a maximum frequency or a specified interval, preventing it from being invoked too frequently.

# Day 53

261. ### What is debouncing?
     Debouncing in JavaScript is a way to control how often a function gets called when there are frequent events happening, like typing or scrolling. This can be useful for optimizing performance and avoiding unnecessary function calls.

262. ### What is global execution context?
     The global execution context is the default or first execution context that is created by the JavaScript engine before any code is executed(i.e, when the file first loads in the browser). All the global code that is not inside a function or object will be executed inside this global execution context. Since JS engine is single threaded there will be only one global environment and there will be only one global execution context.

263. ### What is function execution context?
     In JavaScript, the function execution context refers to the environment in which a function is executed or called. Each time a function is invoked, a new execution context is created specifically for that function. It consists of two main components: the variable environment and the scope chain.

264. ### What does the variable environment in JavaScript's function execution context contain, and what is its purpose?
     The variable environment contains all the variables, function declarations, and function arguments specific to that function. It keeps track of the function's local variables and parameters, allowing the function to access and manipulate them during its execution.

265. ### What is a scope chain in JavaScript's function execution context?
     The scope chain is a list of all the variable environments that are accessible to the function. It is used to resolve variable references during the function's execution. When a variable is not found in the current variable environment, JavaScript looks up the scope chain to find the variable in outer environments until it reaches the global execution context.

# Day 54

266. ### What is Minification?
     Minification is the process of removing all unnecessary characters(empty spaces are removed) and variables will be renamed without changing it's functionality.

267. ### How do I modify the url without reloading the page?
     The `window.location.href` property will be helpful to modify the url but it reloads the page. HTML5 introduced the `history.pushState()` and `history.replaceState()` methods, which allow you to add and modify history entries, respectively. Example:
     ```
     window.history.pushState("page2", "Title", "/page2.html");
     ```

268. ### What are dynamic imports in javascript?
     Dynamic imports in JavaScript allow you to load modules or scripts dynamically at runtime, instead of including them statically in the initial page load.
     ```
         import('module.js')
      .then(module => {
        // Use the imported module
        // ...
      })
      .catch(error => {
        // Handle any import errors
        // ...
      });
     ```

269. ### What paradigm is Javascript?
     JavaScript is a multi-paradigm language, supporting imperative/procedural programming, Object-Oriented Programming and functional programming. JavaScript supports Object-Oriented Programming with prototypical inheritance.

270. ### How do you empty an array?
     You can empty an array quickly by setting the array length to zero.
     ```
     let cities = ["Singapore", "Delhi", "London"];
     cities.length = 0; // cities becomes []
     ```

# Day 55

271. ### What is a lambda function?
     A lambda function, also known as an arrow function in JavaScript, is a concise and shorthand way of defining a function. It uses the => arrow syntax to indicate a function, allowing for shorter and more readable code.

272. ### What is variable shadowing in javascript?
     If there is a variable in the global scope, and you'd like to create a variable with the same name in a function. The variable in the inner scope will temporarily shadow the variable in the outer scope. It is called variable shadowing.

273. ### How do you assign default values to variables?
     You can use the logical or operator || in an assignment expression to provide a default value. The syntax looks like as below,
     ```
     var a = b || c;
     ```

274. ### What is a rest operator in javascript?
     The rest operator in JavaScript is a special syntax that allows you to pass an indefinite number of arguments to a function. It is represented by three dots ( ... ).
     ```
     function partyGuests(...names) {
     console.log(names);
     }

     partyGuests('Alice', 'Bob', 'Charlie');
     ```

275. ### What is a spread operator?
      The spread operator (`...`) is used to spread elements from an array or object into another array, function call, or object literal. It allows you to unpack or expand the individual items or properties from the source into a destination.
     ```
     const fruits = ['apple', 'banana', 'orange'];
     const fruitSalad = ['kiwi', 'grape', ...fruits, 'melon'];
     //fruitSalad = ["kiwi", "grape", "apple", "banana", "orange", "melon"]
     ```



