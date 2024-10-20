# CrytoniteTaskphase

HTML Report:

Elements and Tags-
Elements on an HTML page are just pieces of content wrapped in opening and closing HTML tags.
For example, an opening paragraph tag looks like this: <p>.
<p>some text content</p>

Void Elements-
Some HTML elements do not have a closing tag. These elements just have a single tag, like: <br> or <img>. They are known as void elements because they are void of any content, there is nothing inside of them. No closing tag means they can’t wrap content like other tags do.

Doctype-
Every HTML page starts with a doctype declaration. The doctype’s purpose is to tell the browser what version of HTML it should use to render the document.

HTML element-
After we declare the doctype, we need to provide an <html> element. This is what’s known as the root element of the document, meaning that every other element in the document will be a descendant of it.

Head element-
The <head> element is where we put important meta-information about our webpages, and stuff required for our webpages to render correctly in the browser.

Body element-
The final element needed to complete the HTML boilerplate is the <body> element. This is where all the content that will be displayed to users will go - the text, images, lists, links, and so on.

Example:
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>My First Webpage</title>
  </head>

  <body>
    <h1>Hello World!</h1>
  </body>
</html>

Paragraphs:
A paragraph element is defined by wrapping text content with a <p> tag.
Headings:
Headings are different from other HTML text elements: they are displayed larger and bolder than other text to signify that they are headings.There are 6 different levels of headings starting from <h1> to <h6>.
Strong:
The <strong> element makes text bold. It also semantically marks text as important
Em:
The <em> element makes text italic. It also semantically places emphasis on the text
Comments:
HTML comments are not visible to the browser; they allow us to comment on our code so that other developers can read them and get some context about something that might not be clear in the code.In order to write an HTML comment, we just enclose the comment with <!-- and --> tags.

Lists:
Unordered List:
Unordered lists are created using the <ul> element, and each item within the list is created using the list item element <li>.
Ordered List:
Ordered lists are created using the <ol> element. Each individual item in them is again created using the list item element <li>.
