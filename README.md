 INTRODUCTION TO HTML AND CSS
       
# HTML INTRODUCTION
HTML forms the foundation of a website and web app development
is responsible for the marking up content of a website
known as a declarative language
HTML-Hypertext Markup Language
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
 -a chart of data from a research project ,that is a table a bunch of information by aligning things into rows and coloums that is a data table ,when you decide to instert a table into the document ,when do you decide if you going to use excel instead of word? or google sheets instead of google docs?
 -this is how you decide to use a table in HTML because there is specific information that is best conveyed in a table,comparing prices of things tat are for sale ,population data by town ,election results,product comparisions ,schedules ,bits of information collected that people want to quicly compare .
 -this is what tables are for ,the data might be numbers but not alwys it could even be text,images or other things as long as there is a semantic reason for the data to be organized into a table that meaning is added by an arrangement into rows or columns the table conveys a relationship between the data cells and the header cells between one column oe row and te next
 -if that is the nature of the information at hand then use a table in HTML to semantically mark it up as what it is ,you can use CSS to rearrange how a table is displayed changing the layout for different sized screens is also okay it does not always have to look like a table but what matters is that if the information is inherently a table ,then use a HTML table.
 Building HTML Tables
 -to create an HTML table you use serval different HTML elements in just the right combination: Table,TR,TH and TD
   -The table element wraps around the whole table around all your content and markup for that table ,marking the beginning and end of the table itself ,the tr element stands for table row and wraps its self around a set of elements defining them as belonging to the same row ,the th element stands for table header and defines a header for a column ,the td element stands for table data and marks cells up for data
   <table></table>
   <tr></tr>
   <th></th>
   <td></td
        
 # INTRODUCTION TO CSS
 -CSS ,short for cascading style sheets is the language that controls the pretty stuff on websites.Html and CSS workhand in hand to create the visual aspects of a webpage
 What is CSS?
 -A style sheet is like a CSS file that holds all the styles for a webpage,that adds visual appeal to a webpage ,to connect the Html and Css you simply link them together Html and Css are closely conneted and works hand in hand with each other however before we go futher into Css lets take a look at Html
 Plain browser HTML page
 -HTML is all about recognizin commonly used elements such as paragraphs ,headings ,lists and links etc that define the structure of a webpage ,when viewing raw Html in a web browser it looks pretty awful and ugly.
 -A style sheet within the browser determines this unattractive apperance with Times New Roman font ,bold headings and understandable webpages using only HTML they are certainly not pleasing to the eye to make our pages look better by changing the font colors and spacing we need CSS:
 -CSS has two parts, 1.The selector 2.The declaration block
 -The selector specifies a pattern in the Html and if the pattern matches the styles within the declaration block are applied to the corresponding Html elements,it is possible to have multiple styles applied to the same pattern and that is where the cascading part of Css comes into play.
 -In Css ,each style declaration consists of two parts which is A property and A value
 -The first aspect of Css is the selector because it is essential to be able to select specific elements in HTML,without that ability understanding the properties and values will not be very useful
 Writing your first Comment and Element Selector
 -To get started with Css,we willl begin by writing simple Css code for your document,in the exercise files locate the link to the starting sublime text for this section titled "01-01-start writing your first element selector" ,when opening it you will find a set of headings ,subheadings and paragrphs that we can work with
 Css Selector
 -in the exercise file example,we have an H1 representating the name of our site ,H+ sport,followed by a paragraph an H2 for company history and another H2 for guarantee and ideals which includes guarantee and philanthropy sections,there are several pararaphs in between.
 -There are also a few notes like an HTML comment at the top ,indicating that Html comments are different from Css coments ,in Css comments are written with a slash star and you can leave yourself comments too for reference while writing code now lets focus on selectors.
 -The first type is the element selector,if you want to select all the paragraphs on our page and make them blue,we can use the HTML element "p" as the selector ,so in our Css we write "p" without the angle brackets and set the color property to blue as simple as that however we can make it more complex later on.
 -If we want to make all the H2s red for example we use the selector H2 in the Css again,we use the color property and set it to red ,now all the H2s on our page will be red 
 Writing a Class Selector
 -in our current work all paragraphs have the same blue color however we want to make a specific paragraph green so then we can assign classes to  Html elements to create a reference point for styling , a class attribute that can be added to any Html elements providing additional details about the element
 Start Class Selector
 -Start with the Html code,if we want the first paragraph to be green we can add a class attribute to the paragraph tag and give it a name like"intro" ,this way it will stand out as the introductory paragraph in Css we use a dot(.) before the class name to differentiate its form HTML element selectors.
 -Write "intro" and set the color to green ,now if we want to style a specific part of a paragraph differently we can use a span element with a class attribute for example make the sentence about the guarantee orange and bold ,you fo this by adding the span tag with class="gurantee" around that sentence in Html.
 -Then in Css, we write ".guarantee" to select that class and set the color to orange and the font-weight to bold
 Finish class selector
 -Take the sentence "Philanthropy is extremely important to us" and make it black,bold,and all uppercase,a starting point has already been provided with the setting of the class name as "important" and the Css property"text" transforms:"uppercase",find a way to select that sentence in the Html and complete the style by making black and bold.
 Grouping Selectors
 -There are times when you want to apply the same style to different types of selectors e.g if we want all the paragraphs on the page to be green ,you should know how to do this as it was explained above.
 Start Group Selector
 -now consider making list items green too,take a look at the Html and consider how we would achieve that most likely it would be written as<li>{green;},however if we had many other elements and classes that also needed to be green it would mean that this would be a lot of repetitive code if this route was followed so this is where grouping selectors come in handy instead if writing seprarte styles for <i>p</i> and <li></li> we can combine them using a comma :<i>p.li<i>{green;} the web browser will apply this style to all paragraphs and list items evaluating each one individually.
 -what about using Css we can do that tooo!
 Finish Group Selector
 -lets say we want to make thr words "mineral water" ,we can add min<i>eral<i> to the selector where min<eral> is the name of our class then inside the Html we can apply the class to the specific text using <spanmineral> mineralwater </s pan> this will make the word mineral water green too ,so whenever you see slectors grouped together with commas,it means each of those items is a separate selector ,whether its paragraphs ,list iteams or anything with the class "mineral" the text will be atyled as green 
