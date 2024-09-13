# 100-days-of-code

## Day 1

For day 1, I decided to go back to basics and build a simple FAQ accordion using HTML, CSS and Javascript.

This was adapted from a challenge by Frontend Mentor, but I customised the design and content to make an FAQ page for my podcast, Flourish and Thrive🎙️
As I hadn't been able to code all summer due to traveling and working at a summer camp, I was feeling a little rusty! But it certainly felt good to flex my coding muscles and see how much I had remembered from my Northcoders bootcamp.

This was a great opportunity to revise my CSS styling, particularly working with flexbox, and also a good refresher on DOM manipulation. I really enjoyed playing around with the styling to match the branding of the podcast (lots of pink!). I also added a transition to ensure the accordion opens and closes smoothly, to improve the user experience.

Repo: https://github.com/alicewilson17/faq-accordion

## Day 2

Today I built an interactive rating component, another challenge by Frontend Mentor. This project was a great opportunity to remind myself how the DOM works and how Javascript can be used to manipulate HTML elements. I also feel like I'm getting the hang of CSS flexbox, which was something I used to struggle with! I also learned how to toggle the appearance and disappearance of elements using event listeners.

I'm particularly proud of successfully implementing a feature that captures the user's rating based on their button selection and displays that rating once the submit button is clicked. It's always a great feeling when the code works on the first try!

Overall, I enjoyed this project and found it incredibly valuable to learn how to build this component. This experience will definitely be useful for future website development!

Repo: https://github.com/alicewilson17/interactive-rating-component

## Day 3

Finished building my portfolio website! I started building this before I went traveling, so thought it was about time I got it up and running. I built this using React and styled it using Vanilla CSS. I’ve kept the styling pretty simple for now, as I want to focus my energy on building projects and enhancing my coding skills.

Live site: https://alicewilsondev.netlify.app/

## Day 4

Started building a landing page for my podcast website, using Vanilla Javascript, HTML and CSS. Spent today building out the basic HTML elements and adding some basic styling.

## Day 5

Finished off the landing page, adding in the Javascript functionality. I also added a form for the user to sign up for email updates, which was a great refresher on form validation. 

I also played around with the CSS to make the page responsive, so that the layout looked good on screens of all sizes.

Repo: https://github.com/alicewilson17/base-apparel-landing-page

## Day 6

Study day. Started the Codecademy Intermediate Javascript course, with the aim to refresh my Javascript skills and build my coding confidence. Today I covered Javascript Classes, and really took the time to refamiliarize myself with the content. During the bootcamp there were so many new concepts to learn in such a short time, so I really enjoyed having the time to properly absorb the concept and make sure I really understood it and its use cases.

Also did some katas on codewars.

## Day 7

Started the Scrimba React course, to further develop my React skills. I love the format of this course as there are so many challenges for you to complete on your own, and projects to build, instead of just following along with a video. This interactive way of learning really works for my brain!

Also made a few more final changes to my portfolio website.

## Day 8

Continued with the React scrimba course. It's so engaging I really like the format!

## Day 9

React scrimba course again. I feel like I have a really good understanding of props now! Built a clone of the Airbnb experiences page to practise building static web pages using React, and passing data on props from a parent to a child component.

## Day 10

Today on the React Scrimba course I started looking at dynamic web applications. Started building a meme generator site. Covered event listeners and state in React. The course went into detail on when to use props vs when to use state and it really imporved my understanding!

## Day 11

Another day of the React Scrimba course - today was a deep dive on state and the various ways it is used in React, as well as the different ways you can update state and different use cases.

## Day 12

Today in the React course we covered conditional rendering of components, and started looking at forms in React and how they differ from regular HTML forms.

## Day 13

Another day of the React course - continued with a deep dive into React forms and their various elements. Learned about controlled components, and the useId hook to help improve accessibility.

## Day 14

Today in my React course, I learned about side effects and how the useEffect() hook can be used to perform side effects in React components. This will be especially useful when making API calls within my React apps! Also learned about cleanup functions and the circumstances under which these are needed.

## Day 15 

Started the final projects of the react scrimba course. Modified an existing codebase to implement a dark and light mode, and a toggle function to toggle between the two modes. Jumping in to an existing codebase and getting my head around the code is something I’ll have to do regularly as a software engineer so this was great practice.

## Day 16 

Added some new features to an existing codebase for a Markdown Notes App. Really taking the time to understand the codebase is a crucial skill when working with a company’s codebase as a software engineer.
I added the following features:
- Any changes to notes will be synced with localStorage, so the notes retained even after the app is refreshed. 
- Changed the note title in the sidebar to be the first line of the note.
- The most recently modified note is bumped to the top of the list.
- The user can delete a note upon clicking the delete icon.

## Day 17

Started refactoring the notes app to connect to firebase firestore. This means that the data will be saved to an actual database instead of localStorage, so the notes data is saved in a much more permanent and robust way.
Set up Firestore project and connected it to the app. 
Used the firebase onSnapshot function to keep the local array of notes in sync with the database.
Bug to fix tomorrow: createNewNote function was changed to create a new note in the firestore database. Currently it is adding new things to the firestore collection when clicked, but it must not be syncing to the local array of notes, as it still thinks the array is empty and so it is not rendering the screen with the editor on it. 

 

