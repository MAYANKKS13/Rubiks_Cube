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
We have to match the edge color to the center color as shown in the diagram and to perform the algos depending if the edge piece has to be placed on the right side (1st diagram) or left side (2nd diagram). In this way, the 2nd layer is solved. <br>
See, we are just replacing the incoorect piece with the correct edge piece. So there may occur situation if the the required piece is in the second layer itself but swapped in its position as shown in the diagram.<br>

<div id="header" align="center">
  <img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/37f98052-82c8-489a-a242-c2836a6c1c1c" width="120" height="120"/>
</div><br>

In this condition, simply execute any of the algos mentioned above depending whether the piece is on the right or left side. In this way, the correct piece will come to the top layer and now perform the required algorithm from the table.<br><br><br>

#### Step 4:- Last layer Cross

Now we have solved the two layers of the cube and its the time for the last layer. Now from here, things are little complicated as now we have to do moves which are not going to affect the previously solved two layers.<br>
First step towards solving the last layer is making the cross on it like this.

<div id="header" align="center">
  <img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/3132124c-61de-430b-9566-4f3fb428742a" width="120" height="120"/>
</div><br>

For this, firstly we are going to get atmost four cases as shown in the figure <br>

<div id="header" align="center">
<img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/22f7f795-fce2-424d-8b37-1a087926606f" width="120" height="120"/>(a)
<img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/490b6a4f-9f4f-4173-9d52-2094a7d0ed1d" width="120" height="120"/>(b)
<img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/ded6ad3b-a81e-45e0-ada0-62584fa034fa" width="120" height="120"/>(c)
<img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/634a5bf5-1f44-456c-bee7-8daa80adb14d" width="120" height="120"/>(d)
</div><br>
And there is only one algorithm<br><br>
<div id="algo" align="center">
<b>F R U R' U' F'</b>
</div><br><br>

Now out of the above four figure, if you have got (d) then it is okay as we have got an inbuilt cross already. Now for the remaining three cases, our main aim is to get the fourth case. The main advantage is that when you apply the above algorithm, it is going to give you the other cases. When applied to (a), it will give you (b). When applied to (b), it will give you (c) or even (d) & when applied to (c) it will give you (d).<br><br>
Now, there are certain ways how you should apply that algo to the cases.<br>
***For (a)***:- Apply the algo anyway you want.<br>
***For (b)***:- Firstly keep the backward L towards yourself to the right side and then apply the algo<br>
***For (c)***:- Keep the line in the horizontal position and then apply the algo.<br><br>
This part is only the matter of identification of the cases. Means you may get some variations of the four cases mentioned above as shown in the figure

<div id="header" align="center">
<img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/45207568-3dd8-4c71-aabf-22fbdf609d41" width="120" height="120"/>
<img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/e399aa2b-2963-4510-b5cb-dfd7eed349b3" width="120" height="120"/>
<img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/8bedf165-7c31-40c8-9105-b7ab8f934019" width="120" height="120"/>
<img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/0f53dab6-900a-48f3-9436-5bd40244a5d4" width="120" height="120"/>
<img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/cfdce003-cebc-4911-bf1c-d63503152a1f" width="120" height="120"/>
</div><br><br>

You have to only identify the cases among the (a), (b), (c) or (d) and do as per the above guidance. In this way you have solved the cross on the lasst layer. Now, the next step is to match the last layer edges.<br><br><br>

#### Step 5:- Last layer Edges

This part of the solving process is quite very easy. Just like the first layer, similarly we have to do the edge matching but keeping in mind that the moves are not going to alter the previously done steps till now. <br><br>
For the last layer edges match, you are going to get atleast two edges match with the center colour already or all the four edges (solved case). Firstly, turn the top face untill two of the edge piece match with the center colour. Now, here two cases only occur as shown in the figure. <br>

<div id="header" align="center">
<img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/cd0842a8-a203-4c64-8747-4b467877872f" width="120" height="120"/>(a)
<img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/1a5ba84d-1091-43e2-91c6-f03a3aaecd9f" width="120" height="120"/>(b)
</div><br>

Case (a) where unmatched edges are adjacent to each other and Case (b) where the unmatched edges are opposite to each other. <br><br>
And just like the last layer cross, here is also only one algorithm<br>
<div id="algo" align="center">
<b>R U2 R' U' R U' R'</b>
</div><br><br>

Now, you should apply the algorithm in the following ways:- <br>
***For (a)***:- Keep the unmatched edges on your right and front side and apply the algorithm. <br>
***For (b)***:- Keep the unmatched edges on your right and left side and apply the algorithm, which will give you the Case (a) and then do the algo as said above. <br><br>
In this way, you have solved the last layer edges also and the cube will look like this now, left with only the remaining 8 corners of the cube. <br>
<div id="header" align="center">
  <img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/0afccf3e-15ec-4a17-b057-cf5768d0531e" width="150" height="150"/>
</div><br><br>

#### Step 6:- Last Layer Corners

This part of the process is divided into two steps:-<br>
***Step 1***:- Placing the corners in the right places matching with the center colours.<br>
***Step 2***:- Permute the corners in their respective places to get the cube solved.<br><br><br>
**Step 1**:-<br>
After solving the last layer edges, we are going to get atleast one corner cubie its right place (need not to be in the correct orientation, only at the right place). We have to bring that corner to the bottom right of the top layer as shown in the figure by rotating the cube and then perform the given algorithm <br>

<div id="header" align="center">
<img src="https://github.com/MAYANKKS13/Rubik-s-Cube/assets/89644981/d44e1856-7156-49c3-9dff-e298d1600b96" width="120" height="120"/>
</div><br>
<div id="algo" align="center">
<b>L' U R U' L U R' U'</b>
</div><br>
This will change the positions of the other three corner cubies. Check if they have been placed in their correct position. If not, then perform the algorithm again untill its done. <br>
In this way, all the corners will be placed in their right positions.<br><br>































