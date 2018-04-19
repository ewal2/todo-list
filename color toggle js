1 Version

var button = document.querySelector("button");
var body = document.querySelector("body");

button.addEventListener("click", function(){
  body.classList.toggle("purple");
//document.body.classList.toggle("purple"); //also fine
});

.purple{
  background: purple;
}

2 Version


var button = document.querySelector("button");
var isPurple = false;


button.addEventListener("click", function(){
if(isPurple){
document.body.style.background = "white";
isPurple = false
} else{
document.body.style.background = "purple";
isPurple = true;
}
});

Version 3

var button = document.querySelector("button");
var isPurple = false;


button.addEventListener("click", function(){
if(isPurple){
document.body.style.background = "white";
} else{
document.body.style.background = "purple";
}
isPurple = !isPurple;
});
