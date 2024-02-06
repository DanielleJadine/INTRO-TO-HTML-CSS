# INTRO-TO-HTML-CSS

# HTML INTRODUCTION
HTML forms the foundation of a website and web app development
is responsible for the marking up content of a website
known as a declarative language

# HTML SYNTAX
Used  to structure web pages
uses tags ,which are enclosed in less-than and greater -than symbols
these tags come in two types - opening tags and closing tags
however these tags work together to define elements 
an entire HTML document is a bunch of HTML elemnts nested inside each other
the browser uses the DOM tree to create accessibility
pay attention to where we open and close tags and how we nest elements within each other ,it helps convey meaning about the content and interfaces.
# HTML PARAGRAPHS/ ARTICLES
Firstly ,there is a opening tag for the article 
inside you will find a headline followed by three paragraphs
however the third paragraph has a emphasized text for effect
then to close the article you will use a closing tag 
this structure tells us the article consists of a headline and three paragraphs
if a error occurs where as the browser is showing three paragraphs as a single text , we will use HTML tags to indicate the paragraphs 
# HTML HEADLINES
Hadlines are titles that lead us to futher information when clicking on it ,it acts as something that will attract te readers attention
HTML elements are used for marking up headlines 
these elments comes in six different types h1, h2, h3, h4, h5 and h6 when used in a browser each headline has a distinct visual effect , they also convey a sense of hierarchy in how the browser interprets and communicates
h1 elements is the largest and most prominent ,while h6 is the smallest and doesnt grab attention that much
other elements just falls somewhere in between in terms of importance or prominence ,however selecting an appropriate headline is generally straightforward but at times determining which level of headline is most suitable can be challenging 
# HTML BOLD AND ITALICS
there are four HTML elements related to this topic which is two for bold and two for italic 
ITALICS
there are two reasons for using italics
-the first reason is to make a strong point 
-the second when using it when typing a name of a movie or Tv show just to indicate to our browser when something should be verbally emphasized and when to simply visually distinguish
however in this case istalics is twofold
BOLD
We use bold when we want to indicate that something is very important or even when we want to warn someone , then we would put the text in bold 
another reason is that you wod want to catch a readers attention when putiing something in bold
# HTML LISTS
there are three types of lists , ordered lists ,unordered list and definition lists
- Unordered list are the most common used type ,each item on the list is enclost in an <li> element which represents a list item
to define the entire list and specify its type , we wrap all ietms in a <ul> element , which stands for an unordered list however if you want to make our code more readable ,indent the list items by adding some spaces or tabs before each one
- Ordered list ,which is similar to underordered list but with a small difference instead of <ul> to wrap the list items we use <ol>
-Defintion list is used when creating a list that resembles a key value pair in computer science , we have terms and thier corresponding description
# HTML QUOTES
this topic consists of two elements which are <cite> and < blockquote> they serve a semantic purpose whereas they inform other computers what something is
also provides a convenient way to apply custom styling.
However ,with CSS we can make these elements look however we feel like by giving blockquotes a special apprance and making it stand out .
-Using blockquotes in context
e.g inside <blockquotes> element there are two paragraphs and the <cite> element however we can include any element we want within the blockquote by even putting a lisy or a headline .
-Using inline quotes
these quotes are simply typed in,but we believe they should be curly quotes and not straight quotes but different languages and regions have their own conventions for displaying quote marks
to make things easier we can just use the <q> element in HTML element which is just short for quote when using this element the browser will automatically provide the appropriate quote marks for you ,howver some HTML elements lie<strong> ,<b> ,<l> and <em> are called inline because they are meant to wrap around phrase of text that are inline with other content but they do serve a similar purpose as the <q> element .
There are certain elements like the block  level elements , block quotes ,paragraphs ,and ordered lists these elements essentially create separate blocks on the page however some of this relates to CSS, where you can switch the layout of the behaviour of elements from the block to inline or vice versa.
# HTML DATE AND TIME INPUTS
-Using date elemnets 
<time datetime=2025-25-05-8>
HTML attributes provide additional information to HTML elements in this case the datetime attribute allows us to specify te date or the time ,the format of time within the date time attribute has to be specfic. Dates and times have a specal format that machines can understand . However we dont have to spell out the entire date on a web page because often websites use phrases like five hours ago or 10 days ago for time staps but behind scences the attribute still uses the proper machine readable version.
machines prefer a highly standardized format
# HTML CODE ,PRE AND BR
-Using code element
code is treated as an inline element meaning it remains part of the sentence its in by default
- Using the br element
- the br element is a simple tag without opening or closing tag it doesnt contain anything inside it, it just indicates where the line breaks should happen
-Using pre element
when wanting to achieve spacing to be an integral part of contents meaning use the HTML and the pre element to achieve that




