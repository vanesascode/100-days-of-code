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


### Day 2️⃣2️⃣: August 25, 2023   

At 4geeks bootcamp we’ve had a look at Jest Unit Testing with #Javascript

Therefore, today I’ve been experimenting with different built-in Jest #methods by myself in order to practice and get a better hold of it. 

Describe, it, test, expect, matchers(toBe, toEqual, toContain, toThrow, toMatch, toHaveProperty, etc.), 

Find my notes and code here: https://github.com/vanesascode/jest-configuration-and-examples





Another day I want to be discovering other methods and features such as: beforeAll, afterAll, veforeEach, Mocking, Snapshot testing, etc. 

***

### Day 2️⃣3️⃣: August 26, 2023   

Continuing with @4geeksacademy program, more event listeners! 🌟
Now form events, very useful all the time. See my interactive notes in the gif picture below if you don’t know them yet 😉

“input”
“change”
“submit”
“reset”
“focusin/out”
“keydown/up”

Code and notes: https://github.com/vanesascode/mastering-the-DOM-with-JS

🔹 **HOW TO CONTINUE:** 

However…. I must get into React now and start working with events such as onKeyDown, onChange, onClick, etc. 

***

### Day 2️⃣4️⃣: August 28, 2023   

As mentioned on my day 22 of the challenge,  I dug more into more Jest features: beforeAll, beforeEach, Mocking (jest.fn, jest.mock) &  Snapshot testing. 
You can find my notes and exercises here once more: https://github.com/vanesascode/jest-configuration-and-examples

👉 Yesterday I didn’t post and won’t be doing so on Sundays anymore. This is because I am spending loads of hours during the week, on the 4geeks bootcamp, my personal going in depth of things and also this 100 days code challenge to show it all. 

And I needed a break, a healthy break. 🤦‍♀️

And I will need a break from time to time, so I am more productive when I start coding again the following day. 💪

I hope you agree with me ❤️


🔹 **HOW TO CONTINUE:**

I'll get into React with Typescript. 

***

### Day 2️⃣5️⃣: August 29, 2023   

Today I am coming with a new tutorial in my blog. It tells you about the Typescript Record Utility Type, the optional operator, assertions, and of course, gives you visual examples to understand it.

Site: https://devschool-vanesascode.vercel.app/blog/typescript-record-utiliy-type

🔹 **HOW TO CONTINUE:**

I'll get into React with Typescript. 

***

### Day 2️⃣6️⃣: August 30, 2023   

I have been following Dave Gray's course on Typescript with React:

👉 So far, I have been practicing:

useState

useEffect

useRef

useCallback

useMemo

useReducer

🌟And made a site where you can test the different exercises I did: https://exercices-react-typescript-vite.vercel.app/

Code and notes: https://github.com/vanesascode/exercises-react-typescript-vite

🔹 **HOW TO CONTINUE:**

I think I’m ready to start projects with Typescript (however, want to dig into Tailwind first) 

***

### Day 2️⃣7️⃣: August 31, 2023 

Before moving to Tailwind, one of the things that I was still missing in CSS was to understand the before and after pseudo-elements and the keyframes for animation. 

☀️That was the motivation to create this sea scene with a sun that is made of before and after pseudo-elements so it has different layers, and in which the ships move over the waves of the sea (and stop if you hover over them)⛵

In my repository you’ll find the readme file with  lots of notes and of course, the code: 
https://github.com/vanesascode/sea-scene-css-animation-before-after

🔹 **HOW TO CONTINUE:**

I should move on, and learn #Tailwind now! 💪

***

### Day 2️⃣8️⃣: September 1, 2023

I’ve started to follow a tutorial that focuses on creating a UI/UX landing with React and Tailwind. My main objective, though, is to start to become familiar with Tailwind syntax and configurations. 

So far I’ve: 

