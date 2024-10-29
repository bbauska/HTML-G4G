**(HyperText Markup Language)**

{From Geeks4Geeks}

a.  **Basic HTML**

b.  **Forms and Validation**

c.  **Semantic Tags**

d.  **Accessibility**

a.  **Basic HTML**

### What is HTML?

**[HTML](https://www.geeksforgeeks.org/html-introduction) stands
for Hyper Text Markup Language**. It is a markup language that consists
of different tags. It is used to define the structure of the web pages.

### What are Semantic elements in HTML?

The [**semantic elements**](https://www.geeksforgeeks.org/html5-semantics) in
HTML are the elements that contain the meaning of the content and the
structure of the HTML document. These elements contain content that is
related to their names or reflects their names. Some of the
**[semantic] HTML elements are listed below:

-   Header
-   Main
-   Section
-   Article
-   Aside
-   Footer etc.

### What are the Empty elements in HTML?

> The [**empty elements in
> HTML**](https://www.geeksforgeeks.org/what-are-empty-elements-in-html) are
> the elements that don't require a closing tag followed by the opening
> tag. These elements are also known as self-closing elements. Example:
> \<img\>, \<input\>, \<br\>, \<hr\> etc.

### Differentiate between the Inline and the Block elements in HTML.

> The [**Inline
> elements**](https://www.geeksforgeeks.org/html-block-and-inline-elements) in
> HTML are the elements that do not start from a new line every time and
> take up the same space and width as acquired by the content. The
> margin and padding properties applied at the top and the bottom of
> these elements may not have the expected effect. Examples: \<a\>,
> \<strong\>, \<img\>, \<input\> etc.
>
> The Block elements automatically starts from a new line and takes up
> the whole view-port width irrespective of the contained content. The
> padding and margin properties have the same effect on all the four
> sides. Examples: \<div\>, \<h1\> to \<h6\>, \<p\>, \<table\> etc.

### What is list in HTML? Explain different types of list available in HTML.

> In HTML, the [**lists**](https://www.geeksforgeeks.org/html-lists) are
> used to represent a collection of different items. There are three
> types of lists available in HTML as listed below:
>
> **1. Unordered List: **It is defined using the \<ul\> and the \<li\>
> tags. By default, it represents the items with a bulleted dot.

```
<ul>
  <li>List Item 1</li>
  <li>List Item 3</li>
  <li>List Item 3</li>
</ul>
```

>
> **2. Ordered List: **It is defined using the \<ol\> and \<li\> tag. By
> default, it represents
> the[ list](https://www.geeksforgeeks.org/list-cpp-stl) items with
> numeric digits.

```
<ol>
<li>List Item 1</li>
<li>List Item 3</li>
<li>List Item 3</li>
</ol>
```
>
> **3. Definition List: **It is a special kind of list which is used to
> list the or terms with their definitions. It can be defined using the
> \<dl\>, \<dt\> and \<dd\> tags. dt -- definition term, dd --
> definition description
>
```
> <dl>
> <dt>First term</dt>
> <dd>Definition 1</dd>
> <dt>Second term</dt>
> <dd>Definition 2</dd>
> <dt>Third term</dt>
> <dd>Definition 3</dd>
> </dl>
```

### What is the basic structure of an HTML document?

The basic structure of an [**HTML
document**](https://www.geeksforgeeks.org/dom-document-object-model) in
HTML5 is shown below:

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Document</title>
  </head>
  <body></body>
</html>
```

1.  **Explain the elements used in the basic structure of an HTML
    document.**

The elements used in the basic structure of an HTML document are
explained below:

-   **[&lt;!DOCTYPE html&gt;](https://www.geeksforgeeks.org/html-doctypes): **It
    represents the HTML5 version of the HTML.

-   **[&lt;html&gt;](https://www.geeksforgeeks.org/html-tutorial): **It is
    the root element of the HTML document.

-   **[&lt;head&gt;](https://www.geeksforgeeks.org/html-head-tag): **It
    contains the meta data i.e. the data about the data. The content
    contained by this tag is not visible on the web page.

-   **[&lt;title&gt;](https://www.geeksforgeeks.org/html-title-tag): **It
    contains the title of the document which will be visible in the
    browser tab.

-   **[&lt;body&gt;](https://www.geeksforgeeks.org/html-body-tag): **It
    contains the content of the web page in the form of the HTML tags
    like **div, anchor, paragraph, headings, etc.**

### Explain tags in HTML.

The HTML tags are used to define the elements on the web page.
Basically, they are the keywords that are enclosed inside the **angle
brackets(\<\>). **Some examples of HTML tags are **\<div\>, \<p\>,
\<a\>, \<span\>, \<img\> etc.**

### Why ['alt' attribute](https://www.geeksforgeeks.org/html-alt-attribute) is used with the [&lt;img&gt; tag in HTML](https://www.geeksforgeeks.org/html-img-tag)?

The alt attrbute provides a alternative content that is related to the
image which will be shown on the web page if the image does not gets
loaded. It is used to define our image in that case.

### **1.10. What is the difference between the [&lt;div&gt;](https://www.geeksforgeeks.org/div-tag-html) and [&lt;span&gt;](https://www.geeksforgeeks.org/html-span-tag) tag in** **HTML?**

The below table will show the differences between the div and span tag
in HTML:

| **&lt;div&gt;tag**        | **&lt;span&gt;tag**          |
| ----------------------- | ------------------------ |
| It is a block-level element.         | It is an inline element. |
| It can be used to group and structure the content of the web page. | It is mainly used to interact and style the particular part of the web page. |
|  It represents a bigger section of the web page.  | It is used to target small parts of the web page. |
|  It starts from a new line and takes up the full width available. | It does not starts from a new line and takes up the only  required width as taken by the content. |

### Why the [&lt;meta charset = "UTF-8"&gt;](https://www.geeksforgeeks.org/what-is-the-purpose-of-using-the-meta-charsetutf-8-tag) tag is used?

It is used to set the character encoding of the charaters for the
document to **UTF-8 **to properly display the text and the special
characters on the web page.

### What is the purpose of using the 'role' attribute in HTML?

The [**role **attribute](https://www.geeksforgeeks.org/what-is-the-purpose-of-role-attribute-in-html) defines
the functionality and the purpose of an element mainly the
accessibility. It provides the additional information for the assisstive
technologies such as screen readers, to convey the exact meaning of the
element to the users with disabilities.

### 1.13. Differentiate between the GET and the POST methods in HTML forms.

The below table will explain the [differences between the GET and
POST](https://www.geeksforgeeks.org/html-form-method-attribute) methods
in HTML forms:

|  **GET Method** | **POST Method** |
| ------------------------- | ------------------------- |
| It is a insecure way to send data on the server. | It is a secure way of sending the form data. |
| All the form data parameters are visible in the URL. | None of the parameters are visible anywhere. |
| It has a URL length limit that varies for different browsers. | It has a bigger URL length limit as compared to the limit of the GET method. |
| Results are cached by the browser by default. | Does not caches the responses in the browser by default. |
| Users can bookmark the form submission. | Responses can be bookmarked easily. |

### What is the use of the &lt;iframe&gt; tag?

The[ &lt;iframe&gt; tag](https://www.geeksforgeeks.org/html-iframe-tag) is
used to embed the external documents or the web pages inside the current
document by specifying its link inside it. It is mainly used to embed
the external videos, maps and other external content.

### Explain the features of HTML5?

HTML5 introduced some new features that are listed below:

-   Introduced new semantic elements
    like: **[&lt;header&gt;](https://www.geeksforgeeks.org/html5-header-tag), [&lt;footer&gt;](https://www.geeksforgeeks.org/html5-footer-tag), [\<nav\>](https://www.geeksforgeeks.org/html-nav-tag), [\<aside\>](https://www.geeksforgeeks.org/html5-aside-tag), [\<article\>](https://www.geeksforgeeks.org/html5-article-tag), [&lt;section&gt;](https://www.geeksforgeeks.org/html-section-tag) etc.**

-   New form input types such as **email, url, number, date, etc.**

-   It introduced
    the **[&lt;audio&gt;](https://www.geeksforgeeks.org/html5-audio-tag)** and **[&lt;video&gt;](https://www.geeksforgeeks.org/html5-video) **tags
    to embed audios and videos and reduces the dependence on the third
    party libraries.

-   **&lt;canvas&gt;** element to draw graphics and animations using
    JavaScript.

-   Introduces the browser storage
    as [l**ocalStorage**](https://www.geeksforgeeks.org/javascript-localstorage)** **and **[sessionStorage](https://www.geeksforgeeks.org/html-dom-window-sessionstorage-property) **to
    store data in the browser.

### What is localStorage?

[localStorage ](https://www.geeksforgeeks.org/javascript-localstorage)is
a client-side web storage mechanism that allows web applications to
store key-value pairs persistently in a user's web browser. It provides
a simple interface for storing data locally.

### What is sessionStorage?

It is also a web storage API provided by the web browsers to store the
data in the similar way as stored in the localStorage in the form of the
key-value pairs. The data stored in
the [sessionStorage](https://www.geeksforgeeks.org/html-dom-window-sessionstorage-property) will
only be accessible for one session such that if user closes the window
or tab the stored data will be lost.

### Differentiate between localStorage and sessionStorage.

The below table lists the[ differences between the local and the session
storage](https://www.geeksforgeeks.org/localstorage-and-sessionstorage-web-storage-apis):

| **localStorage**                    | **sessionStorage** |
| ----------------------------------- | ----------------------------------- |
|  The stored data can be accessible  |  The stored data access is limited  |
|  in all the opened tabs in the browser.     |  to the current tab or window only. |
|  The data will be persistent if the | The data will be lost once user     |
|  tabs are closed and opened again.  | closes the tab or the window.       |
|  Used to store the data for long term.   | It is used to store the data for as long as you want to store it. |
|  The data can be cleared using      | The data can be cleared either by   |
|  the **clear() **method only.       | closing the tab or by using the     |
|                                     | **clear() **method as well.         |

2.  **What is the purpose of
    using [&lt;figure&gt;](https://www.geeksforgeeks.org/html5-figure-tag) and [&lt;figcaption&gt; ](https://www.geeksforgeeks.org/html5-figcaption-tag)elements
    in [HTML5](https://www.geeksforgeeks.org/html5-introduction)?**

The **&lt;figure&gt;**element is used to display the media content on the
web page like audios, videos etc. While, the **&lt;figcaption&gt;** element
is used to give a caption or legend to the content shown by
the **&lt;figure&gt; **element.

### 1.20. Write the HTML code to create a [table](https://www.geeksforgeeks.org/html-tables) with 3 columns and 3 rows.

The below code creates a table with 3 rows and 3 columns:

```
<table border="1px">
  <thead>
    <tr>
      <th>col 11</th>
      <th>col 12</th>
      <th>col 13</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>col 21</td>
      <td>col 22</td>
      <td>col 23</td>
    </tr>
    <tr>
      <td>col 31</td>
      <td>col 32</td>
      <td>col 33</td>
    </tr>
  </tbody>
</table>
```

**21. How can you merge the rows and columns of a HTML table?**

You can use the **colspan **and the **rowspan **attributes with
the **\<td\> **element and specify the number of rows and columns to be
merged by passing a numerical value to the defined attributes.
The **[colspan](https://www.geeksforgeeks.org/html-colspan-attribute) **attribute
can be used to merge columns while
the **[rowspan](https://www.geeksforgeeks.org/html-rowspan-attribute) **to
merge the rows.

**22. Describe data attributes in HTML.**

The [data
attributes](https://www.geeksforgeeks.org/html-data-attributes) in HTML
are defined to collect the data that is private to the web page or the
web application. It is basically used to personalize the JavaScript for
the particular user or visitor on the web page based on the actions of
that user on the web page. Now a days, the data attributes are suggested
not to use on a web page as these attributes can be changed easily by
going to the browser **developer tools** and **inspect element.**

**23. What is CSS?**

[CSS](https://www.geeksforgeeks.org/css-tutorial), which stands for the
Cascading Style Sheets. It helps to design and style the web page to
make it attractive for users. CSS provides us a lot of selectors to
select the HTML elements and style them according to the requirements.
Some of the [**CSS
selectors **](https://www.geeksforgeeks.org/css-selectors)are [Element
Selectors](https://www.geeksforgeeks.org/css-element-element-selector), [**Class
Selectors**](https://www.geeksforgeeks.org/css-class-selector) and [**Id
Selectors**](https://www.geeksforgeeks.org/css-id-selector).

**24. Explain selectors in CSS.**

In[ CSS, selectors](https://www.geeksforgeeks.org/css-selectors) are
used to select elements and style the element by providing CSS
properties to it. Below is the list of some common CSS selectors:

-   **[Element
    Selector:](https://www.geeksforgeeks.org/css-element-selector) **Select
    directly by using the name of the element.

-   **ID Selector: **Define ID attribute and select using the \# prefix
    followed by the value of ID attribute.

-   **Class Selector:** Define Class attribute and select using the .
    prefix followed by the value of class attribute.

-   **Universal Selector (&ast;):** Select using the &ast; sign.

-   **Attribute Selector: **Select the elements based on the attribute
    values. Eg: **input&lbrack;type="text"&rbrack;{}**

-   **Direct Child Selector:** Select element using any of the above
    selectors and use &gt; followed by direct child selector. Eg: **parent &gt; child{}**

-   **Pseudo Selectors:** These are selectors like :hover, :nth-child(),
    ::after, ::before etc.

**25. Explain the precedence of the Class, Id and Element selectors in CSS.**

The precedence of the ID, Class and Element CSS selectors is shown
below:

-   ID Selector &gt; Class Selector &gt; Element Selector

-   ID Selector + Class Selector &gt; ID Selector + Element Selector &gt; 
    Class Selector + Element Selector

**26. What are the best practices for using JavaScript and CSS?**

The best practices for JavaScript and CSS can be defined according to
the project requirements. Below are some general best practices listed
for JavaScript and CSS:

-   Always use an external file for defining the JavaScript and CSS
    with **.js** and **.css** extensions respectively.

-   Always link the CSS file inside the \<head\> tag of the HTML
    document.

-   Always add the script file at the end of the \<body\> tag just
    before where body closes.

-   Try to write JavaScript in strict mode to avoid errors and write
    cleaner JavaScript.

-   Avoid creating global variable and use the meaningful name to define
    the variables.

**27. What is difference between visibility: hidden and display: none properties in CSS?**

The **visibility: hidden** property only hides the content of the
element on which it is used. It does not removes the element from the
document and keep the space as it is so that no other element can
replace it on the UI. On the other hand, the **display: none** property
not only hides the element but removes it from the document and the
space acquired by the element is now free to be acquired by the other
elements.

**28. Mention the issues faced by developers while running the CSS in Internet Explorer (IE)?**

Below list shows the issues faced by the developers in Internet
Explorer:

-   Transparency of the images with **.png** extension.

-   Issues related to Z-index property.

-   Sometimes, it doubles the margin added to an element.

-   Box model has a different interpretation.

-   Lack the support for the CSS3 Features.

**29. Explain box-model in CSS.**

The box model in CSS is basically a blue print of an element with some
properties. The box model contains four elements which are content,
padding, border and margin.

-   **Content:** It can be the text content or the nested HTML elements
    with some content inside a element.

-   **Padding:** It is the space around the content of the element or
    the space between the content and the borders.

-   **Border:** This is the stroke or outline provided to the element to
    see its boundaries or style it.

-   **Margin:** It is the space around the whole element, it is the gap
    outside the element from other elements or the space between the
    border of this element and other elements.

**30. What is the purpose of z-index property in CSS?**

The **z-index** property is used to control the stacking order of the
elements that are positioned using the **position** property in CSS. The
higher or the positive values will make the element appear on the top of
the other elements while the negative or the lower values make them
appear behind the elements with higher values.

**31. What is the use of float property?**

The **float** property allows to set the child elements of a container
either on the left side of it or at the right side of it. The possible
values for this property are **left, right, initial, inherit,** and **none.**

**32. Explain different ways to display an element at the center of the web page.**

There are many ways to center a element on the web page as described
below:

-   **Using margin:** The **margin** property can be used to center a
    element horizontally by giving **margin auto** from left and right
    of the element as **margin: 0 auto;**.

-   **Using display:** The display property with value **flex** can be
    used to center a element vertically as well as horizontally by using
    some extra properties as **align-items: center;** and **justify-content: center;.**

-   **Using position and transform: **You can position a element to give
    it a **left** and **top** to **50%** and then use
    the **transform** property with value **translateY(-50%);**

**33. Describe the use of the position property in CSS.**

The position property is used to position an element with respect to
different elements according to the given property value. The possible
values of this property are **relative, absolute, fixed, sticky,** and **static.**

**34. What are pseudo classes and pseudo elements in CSS?**

The pseudo classes and pseudo elements are different entities in CSS.
They are combinely known as pseudo selectors in CSS. Below is the
explanation for them:

-   **pseudo classes: **These are the classes that selects the elements
    based on their state and the position. Some pseudo classes
    are **:hover, :focus, :nth-child etc.**

-   **pseudo elements: **These are the virtual elements that are mainly
    defined to style a particular part of an element in the HTML
    document. Some pseudo elements are **:before **and **:after.**

**35. Why is the '!important' used in CSS?**

The **!important **declaration is used to give higher precedence to a
CSS property to override it from other conflicting styles defined on a
element using the same property such as **width: 30px !important; **will
override the property **width: 25px; **defined on the same element.

**36. What is the purpose of 'box-sizing' property in CSS?**

The **box-sizing **property is used to determine the way of calculating
the height and width of a element. It determines whether the border and
padding will be included or not to calculate the height and width of the
element. The common values
are **content-box(default) **and **border-box.**

**37. Tell me about CSS preprocessors and their advantage over pure
CSS?**

A CSS preprocessor is created using a scripting language that extends
the CSS rules and processed in the regular CSS by creating a file
with **.css **extension. Mostly used CSS preprocessors
are **SASS **and **LESS. SASS **is based on the **Ruby
language **while **LESS **is based on JavaScript, initially it was also
based on **Ruby **but now shifted to **JavaScript. **They provide some
extra features like **creating variables, mixins, code nesting **and
some other features to enhance code maintainablility.

**38. What is the meaning of 'Cascading' in Cascading Style Sheet?**

Cascading represents the specificity order in applying styles. These
styles can be defined by the user, author or they can be the default
browser styles. The specificity order for the styles is **user styles \>
author styles \> default browser styles.**

**39. Explain Media Queries in CSS.**

Media queries are the block of CSS code defined for a particular width
or range of the width. These can be defined using
the **\@media **keyword with **screen **to specify styles for a
particular width or range of width. They are used very commonly to
create responsive designs.

**40. Describe CSS sprites and their importance to improve website
performance.**

CSS sprites are a technique that is used to compress multiple images
available on the web page into a single image file. It arranges all the
images in a grid-like layout. The **background-position **property of
CSS can be used to display the different parts of the combined image as
background for different elements. It improves the web performance by
reducing the server requests as the website has to request only a single
image now instead of requesting multiple images.

**41. How you can optimize the loading of CSS files in browser?**

There are multiple techniques available to optimize loading of CSS files
as listed below:

-   By minimizing number of CSS files.

-   CSS minification

-   By leveraging the browser cache

-   Load the un-necessary styles using asynchronous or deffered loading.

**42. How to create responsive designs?**

There are some key concepts available in CSS that can help you in
creating responsive designs as listed below:

-   Using [**Media
    queries**](https://www.geeksforgeeks.org/css-media-queries)

-   Using the **flexbox layout**

-   Using the **grid layout**

-   Using responsive CSS properties like **percentage** and **vh, vw.ow
    to create responsive designs?**

b.  **Forms and Validation**
