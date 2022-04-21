# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Eduardo Aguilar**

Time spent: **11** hours spent in total

Link to project: https://glitch.com/edit/#!/titanium-ossified-handball

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

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

Game Loss
![](https://i.imgur.com/KMCzmXK.gif)

Game Win
![](https://i.imgur.com/RNdkXNv.gif)

![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

https://www.rapidtables.com/web/css/css-color.html 
(For font and color)

https://stackoverflow.com/questions/38020361/javascript-guessing-game 
(Helped understanding my issue)

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

I only encountered one significant issue when attempting to run the game using the guess variables provided. Using the variables provided I was only allowed to attempt the guessing game until the third round then the game would end abruptly. Immediately I determined the issue was due to the Javascript guessing aspect of the game, after troubleshooting and a bit of research I determined I needed to add another variable to keep track of the progress I was making in this case I added a lossCount variable set to 0 and added it to my guess function. Adding this to my function allowed my game to complete the color pattern and prompted me with the “Win Game” alert as well as the “Loss Game” alert when selecting the wrong color which marked it as a guess.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

I found this project to be a fun learning experience, more specifically after completing this submission I gained a little bit more knowledge in terms of the sound frequencies in code. Yet, it still had me wondering how these variables are made and determined to create those types of frequencies? Is there a chart or a data table that helps with these? And as it was slightly mentioned how is sound theory incorporated with code?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

With the extra time I had, I decided to add some style features such as fonts and color for the background I also altered the original pattern for the game. If I had a few more hours to work on this project I would consider adding another color block to further complicate the game pattern and also alter the sound by adding new sound variables to test new pitches for the color blocks; it would be a cool feature to add and learn a little more about in the process of creating it. 



## Interview Recording URL Link

[My 5-minute Interview Recording]
(https://www.loom.com/share/bcd51f2854174398863e3f7899aa6e95)


## License

    Copyright [Eduardo Aguilar]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
    
