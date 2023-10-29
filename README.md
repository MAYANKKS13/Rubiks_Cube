# Rubik-s-Cube



The different methods by which we can solve a Rubik's Cube are:-
<UL><LI>Beginner Method.</LI>
<LI>CFOF Method</LI>
<LI>Roux Method</LI>
<LI>Z Method</LI>
<LI>Old Pochmann Method (For Blindfolded Solving)</LI></UL> <br><br>

<div id="topic" align="center">
  <H2>Beginner Method</h2><br>
</div> 
In this method, Cube is solved layer by layer. First layer is solved by solving the edges or making a cross and then placing the corners. Then the 4 edge cubie is placed at right place end up solving the 2nd layer. At last, last layer is solved by making the cross, permutating the corners and then orienting the corners and up solving the cube. <br><br>


#### Step 1:- The Cross     
  
<p>First step in solving the Rubik's Cube is to make cross on the first layer. It means that we have to place the 4 edges of the top layer correctly matching with the respective colours of the center pieces of the cube. This is how the cube should be after making cross.</p>

<div id="header" align="center">
  <img src="https://solvethecube.com/img/cubes/xwxwwwxwxxrxxrxxxxxbxxbxxxx.png" width="150" height="150"/>
</div><br>

<p>This step is completely intuitive. One can solve for each cubie logically.   
One thing you have to keep in mind only that if solving for an edge is disturbing the solved edges, then one should do some setup moves, then solve for the edge and then undo the setup move.<br>  As this step is completely intuitive, there are certain cases that occur for which you can do some moves to make the edges solve correctly.  These are at max two cases that may make beginner a little difficult.  Just do these moves to make the edges solve. </p>

<div id="table" align="center">

| Case                                                                                                                                                                    | Algorithm        |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------- |
| <img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/fbfed80c-dbb8-402d-90af-32721c1b3f5f" alt="Screenshot (10)" width="100" height="100">             | U' R' U F'   |
| <img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/2c8f6752-1668-49bb-bc68-0ef8e0fbe3d5" alt="Screenshot (10)" width="100" height="100">             | R' U' R U R'  |

</div><br>


#### Step 2:- The Corners

Now after making the cross, we have to place the four corners of the top layer to their respective correct positions. This part is quite easy. <br>  One has to just bring the desired corner on the bottom layer of its correct position and do the algorithms. <br> Here occurs only 3 cases. Solving these cases for every corner will eventually solve the four corners of the 1st layer.

<div id="table" align="center">

| Case                                                                                                                                                                    | Algorithm        |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------- |
| <img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/fcb430fe-7e22-4dc6-81c3-8fa9dfad40af" alt="Screenshot (10)" width="100" height="100">             | D' R' D R  |
| <img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/d3072c3e-66af-41ad-9f32-c2d26137827c" alt="Screenshot (10)" width="100" height="100">             | D F D' F' |
| <img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/5e11f141-a274-42d5-9b64-67ce2f8fbd1a" alt="Screenshot (10)" width="100" height="100">             | R' D R F D2 F' |

</div><br><br>

After solving the corners, our first layer is solved now and the cube will look like this.<br>
<div id="header" align="center">
  <img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/c1e18478-0e87-4ff5-88b7-8a13d056ab24" width="150" height="150"/>
</div><br><br>


#### Step 3:- Second Layer   

Now, after the first layer, we have to solve the second layer. This part is easy as we have to put only four edge pieces of the second layer to their correct posotion and the algorithm required to do this is quite similar for every edge.<br><br>
_[Note:- The first layer that we solved previously have to keep at the bottom (means the white face in our case) & the yellow center at the top]_<br><br>
Now for this, firstly we have to bring the edges of the second layer (means the edges that do not have the top face color i.e. yellow color in our case) to the top layer and have to perform these algorithms as shown in the diagram

<div id="table" align="center">

| Case                                                                                                                                                                    | Algorithm        |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------- |
| <img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/ef9ae0fe-3413-40eb-85e9-8c895c4a6b1e" alt="Screenshot (10)" width="100" height="100">             | U R U R' U' F' U' F |
| <img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/b4f70812-7121-422f-aa02-3973f6d38f33" alt="Screenshot (10)" width="100" height="100">             | U' L' U' L U F U F'|

</div><br>
We have to match the edge color to the center color as shown in the diagram and to perform the algos depending if the edge piece has to be placed on the right side (1st diagram) or left side (2nd diagram). In this way, the 2nd layer is solved. <br><br>
See, we are just replacing the incoorect piece with the correct edge piece. So there may occur situation if the the required piece is in the second layer itself but swapped in its position as shown in the diagram.<br>

<div id="header" align="center">
  <img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/37f98052-82c8-489a-a242-c2836a6c1c1c" width="120" height="120"/>
</div><br>

In this condition, simply execute any of the algos mentioned above depending whether the piece is on the right or left side. In this way, the correct piece will come to the top layer and now perform the required algorithm from the table.<br><br><br>

#### Step 4:- Last layer Cross

Now we have solved the two layers of the cube and its the time for the last layer.

