# CSS Images and colors
Identify a color scheme
-When it comes to color ,it may seem simple however it is a topic that deserves its own course the goal is to choose a color scheme or specific colors for your website .
-if you have to design a background you can create it yourself ,if you struggle with colors not to worry there are plenty of resources that can help you.
-We will explain Canvas approah but if you search for a color palette genertor on Google ,there are many other options available
-Canva is like a friendly graphic design companion for non-designers ,they offer three different methods for creating color palettes 
-the first one displayed at the the top of their webpage and you can findthe link in the exercise files, Canva extracted some colors from the donut picture that you canuse for a webpage about donuts, another way to create a color palette generator .
-Next we have a photo of people in a canoe,notice that we extracted colors directly from the image ,such as dark green,pinkish and lighter grays however if you continue clicking you will find various options for demo images,so if you come accross an image you fancy and want to use its color scheme simply upload it to Canva and you may have discovered a palette that suits your website.
Color Pallette Generator Demo
-there are varoius color palettes available and these are just a few examples they have, you can explore many more options they have
Formatting Color in CSS
-after selecting a color palette the next is to incorporate it into your code, it might sound straightforward since this has already been covered in tis course.
-up to this point we have been using what is referred to as named colors ,these are colors that have specific names assigned to them however while there are millions of colors available online only a limited number of them have names in CSS.
Named Colors
-the provided color chart displays some examples of these named colors that can be used in code, however it is important to note that your color palette may not include any named colors and there are only around 130 of them available so what do you do if the color you want to use doesnt have a name
-the most common way to represent colors online is through hex codes also known as hex values or hex format ,hex is short for hexadecimal
-hex values are typically six-digits long and consists of numbers zero to nine and letters A to F 
-the first two digits represent red ,the next two represent green and the final two represent blue ,these digits correspond to numbers ranging from zero to 255
-Canvas color palettes also display hex values,color names and hex values are most commonly used for working wit colors on the web
-while editing other peoples CSS you may come across different syntax worth-mentioning for instance,the hex value "7778899"can be shortened to "789" if each two-digit pair is the same ,this three-digit format is relatively common but only applicable when numbers are identical
Other Color Formats
-another syntax you might encounter is the RGB format ,where colors are written out using Base 10 numbers to specify the red,green, and blue channels ,this formats can also be represented as an eight-dight hex number or RGBA ,in both cases the last number (e.g,CC in the RGB value ) corresponds to Alpha which relates to opacity and transparency of the color.
-it determines how well we can see through the color,other color formats like HSL OR HSLA may also be used occasionally , particularly within platforms like squarespace  converting color formats is a breeze! just enter your color value into google and it will provide you with a color picker that offers various conversions colorpickers
-if you prefer DuckDuck ,go it also gives you color conversions along with complementary and analogues colors for your website ,another option is to visit the color Hex website where you can explore shades ,tints , and color palettes specific to your choosen color  depending on the specific information you need any of these resources can come in handy
Background Text Color in CSS
-In the excersie files,you will find links to the starting and ending states for Sublime Text along with additional resources lets begin by testing a named color
02-03 Start Background and text in color
-In the H1 section ,there is a lovely pink color ,but it is hard to read on a white background ,to find a color we like refer to the named color chart provided in the excercise files, scroll down, and choose a teal color by changing the pink to teal , we can see that it works well on our webpage
-another approach is to select a color palette , there is one called "Fiery Cracked Earth" in Canva which includes the colors you may want to use it as it is important to note that Canva assigns names to these colors but they may not work in Sublime Text 
-Instead work with the hex values provided on the CSS named colors chart e.g if you want to use the alternative teal color for an H2 copy the hex values provided on the CSS named Colors Chart e.g if you want to use the alternative teal color for an H2 copy the hex code from Canva and replace the existing color in the CSS
-we can also change the background color for elements, by using the "background-color" property and specify a hex color , color the background behind specific elements for readabiltity adjust the text color as well ,for instance set the  text color to white using the hex code"FFF" or"FFFFFF" for white background
02-03 Finish -Background and text Color in CSS
-Lets continue to the undered list(ul), instead of using a text color set it up as a background color then choose the beige color from canva and apply it as the background color for the ul,lastly remember that we can also style the entire webpage using the "body" HTML element by selecting a specific color such as the yellow color from canva you can change the background color for thhe entire page giving it a different look than the default white
-lets wrap it up ,we have covered the idea of using colors in the text and background elements you can choose a color for text and another color for background whether it is a specific element or the entire page we also demonstrated how you can select colors from the named color palette or create your own custom colors using canva
Understanding images in CSS
-Imanges are frequently found on webpages ,they can be added either in HTML or CSS firstly we will discuss the image formats suitable for the web and then explore how to include using CSS and HTML
Common web images types
-there are various image formats like GIF , PNG , JPEG ,BITMAP, TIFF and more proprietary formats like PSD,traditionally the web has supported three types of image formats 
1.GIF-has limited colors but could include transparency and animation
2.PNG- has more colors and transparency but no animation .GIF and PNG were suitable for illustrations such as logos or cartoons
3.JPEG- stands for joint photographic Experts Group was optimed for photographs ans supported millions of colors but lacked transparency and animation
-recently a new image format called WebP  has emerged ,WebP csn be used for any image type and offers high compression for smaller file sizes resulting in faster website loading times its expected that WebP will grow in populartity due to its versatility and efficiency in loading both photos and illustrations quickly with small file sizes, when working with images it is important to choose the right format ,saving a photograph as a GIF would result in color loss and potentially larger file sizes ,another tip is to make images smaller for faster downloads and this can be achieved by adjusting the dimensions of the image to the required size, trimming or cropping unnecessary parts, and resizing the image.
-images taken directly from mobile phone or cameras are usually large and take longer to download once the dimensions are set , reducing the file size helps optimize the image faster loading
-tools like tinypng.com or Adobe Photoshop can be used to reduce image files sizes e.g an image on tinypng.com was reduced from 57 kilobytes to 15 kilobytes without any loss in quality ,taking this extra step improves website loading speed and enhances the user experience
-Now that you have an understanding of images lets explore how to include them inqwbpages using HTML and CSS ,in HTML you can use the image element to place an image on the webpage alongside the text ,these images are crucial for conveying the pages message such as logos or social media icons ,on the other hand CSS allows you to include background images which are purely decorative and not essential to the webpages text
-Background images can repeat or display only a portion of the image based on configuration ,lets delve into some of these properties in code
Working with Background images in CSS
-you will now adding background images to our webpage ,first check the images we are working with inside the CSS you will find two background images as comments you can see the property background image , and the URL value enclosed in parenthes
-copy the URL and paste it into a new tab to view the images , the "blue dots" image consists of multiple blue dots whie the "Lil CSS,no code growth" image has a different design .its important to preview the images before using them
02-05 Starting Working with Background images
-now apply the "blue dot " image to the webpage ,remove the comment and add it as the background image for the body element in HTML,notice that the image size is smaller than what it appears on the page ,but it adjusts well
-Background images flex and can tile both horizontally (X-axis) and vertically (Y-axis), creating a wallpaper effect ,this works nicely for low  contrast images like the "blue dots" alternatively you can assign the background image to specifc elements ,such as an H1 heading and it will only fill the space.
-the text may look tight against the edges and things might appear unpleasant at this point , but we will improve it later in the course
02-05 Finish-Working with Background Images
-by experimenting with different background images and properties you can enhance the visual appeal of our webpage , the image set as the background of the UL looks a bit awkward in this case ,so make it better by changing the bottom to around 50% this will reduce the empty space and show more of the plant in this specific instance
# Understanding type in CSS
-Unattractive and poorly designed websites bother most people and they agree that there is something undenibly wrong with the way the pages,the main issues are the fonts and the spacing
-lets start by discussing fonts in this chapter ,spacing will be covered later,already you have some knowledge about fonts so we will build upon that
Common types of fonts
In general people who are not designers usually categorize fonts so that its more simple
-Common font types in CSS refers to different styles of fonts that can be applied to text which there are two types:
-Serif-fonts with small line or ”feet” at the end of characters , they are more  associated with a traditional ,formal appearance,when letters were manually set on a printing press ,they were never perfectly aligned ,the serifs helped connect the letters making the text easier to read on the other hand 
-Sans Serif- fonts without the small lines at the end of characters ,they typically have a modern look with computer typesetting san serif fonts are mainly used on the web for extented text because they look clean and are easy to read.
-so what is the default font used on the web you might ask well it is usually Times New Roman ,but not always becaause web fonts are a bit more complicated than print fonts because they depend on where the fonts come frpm, people access web pages using various devices like phones , tablets and desktop computers even though some individuals have many fonts installed ,while others only have the default fonts on thier devices .
-When a font is not specifically listed your web page will call for a font from the users device ,this limits your font choices when working with CSS to ensure compatibility it is common to specify multiple fonts at once known as font stack for instance a common font stack is arial, helvetica ,san serif however arial is commonly availble on pcs  ,helvetica on macs and sans serif is a fallback that requests the devices default sans serif font if arial or helvetica are not available.
03-02 Start Applying type formatting
-To apply text formatting in CSS ,you can use various properties to control the appearance of text
-Including font-family , font-size , font-style , font-weight, text-align , text decoration and color among others
-You can adjust these properties according to your design requirements to achieve the desired type formatting for your website .
-this property allows us to change the fonts on the page use a font stack starting with arial ,the helvetica and finally sans serif ,the web browser will evaluate these fonts in order if aerial is installed it will be displayed otherwise it will try helvetica
-if neither is available the default sans-serif font on the computer will be used on your computer have both aerial and helvetica installed ,if we look at the plus sign on the page we can easily compare the two fonts and when aerial is removed from the font stack
Understanding and Applying size in CSS
-up until now the size of our text has been determined by the web browser default style sheet ,there is nothing inherently bad about these sizes but sometimes you may feel the need to modify them or apply them electively to specific sections in text
-To apply size in CSS ,you can use various properties to control the dimensions of elements.
-Including width height ,padding ,margin and border 
-You can adjust these properties according to your design requirements to control the size and spacing elements of your website
Font measurement and size
-inweb design there are two types of sizing absolute and relative ,absolute sizes such as points or pixels remain the same regardless of the screen size , on the other hand relative units like percentages or R-E-M can adjust based on the page size when zoomed the font sizes using relative units scale proportionally wit the rest of the page this is why designers often prefer using relative units for better flexibility
Font Size conversion
-according to web developers the preferred font size unit is usually rem ,in simple terms 1 rem is equivallent to 16 pixels so if the font size is specified as 1.5 rem you can mulitply it by 16 to get the size in pixels which would be approximately 24 pixels 
-conversely if the font size is set as 0.8 rem it is roughly the same as 13 pixels ,luckily you dont have to perform these calculations manually because there are numerous online calculators availble for this purpose
Point to REM Converter
-this is the point to REM converter tool found on codebeautify.org. you can access it through the provided link in your exercise files , when working with web design some people find it easier to think in pixels rather than rem especially if theyr receive sizes in points from their designer which is common in print design
-this calculater helps you convert between different sizes used on the web
-similary if a graphic designer tells you to use 18 points the converter will give  you the equivalent in rem ,which in this case would be 1.5 rem its important to note that rem can have decimal values 
03-03 Start Understanding and Applying size in CSS
-According to the statement there is no rule stating that your lower-level headings (h2,h3,h4,etc) must be smaller than the h1 heading 
-in certain situations you might actually prefer the h1 ro be smaller and the h3 to be larger , it is important to note that the default sizes for headings are determined by your browsers style sheet ,it is crucial to maintain the proper order of headings for accessibility and document outlining purpose
Understanding the Box Model in CSS
-The web page we have created looks decent with the basic CSS we applied , however one major issue is the lack of spacing we can see that there is not enough room between the text and color bars
The Box Model
-in web development every HTML element is like  a box with different properties are always present even if their value is the border which is like a line surrounding the content
-we can choose to display all four sides of the border or just a few ,and there are various styles available for the border, next we have the padding which is the space between the border and the content it can also have its own background color
-when we add padding we are essentially pushing the edge of the box away from the content,outside the border there is the margin which represents the space between the border and the content 
-it can also have its background color when we want to separate intersecting elemenst adding some margin will do the trick
-we can assign properties to individual sides or apply them to all four sides at once
-outside the border there is the margin which represents the space between the border and the content ,it can also have its own background color when we want to add separate intersecting elements adding some margin will do the trick 
-there are shorthand properties to individual sides or apply them to all four sides at once ,there are shorthand values avaiablr for border, paddimg and margin which provide a more concise way to set these properties
Applying dimensions to the box mode;
-starting from the top of the slide we can add a red border of one pixel thickness using the CSS property"border:1px solid red",this will create a soild red border around the element ,now if we use the property "border-left" it will only apply the red border to the left side of the box while the other sides remain unaffected similary when it comes to setting margins using "margin:1rem" will add one REM (root em) of margin to all four sides of the box
Working with Border ,Padding and Margin in CSS
-after learning about border,padding and margin it is time to put that knowledge into pratice on a webpage
03-05 Start Working with border, padding and margin in CSS
-currently an image has been added to the page and there are some issues we need to address ,to fix these problems start with the body element which has a default margin from the browser style sheet ,remove that margin by setting it to zero
# Advanced CSS properties and conceptStyling with links
Styling links with CSS allows us to customize their appearance to match the design of the website , you can change their color , underline , hover effects , and more
Inheritance in CSS
Refers to the mechanism by which certain properties of  a parent element are passed down to its children
This means that child elements inherit specific styles from their parent elements reducing the need to explicitly define those styles for each child element
Not all properties are inherited by default : only certain properties , such as font properties
Debbugging CSS with borders and background colorsDebugging CSS with borders and background colors can help you visualize the layout and positioning of elements on a webpage.
BORDERS
Adding borders to elements can help you see their boundaries and spacing more clearly ,you can use borders to identify the size and positioning of elements relative to each other.
BACKGROUND COLORS
Setting background colors for elements can also aid in debugging by making it easier to distinguish between different parts of your webpage.
By adding these styles selectively to elements or containers that you want to inspect or troubleshoot ,you can identify layout issues ,alignment problems, or unintended overlaps more easily ,once you have identified and resolved the issues you can remove the debugging styles from your CSS.  











