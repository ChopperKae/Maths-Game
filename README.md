html{
    height: 100%;
    background: radial-gradient(circle, #FFFFFF, #DDDDDD);
}

#container{
    height: 400px;
    width: 600px;
    background-color: #98CEEB;
    margin: 100px auto;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0px 4px 0px 0px #0290DC;
    -webkit-box-shadow: 0px 4px 0px 0px #0290DC;
    -moz-box-shadow: 0px 4px 0px 0px #0290DC;
    position: relative;
}
    
#score{
    color: #999D60;
    background-color: #F2F78E;
    left: 530px;
    box-shadow: 0px 3px 0px 0px #9DA24D;
    -webkit-box-shadow: 0px 3px 0px 0px #9DA24D;
    -moz-box-shadow: 0px 3px 0px 0px #9DA24D;
    padding: 11px;
    position: absolute;
    }  

#correct{
    color: white;
    background-color: #37CA4D;
    padding: 11px;
    left: 260px;
    position: absolute;
    display: none;
    
    
}

#tryAgain{
    color: white;
    background-color: #ED4D17;
    padding: 11px;
    left: 260px;
    position: absolute;
    display: none;
}

#question{
    height: 130px;
    width: 450px;
    color: black;
    background-color: #9BA4ED;
    box-shadow: 0px 3px #5060A3;
    -webkit-box-shadow: 0px 3px #5060A3;
    -moz-box-shadow: 0px 3px #5060A3;    
    margin: 50px auto 10px auto;
    font-size: 100px;
    text-align: center;
    line-height: 100px;
    font-family: cursive, sans-serif;
    }    

#instruction{
    height: 45px;
    width: 450px;
    color: black;
    background-color: #B68BDB;
    box-shadow: 0px 3px #875BAC;
    -webkit-box-shadow: 0px 3px #875BAC;
    -moz-box-shadow: 0px 3px #875BAC;
    margin: 10px auto;
    font-size: 15px;
    text-align: center;
    line-height: 45px;
}

#choices{
    height: 90px;
    width: 450px;
    margin: 10px auto;
}

.box{
    height: 80px;
    width: 80px;
    float: left;
    background-color: white;
    margin-right: 43px;
    border-radius: 3px;
    box-shadow: 0px 3px #8CA9BA;
    -webkit-box-shadow: 0px 3px #8CA9BA;
    -moz-box-shadow: 0px 3px #8CA9BA;
    cursor: pointer;
    color: darkgray;
    text-align: center;
    line-height: 75px;
    position: relative;
    transition: all 0.2s;
    -webkit-transition: all 0.2s;
    -moz-transition: all 0.2s;
    -o-transition: all 0.2s;
    -ms-transition: all 0.2s;
}

.box:hover, #startreset:hover{
    background-color: #A096FA;
    box-shadow: 0px 3px #6B60D6;
    -webkit-box-shadow: 0px 3px #6B60D6;
    -moz-box-shadow: 0px 3px #6B60D6;
    color: white;
}

.box:active, #startreset:active{
    top: 3px;
    box-shadow: 0px 0px #6B60D6;
    -webkit-box-shadow: 0px 0px #6B60D6;
    -moz-box-shadow: 0px 0px #6B60D6;
    
}
#box4{
    margin-right: 0;
    
}

#startreset{
    height: 40px;
    width: 100px;
    background-color: #CDE7F5;
    margin: 0px auto;
    border-radius: 3px;
    box-shadow: 0px 3px #76A4BE;
    -webkit-box-shadow: 0px 3px #76A4BE;
    -moz-box-shadow: 0px 3px #76A4BE;
    cursor: pointer;
    color: black;
    text-align: center;
    line-height: 40px;
    position: relative;
    transition: all 0.2s;
    -webkit-transition: all 0.2s;
    -moz-transition: all 0.2s;
    -o-transition: all 0.2s;
    -ms-transition: all 0.2s;
}

#timeremaining{
    height: 20px;
    width: 160px;
    padding: 10px;
    background-color: #ACD749;
    box-shadow: 0px 3px #79A4C1;
    -webkit-box-shadow: 0px 3px #79A4C1;
    -moz-box-shadow: 0px 3px #79A4C1;
    border-radius: 3px;
    position: absolute;
    top: 365px;
    left: 430px;
    display: none;
/*    visibility: hidden;*/    
}

#gameover{
    height: 200px;
    width: 480px;
    background: linear-gradient(#F9C966, #FE7C6A);
    position: absolute;
    color: white;
    font-size: 40px;
    text-align: center;
    text-transform: uppercase;
    top: 80px;
    left: 80px;
    z-index: 2;
    display: none;
    
    
    
}



/*
<!-- The box-shadow property allows us to add a shadow to the sides of an element.
The syntax is box-shadow: [horizontal offset] [vertical offset] [blur radius] [optional spread radius] [color].
A positive number will be for the right and bottom part of the element. A negative value will be used to put the shadow on the left and top part of the element. The blur radius is kept at 0 if you want the shadow to be sharp. If you increase that it will become more and more blur. The spread radius which is optional controls the size of the shadow.

We need to set the position as relative for the HTML div and position as absolute for the other divs so that they will follow the position relative to the HTML div. 

There's a cursor property that when user hovers above the element, it can become a pointer instead of an arrow.

The difference between the display and visibility properties is that
when we use the visibility property and set it to hidden, it's actually still on the page and will still interact with the other elements.
whereas display:none is going to hide the element and will not interact with the other elements.

We give the gameover div a  z-index: 2; so that it will appear on top of the other elements since the default z-index for the other elements is 0.





*/
