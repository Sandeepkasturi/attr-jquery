# attr-jquery
An jQuery Method to Access HTML Attributes
The first line declares that this is an HTML document.
The <head> section of the HTML document contains two <script> tags. The first one includes the jQuery library from a remote source (in this case, from the official GitHub repository). The second one contains the code that will be executed when the document is ready.
The $(document).ready() function is used to specify what should happen when the HTML document is fully loaded and ready to be manipulated. In this case, the function is used to get the value of the title attribute of the first <em> element on the page.
The $() function is the entry point for jQuery. In this code, it selects the first <em> element on the page using the $("em") selector.
The .attr() method is used to get the value of the title attribute of the selected <em> element.
The var title = ... line declares a variable named title and assigns it the value of the title attribute that was retrieved in step 5.
The $("#divcls").text(title) line sets the text of the element with the ID divcls to the value of the title variable. This replaces the initial content of the <div> element that contains the <em> and <p> elements.
The <body> section of the HTML document contains a <div> element with the ID divcls, which initially contains an <em> element with the title attribute "Jquery Attributes" and a <p> element with the ID para.
When the document is fully loaded, the jQuery code selects the first <em> element on the page, retrieves its title attribute, and sets the text of the divcls element to the value of the title attribute. As a result, the initial content of the <div> element ("This is first paragraph") is replaced with "Jquery Attributes". The <p> element with the ID para is not affected.
