# simulation final project
&nbsp; This repository contains 9 parts. These parts are as follows:<br />

### 1. simple graphs:
&nbsp; We have to compare algebraic-connectivity, natural-connectivity(natural-eigenvalue), energy, laplacian-energy and ... of some graphs
(specially erdos-renyi, watts strogatz and scale-free) and also ioncreasing number of nodes in these graphs and recalculate these parameters
in order to compare them. It is better to draw these graphs degree distribution.<br/>

### 2. RSRBG(random semi regular bipartite graphs):
&nbsp; Implementing the provided algorithem for generating random semi regular bipartite graphs. Then generate numbers of this graph with different
values and calculate same parameters as question 1 for them with their degree distribution. And compare them graphs in question number one. <br />

### 3. RSRBG(random semi regular graphs):
&nbsp; Implementing provided algorithem for generating random semi regular graphs. Then generate numbers of these graph with different
values(also increase number of nodes in these samples) and calculate same parameters as question 1 for them with their degree distribution. And compare them with
other graphs that has been mentioned earlier.<br />

### 4. line graphs:
&nbsp; Generate line graphs of all previously mentioned graphs and calculate mentioned parameters for them with their degree distribution. Then compare these 
parameters to see if they stayed the same or not.

### 5. total variance distance:
&nbsp; Draw scale-free degree distribution on log-log scale with different γ parameter.<br />
Generate numbers of scale-free graphs with same number of nodes and then calculate the probability of each degree in tyhese graphs and compare them.
Then calculate total variance distance for all of them and compare them.<br />
Then repeat all these process with higher graph size(node number).

### 6. regular graphs:
&nbsp; Generate numbers of δ-regular graph and then remove edges randomly one-by-one to until the graph gets disconnected. Then do the exact same process for the RSRBG
graphs with same number of nodes and edges. Also in the steps that you are removing an edge, calculate algebraic-connectivity for these graphs and at the end draw this 
parameter plot and compare them.

### 7. girth & cage:
&nbsp; From all previously mentioned graphs in this project, generate a sample for each one of them and calculate cage and girth for them(try to have same number 
of node and edge). Then compare them with each other.

### 8. nodes lifetime:
&nbsp; Imagine that for graphs that have been mentioned so far, we have a life time that is generated from a distribution like pareto, shifted pareto(lomax), weibull, exponentional,
uniform and ... . Then with the help of simulation compare isolation/disconnection for these networks and draw a plot for them (first compare each distribution on same graph 
then compare same distribution on different graphs).

### 9. TTT:
&nbsp; compare TTT of different graphs.
