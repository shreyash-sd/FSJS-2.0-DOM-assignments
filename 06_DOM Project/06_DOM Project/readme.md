# ***DOM Assignments 6*** :-

***Task 1*** : Change the logo with logo of iNeuron logo.

![output](./Output/DOM%20P3%20SS-1.png)

Ans. Code : 👇

```
const logo = document.querySelector(".logo");
logo.setAttribute("src","./assets/ineuron-logo.png");
```
___
___
***Task 2*** : Change the price value and add a linkedin icon in footer section.

![output](./Output/DOM%20P3%20SS-2.png)

Ans. Code : 👇

```
<!-- // Select the "span" element within an element with class "app_price" and update its text content to "$10" -->

let priceSpan=document.querySelector(".app_price span")
priceSpan.innerText="$10"

<!-- // Create an "i" element with classes "fa-brands" and "fa-linkedin" -->
let i=document.createElement("i")
i.setAttribute("class","fa-brands fa-linkedin")

<!-- // Create a "div" element with class "footer_social_ico" and append the "i" element to it -->
let linkedin=document.createElement("div")
linkedin.setAttribute("class","footer_social_ico")
linkedin.appendChild(i)

<!-- // Select the element with class "footer_social" and append the "linkedin" element to it -->
let footerSocials=document.querySelector(".footer_social")
footerSocials.appendChild(linkedin)
```
---
---
