# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Anna Mei**

Time spent: **2** hours spent in total

Link to project: https://glitch.com/edit/#!/pyrite-unique-noise

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

![](https://i.imgur.com/3d8pyJV.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
N/A

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
One challenge I encountered while creating this submission was bringing all the files together in this GitHub repository. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
After completing this submission, 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
    If I had a few more hours to work on this project, I’d add a few more features to the game. One thing I would add is a counter that would tell the user how many more “rounds” they need before they win the game. Before the game starts, I would also add a separate screen that would allow the user to choose what difficulty they would like their game to be (easy, medium, or hard). The easy level would use an array with an index of 5 as the correct button combination, the medium level would use an array with an index of 10, and the hard level would use an array with an index of 15. I would also like to add a strike counter to each level. For the easy level, the player will start with one strike. For the medium level, the player will start with 2 strikes, and the hard level will have 3 strikes. There will be a variable for strikes, and this variable will update with the amount after the user begins the game and chooses a difficulty level. If a player presses an incorrect button, the variable will update and by subtracting one from the current value of the variable. After each “round” in the game, the program will check whether or not this variable is equal to 0. If it is, the game will end. 



## Interview Recording URL Link

https://drive.google.com/file/d/1NOXoEsWbSGFybuhbRekV-uKWaMU29WDz/view?usp=sharing


## License

    Copyright Anna Mei

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
