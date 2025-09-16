# The CDC conjecture
# Cycle double cover conjecture

The CDC conjecture states that for every bridgeless graph, there is a family of cycles such that each edge is covered by exactly two members of this family.
In an embedding of a graph $G$, an edge $e$ is called **singular** if there exists a facial walk $F$ that traverses $e$ twice. Otherwise, $e$ is called **regular**. Then, the conjecture is equivalent to every bridgeless cubic graph having an embedding with no singular edges. 

If a singular edge $e$ is traversed twice in the same direction by a facial walk $F$, we call it **good singular**, and if $e$ is traversed twice in opposite directions by
$F$ we call it **bad singular**. 

Our computer experiment shows that in a random embedding of a bridgeless cubic graph $G$, the expected number of bad singular, good singular, and regular edges is 1/3 of the number of edges of the graph $G$ for each case.

**Note**: In the Python code, we used the notation "bad negative for bad singular", "bad positive for good singular", and "good for regular"!
