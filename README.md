# Isomorphism


I used help from google to help me remember what onto was and how it is defined.

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

PROOF:

Given:

Graphs  and  are completely connected

They have the same number of nodes n


Since both graphs have the same number of vertices n, we can define a map $f: V_1 \rightarrow V_2$  that 
uniquely maps every vertex in $G_1$ to $G_2$. This function \( f \) is one-to-one
because no two vertices in \( V_1 \) map to the same vertex in \( V_2 \).
It is also onto because every vertex in \( V_2 \) has a preimage in \( V_1 \).

Since $G_1$ and $G_2$ are completed graphs, this means that every pair of vertices
is connected by an edge. Therefore, for any , $u,v \in V_1$  there is a
$(u,v) \in E_1$. Since there is a map f that is both one-to-one and onto between
$G_1$ and $G_2$, this means that $G_2$ is also a completely connected graph. And therefore
$(f(u),f(v)) \in E_2$.

Therefore the graphs are isomorphic by definition of isomorphism.
