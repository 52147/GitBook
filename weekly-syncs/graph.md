# Graph



{% hint style="info" %}
**Graph :** A non-leaner data structure consisting of nodes and links between nodes.
{% endhint %}

## Undirected Graph

* An undirected graph use a set of nodes and a  set of links between the nodes.
* Each node is called vertex, each link is called edge, <mark style="background-color:blue;">**each edge connects two vertices.**</mark>
* &#x20;The order of the two connected vertices is unimportant.
* An undirected graph is a finite set of vertices together with a finite set of edge.
* Both sets might be empty, which is called the empty graph.

## Directed Graph

* A directed graph us a finite set of vertices together with a finite set of edges.
* Both sets might be empty, which is called the empty graph.
* Each edge is associate with the two vertices, called its source and target vertices.
* The order of the two connected vertices is important.

## Simple Graph

* A simple graph is a graph that does **not have more than one edge between any two vertices.**
* And no edge start and end at the same vertices.  (No loops)

## Complete Graph

* For any n ∈ N, a complete graph on vertices, ![{\displaystyle K\_{n}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/ea2b988ea630d2c5571afe47efa3d3b251708acb).
* is a simple graph with n nodes in which every nodes is adjacent to every other node:
* ∀u, v ∈ V : u≠ v ↔ {u, v} ∈  E
* vertices: n
* edges: ![](broken-reference)

## Cycle

## Loop

* An edge that connects a vertex to itself.

## Path

*   Paths in undirected graphs

    * &#x20;In an undirected graph, a path of length m from u to v is a sequence of adjacent edges going form vertex u to vertex v.
    * A path is a **circuit **if u - v.
    * A path traverses the vertices along it.
    * A path is simple if it contains no edge more than once.


* Paths in directed graphs
  * Same as in undirected graphs, but the path must go in the direction of the arrows.

## Adjacency Matrix

* An adjacency matrix is a square grid of **true/false values that represent the edges of a graph**
* If the graph **contains n vertices, then gird contains n rows and n columns.**
* For two vertex number i and j, the component at row i and column j is true if there is an edge from vertex i to vertex j, otherwise the component is false.
* &#x20;We can use a two-dimension array to store an adjacency matrix:
* For example:  boolean\[]\[] adjacent = new boolean\[4]\[4]
* Once the adjacency matrix has been set, an application can examine location of the matrix to determine which edges are present and which are missing.

## Connected

* An undirected graph is connected if there is a path between every pair of distinct vertices in the graph.
* Connect component : connected subgraph
* A cut vertex or cut edge separates 1 connected component into 2 if removed.
* Theorem:
  * There is  a simple path between any pair of vertices in a connected undirected graph.

## Degree of a Vertex

* Let G be an undirected graph v ∈ V a vertex.
* The degree of v, denoted by deg(v), is its number of incident edges. (Except that any self-loops are counted twice.)
* A vertex of degree 0 is isolated.
* A vertex of degree 1 is pendant.





## Even/Odd Degree

* Once you have the degree of the vertex you can decide if the vertex or node is even or odd.
* If the degree of a vertex is even the vertex is called an even vertex.
* If the degree of the vertex is odd, the vertex is called an odd vertex.
* in a multigraph, a loop contributes 2 to a vertex's degree, for the two ends of the edge

![](broken-reference)

| vertex | degree | Even or Odd |   |
| ------ | ------ | ----------- | - |
| S      | 1      | Odd         |   |
| M      | 3      | Odd         |   |
| A      | 2      | Even        |   |
| R      | 3      | Odd         |   |
| T      | 3      | Odd         |   |

## Handshaking Theorem

* Let G be an undirected graph with vertex set V and edge set E.&#x20;
* Corollary : Any undirected graph has an even number of vertices of odd degree.

{% embed url="https://www.cpp.edu/~ftang/courses/CS241/notes/graph.htm" %}

{% embed url="https://slidetodoc.com/discrete-mathematics-the-basic-concepts-of-the-graph" %}

{% embed url="http://www.geom.uiuc.edu/~doty/even.html" %}

