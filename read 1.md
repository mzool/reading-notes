# HTML
# Chapter 1:
# How HTML structure the pages?
## It use an elements each one of them has an opining tag and closing tag for example <h> this one is opining tag and this one is closing tag </h>, Tags act like containers. They tell something about the  information that between open tag and closing tag.

# Tags:
 ## To write a tag start with left angle bracket "<" then write the charachter, then right angle breacket ">". For closing tag put "/" before the charachter.

 # Attributes:
 ## Give additional about the contents in the tags.
 ## How to write attributes?
 ## after the character in the opining tag write the attribute's name then write "=" then the value you want between "" double quotation,
##  \<p lang="en-us">Paragraph in English\</p>.

# Every html code contains :
+ ## Head element, contains information about the page and the title.
+ ## Body element, contains all the appearing contents in the page. 

# Summary of ch1:
+ ## HTML pages are text documents.
+ ## HTML uses tags (characters that sit inside angled brackets) to give the information they surround special meaning.
+ ## Tags are often referred to as elements.
+ ## Tags usually come in pairs. The opening tag denotes the start of a piece of content; the closing tag denotes the end.
+ ## Opening tags can carry attributes, which tell us more about the content of that element.
+ ## Attributes require a name and a value.
+ ## To learn HTML you need to know what tags are available for you to use, what they do, and where they can go.

# Chapter 8:

## Doctype: because ther are several version of html, then we need to tell the browser wich one we use for example we write  \<!DOCTYPE html> one the top of the page.

 html element|work
 ----  | ---        
 \<!-- -->| add comment
  ID attribute| give special identity for the element
  class attribute| give special identity for groube of elements
  block elements| start in the begining of lines always
  inline elements| continue in the same line of their neighbouring
  div| group a several elements in one bloch
  span| inline element that differntiate a part of elements from the other or to contains numbers
  ifram| to put a window in the page like maps
  meta| in the head element, contains information about the page
  description| descripe the page

 
  
  # Chapter 17 :
# HTML5:
+ ## html5 introduces a new set of elements that allow to divide up the parts of a page. The names of these elements indicate the kind of content,for example, header for the top of the page and footer for the bottom.
+ ## article element represents any part of the page can satnd alone or syndicated, we can use article inside article and we can use article for a long text for example or divide it into several article.
+ ## When the \<aside> element is used inside an <article> element, it should contain information that is related to the article but not essential to its overall meaning.
+ ## When the \<aside> element is used outside of an <article> element, it acts as a container for content that is related to the entire page.
+ ## The \<section> element groups related content together, and each section would have its own heading.
+ ## The purpose of the \<hgroup> element is to group together a set of one or more \<h1> through \<h6> elements so that they are treated as one single heading.
+ ## \<figure> \</figure>: use to contain any content that is referenced from the main flow.
# Summary:
+ ## The new HTML5 elements indicate the purpose of different parts of a web page and help to describe its structure.
+ ## The new elements provide clearer code (compared with using multiple \<div> elements).
+ ## Older browsers that do not understand HTML5 elements need to be told which elements are block-level elements.
+ ## To make HTML5 elements work in Internet Explorer 8 (and older versions of IE), extra JavaScript is needed.


# Chapter 18:
# Question to ask before creating website:
+ # Who is the Site For?
 ## you have to spicify age, country, areas, education level, for men or women or mixed and the kind of devices that access the site.
 + # Why People Visit your Website?
 ## for entertainment or to achieve goal, personal or professionl.
 + # What Your Visitors are Trying to Achieve?
 ## you can't satisfy all visotors but you need to put something motivate your visotors to continue in your site.
 + # What Information Your Visitors Need?
 ## put information from many recources, arrange it and keep it easy to find by users.
 + # How Often People Will Visit Your Site?
 ## when you know the answer, then you know when you have to update, for example news websites have to update minute by minute.
 + # After you know the answeres, now you have to put a map for your site and organize all information you collect and how to build your site, you can use wireframe {simple sketch of the key information that needs to go on each page of a site}.

 + # Getting your message across using design:
 ## The aim of the visual design is to communicate, organizing and prioritizing help to understand where the importance and how to read the site.
 + # Visual hierarchy: most people skim the site to find something important then they read it; so Visual hierarchy helps users find what they are looking for using {color, size or font type}.
 + # grouping and Similarity: organize visual elements ito group, Grouping related pieces of information together can make a design easier to comprehend.
 + # Designing Navigation: good navegation let people understand the site about what and make them know where to go. Good navigation properties: concise, selective, interactive, consistance, context and clear.

# Summary:
+ ## It's important to understand who your target audience.
+ ## Site maps allow you to plan the structure of a site.
+ ## Wireframes allow you to organize the information that will need to go on each page.
+ ##  Design is about communication. 
+ ## You can differentiate between pieces of information using size, color, and style.
+ ##  You can use grouping and similarity to help simplify the information you present.


# JavaScript:

## JavaScript makes your page interctive by modifying and accessing the content while you in the browser,also
- ## Let you to set a program rules.
- ## React to events.
# What is a Script?How to write it?
##  A series of instructions that a computer can follow to achieve a goal, to write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it,
- ## Define the goal
- ## Design the script      
- ## Start coding


+ ## Vocabulary: The words that computers understand 
+ ## Syntax: How you put those words together to create instructions computers can follow
+ ## Computers solve problems programmatically; they follow series of instructions, one after another


# How computers undrstand the world?
## computers define everything as an object, every object have its properties, events and methods.
# What is event for computer?
## when users interact with objects in the computer; the result called event.
## Method: is how to do the event.
# How web browsers see the web page?
## 1- Receive a page as html code.
## 2-  Creat a model of the page and store it in the memory.
## 3- Use rendiring engine to show the page on screen.

# How to make a web page using html,CSS and JavaScript?
## first we write the html code wich consider like structure of the page, after that we define how contents will appear by CSS{presentation layer}, and finalley interactive layer wich is JavaScript, These three layers form the basis of a popular approach to building web pages called progressive enhancement. 

+ ## It is best to keep JavaScript code in its own JavaScript file. 
+ ## The HTML \<script> element is used in HTML pages to tell the browser to load the JavaScript file.
+ ## the \<link> element can be used to load a CSS file.
+ ## If you view the source code of the page in the browser,the JavaScript will not have changed the HTML, because the script works with the model of the web page that the browser has created.


