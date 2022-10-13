# Soso Beriashvili
## Contact info
- sosiberiashvili@gmail.com
## About me

I am highly motivated to learn Web-development, specifically Front-End for now. I love designing websites and the way they are built. I surely get a lot of fun out of 
it. It is one of my goals to become a full-stack developer in the future and I'll try to do everything I can to achieve it to the best of my abilities! The internet is 
by far the best place to learn from, and I'm incredibly lucky to have such an opportunity. I currently study the bachelors degree of Physics.

## Skills
- HTML
- CSS
- JavaScript
- Git (basics)
- React (basics)

## Coding example

I coded this project along the course on Udemy. It was quite a good experience and learned some useful techniques. The project is the dicee game. It also contains HTML and CSS files, but for this CV I will provide the code from the JS file.

```
let diceNumber1 = Math.floor(Math.random() * 6) + 1;
let randomDice1 = 'images/dice' + diceNumber1 + '.png';

document.querySelectorAll('img')[0].setAttribute('src', randomDice1);

let diceNumber2 = Math.floor(Math.random() * 6) + 1;
let randomDice2 = 'images/dice' + diceNumber2 + '.png';

document.querySelectorAll('img')[1].setAttribute('src', randomDice2);

let headingContent = document.querySelector('h1');

if(diceNumber1 > diceNumber2){
  headingContent.innerHTML = 'Player 1 Won!';
} else if(diceNumber2 > diceNumber1) {
  headingContent.innerHTML = "Player 2 Won!";
} else {
  headingContent.innerHTML = 'Draw!';
}
```

## Experience

I have a very little of experience as a Junior Frontend developer as I started pursuing this career just recently. Nevertheless, I do buy courses on Udemy, watch a lot of Youtube and do some challenges on websites such as Leetcode and Codewars.