- Become familiar with some Tailwind #syntax (I just love that you mouse over an element and it tells you what CSS it is!) 
- Also with the Tailwind #docs,
- Learned about the custom Tailwind #configuration,
- And how to create complex #classes using javascript and importing them into the components (saves you code and time!)
- How to have a friendly #javascript file to iterate the text and use it in the components, rather than writing the text in the components themselves, 
- How to do the same with the assets (code gets much #cleaner!)
- How to use Javascript #ternaries to determine classes based on the #index of the element (when iterating them from an array)
- How to access elements with the #shortcut ‘Ctrl + click on the element ‘ (really useful tip! ),
- I’ve tried #Figma’s CSS feature (I was amazed and looking to learn more about Figma!)

You can have a look at my notes to learn more about all this: 
Code: https://github.com/vanesascode/bank-landing-page-tailwind-react-vite-ui-ux

🔹 **HOW TO CONTINUE:**

Finishing this website.

***

### Day 2️⃣9️⃣: September 2, 2023
Continuing yesterday’s tutorial, I continue learning: 

- I’m more familiar with Tailwind syntax,
- Tailwind filters for pics are lovely 😍
- I learned how to make the Navbar responsive in mobiles using useState,
- I dug into useful animations,
- I’m more and more aware of the efficiency of styles in Tailwind, which is super emphasized when using custom classes, 
- I’m more aware of how Figma can help with front-end designs decisions, 
- I didn’t know you could apply classes to the <br /> tag 🥳
- Learned how to apply self-closed divs with gradient backgrounds 🌈
- When iterating text from the Javascript file into the component, you have much flexibility using the index of the items, to add, remove elements, classes… 
- You can use reusable components that have their main styles, but that also have styles passed as a prop to fit where they are placed,
- Passing multiple props without specifying each one, by using the spread operator (...),
- Learned about custom CSS variables,
- Discovered the ‘flex column reverse’ css class for making mobile responsiveness easier. 

You can have a look at my notes to learn more about all this: 
Code: https://github.com/vanesascode/bank-landing-page-tailwind-react-vite-ui-ux

🔹 **HOW TO CONTINUE:**

Doing something by myself with Tailwind, without following tutorials

***

### Day 3️⃣0️⃣: September 4, 2023

So, no tutorial following today. All on my own. I had to prepare a simple counter for @4geeksacdemy bootcamp’s homework, and so I decided to take that and go a step beyond applying Tailwind and working in Typescript, all in #Vite. 

📋 I tried to apply all I have learned with the tutorial for the last two days. And so: 

- I had a tsx. file to have my own #custom-classes and then import them into the components.
- I made use of text and background #gradients. 
- I can say now I am more comfortable with Tailwind #Docs. 

🌈 Also, to make the site more interesting:

- I added a #clock sphere with the transform and rotate properties.
- I added a #fullscreen option button.
- I added a toggle #dark/light mode.

👉 Have a look at it: 

Code: https://github.com/vanesascode/life-is-just-seconds-tailwind-react-tsx-vite
Site: https://life-is-just-seconds-vanesascode.vercel.app/

***

### Day 3️⃣1️⃣: September 5, 2023

This is an activity that the Bootcamp has asked us to do. A Todo list with Jsx React and using Bootstrap and CSS. 

The mode is very handwritten notebook like, and so it was a bit challenging to style. 

However, thanks to the help of our teacher [Gabriel Aquino](https://github.com/jgaquino) I learned cool css selectors that made everything easier.

You can learn more in the code notes: https://github.com/vanesascode/4geeks-react-todo-list


***

### Day 3️⃣2️⃣: September 6, 2023  -  Going in depth with  #Tailwind!

My next project is creating a landing page for  a fictional boots brand I’ve invented. 

This gives me the opportunity to: 

Learn more about the custom configuration of Tailwind and applying @layer components and utilities.
Have to deal with the design of professional logo and images by myself and defining my own color palette.
Learn about the dark mode in the Tailwind way. 
Practice, practice and practice until Tailwind is really my friend. 


Code: https://github.com/vanesascode/lizz-boots-landing-tailwind-react-tsx-vite

🔹 **HOW TO CONTINUE:**


For now I only have the #Navbar and the #Hero sections. I’ll be showing you the progress in the following days. 

***

### Day 3️⃣3️⃣: September 7, 2023   -  #Shop Carousel!

Continuing  with the fictional boots brand I’ve invented, now it’s time for the #Featured products section. I used a #React library called `React Slick` to create the carousel which has many settings and is very easy to use. 

👉 I explain how in the code notes: https://github.com/vanesascode/lizz-boots-landing-tailwind-react-tsx-vite

You can also see the progress and give me feedback if you like: https://lizz-boots-vanesascode.vercel.app/

🔹 **HOW TO CONTINUE:**

Next I’ll continue with feature sections 🌟

***

### Day 3️⃣4️⃣: September 8, 2023   

Continuing with the fictional boots brand I’ve invented, now it’s time for the #Quality and the #Services sections.

💪 More structuring and #Tailwind practice building a landing page. 

🌟 You can see the progress and give me feedback if you like: https://lizz-boots-vanesascode.vercel.app/

👉 code notes: https://github.com/vanesascode/lizz-boots-landing-tailwind-react-tsx-vite



### Day 3️⃣5️⃣: September 9, 2023   

#Collage + #Button component

So, on the left of the #offer section, you can see a collage of elements that are placed on top of a transparent canvas that serves as a static background. Then, I use #relative-absolute positions, and #percentages instead of fixed measurements to place the gray backgrounds and the pictures, as I like best. This allows for a creative #responsive design that adapts to different screen sizes and resolutions. 

On the right, there is a button component rendered twice, but with different #props. They are props that I can use if I like, or not use and then receive the default styles instead. I think it’s really handy and gives a lot of flexibility to #React components.

🌟 You can see the progress and give me feedback if you like: https://lizz-boots-vanesascode.vercel.app/
👉 code notes: https://github.com/vanesascode/lizz-boots-landing-tailwind-react-tsx-vite

***

### Day 3️⃣6️⃣: September 11, 2023

#Lizz Boots site almost finished! 🌟

There you go, all the sections finished. Happy to have it finished. 

I added the customers #review sections, another to #subscribe, and of course the #footer. 

In the service cards, I added a cool #CSS effect so they were filled with color when hovered over them 🌈 Using the ::before #pseudo-element!

```
.card::before {
  content: "";
  position: absolute;
  left: 0;
  bottom: 0;
  width: 100%;
  height: 0px;
  background-color: pink;
  z-index: -1;
  transition: all 0.5s cubic-bezier(0.23, 1, 0.32, 1);
}

.card:hover::before {
  height: 100%;
}
```

🌟 Site: https://lizz-boots-vanesascode.vercel.app/

👉 Code notes: https://github.com/vanesascode/lizz-boots-landing-tailwind-react-tsx-vite

🔹 **HOW TO CONTINUE:**

I said I would work on the darkmode feature, but don’t think here in this shop makes sense, so I’ll leave it for a future project! Instead, tomorrow I will add a modal and a toast message informing of cookies  💪

***

### Day 3️⃣7️⃣: September 12, 2023

Lizz #modals 🏴

Now it I can call this project finished: 

- It has a bottom modal for the cookies
- It has a modal to promote the membership of the brand, which appears a few seconds after the page loaded.
- And both, only appear one in a browser thanks to the use of #local #storage

I had to deal with some css problems with responsiveness, and by chance I encountered the `Touch-action` properties, which deal with the touch gestures when mobile/tablet mode. In the end, I didn’t use them. However, I explain them in the notes of the code because I found them very interesting. 

🌟 Site: https://lizz-boots-vanesascode.vercel.app/

👉 Code notes: https://github.com/vanesascode/lizz-boots-landing-tailwind-react-tsx-vite

***

### Day 3️⃣8️⃣: September 13, 2023

Todolist using #Fetch in #React

This is one of the exercises at 4Geeks Academy Bootcamp in which I’ve been learning more. I’m really excited to know now more about what an #API is and how to work with the endpoints to be doing different kinds of requests. 

The exercise uses a school API that lets you create a user, get the list, update it and delete it. The code works now nicely along the API.

Also, the light design is inspired by #Neumorphism which is a #CSS trend.

It’s also been a pile of ternary expressions for conditional rendering and dynamically setting class names or different texts based on certain conditions 💪

Code: https://github.com/vanesascode/4geeks-todolist-react-fetch-api

***

### Day 3️⃣9️⃣: September 14, 2023

Today I am presenting the “Javascript array methods part II” article in my other website “devschool”.

It shows the Javascript #map #forEach and #filter array methods in an interactive way. 

👉 Have a play with it:  https://devschool-vanesascode.vercel.app/blog/javascript-array-methods-part-two

***

### Day 4️⃣0️⃣: September 15, 2023 

More complex #React and #Api stuff!

I’m in the progress of building a new app for the 4geeksacademy bootcamp: a contact list. 

📚 So, after studying #React-router and #Context-Api in class, this app is going to be including these features to put them in practice. 

Also, it will use a school #API in which we’ll have to configure more methods and paths than with the previous project, in order to create all the necessary endpoints for this new app. 

Instead of using JS and Bootstrap, I’ll be challenging myself to do it with #TSX and #Tailwind. 💪

🔹 **HOW TO CONTINUE:**

Build the interface, routes and api endpoints.

***

### Day 4️⃣1️⃣: September 16, 2023

Let’s continue with the #contact list! 📋

I already have a lot of the interface of both the contact list and the contact form, although I am also working on a page for creating and accessing different agendas. They are connected with #React #Router.

💻 I have my React #Context #Api set in the project, with some methods already configured, to GET the contacts from the school Api, DELETE them  and to EDIT  them, all with the help of #Postman. However, I want to be doing all the logic for the agendas stuff I mentioned above.

🔹 **HOW TO CONTINUE:**

I’ll continue doing and will be showing you the progress 💪

***

### Day 4️⃣2️⃣: September 18, 2023

Progress with #contact list! 📋

I can: 

- Create agendas,
  
- delete them.
  
- Create contacts for each agenda,
  
- edit and delete them…

🔹 **HOW TO CONTINUE:**

I have many of the features I wanted, but there are still some things missing. Also the code needs revising and cleaning.🔧🔨

Still, I am already getting most of the school #API possibilities with the agendas and the contacts. 

However, I still have some issues with the routes I have to keep working with. 🤔


***

### Day 4️⃣3️⃣: September 19, 2023

Contact List not finished yet 🔧🔨

But, I for now I can show another couple of components I added: 

 - A modal for the alert that you have to choose an agenda before creating a contact.

 - A modal asking you if you are sure you want to delete an agenda. 


***
### Day 4️⃣4️⃣: September 20, 2023  - Revision #Hooks

Today I felt I needed to take a step back. Although, it depends on how you see it. 

If doing a todolist again is going a step back, then yes. But if you are doing a todolist applying concepts you are not confident with yet, and that are making big projects a nightmare, then I think it’s a step forward. 👩‍💻

Code: https://github.com/vanesascode/todolist-from-easy-to-very-difficult-react-tsx

### Day 4️⃣5️⃣: September 21, 2023 - Starting new project

So, I’m building the skeleton for a new project at the 4geeksacademy bootcamp, a reading list that will be able to have a list of favourite characters, vehicles and plantes from #starwars

Working with a new template for the school, so my code is quite slow…

I’ll be showing the functionalities and the styles, in future days…

***

###  Day 4️⃣6️⃣: September 22, 2023 challenge - Happy with the #ContactList 🌟

In the final stage of the contact list activity using the @4geeksacademy school #API, I think I’ve learned quite a bit about the way in which you manage the states and the functions from your #ContextApi in #React, and into your components. 

I had the problem that I was relying too much on state values in my  Context, and, since they don’t automatically update as much as you would like, then I was losing the views of the contact lists of the users when they were managed or refreshed. 

So, now it is solved thanks to calling the function that fetches the contacts of a user (constructed in the Context)  in the very same component that renders those contacts, every time that component mounts. 

This way, I am not relying on a state with the slug needed in the fetch function from the Context. Instead, I am passing the params from the react-router as the argument, directly into the fetch function. (You see, before, my fetch function didn’t have parameters, and was only relying on the state value for the slug, and it never fetched the contacts on time… )

I know this explanation is confusing without seeing the code, so I invite you to see by yourself if you think it may be useful for you: https://github.com/vanesascode/contact-list-react-router-context-api-tsx-tailwind-vite

Also, you can try the app, but since it is only build with React as an all in one page app, you may encounter the 404 error when refreshing in certain points. Just go back to the main URL if that happens: https://contact-list-react-router-context-api-tsx-vanesascode.vercel.app

Thank you teacher Javier for your patience in the mentoring sessions. I went from lost to the aaaahhh!
Also teacher Juanjo for revising it! 

***

### Day 4️⃣7️⃣: September 23, 2023

Styling #Star #Wars Reading List

While trying to make the “circuits” of the site work, I have started styling it with #Bootstrap and #CSS 

Still needs lots of configuring but we’ll keep it up 💪

code: https://github.com/4GeeksAcademy/vj-Starwars-blog-reading-list

***

### Day 4️⃣8️⃣: September 25, 2023 

Styling #Star #Wars Reading List:

So, for now I have the list of characters, of vehicles and of planets.

🔹 Next, I’ll be creating an article for each. 

🔹 And next, I’ll be making the favorite button work. 

Little by little but without pause ☯

code: https://github.com/4GeeksAcademy/vj-Starwars-blog-reading-list

***

### Day 4️⃣9️⃣: September 26, 2023

Styling #Star #Wars Reading List

So, as promised, there is an article for each character, planet and vehicle, all in a careful responsive way. 

Also, a laser cursor!!! what a geek!!! 🌟

Next, the favorite button work!! 

Little by little but without pause ☯

🔹 code: https://github.com/4GeeksAcademy/vj-Starwars-blog-reading-list

***

### Day 5️⃣0️⃣: September 27, 2023

As scheduled, today I am showing the #Favourites feature: 

- Articles can be added to an array of favs.

- Repetition of articles in the array is avoided. 

- Articles can be removed from the array of favs.

- #Localstorage is configured so the list of favs is not eliminated every time you refresh the browser. 

Let’s go now for the final touches! 🌟

🔹 code: https://github.com/4GeeksAcademy/vj-Starwars-blog-reading-list

***

### Day 5️⃣1️⃣: September 28, 2023 - Todolist with #Redux 💻

I have added a new way of coding a todolist to my todolists repository. So far, in there I had examples of them using useState and useReducer.

Now I have an example with Redux #Toolkit. Also learned about: 

It’s tool #nanoid, which is used to create unique IDs.
#Immer.js, which lets you write simpler immutable update logic using "mutating" syntax.
The Redux #DevTools for Chrome.

code: https://github.com/vanesascode/todolist-from-easy-to-complex-react-tsx

***

### Day 5️⃣2️⃣: September 28, 2023 - Introduction to #SQL #Databases

So, at the @geeksbootcamp we have started the module of SQL (Structured Query Language) , so now I need to spend some time studying rather than coding. 

Then, today, I’ll be understanding this language created by Edgar F. Codd
and Donald D. Chamberlin, and the different relations that exist between tables (in order to avoid duplicity of data): 

🔹 One to one (1:1): Each record in Table A is associated with exactly one record in Table B.  

🔹 One to many, or many to one (1:N/ N:1): Each record in Table A can be associated with multiple records in Table B, or viceversa.

🔹 Many-to-Many (N:N): Multiple records in Table A can be associated with multiple records in Table B. (This type of relationship requires an intermediate table, often called a junction or associative table, to connect the two tables. )

And between today and tomorrow, and next few days, I’ll be mastering the SQL #syntax

***

### Day 5️⃣3️⃣: October 1, 2023 - Practicing #SQL #syntax

So, as I mentioned before, I am learning to use syntax such as: 

SELECT, BETWEEN, LIKE “”/%%, IN, NOT, ORDER BY, ASC/DESC, LIMIT, OFFSET, INNER/LEFT/RIGHT JOIN ON, IS/IS NOT NULL, 
CREATE IF NOT EXISTS, ALTER TABLE ADD/DROP(columns) RENAME(table), INSERT INTO (row) VALUE, UPDATE (row) SET, DELETE (row) FROM, DROP TABLE IF EXISTS (table)…

And also learning about data integrity, schemas (DEFAULT, INTEGER, KEY PRIMARY, FLOAT, etc) and transactions (COMMIT, ROLLBACK, SAVEPOINT, SET TRANSACTION)

I recommend this cool website to practice: https://sqlbolt.com/

***

### Day 5️⃣4️⃣: October 2, 2013 - #star #wars reading list finished! 🌟

So, the force was with me to finish it! 

- Do you like the stars in the background? it’s a #React library called #Particles.js (discovered thanks to @victor ). If you click on the background more stars appear! ✨

- The favourites tab now shows you how many articles you got in your favs list.

- Also, cleaned code so the home component didn’t become so long (got parts of it into smaller and more manageable components) 

- I had a bug: when you clicked many times too fast on the heart of an article, such article was added to the favs array repeatedly, in spite of the fact I had a condition so favs were unique in the array 👉 I corrected it by using a useState and a setTimeout in order to disable the button for some time after clicking. 

- And the best part, you can now try it! I used the platform #Netifly for the first time: https://6515a3746ab5b021194cc363--starwars-readinglist-by-vanesascode.netlify.app/

Thank you again to the team of #4geeksacademy @javier @juanjo @jose May the Force Be With You! 💪💻

code: https://github.com/4GeeksAcademy/vj-Starwars-blog-reading-list

***

### Day 5️⃣5️⃣: October 3, 2023 - Introduction to #SQLAlchemy (CORE)

So, after learning SQL, it’s time to learn how to deal with it with an #ORM (Object-Relational Mapper) or library to create and manipulate databases. 

At @4geeks bootcamp we are learning SQLAlchemy, an open-source Python library to work with relational databases.

👉 Then, I decided to take a crash course on it first, only using #Python and #sqlite (without Flask). It has two parts, the #CORE and the #ORM:

SQLAlchemy Core is a lower-level interface that allows you to work with SQL directly, while the…
SQLAlchemy ORM is a higher-level interface that allows you to work with databases using Python objects. 

💻 I started with the CORE. So:  

I created a Python project and a virtual environment with #venv
I installed SQLAlchemy and #DB Browser.
I created, connected and tested a database.
I learned to insert, select, update and delete in the database. 

I have the repository here, with LOADS of notes I took while learning in the readme file: 

log: https://github.com/vanesascode/100-days-of-code/blob/master/log.md

🔹 **HOW TO CONTINUE:**

Next, I’ll be dealing with the ORM. I’ll be explaining about it here! 💪

***

### Day 5️⃣6️⃣: October 4, 2023 - Introduction to #SQLAlchemy (#ORM)

As I mentioned some days ago, I would be learning too about the ORM in SQLAlchemy💻

So again, I practiced connecting a database and inserting, updating and deleting data. But this time not using #SQL #syntax, but using #Python objects and methods. 

I learned to create #model tables and to work using the #session object instead of the #meta_obj I used with the CORE SQLAlchemy component. 

🔹 **HOW TO CONTINUE:**

Next,  I will be working on the @4geeks bootcamp activities 💪

***

### Day 5️⃣7️⃣: October 5, 2023 - Draft of Portfolio with #Figma

I have been wanting to start my first portfolio for some time, to have a nice place to show my projects.

However, I didn't want to just start doing something willy-nilly, but rather I wanted to have a good draft first and think about all the organization and features it was going to have. A perfect time to learn more about Figma.

I had used it a bit in my previous job, but I was the content creator, not the designer. And now I've had to learn many of the design tools.

As you can see, I'm not a very good designer, but the result offers a good vision of what I would like to build. I want to add a lot of dynamic elements that can't be seen in the draft, but I can annotate them next to the part I want to implement.

![Captura 3](https://github.com/vanesascode/introduction-to-sqlalchemy-sqlite-python-venv-dbbrowser/assets/131259155/5fc8e17f-5eab-4edd-8b79-f807ea5a026a)

***

### Day 5️⃣8️⃣: October 6, 2023 - Database diagrams

At class, at the @4geeksacademy bootcamp,  we used the #SQLAlchemy library in #Python to define database model tables and relationships. 

Then, we used the #ERAlchemy (https://github.com/Alexis-benoist/eralchemy) library to generate entity-relationship diagrams.

So, we did the tables of the #StarWars Reading List we created with React days ago, and the tables of what it would be the database of #Instagram

***

### Day 5️⃣9️⃣: October 7, 2023 - First steps with portfolio

In the draft I imagined lots of animations for my website, so I started with that! 

So, in the intro you can see two divs moving in opposite directions, closing the “square brackets”. In the process I realized that I liked the same idea for my logo: square brackets wrapping a V, instead of only the V. 

Then using useEffects to remove the intro and make the rest of the home page appear, along with CSS animations, I achieved the results you can see. Lots of testing and trying to make it work. 

The particles background added difficulty to what I just explained above, also, thinking that I don’t want the intro to appear everytime the component is mounted… so I’ll see how I solve it. I defined some challenges in the draft that will now need some good thinking to solve them! 

***
### Day 6️⃣0️⃣: October 9, 2023 -  #PYTHON !!!

I remember studying a bit of Python before starting the @4geeks bootcamp , and since then, if encountered, I’ve been able to understand it quite well. 

However, now it’s been time to learn it in depth! So, in class we’ve been busy with that, with readings, lessons and online exercises. 💻

About the readings and classes, I have to say that it was very useful to compare #Javascript and #Python. 

The exercises… they are thousands again, as with the Javascript ones! So I’ll be entertained with that for a while! 💪

***

### Day 6️⃣1️⃣: October 10, 2023 - Todo List API in Python Flask

In this exercise at the 4geeks bootcamp class, we created these endpoints with Python (see code). 

I am very excited because at the moment we are building another API which we will connect to a database and make the whole backend process ourselves. 

The rest of activities at the bootcamp will be all related about backend, which is the part I less know at the moment, until we finally join frontend and backend in the final project. I’ll have the chance to work with the whole full stack using both Python and Javascript and can’t wait for it! 

Code: https://github.com/vanesascode/4geeks-python-flask-api-todolist-tutorial

***

### Day 6️⃣2️⃣: October 11, 2023 - Portfolio progress 🔵

I’ve continued building on my portfolio and so far I almost have the intro, the home and the menu. 

I know the hamburger on the big screen is not usual, but I got inspired by other websites, and, since I am focusing on design as much as usability, I took the liberty of doing it. You can open and close it as a normal menu, but it takes up the entire screen for aesthetics. 

I didn’t want a standard mouse, so I am working on that too. I am using the framer-motion library at the moment, but I don't rule out the possibility of using another lighter one. The particles library is quite heavy so I have to be careful. That is why, all the animations on the rest of components are made exclusively with CSS. 

All icons are SVG, so I can manage them easily, and the dark mode is made with the Tailwind dark class. 

I look forward to showing you more as I progress!

***

### Day 6️⃣3️⃣: October 12, 2023 - Learning Backend

As I mentioned the other day, we keep working on backend at the @4geeksacademy bootcamp. 

We are now with Flask, creating the endpoints of the server to work with the data of a PostgreSQL database, which we are dealing with through database models. All this with 4geeks boilerplate on codespace. 

Little by little we keep making it more difficult. 💪

***

### Day 6️⃣4️⃣: October 13, 2023 - Portfolio responsiveness

Today I worked a bit more on the portfolio,  creating several breakpoints and adapting sizes of all to them. It’s incredible how many hours I stay with this eventually,  since everytime I try to leave the computer I see a new little detail I can’t help trying to improve. 

Also, I got rid of the circle cool mouse, although I left the crosshair style for the cursor. This is because, yes, I need to save kbs for the project to work properly… Also, I was cleaning the code as much as I could at this stage for this very same reason. 

I start having some notes about my code on #github: https://github.com/vanesascode/vanesascode_portfolio

***

### Day 6️⃣5️⃣: October 15, 2023 - Going in depth with #NextJS

As I mentioned these days, I'm building my portfolio with NextJS. First I was going to use VITE, as I have been doing until now, however, although I was still not very familiar with NextJS, I preferred to use it better, due to its better configuration and route stability (and more, although I wasn’t that aware by then).

So before continuing, I thought I should study the framework a little more to get the most out of it. So I decided to take courses by @javascriptmastery who has really specialized in NextJS lately. 

I am currently learning about the #server/client components, the app file #router (layout, page, dynamic routes, loading, errors) , the #metadata for better SEO, and more. I’m especially surprised by the server possibilities and the benefits of having the #backend separated from the frontend using just #React. 

Below, you have a pic in which you can see I have been able to connect Next to #MongoDB and #Google Cloud Console, using Next-Auth, in order to be able to #login with the google email into a new app I am building (and of which I will talk more in future days) 

***

### Day 6️⃣6️⃣: October 16, 2023 - More #NextJS Backend!

I’m excited to have created another backend endpoint in my new NextJS app! This app is going to be a repository of AI prompts, kind of https://prompthero.com/ but much simpler for now.

So, I created the #model and the #endpoint for the prompts  on the #server side, and the form on the #client side  in order to be able to create them from the app. Next step will be to render these prompts on the app #frontend as beautifully as possible! 

I’m explaining the process in the code readme: https://github.com/vanesascode/promptgenius-nextjs-nextauth-mongodb

***

### Day 6️⃣7️⃣: October 17, 2023 - Authentication and authorization in #Flask

We continue with the #Backend at the @4geeksacademy Bootcamp. Now we are learning how to create endpoints in our #Python #API so users can register/login in our app, and  to provide them with tokens so they can access the private resources, all using the library Flask #JWT Extended.

Little by little we keep making it more difficult. 💪

***

### Day 6️⃣8️⃣: October 18, 2023 - Rendering authenticated prompts! 

As I mentioned some days ago, I am building an app that is going to be a repository of AI prompts, kind of https://prompthero.com/ but much simpler. This is a way to get more familiar using #NextJS and its super cool server features. 

Now you can see how every user (logged in with Google)  can create their own prompts in the app. 

Next, I’ll be adding more features to the prompts, such as being able to copy them with a click, editing or deleting them. 

Code: https://github.com/vanesascode/promptgenius-nextjs-nextauth-mongodb

***

### Day 6️⃣9️⃣: October 19, 2023 - Authentication and authorization in #Flask

There is some good progress on the @4geeksacademy Bootcamp project we are doing now. 
I have users in my #database, so I can log in and access private info from the #backend thanks to their #token. 

Next, I’ll be adding more info to these users and rendering it into a private page once they are logged in. And I’ll be adding more #UX to the app by adding more messages to the users depending on what they are doing.

I look forward to having it ready! 💪

***

### Day 7️⃣0️⃣: October 20, 2023 - Editing and Deleting Authenticated prompts 🔧🔨

In my app `promptgenius`, an AI prompts repository,  now you can edit and delete prompts inside the user’s  personal profile. 

It is a bit hard at the beginning connecting the endpoints with the components, the fetches, the functions, etc. so everything makes sense, especially with the dynamic routes. But little by little I am getting familiar with all that in #NextJS 💪

The next step will be to manage the other users profiles too, and above all, the #searchbar to be able to search by prompt, user or tag. 

My code notes: https://github.com/vanesascode/promptgenius-nextjs-nextauth-mongodb

***

### Day 7️⃣1️⃣: October 21, 2023 - Understanding backend better in #Flask & fetches in #React

I’ve had one of those ‘ahahhh’ 😮 moments after days working on making the backend routes and the frontend fetches work together correctly. It proves that only practice makes you really know what you think you understood the first day when you learnt about the theory. 

To set the status codes is so important in the backend routes… I wasn’t that aware at the beginning. And setting the conditionals in the frontend to get the results you want is just an art… 

In short, the hours of frustration paid off. However, much much more has to be practiced to become a full stack Jedi. 🌟

***

### Day 7️⃣2️⃣: October 23, 2023 - Portfolio projects preview page

Today I have recovered my portfolio creation work. It was the turn of the projects' preview page.

Instead of just having images of my apps, I decided to add a gif that activates when you hover over the static image. Additionally, they have frames of thinkpad laptops which will become more evident on the individual description page I will create below for each project (why? first, they adds a retro style to the already retro design of the website, and second, we have a thing for old thinkpads at home, strange but true)

***

### Day 7️⃣3️⃣: October 24, 2023 - Search functionality with #NextJS

Continuing my AI prompts repository app, I’ve implemented a search functionality that  allows  users to search for prompts based on the content, user, or tag associated with the prompts.

The search system utilizes a regular expression to match the search query against the relevant data. To enhance the user experience, I have incorporated a #debounce mechanism that introduces a slight delay before executing the search, ensuring a smoother and more responsive interaction.

Code: https://github.com/vanesascode/promptgenius-nextjs-nextauth-mongodb

***

### Day 7️⃣4️⃣: October 25, 2023 - #React trick!

I was working on my portfolio projects’ preview page, and really wanted to add an arrow next to the title of each project when it was hovered. 

I used a useState to set it, but I encountered the problem that when hovering one project, all projects made their arrow appear, since I am rendering the projects from a constants js file with a map function. 

So I solved it by adding the useState inside in the map function. I didn’t know you could do that! It may sound strange if you didn’t know it either, but it works: 

```

const ProjectsList = () => {

  return (
      <div>
        {projectsPreviews.map((pp) => {
          const [isHovered, setIsHovered] = useState(false);

          const handleMouseEnter = () => {
            setIsHovered(true);
          };

          const handleMouseLeave = () => {
            setIsHovered(false);
          };

          return (
            <div
              key={pp.id}
              onMouseEnter={handleMouseEnter}
              onMouseLeave={handleMouseLeave}
            >

              <div>
                <img
                  src={pp.frame}
                   />

                <img
                  src={pp.img}
                   />

                <img
                  src={pp.video}
                   />
              </div>

              <div>
                <p>
                  {pp.title}
                </p>
                <img
                  src= "/up-arrow.svg"
                  alt="arrow to go to website"
                  className={` ${
                    isHovered ? "opacity-100" : "opacity-0"
                  }`}
                />
              </div>

              <p>
                {pp.desc}
              </p>
            </div>
          );
        })}
      </div>
  );
};
```
***
### Day 7️⃣5️⃣: October 26, 2023 - Individual page for each project: 

So, continuing with the portfolio, I managed to render the more detailed info about each project, from the constants js file, into its page, which has a dynamic url. 

The biggest challenge I’m having, though, it’s about design and lots of css. Time spent on Figma and video editors… Made just one project, but the same has to be done for all of them… 😅

By the way, the project you can see below is the AI prompts repository! Which is finished ( I added some sharing buttons as the last feature) and can be visited here:  https://promptgenius-chi.vercel.app/

***

### Day 7️⃣6️⃣: October 27, 2023 - New #NextJS14 project!

Yesterday I couldn’t believe they were announcing the NextJs 14 already at the #NextJSConf … Jesus,  I haven’t even learned the 13 one yet! 🥵

So, it’s time to keep practicing and started a new course in which the project will be kind of a clone of #Threads by #Meta.  It will be an opportunity to keep messing with NextJS features (with #Typescript this time) 

Today I learned about “Route Groups”, which are folders that  let you nest layouts in the same route segment level. (You just have to wrap the folder into parenthesis to create one of those) 

Also, I started learning about #Clerk , which is an open-source identity and access management platform. I can only say I love it for its simplicity and easy docs,  but also for its so powerful features 😍

As for #TailwindCSS I can say that I now prefer adding some of my  ‘classes’ in my tailwind.config file. In the fontSize options, you can add your types of text there, for example. This way, when you hover over the class in your project, you have the “IntelliSense” or cheat sheet that tells you what it is made of, something that the @layout utilities or components don’t tell you. 

***

### Day 7️⃣7️⃣: October 28, 2023 - Building a form with Shadcn/ui, react-hook-form, Zod and uploadthing.

If you read the title, yeah, too many tools to be learned at once just to build a form. I am following this advanced course I mentioned before on building a social media app, and I have to say that so far it is too much for me at the same time. 

So, I have stopped the course here for now, and tomorrow I will be studying the #react-hook-form library docs only and getting some practice with it. Then, I think I can continue investigating the  #Shadcn/ui components and the  #Zod validations a bit more, and about uploading files with #uploadthing (or with other methods) too before continuing the course. 

Anyway, I can’t wait to learn more about everything!

***

### Day 7️⃣8️⃣ : October 29, 2023  - React-Hook-Form 
 

So, as I mentioned yesterday, today I have been reading the #React-Hook-Form library docs and having a go with it in VScode. 

It really makes handling the data and the message errors in forms much easier! 

I can now say I am a bit more familiar with it, so I can start using it along with UI stuff.

***

### Day 7️⃣9️⃣: October 31, 2023 - Better solution for the problem of adding individual states to mapped elements: 

So I few days ago, I  was working on my portfolio projects’ preview page, and really wanted to add an arrow next to the title of each project when it was hovered on. 

I used a useState to set it, but I encountered the problem that when hovering one project, all projects made their arrow appear, since I was rendering the projects from a constants js file with a map function. So I thought I had solved it by adding the useState inside the map function, which apparently worked well. 

However, I’ve wanted to do the same today in my blog articles list, along with a search bar to be able to find any article by any keyword. When I tested the search bar, it gave me the: “Error: Rendered more hooks than during the previous render. “ which I investigated to find it was a problem having to do with my usestate inside the map loop.

That’s why I had to find another solution (and consider the previous one as bad practice). I solved it by adding another state variable (this time outside the loop, of course) which keeps track of the index of the article that is being hovered on. The onMouseEnter and onMouseLeave events  update such state accordingly. Inside the map function, I added a new variable which checks if the current index matched the index variable. 

Gist: https://gist.github.com/vanesascode/2d0a67975a788070901e2e29fa08c3cc

***

### Day 8️⃣0️⃣: Nov, 1 - Blog progressing!

I have the blog list and can go into each particular pill ( I called them like that, because they are going to be short writings ) using #NextJS dynamic segments.

I added the up transition effect for the arrows suggested by @muhham It really was a good idea, it feels much better now! Thanks for the feedback on my work :) 

I also added a  custom scrollbar, which I really like and adds to the style of the site. I used these properties: 

```
.custom-scrollbar-dark::-webkit-scrollbar,
.custom-scrollbar-light::-webkit-scrollbar {
  width: 5px;
  height: 3px;
}


/*dark*/
.custom-scrollbar-dark::-webkit-scrollbar-track {
  background: #000000;
}


.custom-scrollbar-dark::-webkit-scrollbar-thumb {
  background: #bab6e4;
}


.custom-scrollbar-dark::-webkit-scrollbar-thumb:hover {
  background: #ffffff;
}
```

***


### Day 8️⃣1️⃣: Nov 2, 2023 - React-Hook-Form + Zod + Typescript

Today I’ve again worked on forms, yeeeeehhh forms again. You must be bored by now. 

But they are an important component in websites so the more you practice, the better 🤷‍♀️

So, I have been creating the same form but with different kinds of code, to again see the differences and get more used to the forms functionality: just using React tools, then again with React-Hook-Form library; and then again, this time,  creating a Zod schema, connecting Zod with React-Hook-Form, and creating an endpoint to apply the Zod schema as validation in the server too. 

#Zod is great, but to get a real validation in the server, so I receive a 400 error if something is wrong and so on, I had to use NextResponses anyway. 

So here you have the project in which you can see the code and notes in the readme: https://github.com/vanesascode/react-hook-form-zod-typescript-server-errors-exercises

***

### Day 8️⃣2️⃣: Nov 3, 2023 - Messing with Shadcn/ui 

Shadcn/ui is very much on fire these days and it was used in the social media course I was following. So, I took the opportunity today just to focus on what it is and how to use it. 

It is a library of components for React, that can sound similar to Bootstrap, but the difference is that you actually create React components to be used. They can be customized with Tailwind and they are really easy to use. 

The one I liked the most so far is the ‘skeleton’ one, which offers professional placeholders for your stuff when it is loading. And also, how easy it was to customize the colors theme and set the dark mode. 

Code: https://github.com/vanesascode/shadcn-ui-crash-course-recipe-app-json-server

***

### Day 8️⃣3️⃣: Nov 4, 2023 - Continuing social media app

So now that I have been working with the different technologies individually, I can continue with the social media app course. 

Below you will see, #Clerk, #React-hook-form, #Zod and #Shadcn/ui all in action at the same time, using #Typescript. 
Also, #Uploadthing, to load the images, which I found quite difficult to understand (although they say it’s easier to use than other web services like Amazon S3, which I haven’t used yet, though 🤷) 

Next step is to work with the backend so it is all functional. 💪

code: https://github.com/vanesascode/threds-socialmedia-app-nextjs14-mongodb-clerk-svix

***

### Day 8️⃣4️⃣: Nov 5, 2023 - #Next.js #Server #Actions

So, as I mentioned yesterday, it’s time for the backend of the social media app I am building these days
However, this time, I am not having an api server folder inside the “app” router. 👉 Instead, I am using Next.js “server actions”. 

With server actions, you can define server-side functions without needing separate api routes. These functions can access the form data and perform the necessary server-side operations, such as updating the database. 🌟

You can wrap the connection to the database and the actions in a try and catch structure, but what you won’t have is the possibility of adding the server status you like, or at least I couldn’t (correct me if I am wrong, since I am just learning by myself basically and could be mistaken). Although you can see the status messages that keep occurring, in Chrome's network tab all the time, sure. 

And you may say, but when a server action modifies data, such as updating user information or creating a new record, the updated data needs to be reflected on the client-side, right? That’s why Next.js has a #revalidatePath function that triggers a revalidation of the specified path, and which makes the page to be regenerated and updated with the latest data in real-time.  

Another important thing is that you must set the “#use #server” indication at the top of your actions files. Otherwise you’ll get errors such, “can’t read properties of undefined” and things like that. This is because you can’t directly create database actions through the browser side.

👉 Another thing I learned: 

In the code below, notice that the order of the name, path, username, userId, bio, and image values in the object passed to the ‘updateUse’ function does not matter. The function is designed to extract those values from the object and use them in the correct order, regardless of the order in which they were passed.

This is because the function is using object destructuring to extract the values of those properties from the object. #Object #destructuring allows you to extract values from objects by specifying the property names you want to extract, and the order of the property names in the destructuring statement does not matter. Why does it matter? Because it will avoid possible errors in the future. ✨

code: https://github.com/vanesascode/threds-socialmedia-app-nextjs14-mongodb-clerk-svix

***

### Day 8️⃣5️⃣: Nov 6, 2023 - Another complex #NextJS Form

So now that I have the 'users' managed in the social media app I am building,  I have repeated the process for the creation of the user's  ‘Threads (or Twits, or call them as you like). This time the process was easier because I didn’t have to deal with image files: 

- So, I have again created a form, using #Shadcn/ui elements, adding #zod validation and connecting it to the #React-Hook-Form functionality of the form with a #resolver.

- Then, I have created the #server #actions that work as backend endpoints in Next.js. As I mentioned yesterday, they are functions related to fetching, creating, deleting, and manipulating, in this occasion, threads. 

- Of course, ‘threads’ #moongose #model has been created too, so the server actions can have access to the table threads in the database of #MongoDBAtlas. 

code: https://github.com/vanesascode/threds-socialmedia-app-nextjs14-mongodb-clerk-svix

***

### Day 8️⃣6️⃣: Nov 7, 2023 - searchParams and Pagination in #Nextjs

Now that I can render threads in my social media app home page, it was time to apply some pagination to handle the amount of threads shown. 

In Next.js, the #searchParams property is derived from the query parameters in the URL. It allows you to access and manipulate these parameters. So, to deal with the pagination, I was able to pass the searchParams object to the fetchPosts server action function in order to retrieve posts based on the page number. This server action function also gives me access to a variable I called ‘isNext’, which determines if there are more posts to show on the next page.

To enable or disable the pagination buttons, I created a Pagination component. In there, there is a ‘handleNavigation’ function that handles the navigation logic based on the button clicked and updates the URL accordingly.

The initial pagination value is set to 1, of course, and the searchParams object is updated with the new page value when the 'Next' button is clicked. This allows you to navigate through the pages and update the URL accordingly. (see the URL in the pic below) 

code: https://github.com/vanesascode/threds-socialmedia-app-nextjs14-mongodb-clerk-svix

***

### Day 8️⃣7️⃣: Nov 8, 2023 - Parent & Children Threads

In this social media app I’m learning to build, users can post comments on existing threads. By using the parentId and children properties, it is possible to create a nested structure of comments, allowing for threaded conversations in a social media app. Each comment can have multiple replies, and these replies can have their own replies, creating a tree-like structure of comments.

So:

When I created the ‘thread’ model, I added an optional ‘parentID’ and possible ‘children’ properties that would be created when comments are saved. So, when the comment is created, it takes the id of the original thread as the parentID. This way I have it easy to render either original threads in the client’s (the ones that don’t have a parentID) and the comments (the ones that do have a parentID) 

Then, in the same ‘addCommentToThread’ server action, I am pushing the comment as children to the original thread. So, while I am creating the comment, I am also updating the original thread with this new property in the database. This way, I can render together all the comments that are related to a particular original thread. 

Since this is made recursive, once I create a comment from another comment, This second comment gets the ID of the first comment( which is the ID of the original comment) and sets it as its parentID. 

Each thread is rendered in a ThreadCard component, which in the case of comments, has a boolean true  ‘isComment’ prop. This makes it possible to conditionally render or apply different styles or behaviors based on whether the component represents the original thread or a comment.

And how is it that the comment passes to be kind of an ‘original thread’ in the individual thread page, when I create a comment of the comment? Because the Link that the button of replying holds, is going to /thread/${id} , thanks to params. And when clicking, then the individual thread page renders again, but placing each thread id into the Thread component that it has to go to…

Jesus! I found it really hard to understand it all. However, trying to explain it here in the code challenge post, helped a lot to organize the code in my head and see the light. 

code: https://github.com/vanesascode/threds-socialmedia-app-nextjs14-mongodb-clerk-svix

***

### Day 8️⃣8️⃣: Nov 9, 2023 - Conditionally rendering the profile page

It is not new that the profile is rendered conditionally depending whether it is the profile of the user it is logged in or another user. It is a good way to reutilize the profile page and its components. 

However, the special thing here in this app,  is that it uses the user id of both the database of Clerk and  the  database of MongoDB for the condition to render certain things in a profile or another. I will explain myself better: 

- As I mentioned in previous days,  when the user is logged in for the first time, is registered in Clerk first. There it has an id. Then the user is sent to a process of onboarding, in which the user has to add more info to their profile. When this form is saved, the user has another id that comes from the mongoDB database. 

- Then, when you click on the pic or the username of a post, you are sent to the path ‘/profile/{user.id}’ . This ‘id’ is the one from Clerk. So, by comparing this id from Clerk with the _id from mongoDB, of the current logged in user, I can add an edit button (see in the video) to the current user’s profile (because the result of the comparison is true) and make it not appear in the rest of user’s profiles (because the result of the comparison  is false). 

code: https://github.com/vanesascode/threds-socialmedia-app-nextjs14-mongodb-clerk-svix

***

### Day 8️⃣9️⃣: Nov 10, 2023 - Reusable components trick in #React

The component that renders the threads in the social media app I’m building is a component that I reuse quite a lot. In the case of rendering all the comments (which are also thread components) of a particular thread, all together one below the other, I wanted to add more bottom margin below the icons, so the line below the profile pic also became longer. 

A trick to add a modification that only applies to the component sometimes, is to add a prop to the component (only when you want the modification) that you can add to its code as a condition. If the prop is true, then the changes apply. 

***

### Day 9️⃣0️⃣: Nov 11, 2023 - Search users implemented

The social media app I’ve been talking about these days, has now the part of searching users implemented. 

In the AI prompts app I collected the search query (a string)  using ‘useState’ and then applying a regular expression in the ‘fetchPosts’ function to match the search query against the data. This time,  I am including the search query in the URL and collecting it in the ‘searchParams’ in order to send it to the ‘server action’ that is retrieving the users. 

So in the search bar, if there is a search query in the input, then:  `router.push(`/${routeType}?q=` + search)`. The server action receives this searchParams and then it does the logic with the regular expression. Of course, if there is no search query, then the server action just gets all the users. 

I build this search page along with the pagination I explained the other day, which also uses searchParams.

code: https://github.com/vanesascode/threds-socialmedia-app-nextjs14-mongodb-clerk-svix


***



