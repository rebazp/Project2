# ROCK - PAPER - SCISSOR - LIZARD - SPOCK

This game is made for entertainmet purpose for those who want to play rock, paper, scissor, lizard, spock. Here you can play the game as much as you want by yourself against the computer. It's easy to use and is enjoyable for all ages.

You play against the computer which picks a random option everytime. The rusults are shown so it's to keep track of the score.

![Responsive Mockup](assets/images/2ndresponsive.jpg)

## Features

The game have three main objects. One area for the game where the player chose one option (rock, paper, scissor, lizard, spock). When the player have chosen one option the computer will immediately also chose one random option. Based on the rules. The game either ends in win, lose or draw.

The second object is to keep track of the results. The player, computer and draw scores are shown and updates after every turn.

The third object is the picture showing the rules of the game. It's easy to understand with suitable icons for all ages.

### Existing Features

- __Game Area__

  - This section will allow the user to play the game. The player will see the player and computer choice. When the player have chosen one option, the result will appear. There are buttons with five options which the player can chose from by clicking on them. The player can only chose one option at the time.

![Game](assets/images/2ndgame.jpg)

- __Score Section__

  - This section shows the current score of the game.

![Rules](assets/images/2ndscore.jpg)

- __Rule Section__

  - This section shows a simple to understand picture with the game rules.

![Rules](assets/images/2ndrules.jpg)

## Testing

I have played this game many times with multiple options to see if it works as intended. From my testing I haven't stumbled upon any problems with the game. The computer picks one random option everytime and follows the rules on who won, lost or draw.

The game works on different platforms and is adaptive and responsive.

## Bugs

I did not encounter any bugs. But I did have to try different options to make the game work with the addition of lizard and spock since the main game code was based on rock, paper and scissor.

### Unfixed Bugs

There is no unfixed bugs.

### Validator Testing

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgithub.com%2Frebazp%2FRock-Paper-Scissor-Lizard-Spock.git#textarea)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Frebazp.github.io%2FRock-Paper-Scissor-Lizard-Spock%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=sv)
- JavaScript
  - No errors were found when passing through the official [Jshint validator](https://jshint.com/)
    - The following metrics were returned:
    - There are 5 functions in this file.
    - Function with the largest signature takes 1 arguments, while the median is 0.
    - Largest function has 7 statements in it, while the median is 7.
    - The most complex function has a cyclomatic complexity value of 17 while the median is 4.
- Accessibility
  - I confirmed that colors and fonts chosen are easy to read and accessible by running it through lighthouse in devtools.

![Lighthouse](assets/images/2ndlighthouse.jpg)

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows:
  - In the GitHub repository, navigate to the Settings tab
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here - [GitHub link](https://rebazp.github.io/P2RPSLSGame/)

## Credits

The code that I've used in this project is my own and inspired from tutorials and Youtube channels:

- [JavaScriptInfo](https://javascript.info)
- [W3Schools](https://www.w3schools.com)
- [Bro Code](https://www.youtube.com/watch?v=n1_vHArDBRA&ab_channel=BroCode)
- [Coding with Jon](https://www.youtube.com/watch?v=Nb1YRElHVLc&t=3s&ab_channel=CodingwithJohn)

### Content

- The main game area and function is inspired from [Bro Code](https://www.youtube.com/watch?v=n1_vHArDBRA&ab_channel=BroCode), [JavaScriptInfo](https://javascript.info) and [W3Schools](https://www.w3schools.com)
- The winner area and code for lizard and spock is inspired from [Coding with Jon](https://www.youtube.com/watch?v=Nb1YRElHVLc&t=3s&ab_channel=CodingwithJohn),  [Bro Code](https://www.youtube.com/watch?v=n1_vHArDBRA&ab_channel=BroCode) and [W3Schools](https://www.w3schools.com)
- The score area is inspired from [W3Schools](https://www.w3schools.com) and [JavaScriptInfo](https://javascript.info)
- The style and coloring code is inspired from [Bro Code](https://www.youtube.com/watch?v=n1_vHArDBRA&ab_channel=BroCode) and [W3Schools](https://www.w3schools.com)
- Picture with instructions on how to play the game comes from [Momonhg](https://www.momonhg.com/blog/rock-paper-scissors-lizard-and-spock-game)

### Media

- The photos used in this game comes from a blog by [Momonhg](<https://www.momonhg.com/blog/rock-paper-scissors-lizard-and-spock-game>)

## Acknowledgement

- I would like to thank my mentor Rohit Sharma and the community at slack.