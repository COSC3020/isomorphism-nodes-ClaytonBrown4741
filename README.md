[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12547963&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.  

**Answer**:  
If the two graphs do not have the same number of nodes, then that means that there  
cannot be a bijective function that maps between the two, and therefore, they can't  
be isomorphic. This is because if one of the graphs has a differing number of nodes  
than the other, the function that maps between them can't possibly be onto *and* one  
to one. For instance, let's assume that graph A has more nodes than graph B and there  
is a function that maps A to B. This function cannot be one to one, as there will always  
be at least one two elements in A that map to the same element in B.  
Alternatively, if we simply exclude the extra elements from the the function, then it is  
no longer onto. This same principle applies if Graph A has less nodes than Graph B.  
So, because there is no bijective function that can map A to B, then that means the graphs  
cannot be isomorphic.  
(Please note that if anything is wrong with my reasoning or if I was too vague at some  
point, please don't hesitate to let me know what I did wrong and I will fix it right away.  
Thank you).
