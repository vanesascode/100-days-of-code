# #100DaysOfCode Challenge - Log


### Day 1️⃣: August 4, 2023

**Today's Progress**:  

I’ve been working on a very simple only one page blog. 💻
However, I created a google search bar for the first time, which it is seen in the navbar when screen is wide and in the footer when seen in a mobile. 
🌟 And created a scroll css quite recent effect on the images! (notice that the scroll effect can only be seen in recent Chrome browsers). 

Visit web [HERE](https://vanesascode.github.io/css-scroll-effect-and-google-search-bar/)

**Thoughts:** I’m struggling with the favicon.ico 🤷‍♀️

🔹 **HOW TO CONTINUE:** 

I'd like to keep working on it and grow it as professional blog.
[Code](https://github.com/vanesascode/css-scroll-effect-and-google-search-bar)

***

### Day 2️⃣: August 5, 2023

**Today's Progress**:

I’ve been working on a big form for an enrollment context. 📑 
For now, I have just got all the inputs I found around, and kind of organized the labels and inputs using bootstrap 🌟 
I already started adding some Javascript but that is something that needs a lot more work. 

See progress [HERE](https://vanesascode.github.io/super-form-css-bootstrap-javascript/)

**Thoughts:** It's messy with so many inputs 😂

🔹 **HOW TO CONTINUE:** 

My goal is to use as many #html form inputs as I can, to practice with all of them, and to make the form look modern and responsive, as well as functional using javascript. 
[Code](https://github.com/vanesascode/super-form-css-bootstrap-javascript)

***

### Day 3️⃣: August 6, 2023

**Today's Progress**:

I kept working on the Javascript of yesterday’s form. I added: 

Regular expressions(RegEx) to validate user input in form fields.
The “setCustomValidity()” method with the “onvalid” and the “oninput” attributes, to set specific validity rules, and created a validateInput() function to make it all work. 
I created the showValue() function to show the value of the range (slider) input.
Since I couldn’t apply certain rules to the radio and checkbox inputs using the previous, I created a JS file for each, in which there are some functions that make a red message appear below the inputs if no radio or checkbox is selected and that make a textarea appear in case you check the ‘other’ radio or checkbox, so the user can introduce some comments. 

To find more info about all this, check my README.md file in the code. It’s all explained [there](https://github.com/vanesascode/super-form-css-bootstrap-javascript)

See progress [HERE](https://vanesascode.github.io/super-form-css-bootstrap-javascript/)

🔹 **HOW TO CONTINUE:** 

I don't think in the mobile version the error messages work. So I need to make it work in mobiles as well. 

***

### Day 4️⃣: August 7, 2023

**Today's Progress**:

I improved the performance of the radios.js and checkboxes.js files by storing all the elements I could outside of the functions, and improved the range input visualization. 

I also noticed that in the mobile version, the form didn’t show the validation messages or even the titles, so I had to think about another option. It took me quite a while, but I made it! 🥳 I added a red border and error message to the inputs of the form that were empty or that didn’t follow their defined RegEx pattern. Well, only to the 6 first inputs…

I did it thanks to:

- A function I created to make sure that no input is empty when the user presses the submit button: validateInput(inputName, alertName)
- Another function to validate when the user makes changes to the input: function removeInputErrors(input, alert, regex)
- The stars in this were the “event listeners” of course!!!

To find more info about all this, check my README.md file in the code. It’s all explained [there](https://github.com/vanesascode/super-form-css-bootstrap-javascript)

See progress [HERE](https://vanesascode.github.io/super-form-css-bootstrap-javascript/)

🔹 **HOW TO CONTINUE:** 

Next, I want to spend time finding the way to apply this to the rest of inputs. 

***

### Day 5️⃣: August 8, 2023

**Today's Progress**:

Today I didn’t code much in order to show something finished. However, I studied GIT for real, with many tutorials ( I specially recommend the ones by [Simon Bao](https://www.youtube.com/@SuperSimpleDev) and practiced #FeatureBranchWorkflow with classmates in the @4geeksacademy classes ( really important to realise if you really know your commands!). 

👉 These skills are as important as coding if you really want to work in a professional team ❗❗

- Here are all my notes, a [long guide which may be useful to learners like me: ](https://github.com/vanesascode/git-cheatsheet)

🔹 **HOW TO CONTINUE:** 

Next I’d like to learn about interactive rebase, cherry-picking, reflog and more.

***

### Day 6️⃣: August 9, 2023

**Today's Progress**:

Super form finished for now! 🎉 I achieved all my current goals with it and now all compulsory inputs (both text and select ones)  turn red and give you a message in case you want to send the form and they are empty or not filled as #RegEx or other rules are set (as for example, that the confirmation password is the same as the initial password) 💻  Lots of #javascript you’ll find explained in the readme.md file. 

To find more info about all this, check my README.md file in the code. It’s all explained [there](https://github.com/vanesascode/super-form-css-bootstrap-javascript)

Visit it in [HERE](https://vanesascode.github.io/super-form-css-bootstrap-javascript/)

🔹 **HOW TO CONTINUE:** 

👉 Next, I want to merge this form and other landings I have into one flask app, and keep working from there to make a complete webpage. 

***

### Day 7️⃣: August 10, 2023

**Today's Progress**:

💡 My objective now is to join, into just one website, some of the landing pages I have already done and that are kind of related, and keep growing the website. This will give me the chance of working on a bigger project. 


So, I thought of mixing my dev jobs and dev school pages into a just one fictional developers school website, in which I will also keep a blog with my notes and materials I create while learning. 


💻 The first step has been creating a `Flask` app, and creating a provisional home page. I also merged  the dev jobs web I had already done before and modified the footer. I Organized a little bit the folders and files of my project too, since there is a lot of stuff already in one project. However, I love working with `Jinja` as a templating engine, and it makes life easier.   

🔹 **HOW TO CONTINUE:** 

🔧🔨There’s a lot of work to do: the design of the web as a whole, adding my super form, adding a blog and keeping it, etc. Loads of work for the next days of code challenge. Tips and advice are more than welcome!

[Code](https://github.com/vanesascode/devschool-vanesascode)

[Web in progress](https://devschool-vanesascode.vercel.app/)

***

### Day 8️⃣: August 11, 2023

**Today's Progress**:

As I mentioned yesterday, I had to work on the design of the my new web as a whole before continuing building it. This is because I merged different elements made in different moments, and I didn’t follow kind of rules when working with the templates and the index pages. 😔

Therefore, I needed to take a step back and ensure that the design of the entire website was cohesive and followed a consistent strategy. 

For example, the templates that are part of the index ones now don’t include vertical margins or paddings, so they are as reusable and “easy-lego-like” as possible. 

And in the index templates I tried to add paddings rather than margins, so when trying to set in a template element I didn’t confuse myself and I always did it in the same way. 

The margins and titles now use media queries many times for responsiveness, since I found myself limited with Bootstrap options. 

Also I took care of the horizontal paddings, so they were consistent, especially in the mobile view, in which is more obvious and so very important.  😱

So, these are changes that may not be very noticeable to the user right now, but that really make a difference and that prevent me from going crazy with the css when the site grows.

Next time I’ll start the project more consistently from the beginning and will avoid all this nuisance 🤷

[Code](https://github.com/vanesascode/devschool-vanesascode)

[Web in progress](https://devschool-vanesascode.vercel.app/)

💪 Planning and being organized is key!!!!

🔹 **HOW TO CONTINUE:** 

Lots of things can be done in this website... blog and apply page to start.

***

### Day 9️⃣: August 12, 2023

**Today's Progress**:

Today I’ve had a break from frontend work and have been studying #Typescript

TypeScript (created by @microsoft ) is important because it is a statically typed superset of #JavaScript that helps catch errors during development, improves code readability, enhances tooling support, and enables better code organization and maintainability.
So, along with the course for beginners by Dave Gray (https://www.youtube.com/@DaveGrayTeachesCode/featured), the docs of the official site (https://www.typescriptlang.org/)  and exercises by w3schools (https://www.w3schools.com/typescript/index.php) 

I’ve been writing TS and compiling it into JS in order to learn types, objects, arrays, tuples, enums, functions, type assertions and classes for now. 

🔹 **HOW TO CONTINUE:** 
I have to continue with the course and then start easy projects. 

Log: https://github.com/vanesascode/100-days-of-code/blob/master/log.md

Code and notes: https://github.com/vanesascode/typescript-course

### Day 1️⃣0️⃣: August 13, 2023

**Today's Progress**:

After studying classes in javascript and in #typescript, as I mentioned yesterday, I felt I needed a practical example to work with in order to understand them better and keep motivated with them. 

So I worked on a booklist in which you can add, remove and edit titles of books, which works very much like a todo list. At the same time, I kept a record of what I was learning in the first blog article I have added in my “dev school” site. 

[Code](https://github.com/vanesascode/devschool-vanesascode)

[Article](https://devschool-vanesascode.vercel.app/blog/javascript-classes-booklist)

🔹 **HOW TO CONTINUE:** 

The site needs lots and lots of work yet! 

***

### Day 1️⃣1️⃣: August 14, 2023

**Today's Progress**:

I continued with my typescript studying and came across index signatures. 🤔 I wondered when they could be useful so I worked on a practical example: a simple product catalog of clothes. 💡 

📝I kept a record of what I was learning once again, in the now the second blog article I have added to my “dev school” site.

I hope the article is useful for learners like me: it tells you about typescript index signatures, lets you try the catalog, and shows you the code to do it yourself step by step. 💻

Any feedback is more than welcome! 🙏

[Code](https://github.com/vanesascode/devschool-vanesascode)

[Article](https://devschool-vanesascode.vercel.app/blog/typescript-index-signatures)

🔹 **HOW TO CONTINUE:** 

The site needs lots and lots of work yet! 

***

### Day 1️⃣2️⃣: August 15, 2023

**Today's Progress**:

Improved the visualization  of the articles. Really looking consistent and professional. 

Apart from the breadcrumbs, now there’s a module that gives info (title, category, author, date), and a module for the latest articles.
This, being all responsive (the modules move depending on the size of the screen).
Also, icons to share the article on social media!
And a subscription to the newsletter box, functional, along with a privacy policy page. 

Improved a bit the SEO (Search Engine Optimization) to help increase its visibility and organic traffic: 

I optimized meta tags: meta descriptions and keywords.
Added simple structured data markup.
Revised the HTML headings (h1, h2, h3, etc.) 

[Code](https://github.com/vanesascode/devschool-vanesascode)

[Article](https://devschool-vanesascode.vercel.app/blog/javascript-classes-booklist)

🔹 **HOW TO CONTINUE:** 

The site needs lots and lots of work yet! 

***


### Day 1️⃣3️⃣: August 16, 2023

I’ve had another break to study #Typescript in depth. Again, along with the course by [Dave Gray](https://www.youtube.com/@DaveGrayTeachesCode/featured), the docs of the official site of [typescript](https://www.typescriptlang.org/)  and exercises by [w3schools](https://www.w3schools.com/typescript/index.php) 

This time learning 📝

-  Type indexing and the the keywork #keyof (I already wrote an article about index signatures, but now went more in depth)

-  Generics <T>

-  Utility types (partial, record, pick-extract, omit-exclude, returntype, parameters, etc.)
  
🔹 **HOW TO CONTINUE:** 

😵 A lot of information I’ll be trying to interiorize by doing projects. 

[Code and notes](https://github.com/vanesascode/typescript-course)


***

### Day 1️⃣4️⃣: August 17, 2023

Since we are now studying Javascript arrays in the @4geeksacademy bootcamp, I created an interactive article in which you can try some array methods without  coding, just visually,  in order to understand them better. 

Site: https://devschool-vanesascode.vercel.app/blog/javascript-array-methods-part-one

🔹 **HOW TO CONTINUE:** 

I’ll be creating more articles like this with different array methods: it really helps me interiorize them and I hope it can also help other beginners that are starting to learn them. 

***

### Day 1️⃣5️⃣: August 18, 2023

Today, I just focused on the javascript exercises provided in the @4geeks bootcamp. They give you hundreds so you stay entertained forever, so you really learn your code. So that’s good 👍

🔹 **HOW TO CONTINUE:** 

Continuing them, cos they're loads! 

***

### Day 1️⃣6️⃣: August 19, 2023

Today did some little improvements to my devschool website: 
- Added a dropdown in the navbar
- Added the form I had done some days ago in another project, with a toast message. 
- Added a modal thanking the user once they subscribe
  
[Web in progress](https://devschool-vanesascode.vercel.app/)

***

### Day 1️⃣7️⃣: August 20, 2023   

🌟 I’m very happy to have added my first box of comments in one of my blog articles! 🥳

It’s very simple at the moment but it’s the result of quite a search by myself on how to connect my #flask app to my mongoDB Atlas #database
⛓ Also, I installed #dotenv and hid the connection string from the app.py file. I explain how to do it in the readme.file

Site: https://devschool-vanesascode.vercel.app/blog/typescript-index-signatures

🔹 **HOW TO CONTINUE:** 

Next,  I’ll refine it all a bit, and will manage to add it to my other articles!


***

### Day 1️⃣8️⃣: August 21, 2023    🌟 Cool blog comments as promised!

So, there we go! Now every article of my blog has a box comments in which you can add your name and see the date of posting
The number of current comments dynamically renders in the title (I love #Jinja ! )

In the backend I separated the database-related code into its own file (database.py), so I didn’t clutter my app.py file that much. I also separated the post routes for the database into its own file with the Flask's `Blueprint` feature.

However, you cannot get into the website for now, since the render with vercel is failing and I still have to find out why... 🥺

🔹 **HOW TO CONTINUE:** 

I hope to solve it soon. 

***

### Day 1️⃣9️⃣: August 22, 2023   

So I created a modal popup asking you to subscribe when you enter in the website for the first time. 

Then, thanks to #localStorage, it doesn’t appear again unless you totally clean your browser 🌟

code: https://github.com/vanesascode/devschool-vanesascode
🔹 **HOW TO CONTINUE:** 

I hope to solve the deployment soon.... 

***

### Day 2️⃣0️⃣: August 23, 2023   

At the moment, in the @4geeksacademy bootcamp, we are working with the #DOM.

🌟Things getting exciting now! 

🐭 mouse events: 

“click”
“contextmenu”
“mouseover/out”
“mousemove”
“mousedown/up”

Code and notes: https://github.com/vanesascode/mastering-the-DOM-with-JS

🔹 **HOW TO CONTINUE:** 

Learning more about other events

***

### Day 2️⃣1️⃣: August 24, 2023   

I put into practice my Typescript recent learning and created a todo-list following one of @DaveGray tutorials. It was really hard for me at the beginning, it took me several days to analyze the classes used in the ts.files but eventually I got through them. 

🌟 You can compare the Typescript and the compiled Javascript in the same website. Visit it: https://zen-todo-list-vite-typescript-classes.vercel.app/

In the readme.md file I have thousands of notes 😅
Code: https://github.com/vanesascode/zen-todo-list-vite-typescript-classes

🔹 **HOW TO CONTINUE:** 

Next I'll work with Typescript with React.

***

