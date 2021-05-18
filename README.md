# AlgorithmHandTracingPractice

## Apr 25, 2021     
[Reference solutions🔗](https://github.com/mialsy/AlgorithmHandTracingPractice/blob/master/sol/hand_trace_practice_01.pdf) Please let me know if you find any mistake.

#### 2-3 tree:
|insert this: |                	then remove|
|---|---|
|conquer      		|	c, n, r|
|sparkling|                      k, l, g|
|tedious|				e, i|

#### Heap:
insert & build from bottom up, then remove min 3 times	
- 21， 13， 26， 29， 6， 0， 16
- 4， 12， 17， 1， 16， 11， 20
- 20， 2， 15， 8， 4， 9， 8

#### Compact prefix tree:
insert this:

- chalk, bedroom, cherries, unit, unused, chance
- standing, connection, shirt, striped, shed, cream, corn

#### Construct tree from both preorder and post order: (just do one) 
- favour
- sample
- reward

## Apr 26, 2021
[Reference solutions🔗](https://github.com/mialsy/AlgorithmHandTracingPractice/blob/master/sol/hand_trace_practice_Apr26.pdf) Please let me know if you find any mistake.

### B-trees
#### Insert into tree with degree of 4
- [19, 4, 11, 16, 21, 26, 13, 0, 1, 2, 20]
- [9, 10, 14, 28, 13, 5, 26, 25, 4, 12, 3, 20]

#### Insert into tree with degree of 5
- [19, 4, 11, 16, 21, 26, 13, 0, 1, 2, 20, 3, 5]
- [29, 26, 20, 28, 8, 10, 19, 16, 6, 18, 11, 22]

### Serialization
#### Serialization of binary tree => construct tree back
- AB/CDE//F////
- ACD//E//BF//G//
- AB//CD//EF//G//

#### Serialization of N-nary tree => construct tree back
- ADB)HE)F)))CI))G))
- BCF)D)HAE))F))I)))

#### Given binary tree => serialization
<img src="https://github.com/mialsy/AlgorithmHandTracingPractice/blob/master/res/Screen%20Shot%202021-04-25%20at%208.11.27%20PM.png" width="400" title="binary tree">

#### Given n-nary tree => serialization
<img src="https://github.com/mialsy/AlgorithmHandTracingPractice/blob/master/res/Screen%20Shot%202021-04-25%20at%208.10.33%20PM.png" width="400" title="n-nary tree">

### Graph
#### run DFS and BFS on following graphs (traverse the node with smaller alphabetic order) : 
<img src="https://github.com/mialsy/AlgorithmHandTracingPractice/blob/master/res/Screen%20Shot%202021-04-25%20at%208.10.58%20PM.png" width="400" title="graph">

# For final May 18:

[Reference solutions🔗](https://github.com/mialsy/AlgorithmHandTracingPractice/blob/master/sol/Hand_trace_practice_final.pdf)

Note topological sort you may get quite different result based on where you start.

### Disjoint set - show table:
<ol>
<li> 
  <br>
  <ul>
  <li> createSet(10)
  <li> Union(0, 6)
  <li> Union(6, 4)
  <li> Union(9, 5)
  <li> Union(3, 4)
  </ul>

<li> 
   <br>
  <ul>
  <li> createSet(8)
<li> Union(6, 3)
<li> Union(0, 2)
<li> Union(7, 6)
<li> Union(7, 2)
<li> Union(1, 2)
   </ul>
  </ol>
  
### Topological Sort

Topological Sort - show both with removing edge and the start/finish time method
- 
|Course|Prereq|
|---|---|
|L101|			   L100|
|L109| 		   L101, L103|
| L103| L101|
| L105 | L106, L104, L102|
| L102	|  L100|
| L104 |		   L103, L101|

-
|Task 			| Need to finish before this task|
|---|---|
|BrewCoffee|		BoilWater, GrindCoffee|
|BoilWater|		FilterWater, HeatStove|
|Breakfast|		BrewCoffee, MakePancake|
|MakePancake|	PrepareEgg, HeatStove, FilterWater|
|GoToWork|		Breakfast, CleanKitchen|
|CleanKitchen |	PrepareEgg, MakePancake, BrewCoffee|

- ￼![image](https://user-images.githubusercontent.com/51009396/118569741-66255280-b72f-11eb-85c8-f7343661750f.png)


### Strongly Connected Component
￼![image](https://user-images.githubusercontent.com/51009396/118569791-7ccba980-b72f-11eb-97d9-44ae736d6259.png)

### MST - show both prim & Kruskal
￼![image](https://user-images.githubusercontent.com/51009396/118569798-805f3080-b72f-11eb-8d81-3aafa8f9f995.png)
