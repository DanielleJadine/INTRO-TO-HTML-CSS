INTRODUCTION TO HTML AND CSS

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
Code formatting in HTML
-IN FIGURE41 the character entity was used ,these entities are formatted like , an ampersand ,a short code and a semicolon however you can include them in a HTML file they are converted into the specific file you prefer .We apply this technique to replace every instance of greater than or less than symbols with their corresponding character entities, the WC3 has a handy reference chart for all the character entities.
Using non-breaking spaces in HTML
-non-breaking space has a unique role and usually spaces in the text allow lines to break and works to remain intact
More non-breaking spaces in HTML
-we use a special kind of space called non-breaking space in HTML ,this tells the browser not to break the line between two words however non-breaking spaces can also create multiple spaces between words but the browser will only recognise the first space.
# HTML NAVAIGATION AND LINKING
HTML Links
-whn wanting to create a link you would use the A element which stands for anchor: to achieve this you need to add an herf attribute with a URL enclosed in quotes the URL will take you to where the link is 
HERF- HYPERTEXT REFERENCE
Between the opening and closing A tags ,you can place text or image or even both to make them clickable howver by default the A element is inline and can be placed within a paragraph or any other text.
-URLs can be very versatile because when linking to another website or specific page on the web you can include the entire URL, it does not matter if it has a trailing slash or not 
-these types of URLs are called absoulte URLs because they point to a precise location on the web
-in an absolute URL the HTTP or HTTPS part must be included which stands for Hypertext Transport Protocol
-the difference betwwen HTTP and HTTPS is that the S stands for sercure
Creating a relative URL 
-is not only useful for  the A element linking but also it is a skill used to refernce image files, video files ,CSS,Javascript files or any other files where the path is specified
Creating URLs from scratch
- firslty take in how the files are organised
- then think , about a bunch of files that are neatly organised into different directories or folders so if we want to link a blog post from March 9th instruct the browser to look inside the folder called (blog) and locate the folder named March-9html, however filenames come with extensions like html,jpg,CSS,js whereas folder names simply have names like (blog) or (people) withput any extensions
Creating local URLs
-when creating URLs it can either be relative or absolute .
-relative URLs are based on the current files location,while absolute URLs start from the root of the website
-by using folders and index html files, we can create clean and user-friendly URLs however using relative URLs can be extremely helpful ,especially when working on a project that moves from server to server
# NAVIGATION
Main navigation
- each link is wrapped in a element with the correct URL and then enclosed in an (li) element to create a list of links to maintain the order ,wrap  the whole list in  a (ul) element which represents an unordered list.
- finally encompass the entire menu in a (nav) element to indicate that it is the site navigation
- give the menu some visual apperance so that it doesnt look plain also to attract the readers attention apply CSS styling
 Breadcrumbs
