# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Diana Sanchez

Time spent: 3.30 hours spent in total

Link to project: https://glitch.com/edit/#!/separate-amplified-cardinal

## Required Functionality

The following **required** functionality is complete:

* [*] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [*] "Start" button toggles between "Start" and "Stop" when clicked. 
* [*] Game buttons each light up and play a sound when clicked. 
* [*] Computer plays back sequence of clues including sound and visual cue for each button
* [*] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [*] User wins the game after guessing a complete pattern
* [*] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [*] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [*] Buttons use a pitch (frequency) other than the ones in the tutorial
* [*] More than 4 functional game buttons
* [*] Playback speeds up on each turn
* [*] Computer picks a different pattern each time the game is played
* [*] Player only loses after 3 mistakes (instead of on the first mistake)
* [*] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://i.imgur.com/ws0rR9g.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
  [1] https://www.w3schools.com/js/js_random.asp used for the random patteren generator
  [2] https://www.w3schools.com/tags/tag_img.asp used for img in button

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
  I had trouble placing the pictures in the position of the button, so that it appears when it is clicked. However, I noticed that the JavaScript 
  functions lightButton and clearButton could be added to the onmousedown and onmouseup to work the same way lit does but remove the class "hidden" 
  from the img. I used the class "hidden" in the images the same way it was used for the start and stop buttons, so it gets removed when the mouse 
  is down and added when the mouse it up. For the GIF, It was hard to demonstrate all of the requirements in a small time frame since EZGif only 
  allows you to convert a 60 second video to a gif and its only 5 frames per second. To make it 10 frames per second, I sped up the video to 2x 
  speed and converted it so it isn't as choppy as the 5 fps option. I tried to use a different converter so that I could make a longer gif but 
  the HackMD workspace didn't let me upload a large gif so I had to use the sped up gif with low frame rates. Also the gif doesn't demonstrate the 
  sound of the buttons which isn't something that could be fixed unless a video was uploaded.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
  One question I have about web development after completing this task is what exactly is the process of transferring a game 
  or service that was coded using multiple files into an app store. Would it be similar to the process of compiling files in a
  zip folder and having it available to download and run on a different platform? I'm also interested in the cost of uploading
  a game, would the price be dependent on the number of files/lines of code? 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
  If I had more time to work on this project I would definitely try and find a way to implement more complex sounds than a single tone, maybe as a challege in further runs of the game.
  I would also display the number of mistakes on the actual page, since I didn't implement that feature in 
  the current sample. Something else that would be interesting is to add is to display the notes that match the frequency of the button. For example, I made my 
  first button match the frequency of the G chord on the piano, second= A, third=B, fourth=D, fifth=A at a higher octave, sixth=G at a higher octave, and seventh= C. 
  When the game is first played, I actually programmed it to play a specific sequence(Zelda's lullaby) rather than a random one since I thought it would be fun to make.
  So I think making a set of sequences that play specific songs, and display the song at the top of the page, would be really interesting to implement.

## License

    Copyright Diana Sanchez

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.