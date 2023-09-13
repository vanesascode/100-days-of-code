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


