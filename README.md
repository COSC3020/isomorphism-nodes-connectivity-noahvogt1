# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.


Given:

Graphs  and  are completely connected

They have the same number of nodes n


Since the graphs are completely connected, we can say that each vertex in G_1 
and G_2 are adjacent to every other vertex in each graph respectively. Because
both graphs have n vertices, we can define a map that uniquely maps every vertex
in G_1 to G_2. This means the map is both one to one and onto proving bijection.

Since G_1 and G_2 are completed graphs, this means that every pair of vertices
is connected by an edge. Therefore, for any $f: V_1 \rightarrow V_2$  there is a
$(u,v) \in E_1$.
