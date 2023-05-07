# ***DOM Assignments 5*** :-

***Task*** : Match the output with the given output image with the help of DOM manipulation.

![output](./Output/DOMP2SS.png) 

Ans. Code : 👇

```
//added proSubscription
let proSubscription=document.createElement("a")
proSubscription.className="btn"
proSubscription.innerText="Pro Subscription"

const buttonsDiv=document.querySelector(".nav-links+div")
buttonsDiv.appendChild(proSubscription)

//added chinese
let chinese=document.createElement("a");
chinese.innerText="Chinese(7)"
let receipiesList=document.querySelector(".tags-container div")
receipiesList.appendChild(chinese)


// add 6th card
let img=document.createElement("img")
img.className="recipe-img"
img.src="./img/recipe-4.jpeg"
let h5=document.createElement("h5")
h5.class="recipe-name"
h5.innerText="Maggi"
let p=document.createElement("p")
p.className="recipe-disp"
p.innerText="snax"
let link=document.createElement("a")
link.className="recipe-text"
link.appendChild(img)
link.appendChild(h5)
link.appendChild(p)
let div=document.createElement("div")
div.className="card"
div.appendChild(link)
let recipeGallery=document.querySelector(".recipe-gallery")
recipeGallery.appendChild(div)



//added Name
let a=document.querySelector(".page-footer p a")
a.innerText="Shreyash Dawake"


```
___
___
