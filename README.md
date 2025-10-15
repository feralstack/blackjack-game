# blackjack-game

Scrimba code along learning project to create a simple blackjack game. I worked through multiple lessons and did all the scrims. Lots of new JavaScript concepts were introduced

## 🔧 Built With

- HTML5
- CSS3
- JavaScript

## 🚀 Live Demo

https://willowy-travesseiro-add552.netlify.app

## 🧠 What I Learned

- Arrays - how to create them, add to them, remove the last piece of data, that they can store multiple types of data, they are zero indexed, how to access data in the array according to it's index number `[n]`
- Objects - how to create them, that they can store multiple types of data, how to access specific items of data with the `object.data` notation
- Booleans - true or false
- `if else` statements - determine what will be returned according to the selected criteria
- Comparison operators - equal to `===`, greater than `>`, less thank `>`
- Logical operators - AND `&&`, OR `||` - `&&` used so that a new card can only be drawn whilst the player is still in the game (ie. not bust or holding blackjack)
- `for` loops - used to create incremental iteration (in this case for outputting the card numbers from the array)
- The `Math` object - used for generating random numbers `Math.random()` , knowing to multiply by the whole number to get ranges above 1, and rounding down to nearest integer `Math.floor()` (have to add +1 as `.floor` will always round down, and `.random` number will always be less than whole number eg. 6 will be 5.99, which flow will round down to 5)
- `return` statements - specifies value to be returned by a function

## 📦 Next Steps

- [x] Deploy to Netlify
- [ ] Allow player to enter their own name
- [ ] Allow player to place bet for each game and deduct amount from balance
- [ ] Add player winnings to player balance

---

## About Scrimba

At Scrimba our goal is to create the best possible coding school at the cost of a gym membership! 💜
If we succeed with this, it will give anyone who wants to become a software developer a realistic shot at succeeding, regardless of where they live and the size of their wallets 🎉
The Fullstack Developer Path aims to teach you everything you need to become a Junior Developer, or you could take a deep-dive with one of our advanced courses 🚀

- [Our courses](https://scrimba.com/courses)
- [The Frontend Career Path](https://scrimba.com/fullstack-path-c0fullstack)
- [Become a Scrimba Pro member](https://scrimba.com/pricing)

Happy Coding!
