# Anime-Clicker-1.0.2
Fully functional anime clicker! 
Save and load the game if you need to go to sleep for the day, you can come back and your progress will not be erased! 
Want more characters? Think the clicker is too easy? 
Open source code with comments for you to dive into. Very simple to add new characters and new anime seasons! 
Any questions just msg me, made with love from Minenik :3


A small exploit:

setInterval(function() { var classes = document.getElementsByClassName('heroButton');
var i=classes.length-1;
while (i>classes.length/2) { 
var Rate = classes[i];
Rate.click(); 
i-=1;
}
},2500);
