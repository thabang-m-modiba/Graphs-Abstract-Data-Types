# Graphs (source: Data Structures and Algorithms in Java 6th Edition, Micheal T. Goodrich, Roberto Tamassia, Micheal H. Goldwasser)
## Definition of a Graph.
Not your usual bar or line graph 😄.
* A Graph is a way of representing relationships that exists between pairs of Objects (Vertices or nodes).
* A Graph data structure consists of a finite <b>set of vertices</b> (also known as nodes or objects as defined above☝️), together with a <b>set of edges<b> (also called links) that connect these vertices together.
* A Graph can be formally defined as G = (V, E), where V is a set of vertices and E is a set of edges.

## The two main categories of a Graph are:
1️⃣ Directed Graphs - in this case, edges are ordered pairs (u, v), meaning the connection between the vertices has a direction from u to v.<br>
2️⃣ Undirected Graphs - in this case, endges are unordered pairs {u, v}, meaning the connection between the vertices is bidirecional.

## Some important terminology in Graph structures.
* Two vertices joined by an edge are called the <b>end vertices</b> or ⭐<u>endpoints</u> of the edge.
* If an edge is directed, its first endpoint is called the ⭐<u>origin edge</u> and the other endpoint is called the ⭐<u>destination edge</u>.
* Two vertices u and v are said to be ⭐<u>adjacent</u> if there exists an edge with endpoints u and v.
* An edge is said to be ⭐<u>incident</u> to a vertex if the vertex is one of the edge's endpoints.
* The ⭐<u>outgoing edges</u> of a vertex are the directed edges whose origin is that vertex.
* The ⭐<u>incoming edges</u> of a vertex are the directed edges whose destination is that vertex.
* ⭐<u>The degree</u> of a vertex v, denoted by <u>deg(v)</u>, is the number of incident edges of v.
* The ⭐<u>in-degree</u> and ⭐<u>out degree</u> of a vertex v are the number of the incoming and outgoing edges of v, and are denoted by <u>indeg(v)</u> and <u>outged(v)</u>, respectively.

## Core Operations of a Graph ADT
* <code>adjacent(G, x, y)</code> - Tests whether there is an edge from vertex $x$ to vertex $y$.
* <code>neighbors(G, x)</code>
* <code>add_vertex(G, x)</code>
* <code>remove_vertex(G, x)</code>
* <code>add_edge(G, x, y)</code>
* <code>remove_edge(G, x, y)</code>
* <code>get_vertex_value(G, x)</code>
* <code>set_vertex_value(G, x, v)</code>
* <code>get_edge_value(G, x, y)</code>
* <code>set_edge_value(G, x, y, v)</code>
