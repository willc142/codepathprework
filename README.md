# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Will Confoy**

Time spent: **1.5** hours spent in total

Link to project: (https://glitch.com/edit/#!/longhaired-sudden-feet?path=script.js%3A68%3A19)

## Required Functionality

The following **required** functionality is complete:

* [1] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [1] "Start" button toggles between "Start" and "Stop" when clicked.
* [1] Game buttons each light up and play a sound when clicked.
* [1] Computer plays back sequence of clues including sound and visual cue for each button
* [1] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
* [1] User wins the game after guessing a complete pattern
* [1] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [1] More than 4 functional game buttons
* [1] Playback speeds up on each turn
* [1] Computer picks a different pattern each time the game is played
* [1] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!
  I also made the start and stop buttons change color when hovered over so that it looks a little better.

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://github.com/willc142/codepathprework/blob/main/codepathprework.gif)
![](https://github.com/willc142/codepathprework/blob/main/codepathprework2.gif)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
I looked up the functionality for the Math.random function, as well as Math.ciel and also .hover. Also, I looked at a list of colors in css so that I
could choose a good looking color for the new buttons.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
Randomizing the array was surprisingly difficult, because it was not actually randomizing when it seemed like it should be. I added console.log()
lines to check what was happening and realized that Math.random gives floating point numbers instead of integers, so I looked back at the
documentation for Math.random online and saw that it recommended using Math.floor or Math.ciel in order to get integers, so I added that and
changed it to work for my specific case. This was definitely the most challenging part, as the only other bugs I had were from forgetting to change
the guess values for the new buttons in the html file. I tried to debug it in javascript initially, but I eventually got the feeling that something was off with the html file rather than the javascript itself. Then I checked the html file, noticed the issue, and fixed it.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
I'm curious as to what the development of harder projects looks like. It was really interesting working in html, css, and javascript at the
same time and it was all surprisingly intuitive. I'm curious what other languages mix in, and how you can transmit data from your website to a database that you can then work on in another language entirely. I bet that it would be a really interesting problem to go further in depth in web development and get to collecting data and processing it efficiently.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
Firstly, I would find a way to add a tries left counter, and have it tick down when the user makes an error. I'm not entirely sure how to get the
javascript variable to display on the page and update in real time. Then, my next priority would be to add a field where the user could specify how
long they wanted to pattern to be, so that it wouldn't be 8 long every time. After that, I would try to go more in detail on the aesthetics of the page and make it all look better.



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/19eea54336b345ba83f93932625b16ef)


## License

    Copyright [Will Confoy]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
