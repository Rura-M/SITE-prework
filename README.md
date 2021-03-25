# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Ruramaimunashe Mutefura

Time spent: 2hrs

Link to project: https://glitch.com/edit/#!/smooth-glimmer-flyingfish?path=style.css%3A1%3A0
## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] The buttons produce a shadow and a highlight when they are hovered over.

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![](https://github.com/Rura-M/SITE-prework/blob/main/gif/ezgif.com-gif-maker%20(5).gif)
![](https://github.com/Rura-M/SITE-prework/blob/main/gif/ezgif.com-gif-maker%20(2).gif)
![](https://github.com/Rura-M/SITE-prework/blob/main/gif/Hnet-image.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

  w3schools: https://www.w3schools.com/css/css3_buttons.asp

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
I had trouble identifying where to place the hover effects. I tried placing the effects for each button, but it was not working. After doing some research and asking other people with experience using CSS, I figured that I had to place this styling under the overall styling for buttons. I learned that one of the main things to consider when placing styling is which features need to be affected by that styling and if they can be placed under one body to reduce redundancy. Through the research I did, I discovered that there are different ways of styling buttons. I tried some of the styles but they were not working well with the demo app. With more practice, I am sure I'll be able to figure out how to implement these styles. 
I also had challenges with implementing the logic for the Guess function as I did not have any prior knowledge of Javascript. The code I wrote kept on continually running as I had not included conditions for when progress was equal to pattern length. I realized this issue after comparing it with the provided code. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I would like to know more about styling web pages. I have seen webpages which have overlays and I am interested in knowing more about how this is achieved. Also, I am interested in knowing how game web applications are created and the frameworks that are used for styling? I would also like to know how web games are supported on a large scale such they have high perfomance especially under stress conditions. Also, if this was to be further developed, how would we store game progress of a person (i.e. how do we connect the backend to the front-end)? I would also like to know more about the different paths available in web application development. I would also like to know how different teams cooordinate in building a web app.


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I would spend time adding features that improve the UI of the game by using CSS frameworks e.g. Bootstrap. Another feature that I would like to add are celebratory features, e.g a trophy, that is displayed on the screen when the user wins and another when the user loses. I would also add different categories of sounds e.g animals, songs, etc. I would also explicitly add levels of difficulty so that the user can easily measure their progress. Another interesting feature would be a multi-player feature which can also keep scores.


## License

    Copyright [Ruramaimunashe Mutefura]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
