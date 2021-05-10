# SEI Project 2: Quizavision

## Table of Contents
Overview<br/>
[Brief & Timeframe](#brief) <br/>
[Link to Project & Installation](#project) <br/>
[Technologies used](#technologies-used) <br/>
[Development (screenshots & featured code)](#development) <br/>
[Known bugs](#bugs)<br/>
[Wins and Challenges](#wins)<br/>
[Future improvements](#improvements)<br/>
[Key learnings](#learnings)<br/>

## Overview
This was my second project at GA and we had to create a React app within 48 hours, in pairs, that consumed an external API.
<br/>
<br/>
![quizavision-homepage](https://github.com/hannahtinacci/sei-project-two/blob/master/quizavision-home.gif)

## <a name="brief"></a>Brief 
* Consume a public API
* Have several components
* The app can have a router with several "pages", if it makes sense for your project
* Include wireframes
* Be deployed online and be accessible to the public

## Timeframe
48 hours

## <a name="project"></a> Link to deployed project 
https://quizavision.netlify.app/

## Code installation
* Clone or download the repo
* In Terminal run the command: yarn
* Start development server by running: yarn start



## <a name="technologies-used"></a>Technologies used
* React.js & React Hooks
* JavaScript (ES6)
* HTML5
* Axios
* Insomnia
* Bulma
* SCSS
* Git/GitHub
* Open Trivia Database API: https://opentdb.com/api_config.php


## <a name="development"></a>Development 💻

### Planning
My partner and I started out exploring the numerous public APIs that are available looking for two things: a topic we both enjoyed and the data in a workable format for such a short timeframe. We knew from previous tasks that drilling down into JSON objects for exactly what you wanted can sometimes be tricky so we made sure to explore the various endpoints of the APIs we were considering using Insomnia. In the end, we decided to build a trivia style quiz using the Open Trivia Database API.

The Open Trivia DB has many questions, of varying difficulty levels, and 23 categories to choose from. We had to narrow it down so initially went for four categories with multiple choice answers. Below are a couple of wireframes that show our ideas for the basic layout of the homepage and main question page. 


### Process

## <a name="bugs"></a>Known bugs


## <a name="wins"></a>Wins and Challenges

### Challenges 
Being the first React app I’d built there were, of course, challenges, add to that the very limited timeframe and one could have expected more issues. However, one of the main challenges was the way the answers were stored in the API: the correct answer was a key-value pair, and the incorrect answers were stored in an array. This proved troublesome in extracting all of the answers and randomising for a new question each time. We got there in the end! 

### Wins 🎉
This was my first project working in a pair and I found it eye-opening and thoroughly enjoyable. It felt great to work with someone towards a common goal and we pair-coded for the majority of the time, supporting each other and making it a lot easier to avoid those easily missed mistakes that a second pair of eyes catches in no time. It was a fantastic learning experience. 

## <a name="improvements"></a>Future improvements 
* Timer. Whilst the idea of having a timer display how long a user had to complete a set of questions was on our initial wireframe, it was too low down on our list of priorities for bonus features. 
* More categories. The Open Trivia DB API had many categories so this could help turn the quiz into a training ground for pub quizzes. 
* Authentication. This was explicitly left off the brief but it would be a nice addition to allow users to login in and see their previous scores and share with other users. 


## <a name="learnings"></a> Key learnings ✨
After the first solo project, this project taught me to be mindful of my partner and how they liked to work, as well as being aware of my own working habits. With it being my first React app, too, it solidified my understanding of setting state and passing props, as well as become a lot more comfortable with interrogating APIs and their endpoints. 
