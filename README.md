# Cube-Project
﻿<!DOCTYPE html>


<html>


<header>
    <title>Solving the Rubiks Cube</title>
</header>
<style>


p {font-family: Times New Roman, Times, serif;}
body {background-image: url('https://images.pond5.com/spining-rubiks-cubes-background-footage-031207221_iconl.jpeg');
        background-repeat: no-repeat;
        background-attachment: fixed;
        background-size: 100% 100%;}
h1   {color: white;
        font-size:50px;}
h2   {color: white;
        font-size: 35px;}
p    {color: white;
        font-size: 30px;
        margin: 30px;
        background: green;
        border: 1px solid black;}
</style>
</head>


<p>&nbsp;</p>
<div>&nbsp;</div>
<div style="background-colour: black; padding: 20px;">
<h1>Solving the Rubik's Cube</h1>
<h2>The Meaning of the Algorithms</h2>
<p>anything with an apostrophe means counter-clockwise</p>
<p>F=Front U=top L=left R=Right B=back D=Bottom</p>
<h2>The Bottom Layer</h2>
<p>To solve the rubik's cube we will have the white on the bottom. First you want to get find the White middle piece. Next you want to line up all of the white center to the side pices. If done correctly it should resemble a cross. the connected sides of the whites should be the same color as the center peice below it. Next we will get the corners aligned like the centers there is a pattern to this. First get a corner piece above the sides to which they will connect. Then use the following pattern : U-R-'U-'R (Repeat the process until corners match with respective side)</p>
</div>
<div style="background-colour: black; padding: 20px;">
<h2>The Middle Layer</h2>
<p>This is where it gets difficult. We are going to first align the pieces of the middle layer. You want to have the corresponding color in a straight line. The top color should be the side you want to move. The following algorithims will tell you what to do: Left: 'U-'L-U-L-U-F-'U-'F Right: U-R-U-'R-'U-'F-U</p>
</div>
<div style="background-colour: black; padding: 20px;">
<h2>The Top Layer</h2>
<p>This is the last Three main steps that I will teach you. first you want to get the yellow to where it has a cross. My way of doing this is to just use F-R-U-R'-U'-F' until you get it. if this does not work just try a different side.When you have this, use this algorithm at a corner without a yellow facing upR-U-R'-U-R-U-U-R'. When you get the fish with a yellow facing you do this pattern on that yellow. when you get the top of yellow done you will notice a pattern with the top. the pattern will have a color on each side and another color in the middle, if not use this algorithm R'-F-R'-B-B-R-F-B-B-R'-R' then you just need the middle top peice. do this algorithm until you get it.this algorithm changes depending on the color that appears at the bottom and the top if the white matches the different color at the bottom middle F-F-U-R'-L-F-F-R-L'-U-F-F/F-F-U'R'-L-F-F-R-L'-U'-F-F</p>
</div>


</body>


    
</html>
