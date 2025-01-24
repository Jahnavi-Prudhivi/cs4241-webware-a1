_[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Lp3BMyDL)
Assignment 1 - Hello World: Basic Deployment w/ Git, GitHub, Glitch
===

Name: Jahnavi Prudhivi
Course: CS 4241 Webware
Assignment 1

Objective
---
The goal is to familiarize with HTML and CSS in this assignment. The first part, index.html, had information about me, a short description about my future plan, my majors, previous CS courses and technologies I’m familiar with for this class, CS 4241 Webware, only. The second part, hobby.html, is a form for users to answer questions related to their hobbies. These questions had form elements including input text box, text area, check boxes, radio buttons, drop down selection list, labels, and a submit button. There is also a navigation bar and additional items I added for achievements.


2. Edit `index.html` to show the following information about you:
    * your name and class at WPI (e.g. class of 2025) Note: Do not put any contact or personal information that you do not potentially want other people outside of this class to see.
    * your major(s) and minor(s)
    * a list of previous computer science courses that you have taken at WPI
    * a table containing your experience with the following technologies and methods (none, some, a lot)
        * HTML
        * CSS
        * JavaScript/Typescript (specify which one)
        * SQL (specify which ones)
        * MongoDB
        * Web Frameworks (specify which ones)
        * unit testing
3. Create `hobby.html` to show one of your interests:
    * use two of the HTML5 semantic block elements - main, section, article, aside, header, footer
    * create a form related to your hobby (such as asking readers to provide information about their interests) that include the following the following form elements
        * input text box
        * text area
        * check boxes
        * radio buttons - note that the radio buttons should permit only a single selection!
        * a drop down selection list
        * labels for each of the elements above
        * a submit button with no action (the button does not do anything for now)
4. Using the <nav> tag and unordered lists as mentioned in class, create the following horizontal navigation menu at the top of the `index.html` and `hobby.html` documents. You will want to research the a: pseudo classes, such as a:hover, to create styles for the four menu selections:
    * Link to `index.html`
    * Link to `hobby.html`
    * Link to WPI's home page
    * Link to an informative web page related to your hobby
6. Complete some technical and/or design achievements (see below).
7. Test your project to make sure that when someone goes to your main page, it displays correctly. You can do this locally by simply running `node server.js` from within the assignment directory.
8. Modify the README file according to the specification below.
9. Commit and push all your changes to GitHub. 
10. Deploy your project to Glitch. You can do this by [importing the repo from GitHub](https://medium.com/glitch/import-code-from-anywhere-83fb60ea4875)
11. Ensure that your project has the proper naming scheme (guide follows) so we can find it.
9. Create and submit a Pull Request to the original repo.

## Option 2 - Fork repo and import to Glitch, edit on Glitch, and then export back to GitHub
Most of these steps are the same as option 1, except that you being by creating a new project Glitch using this repo as a staring point (just choose New Project > Import from GitHub for this and then paste in the link to your repo). At the end, you can export your Glitch project to GitHub by [following these instructions](https://www.youtube.com/watch?time_continue=77&v=aWJFbtrgW4E&feature=emb_logo). *Note that the location of the projecct export feature in Glitch has moved from what they show in this video.* It's now located in Tools > Import and Export (tools is located in the bottom left of the Glitch editor).

## Option 3 - Clone to computer, edit locally, push to GitHub, upload to Glitch
This is the same as option 1, except that for step 6 (Deploy to Glitch) you simply upload each file to your Glitch repository (using New File > Upload a File).

Naming and URL Scheme
---

You must use a consistent naming scheme for all projects in this course.
The name scheme should be `a1-yourGitHubUsername`.
The `a1` will need to be updated to `a2`, `a3`, and so on in future projects.

If we can't find it, we can't grade it.

By default Glitch often assigns your application a random name. To change it, click on the project dropdown menu in the upper left corner of Glitch. You will then see an additional text field displaying the project name in the resulting menu; click here to edit the name.

Achievements
---
Below are some suggested technical and design achievements. You can use these to help boost your grade up to an A and customize the assignment to your personal interests. These are recommended acheivements, but feel free to create/implement your own... just make sure you thoroughly describe what you did in your README and why it was challenging. ALL ACHIEVEMENTS MUST BE DESCRIBED IN YOUR README IN ORDER TO GET CREDIT FOR THEM.

Note that if you want to load resources besides your index.html file (images, an CSS file, a JS file) you'll need to modify server.js to point to these. For now it's easiest to just hardcode paths to the resources, but we'll look at ways to optimize this shortly.

*Technical*
1. (max 5 points) Style your page using an external stylesheet named styles.CSS. Each style rule you apply other than the a: pseudo class styles will get you 1 extra point for a maximum of 5 points. Be sure to describe your style rules in your README.
2. (5 points) Add a simple JavaScript animation to the page.
3. (max 5 points) Experiment with additional *semantic* HTML tags (links, images, tables, header, footer, etc.) Each extra semantic tag beyond the two required ones will get you 1 extra point for a maximum of 5 points. Be sure to list the semantic tags you use in your README.

*Design*
1. (10 points) Create a color palette using [color.adobe.com](https://color.adobe.com). Use all the colors in the palette in your webpage by implementing the appropriate CSS. Add a small screenshot of the color wheel for your color palette to your repo.
2. (5 points) Use a font from [Google Fonts](https://fonts.google.com) in your website.

Resources
---

If you need a JavaScript/HTML/CSS refresher, see [HTML & CSS](https://wpi.primo.exlibrisgroup.com/discovery/fulldisplay?docid=alma9936730811904746&context=L&vid=01WPI_INST:Default&lang=en&search_scope=MyInst_and_CI&adaptor=Local%20Search%20Engine&tab=Everything&query=any,contains,Jon%20Duckett&offset=0) and/or [JavaScript Codeacademy](https://www.codecademy.com/en/tracks/javascript).

If you need a Git/GitHub refreseher, see the GitHub document posted on Canvas and the Learning Git textbook. Addition references that may be useful are [GitHub Bootcamp](https://help.github.com/categories/bootcamp/), the [GitHub Guides](https://guides.github.com/) (especially the ones on Hello World, and Understanding the GitHub Flow, and Forking Projects), and [CodeSchool's Try Git Course](https://www.codeschool.com/courses/try-git).

README
---

Your First and Last Name: Jahnavi Prudhivi

Objective: The goal is to familiarize with HTML and CSS in this assignment. The first part, index.html, had information about me, a short description about my future plan, my majors, previous CS courses and technologies I’m familiar with for this class, CS 4241 Webware, only. The second part, hobby.html, is a form for users to answer questions related to their hobbies. These questions had form elements including input text box, text area, check boxes, radio buttons, drop down selection list, labels, and a submit button. There is also a navigation bar and additional items I added for achievements.

## Technical Achievements

- **StylingPage using an external sheet called`style.css`**: In this, I applied styles for the table (th, td), menu unordered lists, the introduction header (Jahnavi Prudhivi and Hobby), changed the background color of the body, font and color change for header 2, the navigation menu bar background color and the paragraphs colors.
- **Experiment with additional semantic HTML tags`**: I used links for Google font and my watercolor hobby, a footer for my contact information, a header for the navigation menu bar, I used section for the little introduction “About me” bit.


### Design Achievements
- **Creating a Color Palette**: Used three main colors throughout the entire website
- **Used the Roboto Font from Google Fonts**: I used Roboto as the font for the primary copy text in my site.
