# Redux Project Mode Guidelines

## Overview

Welcome to your React-Redux project! We'll be putting all of your awesome knowledge to work during this weeklong project mode. When ideating on project ideas, think of something that will be a good demonstration of what you've learned over the course.

## Project Requirements

1. You will need two repositories - a Rails API that returns JSON and a React-Redux front-end. If you want to include other extenal APIs that is fine, but your Rails API should be responsible for loading that data and serving it to your React application. 
2. Your Rails API must have at least three models - two main resources and a join model.
3. Your Rails API should have test coverage for your models and requests. 
4. Your Redux application must communicate with your backend through web requests using Action Creators and Reducers.
5. There is no minimum requirement for the number of components, but each one should have a sensible scope. I.E. `CatsPage` which loads data and passes it to `CatsIndex` and `CatsShow`.
6. You must use Trello for project management. Keep this up to date - it's worth it!
7. Try to think of an application that will be good for React. [Here are some apps](https://react.rocks/) that are good at leveraging it - just keep in mind that you'll need to appropriately scope the project. 

## Sample Schedule

Here are some benchmarks for the project, along with an idea of when you should expect to hit them.

### Day 1
  + Project Ideation. Decide what you'll be building, including figuring out your domain model, URLs, and wireframeing your views. Decide on the different iterations of your application here as well (skateboard, scooter, bicycle, motorbike, car)  **You must get instructor approval at this point before continuing**
  +  Begin building out your API. Plan to have the first version working by the end of the day Monday.

### Day 2
	
  + Begin implementing your front end components using React and Redux. Decide what data structure your store's state will have.   **You must get instructor approval at this point before continuing**
  + Build with dummy-data first before implementing your API. Get your different actions and reducers set up. 
  + As your adding components, add some basic bootstrap stylings. Don't spend too much time making things perfect, just get your components appearing where you want them. Bootstraps `col` classes are extremely helpful for this. 

### Day 3
 + Finish your MVP version by today. You should have something that works. We'll do a check-in demo for the class as a benchmark and make sure we've deployed to Heroku.


### Day 4 - 5 / Weekend
+ Now that your MVP is working, you can start implementing stretch features. Have a crazy API you'd like to dig into? Go for it. Want to use D3 for data visualization? Now's the time. Your instructor will be here to help you break down these goals. 


### Day 6
+ Cleanup/Bug Fixing - by Monday of Week 2 all of your features should be implemented. This day should be about cleaning up styling and fixing any small bugs. 
<p class='util--hide'>View <a href='https://learn.co/lessons/react-redux-final-project'>React-Redux Final Project</a> on Learn.co and start learning to code for free.</p>
