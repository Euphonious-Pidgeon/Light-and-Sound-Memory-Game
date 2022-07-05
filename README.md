# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Kevin Li**

Time spent: **8** hours spent in total including optionals

Link to project: (https://glitch.com/edit/#!/autumn-triangular-newt?path=README.md%3A88%3A138)

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
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

**Playing the game normally (gif was too long to win the game)**

<img src="http://g.recordit.co/FFwS1xFQox.gif" width=790 height=500><br>

**Losing the game**

<img src="http://g.recordit.co/JPnYWQeHU0.gif" width=790 height=500><br>

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

    The CodePath instructions are out of date to an extent, and finding the necessary information proved to be difficult. 
    I went on YouTube to get a tour of it first through the channel Jon Smikly, and that gave me a good idea of what I was looking for.
    When it came to creating randomized patterns, I had to look up Math.random on W3School, and it was very clear on how to pick numbers within a range.
    In regards to inserting images into a button, I used W3Schools to learn how to do that, only problem is not knowing where to get an image link through the assets.
    For that, I received help from YouTube through a channel called Maniflames.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

    A lot of code was provided by CodePath, and a terrible bug came along with it. When I thought that I finished the necessary functionalities,
    I tested the game and it would not let me click through a sequence of 3. For example, if blue blue green lit up in sequence, clicking blue blue would end the game
    in a loss before the user can click green. However, if one were to click blue then green, the game would continue normally despite missing another blue.
    I thought this had something to do with an array where it only kept track of 2 clicks from the user, but I could not find anything like that in the code.
    I pulled up the log console and everything functioned normally despite the bug. In the end, I went back to the CodePath instructions to compare my code
    2 times to find out that my guessCounter variable in the playClueSequence function had a var in front when it shouldn't have.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

    I wonder if Adobe XD or some other tool would be easier to use when it came to making a website? Adobe XD allows for
    an easy creation of design with functionalities incorporated into it such as clicking interactions. One upside to this tool is that
    there are no code involved to make the site, which drastically reduces potential bugs to be had.
    Although there are probably some functionalities that Adobe XD can't create unlike Javascript, but I reckon those functionalities are rarely used.
    I can be totally wrong though, this is my first time using JavaScript and having sequential memory is definitely something Adobe XD can't easily do (but still possible).
    The language itself is already amazing and yet people are saying react is a lot better, I wonder what types of functionalities are to be expected in the future?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

    I was in the middle of coding up the timer for the last optional stage, but I could not get it to work.
    I coded up the display for it to show on html and was able to hide/unhide it in perfect sync with the start/stop button.
    That's where I started to get tired and loss track of a lot of variables to code the countdown function.
    If I had more time, I would definitely go back and finish it.
    Another thing I would spend more time on is to understand the sound functions provided to us.
    The three functions consists of a lot of code which makes it visually intimidating that as I coded my JavaScript, I usually coded the beginning of the file
    and the end (the middle is where the sound functions are) and in my head, there appears to be this thick fog in the middle, which did not make navigating
    any easier. This fog is also part of the reason why I was losing track of my variables.
    If I do end up understanding the code provided, I would then try to tackle on the optional functionality of including a complex sound.





## License

    Copyright [Kevin Li]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
