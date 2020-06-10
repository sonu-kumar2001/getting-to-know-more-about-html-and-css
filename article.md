# Getting to know more about HTML and CSS

## knowing more about html
We already know about the HTML elements. There are a large number of HTML elements available to display content on a page.But we need to know more about the elements, like which element is best to display different types of content on a page. It's not only that we have to display our content on a page but it is also important to understand how elements are visually displayed.

In HTML document element provides semantic meaning to raw content. Using proper elements for appropriate content plays an important role in HTML coding.

## Semantic

In HTML semantics means using a proper element for appropriate content.Semantic code provide perfect meaning to the content on a page.
There are several benefits of writing semantic code. The search engine also needs to understand your content properly, then only it can rank a page. Therefore semantic also helps in Search Engine Optimization.  
Semantic code is nothing but consists of semantic tags.For example: `<section>`, `<header>`, `<nav>`, `<footer>`, `<article>` etc are some of the semantic tags.

## divs and Spans

**divs** :-A `<div>` is a block-level element which is commonly used to group a large number of contents. To create a container or a wrapper or a division in a webpage we use `<div>` element.
**spans** :-It is an inline-level element which is commonly used for smaller grouping of texts within a block-level element.

Earlier in the above section we have used term like block level and inline level element.So what's exactly a block-level and inline-level element?

**Block-level elment**:-A block-level element always begins from a new line and stack on top of each other. It occupies all the available width. Few block-elements are paragraph, div section, article, nav etc.
**Inline level element**:-An inline-level element does not begin from a new line. They come one after one in a line and takes the width according to the content it wraps inside it.Few inline-level elements are span, anchor, strong, italics, bold etc.

## Text Based elment

Some text based element are Headings,p,strong,b,em,i etc.But we have to be careful while choosing between strong or b,em or i because we have to choose one which is one is more semantic.

## hyperlinks

when we go from one page to another page, one document to another document or from one website to another website. Going from one resource to another required hyperlinks. In HTML document hyperlinks are created using anchor <a> tag.
There is two types of hyperlinks path.

1. Relative path:- It help us go from one page to another page in a website.
2. Absolute path:- It help us to go from one website to another website.

## Structure based Element

some structure based elements are header,nav,main,section,article,aside,footer.which help us to give proper layout of the page.
**Header** :-Header elements usually come on top of a page, article, section, or any other division of a page. Generally, heading, introductory text, and even navigations are wrapped inside the `<header>` elements. `<header>...</header>`  

**Navigation**:-The purpose of the `<nav>` element is to group all the navigation links. For example menus, table of contents, and indexes.The purpose of the `<nav>` element is to group all the navigation links. For example menus, table of contents, and indexes. `<nav>...<nav>`  

**main**:-The `<main>` tag specifies all the main content of the body inside a document. All the content coming inside the `<main>` tag should be unique.`<main>...</main>`  

**section**:-The `<section>` element in HTML document is used to define different section on a page. Typically it includes a heading element but not always.`<section>....</section>`  

**article**:-More often we mark up the content like blog posts, newspaper articles, user-submitted content, etc. inside the `<article>`.

## knowing more about CSS

CSS is a powerful language that is used to style and layout the HTML document. CSS can describe how our HTML elements should be displayed on a page.

## Reset css

CSS resets takes all the element and provides unified styles for all browser. It removes all the default sizing, margin, padding, and all the additional styles from the element.  
One of the most popular CSS reset is [Eric Meyer’s](https://meyerweb.com/eric/tools/css/reset/) reset, which targets all the common elements and resets the styles.

## The Cascading Rule

CSS is a "Cascading Style Sheet" where styles cascade from top to bottom. Cascading allows to add different styles and overwrite the previous styles. In cascading whatever styles come at the bottom will have more precedence than the earlier one.  
For example:
```p{
  color: red;
}```
```p{
  color: green;
}```
The green color will be applied to background


