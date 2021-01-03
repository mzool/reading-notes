# Html:
# Chapter Two:

Element | name | influence
---| ---|---
h1 to h6 | Headings | give different font sizes larger one is \<h2>
B| bold | bold appearance
i |italic | italic appearance
sup| superscript | contain characters that should be superscript such
sub | subscript | contain characters that should be subscript
br |  br   | add a line break inside the middle of a paragraph
hr |hr | to creat a break between themes 
strong |strong| give a like bold appearance to the important words 
em | em | indicates emphasis that subtly changes the meaning of a sentence.
blockquote | quotation | long quote such like a whole paragraph
q | quote | for short quotes
abbr | abbreviation|for abbreviation
cite | cite|for refferencing the element such as a book
dfn | defining instance| for defining a new element
address| address| for contact details of the owner
ins | insert| to show the element that inserted to the page
del | delete | to show the element that deleted
s   |  --- | to indicate the element that no longer accurate



## white space collapsing: when write more than one space bar between the words, bowsers only appear one space.

# Visual Editors and Code views:
## There are many features that are the same in many editors:
+ ## Headings are created by highlighting text then using a drop-down box to select a heading.
+ ## Bold and italic text are created by highlighting some text and pressing a b or i.
+ ## New paragraphs are created using the enter key.
+ ## Line breaks are created by pressing shift and return key at the same time.
+ ## Horizontal rules are created using a button with a straight line on it.

# Code views: show the code that created by the editor and allow to modify it.
# Semantic markup: a group of elemnts that not affect the structure of the web page, but add an extra information on it.

# Chapter 10:
# CSS specify the appearance of html file.
# What is the defference between block element and inline element?
## bolck element should start in the beginning of the line, but inline element could be in the middle of the line for example.
# To understand how CSS work, you have to know the html strucure, inline elements and block elements, then you can choose the appearance for each one of them.
# CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration. 
# CSS Properties Affect How Elements Are Displayed, there are two values you need to determine;     **{property: value;}**, first you write the property you want to modify after that the value of it.

link|\<link>|use to tell the browser to look at CSS file and connect it with html file
----|----|----
href|href|This specifies the path to the CSS file
type|  |specifies the type of document being linked to
rel|   | specifies the relationship between the HTML page and the file it is linked to


# Use **style** to write CSS code inside html file.
# How Css Rules Cascade: 
## Take the last rule over the first, taking the more specify element and you can specify the importance of element and the CSS consider it.
# Why use External Style Sheets?
## you want to apply the same style for more than one page and its easier to edite.


# Chapter 4:
## Links are the defining feature of the web because they allow you to move from one web page to another.
# How to creat links?
## links are created by using \<a> \</a> tag, the url put in the opening tag after "href", and any thing could written between opening and closin tag.
# Directory Structure: its good to organize your website code inside seperated folder.
# Relative URLs can be used when linking to pages in your website.
# Use mailto inside "a" tag to creat an email link.
# Use "target" with a tag to open the link in new tab, should followed by "_blank".


# JavaScript:
# Chapter2:
## Statemant: a script is a series of instructions that a computer can follow one-by-one.
## JavaScript is a case sensetive any change is considered.
## Statements are instrucions and they should start in a new line.
## You should write comments to clarify your code.
## Variables: a presigned values used to jobs.
# Data types:
## Strings: letters and other characters. 
## Numeric: numbers.
## Boolean: true and false
# RULES FOR NAMING VARIABLES :
## Not started with a number.
## Don't use periode or dash in variable name.
## No keywords.
## All variables are case sensitive.
## If your variable made from many names use capital letter with every one.
# Arrays are type of variable that store a list of values.
## How to creat array? here an example:
## var colors;
## colors ['white', 'black', ' custom'];
## var el document.getElementByld('col ors');
## el . textContent = col ors[O]; 
## Every item in the array has a number that called index number, the numbering start from zero not one, if you want to access or update a value in the array you have to write the array name followed with the item index number.
# An expression evaluates into a single value, it can assign value to a variable or use multi variables with expression to return a singl value.
## Expressions rely on things called operators; they allow programmers to create a single value from one or more values. 
## Arithmitic operator: its mathmatical operators using with numbers.
## String's operator: use + to join the strings togethers.

# Chapter 4:
# Decition making: many time in the script there are a two or more wat to take, which one to take is the decition making, and ther are two components to a decition: or conditional statement or a value.
## comparisom operator give a boolean value.

==|equal
---|---
\===|strict equal (value+type)
">"|grater than
"<"|lower than
"<=|lower or equal than
">="|greater or equal than

# Logical operator"

&&| and, give true if both side are true
----|----
"||"|or, give true if one of the both is true
"!"|not, opposite the value
