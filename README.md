Download Link: https://assignmentchef.com/product/solved-cs571-intelligence
<br>



<strong> </strong>

——————————————————————————————————————————-

<h1>Questions</h1>

——————————————————————————————————————————-

<ol>

 <li>In a Best First Search algorithm each state (n) maintains a function

  <ol>

   <li><em>f(n) = h(n) </em></li>

  </ol></li>

</ol>

In an A* search algorithm each state (n) maintains a function

<ol>

 <li><em>f(n) = g(n) + h(n)</em> where g(n) is the least cost form source state to state n found so far and h(n) is the estimated cost of the optimal path from state n to the goal state.</li>

</ol>

Implement Best First Search and A* search algorithm for solving the 8-puzzle problem with the following assumptions.




<ol>

 <li><em>g(n)</em>​ = least cost from source state to current state so far.</li>

 <li>Heuristics

  <ol>

   <li><em>h</em>​<em>1</em><sub>​</sub><em>(n)</em>​ = number of tiles displaced from their destined position.</li>

   <li><em>h</em>​<em>2</em><sub>​</sub><em>(n)</em> = sum of Manhattan distance of each tile from the goal position.</li>

  </ol></li>

</ol>




<ol start="2">

 <li>A local search algorithm tries to find the optimal solution by exploring the states in the local region. Hill climbing is a local search technique which always looks for a better solution in its neighbourhood.

  <ol>

   <li>Implement the Hill Climbing Search Algorithm for solving the 8-puzzle problem.</li>

   <li>Check the algorithm for the following heuristics:

    <ol>

     <li><em>h</em>​<em>1</em><sub>​</sub><em>(n)</em>​ = number of tiles displaced from their destined position.</li>

     <li><em>h</em>​<em>2</em><sub>​</sub><em>(n)</em> = sum of Manhattan distance of each tile from the goal position.</li>

    </ol></li>

  </ol></li>

</ol>




<strong>Instructions: </strong>

<ol>

 <li>Input is given in a file in the following format. Read the input and store the information in a matrix. Configuration of the start state and the goal state can be anything. For example given below T1, T2, …,T8 are tile numbers and B is blank space.</li>

</ol>




<ol start="2">

 <li>Output should have the following information:

  <ol>

   <li><strong>On success: </strong>

    <ol>

     <li>Success Message</li>

     <li>Start State / Goal State iii. Total number of states explored iv.     Total number of states to optimal path</li>

     <li>Optimal Path</li>

     <li>Optimal Path Cost</li>

    </ol></li>

  </ol></li>

</ol>

<ul>

 <li>Time taken for execution</li>

</ul>




<ol>

 <li><strong>On failure: </strong>

  <ol>

   <li>Failure Message</li>

   <li>Start State / Goal State</li>

  </ol></li>

</ol>

<ul>

 <li>Total number of states explored before termination</li>

</ul>

<ol start="3">

 <li>Compare and contrast between the results of the three algorithms for the different heuristics</li>

</ol>








