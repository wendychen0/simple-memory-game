# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Wendy Chen**

Time spent: **8** hours spent in total

Link to project: https://glitch.com/edit/#!/festive-common-wrinkle

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

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://cdn.glitch.global/bc8070c2-95e0-433a-aee8-a0f84941dd0a/lsgame1.gif?v=1648865804582)
![](https://cdn.glitch.global/bc8070c2-95e0-433a-aee8-a0f84941dd0a/lsgame2.gif?v=1648866171947)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
To help with the alerts: https://stackoverflow.com/questions/42947598/alert-text-variable-javascript
For changing button colors: https://www.quackit.com/css/css_color_codes.cfm

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
I found figuring out how to reference different variables and getting the specific syntax of things a bit confusing at first. 
Once I got more familiarized it was better, but specifically implementing the logic in the guess function was one of the harder tasks. 
I had an issue with the game automatically saying the player lost on the third turn even after pressing the right button. I originally thought 
it had to do with my logic when trying to implement the feature of giving 3 lives, but the issue was still there after I commented those lines out. 
I ended up adding multiple console.log lines to check the values for each of the variables after each round and trying to see which one was off. 
It was the guess counter that wasn’t resetting properly on the third turn. I went through the logic multiple times to see where I might’ve went wrong, 
but everything seemed to make sense. Later, I looked over the steps again and found that I had added var to the guessCounter variable when initializing it 
in playClueSequence() which messed with the value.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
Some questions I have about web development is how to figure out all the functions you need to do a task and better understanding adjusting the structure 
of a website when you add in buttons and text. I feel that it can be hard adjusting things to the right locations and getting the right sizing. More broadly, 
I’m curious about the different roles you can get as a web developer and the different levels there are. What are things you can do to optimize a website’s loading time, 
especially if there are tons of users browsing on it simultaneously. Another thing I’d be interested in learning would be tracking the number of users that have visited or 
engaged with the website.


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours for this project, I would want to add additional features like changing the pattern to be completely random each or pick from a list of different patterns to make it more randomized. 
I would work on improving the UI of the game like making the win message pop up in the middle of the screen and adding additional effects like confetti. As well as having the buttons/game centered on the webpage. 
This is related to some of the optional tasks I didn’t get the chance to implement, but I would have tried changing the sounds and appearance of the buttons.



## Interview Recording URL Link

[My 5-minute Interview Recording]
https://www.loom.com/share/39e9e16e6b8a46cb9eabfd825dd86e21


## License

    Copyright [Wendy Chen]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.