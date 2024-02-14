* HTML stands for Hyper Text Markup Language for creating web pages
* HTML contains series of elements like <p><div><h1>.... 
* HTML elements tell the browser how to display the content.
* HTML describe the structure of web pages.
* HTML is the standard markup language for creating web pages.

* Here is a simple example of HTML code:
    <!DOCTYPE html>
    <html>
    <head>
    <title>Example of HTML Code:</title>
    </head>
    <body>
    <h1>heading no 1</h1> 
    <p>paragraph no 1</p>
    </body>
    </html>

* In the example 
 1.<!DOCTYPE html> is using for declare the HTML5 document.
 2.<html> is the root element of page.
 3.<head> containing the meta information of page.
 4.<title> element specifies a title for the HTML page.
 5.<body> element defines the document's body where the body contain all information like heading, paragraph, links, images and other information.
 6.<h1> element defines a large heading.
 7.<p> element defines a paragraph.

* HTML element is defined by a start tag, some content, and an end tag.
        <tagname> Content </tagname>
* HTML elements can hv attributes and attribute provide additional info about elements.attributes are always define in the start tag.
        <tagname name="value"> Content </tagname>
* HTML headings are defined with the <h1> to <h6> tags. <h1> defines the most important heading. <h6> defines the least important heading.
* HTML paragraphs are defined with the <p> tag.
* HTML <hr> tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule. <hr> element is used to separate content with a line in an HTML page.
* HTML <br> element defines a line break. Use <br> if you want a line break (a new line) without starting a new paragraph.
* HTML <pre> element defines preformatted text. Text inside a <pre> element is displayed in a fixed-width font, and it preserves both spaces and line breaks.
* HTML style attribute is used to add styles to an element, such as color, font, size, and more. common property of style [border,background-color,color,font-family,font-size,text-align,padding,margin]. 
        <tagname style="property:value;"> </tagname>
* HTML contains several elements for defining text with a special meaning. Formatting elements were designed to display special types of text:
                <b> - Bold text
                <strong> - Important text
                <i> - Italic text
                <em> - Emphasized text
                <mark> - Marked text
                <small> - Smaller text
                <del> - Deleted text
                <ins> - Inserted text
                <sub> - Subscript text
                <sup> - Superscript text
* HTML <blockquote> element defines a section that is quoted from another source.
* HTML <q> tag defines a short quotation.
* HTML <abbr> tag defines an abbreviation or an acronym, like "HTML", "CSS", "Dr.", "ASAP". Marking abbreviations can give useful information to browsers, translation systems and search-engines.
        <p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
* HTML <address> tag defines the contact information for the author/owner of a document. Text in the <address> element usually renders in italic, and browsers will always add a line break before and after the <address> element.
* HTML <cite> tag defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.). The text in the <cite> element usually renders in italic.
* HTML <bdo> tag is used to override the current text direction.
        <bdo dir="rtl">This text will be written from right to left</bdo>
* You can add comments to your HTML source by using the following syntax: <!-- Write your comments here -->
* HTML links are defined with the <a> tag. Inside <a> we hv some attribute like 'href', 'target'.
    1. To use an image as a link, just put the <img> tag inside the <a> tag.
    2. To use mailto: inside the 'href' attribute to create a link that opens the user's email program.
    4. We can HTML button as a link.
    3. The title attribute specifies extra information about an element. The information is most often shown as a tooltip text when the mouse moves over the element.
    4. To create a bookmark - first create the bookmark, then add a link to it. When the link is clicked, the page will scroll down or up to the location with the bookmark. use the 'id' attribute to create a bookmark then add a link to the bookmark.
        ex: <h2 id="C4">Chapter 4</h2>
            <a href="#C4">Jump to Chapter 4</a>
* HTML images are defined with the <img> tag.Inside <img> we also hv some attribute like 'src', 'alt', 'width', 'height', 'style'.
    1. src - Specifies the path to the image
    2. alt - Specifies an alternate text for the image
    3. You can use the style attribute to specify the width and height of an image. Alternatively, you can use the width and height attributes.
    4. Use the CSS float property to let the image float to the left or to the right. {style="float:right;width:42px;height:42px;"}
* HTML <map> tag defines an image map. An image map is an image with clickable areas. The areas are defined with one or more <area> tags. The image is inserted using the <img> tag. The only difference from other images is that you must add a 'usemap' attribute.The 'usemap' value starts with a hash tag # followed by the name(#imflo) of the image map. Then, add a <map> element. The <map> element is used to create an image map, and is linked to the image by using the required name attribute. The name attribute must have the same value as the <img>'s usemap attribute. A clickable area is defined using an <area> element. We hv some attributes in <area> 'shape', 'coords', 'alt', 'href'. 
* We can add background image in any HTML element. To add a background image on an HTML element, use the HTML style attribute and the CSS background-image property.You can also specify the background image in the style element, in the <head> section.
* HTML <picture> element allows you to display different pictures for different devices or screen sizes.
* HTML tables allow web developers to arrange data into rows and columns. table in HTML consists of table cells inside rows and columns.Each table cell is defined by a <td> and a </td> tag.Each table row starts with a <tr> and ends with a </tr> tag.Sometimes you want your cells to be table header cells. In those cases use the <th> tag instead of the <td> tag.
* HTML lists allow web developers to group a set of related items in lists.An unordered list starts with the <ul> tag. Each list item starts with the <li> tag.The list items will be marked with bullets (small black circles) by default.An ordered list starts with the <ol> tag. Each list item starts with the <li> tag.The list items will be marked with numbers by default.HTML also supports description lists.The <dl> tag defines the description list, the <dt> tag defines the term (name), and the <dd> tag describes each term.
* HTML <div> element is used as a container for other HTML elements.The <div> element is by default a block element, meaning that it takes all available width, and comes with line breaks before and after.





























