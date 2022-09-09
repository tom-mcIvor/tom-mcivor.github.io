[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

# My learning progress

## tom-mcivor.github.io 

## HTML


### This is the building blocks of my website i find this to be easy enough its just going div.container or span.cotainer or sometimes theres a form which my have inputs  





## CSS


#### This is also not too bad at least to get something to happen. To get exactly what you want is hard however. 

### The problem for me when it comes to CSS is how hard it can be to get something simple eg: A simple centered line of text or an image inside a div container. This surely is the blocks anyone needs to make a website.... in order to make just this simple text/image centered inside the box you need to run this rather tendious and long winded CSS code;

      #selector { 
      display: flex;
      justify-content: center;
      align-items: center;
  }

### I guess this is where a Framework like bulma or bootstrap can come in and help. But how many people use these and will these framworks be free and translatable/transposable for my future projects?

# And now comes Jarvascript the hardest out of the 3 front end programmes

### Ive tried to learn jarvascript in about 15 different mini projects and even tho ive done some coding in a statistics programme called R I dont get jarva script
 ### sure i understand when a var is and what const is and let ( bla bla bla )
 ### but i still dont get it

 ### the reason for this I think.. is beacuse theres just so many diffent aspects to jarvascript and i cant get my code 90 percent right like html and CSS i need to get the code 100% right 


 ## functions within fuctions 


 ### why is every little bit of code in jarvascript written with complex stuff like functions why not just run some lines like eg:

      a = "hello world"
      print(a)
      a * 50 = c
      print(c)

### this i understand 

### but noo 

### I need to somehow understand what the hecks going on in these "simple" functions eg;
      btnEl.addEventListener("click", () => {
      trailerContainerEl.classList.remove("active");
      });

      closeIconEl.addEventListener("click", () => {
      trailerContainerEl.classList.add("active");
      videoEl.pause();
      videoEl.currentTime = 0;
      });



### or 


      function addNewImages() {
      for (let index = 0; index < imageNum; index++) {
      const newImgEl = document.createElement('img')
      newImgEl.src = `https://picsum.photos/300?random=${Math.floor(
      Math.random() * 2000
      )}`

     imageConatinerEl.appendChild(newImgEl)
     }
    }




## plus for loops 

### for-loops to me are hard work and need to be avoided at pretty much all costs, however for an average comsci person they are just beginner stuff


### how are you meant to remember this let alone whats actualy happening 

    generateColors();

    function generateColors() {
    colorContainerEls.forEach((colorContainerEl) => {
    const newColorCode = randomColor();
    colorContainerEl.style.backgroundColor = "#" + newColorCode;
    colorContainerEl.innerText = "#" + newColorCode;
    });
    }

### also there needs to be these long annoying const parts to the start of the functions 

  
[dill]: <https://github.com/joemccann/dillinger>




theme: Slate