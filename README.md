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
-Using pre and code together
pre and code elments are often comabined to display a code block with proper indentation to let the browswer know this is a block of code the whole thingg is wrapped in a code element to perserve formatting and spacing it was futher wrapped in pre element in the end we have code, br and pre elemnt working together these elemants come in handy for conveying the structure and apperance of code as well as other types of content
Using superscript ,subscript and small
when putting complex equations on a website ,you should look into MathMl its a specialized markup language for math and more powerful then what HTML can do 
we often need a way to marking as fine print in other words small text that is not important but still needs to be included
superscript ,subscript and small can help you get details right when it comes to   typography and conveying the full meaning of your content
# HTML CAPABILITIES
troubleshooting and debugging HTML code
this is more of an inspection of HTML in  the browser developer tools before we move to the HTML elements 
debugging code
to demostrate this we have a demo in notepadd++ that showcases various HTML elements previously covered
using browser devtools inspector
yhe inspector shows a dom tree which is similar to a family tree of elements and is very helpful
# HTML ATTRIBUTES
- HTML offers additional capabilities through attributes which adds power to any element using global attributes
- global attributes consists of four however when looking at global attributes in HTML that works universally we focus mostly on the highly useful ones which are the class attribute and the id attribute
- the class attribute is the most commonly used
Class and ID attributes
another popular attribute is the ID which is similar to class but we can only use unique names one on an entire HTML page IDs come in handy when we need to address specfic elements in Javascript or targeted links
-class and id provide a way to name HTML elements and reference them in other parts of code stack
HTML offers many attributes that enhance user interaction and provide hooks into browser power however there are numeroud attributes like this ,which provide browser APIs to Javascript
# ARIA ROLES
-are like extra attributes that we can add to HTML elements to make them more meaningful and help browser understand what they represent
Web or online accessbility image
-ARIA roles come into play when we want to provide essential information to assistive technologies like screen raeders ,brailie displays and magnifiers to ensure a website is fully accessible
Using the browser accessibility tree
the accessibility tree is like a companion to the Dom tree ,which the browser creates from the websites content ,however it is crucial for assistive devices like screen readers.
ARIA is a powerful tool that greatly enhances web accessibility and is worth exploring futher especially working with a team struggling with semantic HTML or building a complex appliciation interface ,its roles also provide the necessary tools to make your site accessible to everyone
# FORMATTING HTML
Exploring the inner workings f an HTML file and the options we have for formatting our code where as working with extra spaces browser will ignore it
Working with comments in HTML
-according to programmers they enhance code readability by adding comments that explain its purpose
Working with upper-and lowercase in HTML
-HTML evolved the web industry and embraced the idea of using lowercase letters for everything since in the early 80s and 90s everything was capitalised
however there are still ancient websites with all-caps HTML and there are also newe sites that never use capital letters 
-Working with self-closing elements in HTML
a bunch of elements in this course most of them have opening and closing tags .The newer HTML elements always have both tags,however some of the older elements there are no closing tags
# UNSUAL CHARACTERS
-the symbols < ,> and & are important characters when it comes to HTML

