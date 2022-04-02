# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Shayla Nguyen

Time spent: 3 hours spent in total

Link to project: https://glitch.com/edit/#!/grape-insidious-principal

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
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
The first and second GIFs show a completed game. The third GIF shows the use of 3 lives and losing after the 3rd mistake.
![](https://i.imgur.com/nLGyt1o.gif)

![](https://i.imgur.com/4D0WKlD.gif)

![](https://i.imgur.com/df4rfpO.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://www.tutorialrepublic.com/css-reference/css3-properties.php)

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The biggest challenge I came across was figuring out how to add images to the buttons and make them appear when clicked. I tried to add an img tag in HTML for each button and make the class hidden. However, I could not figure out how to make it appear when the button is clicked. I overcame this problem by instead, making the image the background of the button in CSS rather than adding an img tag. Thus, I could make the image the background only when the button is active and lit and else, there would be no image background.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I would love to know how to make applications be able to take inputs from multiple users, saved them, and allow users to interact with each other, like social media. I was also wondering if there is a way to do web development without using an intermediate application like glitch and how one would go about that. Lastly, once a web application is created, how is it made usable by other people? Is there a link that is created to use or how is it translated into an app on a phone?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had more time, I would definitely try to implement the timer for the game. Additionally, I would add a life visual to show how many lives you had remaining rather than just having 3 lives at the beginning and forgetting how many you have used. Lastly, I would have liked to add different difficulty options (easy, medium, hard) that increase in speed, number of buttons, and length of pattern.



## Interview Recording URL Link

[My 5-minute Interview Recording]
https://mit.zoom.us/rec/share/_128rEfYT9P-ameRDbx7R3eNpn5uYYc8477spKTnFv0bN1n3QPV14GSt51Acy-Nc.YVmivjscr1cEKvce


## License

    Copyright Shayla Nguyen

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.