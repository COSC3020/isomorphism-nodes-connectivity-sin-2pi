# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.
## Answer

There are two graphs $A$ and $B$ that are completely connected and both have $n$ vertices.

We can have $[1,2,3, ..., n]$ represent the vertices of $A$ and $[a,b,c, ..., z]$ represent the vertices of $B$. 

Since both graphs are completely connected, every vertex in $A$ is connected to every other vertex in $A$, and every vertex in $B$ is connected to every other vertex in $B$.

We have a bijective mapping $M: V_A \rightarrow V_B$:


1 $\rightarrow$ a

2 $\rightarrow$ b

3 $\rightarrow$ c

⋮

n $\rightarrow$ z

This mapping $M$ is
- One-to-one: Each vertex in $A$ maps to exactly one unique vertex in $B$
- Onto: Every vertex in $B$ is mapped to by exactly one vertex in $A$

Since both graphs are completely connected, any edge $(u,v)$ in $A$ maps to edge $(M(u),M(v))$ in $B$, preserving all edge relationships.

Therefore, $M$ satisfies the requirements of the isomorphism function $f$, it is a bijection between the vertex sets and preserves all edge relationships.

So, graphs $A$ and $B$ are isomorphic. 

### Sources

I met with Ali during lab hours to help form my statement and double check my thoughts.

******

I certify that I have listed all sources used to complete this exercise, including the use of any large language models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice. 
