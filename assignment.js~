let n = prompt("head or reverse?");
document.getElementById('imgbutton').onclick = click;
document.getElementById("uc").innerHTML = n;

let countwin = "";
let heads = 0;
let tails = 0;
function click() {  
    if(Math.floor(Math.random() * 2) == 0)
    {
    	flip("heads");
    	document.getElementById("img1").setAttribute("src", "head.jpg");	
      document.getElementById("head").innerHTML = ++heads;
     
     if (n=="head") 
     {
     	alert("You win");
     	countwin++;
     	document.getElementById("win").innerHTML = countwin;
     }
     else
     {
     }
      
    }
    
    else{
        flip("tails");
        document.getElementById("img1").setAttribute("src", "reverse.jpg");
      
       document.getElementById("reverse").innerHTML = ++tails;
         if (n=="reverse") 
     {
     	alert("You win");
     	countwin++;
     	document.getElementById("win").innerHTML = countwin;
     }
     
     else
     {
     }
           
    }    
}
function flip(coin) 
{

}