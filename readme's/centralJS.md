# Central JS Docs
To install Central JS go to releases in the right hand side and click Central JS. You can then download the uncompressed version (.js) or the compressed version (.min.js). 
You can also download from our website [CentralJS](central-web-kit.rf.gd). After you have the file go to the head part of your html doc and place it somewhere in it.

<br><br>
There are currently 4 functions in Central JS:
  >1. dom()<br>
  >2. event()<br><br>
  >3. rand()<br>
  >4. choice()<br>

## Document Functions:
The first 2 functions have a similar syntax (The rules of the function):<br>
```dom/event("selector").task(value/function)```<br><br>
The dom Element will edit Page content with the following tasks:

  >edit (Will take selector and edit similar to .innerHTML) EX:dom("h1").edit("Hello world");<br><br>
  >css (Will add css to selector) EX:dom("div").css({'background-color':'black', 'width':'100px'});<br><br>
  >hide/show (Self explanitory will hide/show selector ! Warning if selector is using any sort of display it will be wiped !) EX:dom("h1").hide(); <br><br>
  >toggle (Toggles between Hide and show) EX: dom("h1").toggle();<br><br>
  >fadeIn/fadeOut (Like hide and show but now fades out there NEEDS to be a value inside of the parentesis it will be counted in ms) EX: dom("h1").fadeIn(100);

## Event Functions:
There are 4 event functions in Central JS:
>click (Onclick event) EX: event("div").click(function);<br><br>
>hover (Hover Event) EX: event("div").hover(function);<br><br>
>mouseMove (When the mouse moves) EX: event("document").mouseMove(function);<br><br>
>load (When an element loads on the page) EX: event("document").load(function);<br><br>

# Value Return Functions:
There are 2 value returning functions in CentralJS:
>rand() (Returns a random value between 2 numbers) EX: rand(0,10) >>> Returns random from 0-10<br><br>
>choice() (Returns a random value from a dataset) EX: choice("abc") >>> Returns random value a-b-c<br><br>
