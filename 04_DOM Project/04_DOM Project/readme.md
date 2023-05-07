# ***DOM Assignments 4*** :-

***Task 1*** : Match the output with the given output image with the help of DOM manipulation.

![output](./Output/DOM%20P1%20SS.png)

Ans. Code : 👇

```
// Target the first card's unit stats section for the barbarian
let first = document.querySelector(".clash-card__unit-stats.clash-card__unit-stats--barbarian.clearfix")

// Set the background color of the first card's unit stats section to orange and change the text color to white
first.style.backgroundColor = "#ff9666"
first.style.color = "white"

// Target the last one-third element of the first card's unit stats section for the barbarian and change its text color to white
let firstLastElement = document.querySelector(".clash-card__unit-stats.clash-card__unit-stats--barbarian.clearfix>.one-third.no-border")
firstLastElement.style.color = "white"

// Target the second card's level section for the archer
let Char2 = document.querySelector(".clash-card__level.clash-card__level--archer + div")

// Change the inner text of the second card's level section to "The Archer"
Char2.innerText = "The Archer"

// Target the second card's unit stats section for the archer
let second = document.querySelector(".clash-card__unit-stats.clash-card__unit-stats--archer.clearfix")

// Set the background color of the second card's unit stats section to a lighter shade of red and change the text color to white
second.style.backgroundColor = "#FF6666"
second.style.color = "white"

// Target the last one-third element of the second card's unit stats section for the archer and change its text color to white
let secondLastElement = document.querySelector(".clash-card__unit-stats.clash-card__unit-stats--archer.clearfix>.one-third.no-border")
secondLastElement.style.color = "white"

// Target the third card's unit stats section for the giant
let third=document.querySelector(".clash-card__unit-stats.clash-card__unit-stats--giant.clearfix")

// Set the background color of the third card's unit stats section to a darker shade of orange and change the text color to white
third.style.backgroundColor = "#E07C24"
third.style.color = "white"

// Target the last element of the third card's unit stats section and change the text color to white
let thirdLastElement=document.querySelector(".clash-card__unit-stats.clash-card__unit-stats--giant.clearfix>.one-third.no-border")
thirdLastElement.style.color = "white"

// Target the fourth card's level section for the goblin
let Char4 = document.querySelector(".clash-card__level.clash-card__level--goblin + div")

// Change the inner text of the fourth card's level section to "The Goblin"
Char4.innerText = "The Goblin"

// Target the fourth card's unit stats section for the goblin
let fourth=document.querySelector(".clash-card__unit-stats.clash-card__unit-stats--goblin.clearfix")

// Set the background color of the fourth card's unit stats section to green and change the text color to white
fourth.style.backgroundColor = "green"
fourth.style.color = "white"

// Target the last element of the fourth card's unit stats section and change the text color to white
let fourthLastElement=document.querySelector(".clash-card__unit-stats.clash-card__unit-stats--goblin.clearfix>.one-third.no-border")
fourthLastElement.style.color = "white"

// Target the fifth card's unit stats section for the wizard
let fifth=document.querySelector(".clash-card__unit-stats.clash-card__unit-stats--wizard.clearfix")

// Set the background color of the fifth card's unit stats section to a light shade of blue and change the text color to white
fifth.style.backgroundColor = "#6EACD9"
fifth.style.color = "white"

// Target the last element of the fifth card's unit stats section and change the text color to white
let fifthLastElement=document.querySelector(".clash-card__unit-stats.clash-card__unit-stats--wizard.clearfix>.one-third.no-border")
fifthLastElement.style.color = "white"


```

___
___
