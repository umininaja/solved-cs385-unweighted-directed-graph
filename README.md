Download Link: https://assignmentchef.com/product/solved-cs385-unweighted-directed-graph
<br>
For this assignment, you are to modify the UnweightedDirectedGraph.java file attached as starter code and add a method to compute the <strong>in-degree </strong>and <strong>out-degree</strong> of each vertex in the graph. The in-degree of a vertex is the number of incoming edges to that vertex and the out-degree of a vertex is the number of outgoing edges from that vertex.

For example, in the directed graph shown below, the in-degree of vertex H is 3 (because there are three incoming edges to node H) and out-degree of vertex H is 1 (because there is only one outgoing edge from vertex H). Similarly, the in-degree of node A is 0 and its out-degree is 3.

<strong>What you need to do: </strong>

I have attached two files with this assignment:

<ul>

 <li><strong>Degree</strong>.java: This is a class with two integer attributes: in-degree and out-degree used to store the in-degree and out-degree of a vertex, respectively.</li>

 <li><strong>java </strong>: This is a minimal code for an unweighted directed graph. The only attribute of this class is “adjacencyList” which is a hashMap&lt;LinkedList&lt;V&gt;&gt; where V is a parametric type for vertices in graph. For each vertex in the graph, the adjacencyList stores all the outgoing edges from that vertex. Please refer to the lectures and the practice problem in module 12 for more details on this adjacency list.  The class also has an addEdge method which allows you to construct a graph by adding edges to it.</li>

</ul>

You need to implement the following method in the UnweightedDirectedGraph.java:

<strong>public</strong> Map&lt;V, Degree&gt; findInOutDegrees()

This method returns a Degree object for each vertex in the graph. The return type is a Map of &lt;vertex, Degree&gt;where the key is a vertex in graph and value is a Degree object containing the in-degree and out-degree for that vertex.

To test your method, you can make up a main method and create an instance of

UnweightedDirectedGraph and add edges to it. Then call your findInOutDegrees method and print the map that is returned.