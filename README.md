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

    One challenge I encountered while creating this submission was designing the guess function in the script.js file. While I have had experience coding in JavaScript, it has been a while since I have used it. As a result, I had trouble remembering the syntax, which made it difficult as I encountered a couple of errors while writing the function. To overcome this challenge, I looked at the other functions the tutorial provided to gain an understanding of the syntax (e.g. how the if-statements work, what did and did not need a semicolon, etc.). When I got to this step of the submission, I was also unsure of how I wanted the guess function to work. To overcome this challenge, I decided to pseudocode my thoughts before writing the function. I thought about the steps the function should take when a player pressed a button to guess, and I wrote those steps as comments. After that, I wrote the code around the comments to make sure I was following each step I had written. After I finished writing my attempt for the guess function, I looked at the example code that the tutorial provided to see how accurate mine was before making adjustments. 



3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

    After completing this submission, I started wondering about the difference between a static and dynamic website. While working on the project, I noticed that Glitch labeled this as a static website. From previous research and knowledge, I understand that the main difference between the two types involves the content: the content on a static website stays the same for every user, while information on a dynamic website can change. Dynamic websites can also have databases and APIs connected to them. After this project, which gave me insight into how to create a static website, I would now like to learn more about creating a dynamic website. Additionally, I would also like to learn more about APIs. I have often heard the term "API" when the topic of web development comes up, but I am not very familiar with the concept. However, I would like to learn more and understand how to utilize them as I hope to work with APIs in the future.



4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
 
    If I had a few more hours to work on this project, I’d add a few more features to the game. One thing I would add is a counter that would tell the user how many more “rounds” they need before they win the game. Before the game starts, I would also add a separate screen that would allow the user to choose what difficulty they would like their game to be (easy, medium, or hard). The easy level would use an array with an index of 5 as the correct button combination, the medium level would use an array with an index of 10, and the hard level would use an array with an index of 15. I would also like to add a strike counter to each level. For the easy level, the player will start with one strike. For the medium level, the player will start with 2 strikes, and the hard level will have 3 strikes. There will be a variable for strikes, and this variable will update with the amount after the user begins the game and chooses a difficulty level. If a player presses an incorrect button, the variable will update and by subtracting one from the current value of the variable. After each “round” in the game, the program will check whether or not this variable is equal to 0. If it is, the game will end. 



## Interview Recording URL Link

https://drive.google.com/file/d/1NOXoEsWbSGFybuhbRekV-uKWaMU29WDz/view?usp=sharing


Note: Third party cookies must be enabled if viewing in incognito mode.


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
