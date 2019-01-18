---
title: Front End Challenge
---

## Front End Challenge

Aki wants to plan the first ever developers meetup in JUIT. As plannings stack up, he thinks that a todo list app might help him manage the event better. 

He thinks of developing a simple ToDo List App. Now he has nothing created but only plans and requirements. But he lacks the skills for developing it. Since he has a lot of work to do for successfully organizing the developers meet over coffee in hackerden, he can't learn the required skills so soon.


You may **develop the solutions in groups**.

## Task 
Her Aki by developing a simple frontend for ToDo list app.


### Level 0 - Easy - Let's Get Started!

First things first!  We need to set up the project. Create a folder called todo and open this within your text editor. We need an html file, a css file and a JS file for this project. Go ahead and create those!

`mkdir todo`
`cd todo/`
`subl index.html`
`subl main.css`
`scripts.js`

### Level 1 - Easy - Basic HTML tags and CSS properties.

Level 1 (HTML basics)
There you go! You've created your files, now let's do some work now! 
Open your html file and do the following:
1) Create a web page with the title CodeWithCoffee ToDo App. 
2) Add a CodeWithCoffee logo and a heading for the same. (Center Aligned) 
3) Create a link at the bottom named 'how to use' to another page titled 'Instructions'. 
4) Instructions page: 
    (i) Add logo and heading
    (ii) Write a paragraph describing how to use the web  app. You can also use ordered list for the same. 
    (iii) Create a link named 'back' to get back to the app. 
    

Features | Type | Specific Requirements | Description
--------------|------|-----------------| -------------
Title     | HTML  | NA | Title shoud be `CodeWithCoffee ToDo App`  
Logo & Heading | HTML | Center aligned | You should add Codewithcoffee Logo and a heading for the same.
Links | HTML | Opens in new tab | Add a new page named `instruction.html` and add to your home page.
Style Sheet | CSS | `main.css` | This will be the main CSS file.
Images | Links | Add images as links | Do not add images in root dir

### Level 2 - Easy - Basic CSS and meta tags.

Well done with html! You've had a great start, but the app still looks dull. It's time you customize it! 
Open the CSS file and do the following:

1)  Create a style sheet customising your Web page setting font style, background colour, font color, margins etc.,  of your choice.
2) Include the reference of this file in your html file, i. e. link this file to your html file. 
3) Insert viewport meta tags.

Features | Type | Specific Requirements | Description
--------------|------|-----------------| -------------
Add Meta Tags     | HTML  | NA | Add few meta tags for some info.
Logo & Heading | HTML | Center aligned | You should add Codewithcoffee Logo and a heading for the same.
Background Color | CSS | Dark colour | Keep dark background for the app.
Font | CSS | `font-family: Helvetica, arial, sans-serif;` | Keep appropriate font size.

### Level 3 - Javascript Basics

Nice work with the app till now, but the app still lacks functionality. So now let's add some basic functions to the "*ToDo App*". Now, Aki has to figure out what functionalities he needs in the app. After a lot of brainstorming, Aki has decided that his "*ToDo App*" must have the following capabilities:
1. _He can add an item to the list._
2. _Mark the items as Done._
3. _Remove an item from the list._

**Open the scripts.js file and add the following**:
1. Write code to create a new list item on clicking the add button.

2. Write a function to strikethrough the item when clicked.<br>
(_*hint*: use \<del\> html tag_)

3. Append a close button to all the list items.

4. Write a function to remove the item when the close button is clicked.
