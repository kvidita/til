# Hello I'm Vidita. Here's my dailylogs
- [my pages](/til/my-pages)
- [projects](/til/projects)
- [works](/til/work-pipe)

## 16th june 2023
- TODAY'S LEARNINGS

## 14th june 2023 
- TODAY'S LEARNINGS
  1. containers in html
  2. div tag is used as a container
  3. header tag :- The <header> element represents a container for introductory content or a set of navigational links or the logos.
    - nav tag :- the tag is useful for the navigation links in the header section.
  4. main tag :- main tag specifies the main content of the document and is useful for the voice over to understand the main content.
  5. section tag :- it defines a section of the main content of the document, that should be meaningful together.
  6. footer tag :- it is the bottom section of the document, that may contain the copyright, terms and conditions etc.

## 13th june 2023
- TODAY'S LEARNINGS
  1. img tag for placing images <img>. source must be mensioned through ```src``` attribute. width and height can be customized.
  2. hr tag for a line throughout.
  3. alt :- alternate text that should be displayed in place of the image.
  4. target attribute :- to mention where the link is desired to open.

## 12th june 2023
- TODAY'S LEARNINGS
  1. introduntion to html 
    - html standing for HyperText Markup Language or HTML is the standard markup language for documents designed to be displayed in a web browser.
    - Markup language:- A markup language is a text-encoding system consisting of a set of symbols inserted in a text document to control its structure, formatting, or the relationship between its parts.
    - HTML elements are the building blocks of HTML pages(Elements such as head and body). HTML provides a means to create structured documents by denoting structural semantics for text such as headings, paragraphs, lists, links, quotes, and other items. HTML elements are delineated by tags, written using angle brackets.
    - Elements of html:-  These are indicated in the document by HTML tags, enclosed in angle brackets, generally in pair having start tag and end tag. The general form of an HTML element is therefore: <tag attribute1="value1" attribute2="value2">''content''</tag>. Some HTML elements are defined as empty elements and take the form <tag attribute1="value1" attribute2="value2">, for eg:- <br />.
    - * Elements are not tags.HEAD element is always present, even though both start and end HEAD tags may be missing in the markup. Tags are used to delimit the start and end of elements in the markup. The start and end tags of certain normal elements can be omitted.
    - There are three types of elements
      - normal elements :- start tag, any numbers of attributes, some amount of content, including text and other elements, and end tag, eg, title tag
      - raw text elements :- start tag, any numbers of attributes, some amount of text content, but no elements and end tag
      - void elements :- only have a start tag, contains any numbers of attributes
    - Attributes:- HTML attributes define desired behavior or indicate additional element properties. Most attributes require a value.
2. TAGS LEARNED
  - html :- known as the root element of the document. We use it as first tag because it helps browsers recognise that a given document is a HTML document.
  - head :- The head tag is a container for all the head elements in an HTML page. for eg, title tag.
  - title :- The title tag defines the title of the document. The title must be text-only, and it is shown in the browser's title bar or in the page's tab.
  - body :- The body tag defines the document's body.body element contains all the contents of an HTML document, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.There can only be one <body> element in an HTML document.
  - heading tags: h1, h2, h3, ... to h6. (* headings must be used for structure not for font size, there must be one single h1 tag in the document. Lower level of heading must not be used before it's preceeding level heading)
  - paragraph p :- writing a text in a paragraph (a paragraph is not nested in a paragraph)
  - bold b, italic i, underline u, break br.
  - lists: 
      - ordered and unordered.
      - ol          ul
      - list item: li
  - table:
      - table,
      - table row tr.
      - table heading th.
      - table data td.

  - anchor: <a href="url here">Visit google</a>
  
  - what is Inline elements and block elements. Span is inline element.
  - pre tag
  - id
  - anchor tag with id
  - anchor tag with target  "_blank"

  - Styling
    - color, background-color, font-size, font-family, border-style, border-color, text-decoration, text-align

3. By default style get inherit , you can override style in child.
  

    

## 10th june 2023
- TODAY'S LEARNINGS
  1. mocking some function using 'it', we can use context to mock a function.
    -function mocked can be declared as 
      const mockedFn = context.mock.fn()   :- (specifying that some function is being mocked).
  2. using done while mocking :- specifies that the assertion will be done only after the specified function is called.
  3. for setTimeout, ```the done``` and assertion shall be placed in the right place.
  4. * once code is written, just think about the work it does, internal code must not be remembered.
  5. MVC -(Model-View-Controller)
    - program logic is divided into three interconnected elements
      1. Model:- (central component) application's dynamic data structure, independent of the user interface. It directly manages the data, logic and rules of the application
      2. View:- (Any representation of information) Multiple views of the same information are possible, such as a bar chart for management and a tabular view for accountants.
      3. Controller:- Accepts input and converts it to commands for the model or view.
    example tic-tac-toe done by jayanth.

## 9th june 2023 
- TODAY'S LEARNINGS
  1. inheritance concept 
    - any class is an instance of it's parent
    - parent's public methods and fields becomes accessable to the inhereting class
    - super method refers to the parent class
    - while a derived class inherits a base class, 'super(arguments)' must be the first thing to declare in constructor
    - while inheriting a class 'extends' keyword is used
    - for eg. anything in js is an object as js internally extends everything to an object.

## 8th june 2023
- TODAY'S LEARNINGS
  1. use of documents when required

## 7th june 2023
- TODAY'S LEARNINGS
  1. process.stdin.setRawMode()  :-  a method to take input from standard input as a characters only
  2. exec :- a function used to run a child process
  3. afplay  :- used to play audio
  4. process.stdout.getWoindowSize()  :- to get the window size
  5. process.stdout.columns  :- used to get columns of the window
  6. process.stdin.rows :- used to get rows of the window
  7. process.stdin.cursorTo  :- used to place the cursor in the screen where you want
  8. process.stdout.clearScreenDown()  :- used to clear the screen below the cursor's last position
  9. "a" in obj (checks presense of a key called "a" in object obj)

##  6th june 2023
- TODAY'S LEARNINGS
  1. Set :- a class that creates a set out of given string
  2. EventEmitter
  3. process.stdin :- The process.stdin property returns a stream connected to stdin (fd 0)
  4. process.stdout :-  The process.stdout property returns a stream connected to stdout (fd 1)
  5. process.stdin.on("data")
  6. process.stdin.on("end")
  7. process.stdin.on("err")
  8. fs.createReadStream()

## 5th june 2023
- TODAY'S LEARNINGS
  1. package
    - making package and requiring package
  3. npm
    - initializing :- npm init
    - installing some package :- npm install table 
    - for eg:-
      - npm table (package)
      - npm colors (package)

## 27th may 2023
- TODAY'S LEARNINGS
  1. dependency injection 
    - to have greater control over the code
    - to make code more flexible, less coupled or decoupled
    - helpful for testing the functions that does not returns anything
  2. inversion of control
  3.  jayanth's session
    - example for inversion of control > games having options of changing themes and levels
    - session on markdown documentation
    - creating github page
    - suggestion on putting daily notes on github page collectively
   
