# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Mary Wang

Time spent: 2 hours spent in total

Link to project: (https://glitch.com/edit/#!/clumsy-ludicrous-shovel)

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
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![http://g.recordit.co/23iFDxTxJJ.gif]


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
The article/resource on math.random was used to create the inclusive randomizing feature.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

A safari grammarly extensions was blocking some of my functions and sounds from occurring. I did not realize that this was a browser
issue and was stuck on this problem for a while. Thinking it was my code, I reread the instructions many times. Upon finally realizing the
debugging function, I used inspect element to find that it was a grammarly extension on my safari app that was causing the issue. By switching 
to chrome, I fixed the issue and was able to continue. 

Other than this, the biggest challenge would just be that this was my first introduction to html, javascript, and css. There was a learning curve,
and I had to get used to different syntax. Reading the provided instructions carefully was very helpful as I was able to learn as I completed
the tasks. There was also an issue with my math randomizer function. I didn't realize that I was getting 0 as a random number which didn't correspond to
any of my buttons. Therefore, I had to read through my other files, in this case html, to realize that I needed a randomizer function that would not pick 0.
Upon reading the provided resource more carefully, I noticed a new math.random function that would allow me to set my upper and lower bounds
of the numbers that I wanted randomized. By implementing this new inclusive getRandom function, I could specify exactly which numbers I wanted to be
possibly returned. 


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
Some questions that I have about web development are directed towards UI/UX. How do you ensure that your design is aesthetically pleasing?
As someone with no design experience, many parts of web design are difficult for me. Additionally, how do you make sure that your website is 
intuitive for the user? As the creator, the use and functionalities of what you yourself built would come naturally. However, this may not be the
same for a random user. What are some of the ways that a web developer needs to think in order to have a good birds eye view of the project and ensure 
ease of use?

Finally, now that I have a small understanding of how to design and create functionalities of a website, how would I actually put this onto the web 
and make it accessible to the public? At the moment, it is a project within glitch.com, but if I wanted to share this game to the internet for my friends
to play, how would I do so?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I would like to create a lot more buttons, maybe a total of 30-40 buttons. I feel that this would make it more challenging and require the user to play close
attention. Additionally, I think that it would be cool if the frequency of every pattern would end up playing a tune. It could be a basic tune like twinkle twinkle 
little star. This way, it could also help the user guess the next color even if they missed the hint. By knowing the tune, you could guess which button/note comes next. 

Another cool feature that I would include would be a multiplayer function. You could maybe play with a friend and see who could complete the game the quickest and 
most accurately. I would have to learn much more in order to allow for two players at once and for two different games to be happening at once, but I believe that a 
versus or multiplayer function would allow the game to be more interactive. 

A final feature that I would like to implement would be a game mode where the pattern keeps going until you mess up. This mode could be an ultimate test of memory
and you could try to see how long you could go for before messing up. I would also try to add a high score function to keep track of the player's record. 


## License

    Copyright Mary Wang

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.