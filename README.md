# Graphs (source: Data Structures and Algorithms in Java 6th Edition, Micheal T. Goodrich, Roberto Tamassia, Micheal H. Goldwasser)
### Definition of a Graph.
Not your usual bar or line graph 😄.
* A Graph is a way of representing relationships that exists between pairs of Objects (Vertices or nodes).
* A Graph data structure consists of a finite <b>set of vertices</b> (also known as nodes or objects as defined above☝️), together with a <b>set of edges<b> (also called links) that connect these vertices together.
* A Graph can be formally defined as G = (V, E), where V is a set of vertices and E is a set of edges.

### The two main categories of a Graph are:
1️⃣ Directed Graphs - in this case, edges are ordered pairs (u, v), meaning the connection between the vertices has a direction from u to v.<br>
2️⃣ Undirected Graphs - in this case, endges are unordered pairs {u, v}, meaning the connection between the vertices is bidirecional.

### Some important terminology in Graph structures.
* Two vertices joined by an edge are called the <b>end vertices</b> or <b>endpoints</b> of the edge.
* If an edge is directed, its first endpoint is called the <b>origin edge</b> and the other endpoint is called the <b>destination edge</b>.
* Two vertices u and v are said to be <b>adjacent</b> if there exists an edge with endpoints u and v.
* An edge is said to be <b>incident</b> to a vertex if the vertex is one of the edge's endpoints.
* The <b>outgoing edges</b> of a vertex are the directed edges whose origin is that vertex.
* The <b>incoming edges</b>