-the breadcrumb trail is another type of menu
-however it uses an ordered list (ol) instead of an unordered list since the order of the links matter
-but do not assign the role navigation to this menu instead we add an (aria label) of (breadcrumbs) to provide context when read aloud
Footer links
-these links are typically found at the footer of a page ,they are not part of the  sites navigation
-no (nav) or (unordered list) are necessary here it is straightforward a representation of twp phrases linking to additional content
# HTML Working with Graphics and images 
-when wanting to add a image to a webpage ,we use the image element ,which is written as img
# Image element
-there are four attributes that need to be included in every image
1. we have the source attribute (src) ,which tells the browser which image file to load
2. then we have the alt attribute (ALT) which provides a text description of the image
3. lastly we have the width and height attributes which determine the size of the image .
# Working with a image element
-when the image`s URL is pasted into the source then the image wil start loading ,then add an ALT attribute which serves as a replacement for the image when it cannot be seen
-we can also make ALT text intersing by describing the image
 Responsive images
Html allows us to deliver different image files to screens of different sizes. We can create multiple images files and include them as options in our HTML code.
 Responsive width
Instead of specifying the pixel density like one x, two x, etc indicate the width of each file ,then the browser will decide which image to show based on device density and viewport width
 Figcaption and figures
Basically speaking this shows us how to add an image to a web page and how to match a caption to the image
Figures can be used for more than just images but for interactive graphic 
# Working with media
Working with audio
The audio element is different from the image element because it has both an opening and closing tag it makes it more modern and gives it more power and flexibility
< audio controls src =“audio.mp3” >
Working with video
Just like the audio element ,video element also has a opening and closing tag ,to display a video use the source attribute to specify the video file and if the controls attribute is added the browser will automatically create a video player
Working with Captions and subtitles
We are going to use the track element and link it to a text file to add captions to the video, this element adds functionality to the video player allowing viewers to toggle captions on and off or switch between different subtitle options 
Embedding Media via Iframes
-it is more likely that you will utilize a video service this involves embedding the video player they offer onto a webpage
-Embedding refers to taking content from one site and placing it within the middle of another sites page
-Iframe element has attributes like height and width that can be adjusted, the src attribute is used to specify the source of the video file.
-It is common practice to embed complex content from a service that handles the technical aspects
<!—Iframe=embed content from another source into an HTML document ex. Used for ads ,used in many hacking techniques>
# Content identification
The internet is worldwide and people speak various languages ,in HTML there are tools to indicate the language of your content,by setting things up the correct way search engines will understand whichnlanguage websites are in
<html lang=“en -US”>
…
</html>
The lang attribute
-the lang attribute is used to specify the language of a webpage
-set the language on the main elment that wraps everything else which is usually the HTML element 
-the lang attribute has many options not only to indicate language or regional versions of a langage but also other qualities like the writing system used.
-however, it is also important to specify the contents direction ,use the dir attribute to indicate the direction and it can be applied to any element
-when there is a mix of content ensure to indicate the change in direction for each phrase is set
The meta attribute
-Unicode particularly UTF-8 is widely used it is like massive specification that encodes content to support a vast range of characters ,scripts and even emojis.
-Unicode started with around 7000 characters in 1991 and has expanded to over 137000 aiming to encompass all languages,scripts and communication forms like Brallie and musical notation
-inform the browser about the character set being used
-to specify the charset in HTML simply include a meta charset tag that equals UTF-8. Place this meta element  within the head element on every page of the website
-By definig the lang,dir and charset for a project you contribute to a more inclusive future for the web
<meta charset=“UTF-8”>
HTML Generic elements ,Div and Span
<div> BLOCK LEVEL ELEMENT
<span>- INLINE ELEMENT
Essentially these elements do nothing until CSS or javascript is applied to them.
# HTML Intergration
HTML Page
HTML and all the elements ,attributes ,roles and tools used to mark up content on websites or web apps have been covered.HTML plays a major role in explaining what these things are ,but it is not just limited to that because HTML files are a vital part of the web
-When you want to visit a website you open a web browser or web view and enter a URL,the web server responds by sending back the specific HTML file located at the address
 Standard HTML page head
 - text is often stored in databases and multiple static files are combined in real-time customized for each user
 -visual styling is in CSS files,Javascript is in separate Javascript files and there are additional files for images ,video, audio and ads
 -users visit a URL which prompts a request for an HTML file ,and the server returns a single HTML file
 -the browser reads the file and follow its intructions ,this process is consistent everytime so that the initial HTML file that is returned when a web page is requested is incredibly important it serves as the central hub for everything that happens after the site first loads
 -Once the browser gets the file it starts reading it immediately and follows the instructions one by one
 Structure of the whole HTML file
 -the build system or cms may not have a single file containing all this code ,but there are templates or theme files that determine what gets sent,however once the HTML file is built there are a few crucial parts that every web page needs.
    1.the file should begin wit a doctype statement ,which indicates the era of this HTML file ,however in the past there were different doctype declarations for older HTML versions
    2. next we enclose everything else on the page within an HTML element which means an element named HTML ,it tells us that all the content within it is HTML place the opening HTML tag at the top and the closing HTML tag at the bottom
- At the beginning specify a few things about the web page ,declare the language being used and the content flow direction ,this code is for a website using US-English that reads from left to right 
 -Inside the HTML element there are two main parts where evrything goes;the head and the body, create them using the head and body elements.
 -the head contains all the metadata that the browser needs to know but will not display on the page 
 -the body on the other hand is for all the content and is composed of various elements already discussed in this course,the body is where most of the action happens.
 -The doctype declaration ,HTML head and body elements are the essential building blocks of every web page.
Document Head
-Inside the head of the webpage you put important information that the browser needs to know about the website
-the character set is not something you want your users to see it is intented for the browser ,to convey the use of the meta element
 -ensure thst meta elements sre only plsced inside the head as they provide ,metadata about the page.
 HTML file head section
 -the web page tile is what appears on the browser tab or bookmark when it is saved,also the name appears under top sites when a new browser is opened
The meta element –one common use is to inform the browser that the layout has been adjusted to fit small screens making it  a responsive website
The link element- is a crucial component used extensively within the head section
The script element –is commonly used element in an HTML documents head it instructs the browser to load a Javascript file
Content Structuring consists of six important elements
1 Main-is used once per webpage and tells the browser where the main content is located
2.Header-the header and footer elements mark the head and footer areas on the page. The head is where the files metadata lives and is not displaye to users and the header is used for site headers ,article headers and headers within content .A header is usually found at the top of most web pages and may include a logo,site name and navigation. 
3 Footer-sigifies that there are extra things to convey regardless of the positon on the page
4 Article-Often starts with a title ,subtitle,authors name and publication date which can also be considerd a header ,however some articles begin with metadata like hastags or share buttons which are suitable for a footer element
5 Section-is used to mark sections of content ,its also useful for dividing different topic zones on a website ,each section typically starts with its own headline
6 Aside-is for content that is off to the side like sidebar information or additional details that accompany an article but are not part of its main flow
 
# HTML Working with forms and interactive elements

Form fundamentals
-Form fields have  been an essential part of the web for a long time , its important to use semantic elements in HTML instead od divs and spans because it allows us to leverage the built-in power of the browser 
-because it allows us to leverage the built-in power of the browser,this way we avoid wasting time and effort trying to recreate functionalities that already exists in the browser
-moreover,bu using HTML form elements ,we ensure that forms will be compatible with all devices and input/output hardware even those we may be familar with 
Working with forms
-to create a form, we start with the form element which informs the browser about the presence of a form using opening and closing tags, in  a sign up form there will be tow fields : name and email  these field names can be turned into labels using the label element .Use the input element to provide places for users to input their name and email and unlike other elements the input element does not have a closing tag due to its older structure
-it acts as a marker for the browser to bring in functionality and place it there ,this is where the magic forms ,now a button is needed for users to submit the form use the button element for this
-the text on the button can be customized to whatever is required ,although the form looks good visually it currently lacks functionality
-to achieve this we need to make a backend ,we can add an action and method attribute to make a demo work,although using the "get" method is not secured and is not recommended for real websites
-once set up land on the response page, but the data that was entered does not appear ,this is because the input fields need a "name" attribute to report the data 
Other form element types
-here are the exact same name and email form elements along with a button just with better styling ,add three more fields ;password,search and phone number to see what they can do
-these are very similar in structure to the text and email form fields for the password field ,the type equals password, search and phone number is type equals ;tel, when we start to type into the password field,the browser is warning us not to use this textbox as the site is unsecured and that is because this page is set up to us HTTP and not HTTPs .
-users should not fill out forms like this on sites that have not been secured by HTTPs ,especially not passwords some browsers will bring up an intergrated password manager on password fields to help the user fill in their pasword faster.
-the search field appears a bit to different ,some browsers have a different look and feel for search and will bring up a slighty different keyboard the phone number field will prompt many devices to provide a telephone pad for the keyboard which makes sense when entering a phone number 
<form action=“success.html” method =“get”>
<label for=“name” > Name</label>
<input name=“name” id=“name”  type=“text”>

# Organizing Tabular Infromation in HTML
HTML tables
-you may have heard somewhere that HTML tables are evil and that you shouldnt use them ,in fact you should use them whenyour content is a tble however what you shouldnt do is misuse them
-the whole point of semantic HTML is to tell computers everywhere what the thin is you have ,eg if you have a button use the button element ,if you have a table use the table element
-long time ago when the web was an infant we did not have CSS ,basically we ddnt have the proper tools for styling or laying out our content on a web page those had yet to be invented
-so people did all kinds of things to try and create styling and some form of layout , we typeset our headlines in photoshop and exported them as images so people looking at it would see something beautiful
-the problem wasnt the actual headline it was the picture of the headline,without the proper tools to layout content on the web page people used to take their content and break it up into many pieces and place those into the cells of an HTML table,though this worked it was a horrible hack
-things may have looked okay or even good but the semantics were terrible ,the content was not accessible it was not reuseable or not findable however there is still one place this technique is used which is in HTML email but this is not what tables should not be used for ,it should be used for tabular data so we going to make as if the email thing isnt happening.
 Example of tabular data
 -a chart of data from a research project ,that is a table a bunch of information by aligning things into rows



