# css-grid
/* CSS - Name: "positionstyles.css" */
/* Activity 1 styles */
.content1 {
  /* This is the parent of the activity 1 boxes. */
  display: grid;
  grid-template-columns: 1fr 1fr;
  justify-items: center;
  grid-gap: 20px;
}
.red1 { 
width: 100%; 
height: 100px; 
background-color: red;
grid-column: 1/3; 
} 
.green1 {
width: 100px; 
height: 100px; 
background-color: green; 
} 
.yellow1 {
width: 100px; 
height: 100px; 
background-color: gold; 
} 
.blue1 {
width: 100%; 
height: 100px; 
background-color: blue;
grid-column: 1/3; 
} 
/* Activity 2 styles */ 
.content2 {
  /* This is the parent of the activity 2 boxes. */
  display: grid;
  
  
}
.red2 {
width: 100px; 
height: 100px; 
background-color: red;
position: absolute;
top: 40;

} 
.green2 { 
width: 100px; 
height: 100px; 
background-color: green;
position: relative;
left: 50px;
top: 50px;
 
} 
.yellow2 {
width: 100px; 
height: 100px; 
background-color: gold;
position: relative;
left: 100px;
} 
.blue2 {
width: 100px; 
height: 100px; 
background-color: blue;
position: relative;
left: 150px;
top: -50px; 
} 
/* Activity 3 styles */ 
.content3 {
  /* This is the parent of the activity 3 boxes. */
  display: grid;
  grid-template-columns: 1fr 1fr;
  justify-items: center;
  

}
.red3 {
width: 100%; 
height: 100px; 
background-color: red;
grid-column: 1/3;
} 
.green3 {
width: 500px; 
height: 250px; 
background-color: green;
position: relative;
right: 16px;
} 
.yellow3 {
width: 500px; 
height: 250px; 
background-color: gold;
position: relative;
left: 16px; 
} 
.blue3 {
width: 100%;
height: 100px; 
background-color: blue;
grid-column: 1/3; 
} 
/* Activity 4 styles */ 
.content4 {
  /* This is the parent of the activity 4 boxes. */
  height: 400px;
  display: grid;
  grid-template-columns: 1fr 1fr;
  justify-items: center;
}
.red4 {
width: 560px; 
height: 230%; 
background-color: red;


} 
.green4 {
width: 500px; 
height: 150px; 
background-color: green;
position: relative;
right: 100px;
left: 0.1px;
} 
.yellow4 {
width: 500px; 
height: 150px; 
background-color: gold;
position: relative;
left: 530px;
right: 500px;
bottom: 50px;
} 
.blue4 {
width: 500px; 
height: 150px; 
background-color: blue;
position: relative;
top: 100px;
right: 50px;
left: 0.1px;
} 
/* Activity 5 styles */ 
.content5 {
  /* This is the parent of the activity 5 boxes. */
   height: 400px;
}
.red5 { 
width: 100%; 
height: 200px; 
background-color: red;
position: relative;
top: 50px; 
} 
.green5 { 
width: 200px; 
height: 200px; 
background-color: green;
position: relative;
top: 50px;
z-index: 2; 

} 
.yellow5 {
width: 100%; 
height: 300px; 
background-color: gold;
position: relative;
bottom: 150px;
left: -1px;
/* z-index: 2;  */

} 
.blue5 {
width: 100%; 
height: 200px; 
background-color: blue;
position: relative;
bottom: 200px; 
} 
/* Activity 6 styles */ 
.content6 {
  /* This is the parent of the activity 6 boxes. */
  height: 400px;
}
.red6 {
width: 300px; 
height: 200px; 
background-color: red;
position: relative;
top: 300px; 
} 
.green6 {
width: 190px; 
height: 190px; 
background-color: green;
position: relative;
top: 400px;
z-index: 2; 
} 
.yellow6 {
width: 200px; 
height: 300px; 
background-color: gold;
position: relative;
left: 300px;
z-index: 2;
/* top: 100px; */
bottom: -100px;
} 
.blue6 {
width: 300px; 
height: 300px; 
background-color: blue;
position: relative;
left: 100px;
bottom: 300px; 
} 


/* Do not make any changes below here */
.activity {
width: 70%; 
margin: 20px auto; 
font-family: Arial, sans-serif; 
border: 1px solid black; 
padding: 10px; 
clear:both; 
overflow: auto;
} 

.hint {
border: 1px solid grey;
background: #e0e0e0;
padding: .5em;
position: relative;
margin: 1em 0;
}
.hint h3 {
margin: 0;
}
.hint:hover {
background: #d0d0d0;
}
.hint > div {
display: none;
}

.hint input[type=checkbox] {
position: absolute;
width: 100%;
height: 100%;
opacity: 0;
z-index: 1;
cursor: pointer;
}

.hint input[type=checkbox]:checked ~ div {
display: block;
}

.hint i {
position: absolute;
transform: translate(-6px, 0);
margin-top: 16px;
right: 10px;
top: -3px;
}
.hint i:before, .hint i:after {
content: "";
position: absolute;
background-color: black;
width: 3px;
height: 9px;
}
.hint i:before {
transform: translate(2px, 0) rotate(45deg);
}
.hint i:after {
transform: translate(-2px, 0) rotate(-45deg);
}

.hint input[type=checkbox]:checked ~ i:before {
transform: translate(-2px, 0) rotate(45deg);
}
.hint input[type=checkbox]:checked ~ i:after {
transform: translate(2px, 0) rotate(-45deg);
}
.hint a {
position: relative;
z-index: 1;
}
# positioning.html
