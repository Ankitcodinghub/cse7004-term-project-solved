# cse7004-term-project-solved
**TO GET THIS SOLUTION VISIT:** [CSE7004 Term Project Solved](https://www.ankitcodinghub.com/product/cse7004-term-project-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93902&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE7004 Term Project Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
In this project, you are required to solve the Maximum Weighted Independent Set Problem (MWISP). In graph theory, an independent set is a set of vertices in a graph, no two of which are adjacent. That is, it is a set S of vertices such that for every two vertices in S, there is no edge connecting the two. In the MWISP, you are required to find the independent set of a given graph such that the sum of the weights of the nodes is the maximum [1].

For instance, for the below graph

the nodes g and f form an independent set with a weight sum of 8, whereas nodes r and j form another independent set with a weight sum of 9.

In this project, you are required to solve MWISP for a given graph (i) optimally using GUROBI Optimizer (you can obtain a free academic license) and (ii) using a greedy heuristic and (iii) using a genetic algorithm-based heuristic. You should design an experiment comparing the solutions found by the proposed heuristic solutions to the optimal solutions.

For this project, you are required to implement:

1. A random undirected graph generator for MWISP: The generator should get two parameters:

<ol>
<li>the number of nodes in the graph,</li>
<li>the density of the graph;</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
and generate a random undirected graph with the given number of nodes and the given density. The weights of the nodes should be determined using uniform random distribution on the interval [0-1].

Your generator should save the graph in a text file, the format of which is as follows:

Number of nodes // The first line

Number of edges // The second line

List of node weights (format: X W where W is the weight of node X, X takes values from 0 to |V|-1)

List of edges (format: X Y which indicates an edge from node X to node Y)

e.g. 3

4

<ol start="0">
<li>0 &nbsp;0.32</li>
<li>1 &nbsp;0.45</li>
<li>2 &nbsp;0.89</li>
</ol>
01 02 12 13

Since your graph is undirected, do not include duplicate edges such as 1 3 and 3 1, since edge 1 3 is same as edge 3 1.

The algorithm for generating a random graph is as follows:

For each vertex u:0 to Number_of_Vertices-1

For each vertex v: u+1 to Number_of_Vertices-1

Generate a uniform continuous random number between 0 and 1

If this number is smaller than (the density value), add an edge between u and v.

You are required to generate at least 20 graph files using the following parameters:

</div>
</div>
<div class="layoutArea">
<div class="column">
Number of Nodes 500

1000

1500

2000

</div>
<div class="column">
Density

0.1, 0.3, 0.5, 0.7, 0.9 0.1, 0.3, 0.5, 0.7, 0.9 0.1, 0.3, 0.5, 0.7, 0.9 0.1, 0.3, 0.5, 0.7, 0.9

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
2. A front-end for Gurobi Optimizer: The front-end will read the given graph file and solve the MWISP using Gurobi MIP Solver as a library.

The integer programming formulation of the MWISP is as follows:

max$!∈#𝑤!𝑥!

s.t. 𝑥$+𝑥!≤1 ∀{𝑢,𝑣}∈E

𝑥! ∈{0,1} ∀𝑣 ∈E

where xv is the decision variable indicating whether the vertex v is included in the independent set or not, and wv is the weight of the vertex v.

Please check Gurobi examples for building your model in your preferred programming language https://www.gurobi.com/resource/functional-code-examples/.

Reference manual can be found in

<blockquote class="wp-embedded-content" data-secret="6TVvKb6oUk"><a href="https://www.gurobi.com/documentation/">Documentation</a>
</blockquote>
<iframe class="wp-embedded-content lazyload" sandbox="allow-scripts" security="restricted" style="position: absolute; clip: rect(1px, 1px, 1px, 1px);" title="“Documentation” — Gurobi" data-src="https://www.gurobi.com/documentation/embed/#?secret=6TVvKb6oUk" data-secret="6TVvKb6oUk" width="600" height="338" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-load-mode="1"></iframe>

For each instance, provide a maximum time limit of 1 hour ( set TimeLimit parameter to 3600 seconds before calling optimize method – https://www.gurobi.com/documentation/9.0/refman/java_parameter_examples.html). If the optimal solution cannot be found, then use the suboptimal solution and indicate this in the report.

2. A greedy heuristic solver: The heuristic solver will read the given graph file and provide a greedy heuristic solution. You may implement any greedy heuristic.

3. A genetic algorithm based heuristic solver: The heuristic solver will read the given graph file and provide a heuristic solution.

Your genetic algorithm based heuristic method should get the following five inputs:

<ol>
<li>Name of the graph file</li>
<li>Number of generations</li>
<li>Population size</li>
<li>Crossover probability</li>
<li>Mutation probability</li>
</ol>
For each of the graphs, your program should generate 50, 100, 150 generations with a population of size 50 and 100. For selection of parents, you are required to implement the binary tournament selection method.

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
For crossover, you should use uniform crossover operator with a probability of 0.5. Finally, for the mutation, bitwise mutation operator should be used with a probability of 1/n (n:number of nodes in the graph). Any desired repair function can be used (you should also report details of your repair function).

Therefore, for each of the twenty graphs, you should run your program 6 times (once for each of the above parameter configurations). You should submit fully commented source code along with a report containing tables, graphs and discussion of the results and the effect of parameters. Further details will be discussed after the lectures.

References:

[1] https://en.wikipedia.org/wiki/Independent_set_(graph_theory)

</div>
</div>
</div>
