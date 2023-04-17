
1. Define:

	(a) Subgraph
		Um grafo de G, é um grafo onde o conjunto de vertices é um subconjunto de vértices G e o conjunto de arestas é um
		subconjunto de arestas de G.
	
	(b) Bipartite graph.
		É um grafo onde os vértices podem ser divididos em dois conjuntos disjuntos U e V, tais que toda aresta conecta um vértice 
		em U a um vértice em V.
	
	(c) Hamiltonian graph
		É um caminho que permite passar em todos os vértices de um grafo sem que sejam repetidos.
	
	(d) Eulerian graph.
		É um grafo onde o grau de cada vértice de G é par.

2. Describe how a breadth-first search algorithm works.
		É um algoritmo onde inicia a travessia a partir de um determinado nó selecionado e atravessa o grafo explorando os nós vizinhos, depois
		explora os nós vizinhos do próximo nível.

3. How many edges does a complete graph with n vertices have? What about a complete directed graph with n vertices?
    Número máximo de arestas de um grafo completo se dá pela formula n*(n-1). Já o número de arestas de um grafo completo direcionado
    se da pela formula n*(n-1).

4. What are isomorphic graphs? Draw an example.
	São grafos semelhantes, que possuem o mesmo número de vértices e arestas, além de serem conectados de forma semelhantes.
	A:    a			B: 1
         / \          / \
	    b---c        2---3

5. Calculate the degree of the nodes for both node types in the bipartite adjacency matrix from the figure below. Find the isolated node(s).

![adjacency matrix](./img/matrix01.png)

6. Given the digraph `G = (V, E)` where `V = {M, N, O, P, Q, R, S}` and 

`E ={(M, S), (N, O), (P, R), (N, S), (O, M),
	 (N, Q), (O, M), (P, P), (S, M), (O, N), 
	 (S, M), (N, R), (P, M), (M, S)}`

	(a) Specify, if any, a simple path from vertex M to vertex S.

	(b) Specify, if any, a simple cycle, involving at least 4 nodes.

	(c) Is the digraph connected or not connected?

	(d) What is the degree of vertices N and R.

	(e) Represent the digraph using adjacency list representation.

	(f) Represent the digraph using adjacency matrix representation.

7. Draw the undirected and directed versions of the graph G(V, E), where V = {1, 2, 3, 4, 5, 6} and E = {(2, 5), (6, 1), (5, 3), (2, 3)}.

8. How many edges does a graph have 3 vertices of degree 3 and one vertex of degree 5?


9. Mr. A is friend with Mrs. B, but she doesn't like him back. She has a reciprocal friendship with both C and D, but only C considers D a friend. D has also sent friend requests to E, F, G, and H but, so far, only G replied. G also has a reciprocal relationship with A. Draw the corresponding directed graph.

10. Draw the graph from the previous exercise as undirected and weighted, with the weight being 2 if the connection is reciprocal, 1 otherwise.