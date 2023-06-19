.container{
    max-width: 1200px;
    border: 10px solid black;
    
}


.container:hover .box{
    animation-play-state: paused;
}
.box{
    width: 200px;
    height: 200px;
    background-color: cornflowerblue;
    margin-top: 200px;
    animation-name: myanimation;
     position: relative;
     animation-name: myanimation;
     animation-duration: 2s;
     animation-timing-function: ease-in-out;
     animation-iteration-count: infinite;
     animation-direction: alternate;

}


@keyframes myanimation {
0%{
    background-color: blueviolet;
    left: 0px;
    border-radius: 50%;
}
25%{
    background-color: red;
    left: 200px;
   border-radius: 50%;
}
50%{
    background-color: brown;
    left: 400px;
   border-radius: 50%;
}
75%{
    background-color: rgb(129, 11, 11);
 border-radius: 50%;
    left: 600px;
}

100%{
    background-color: aqua;
    left: 900px;
    border-radius: 50%;
}

}
