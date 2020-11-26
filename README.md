var playing = false;
var score;

//if click on the start/reset
document.getElementById("startreset").onclick = function(){
    if(playing == true){
        location.reload(); //this is to reload page
       }else{//if not playing
           
        //change mode to playing
        playing = true;
           
        //set score to 0   
        score = 0;
        
        //to set the scorevalue inside the score counter to be equal to var score   
        document.getElementById("scorevalue").innerHTML = score;
           
        //show countdown time, the div for the timer was initially set to display:none, so by doing block here, it's like unblocking the display:none function.   
        document.getElementById("timeremaining").style.display = "block"; 
           
        //to change the words Start Game to Reset Game once it's clicked
        document.getElementById("startreset").innerHTML = "Reset Game";   
       }
} 



    //if playing
        //reload page
        //change button to reset button
    
        
        
        //reduce time by 1 sec in loops
            //is there time left?
                //yes-->continue
                //no-->gameover, show gameover div
        //change button to reset game
        //generate a new Q&A


//if we click on answer box
    //if we are playing
        //correct answer?
            //increase score by 1
            //generate new Q&A
            //show correct box for 1 sec
        //wrong answer?
            //show TRY AGAIN box for 1 sec



