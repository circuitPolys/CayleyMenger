# CayleyMenger
Circuit Polynomials in the Cayley Menger ideal

Requires: Wolfram Mathematica

Platform: any that supports Mathematica

Description: This repository contains a database of circuit polynomials in Cayley-Menger ideals, i.e. the minimal dependencies in the algebraic matroids of Cayley-Manger ideals. At prestent the database contains, up to relabeling, all circuit polynomials on 4, 5 and 6 vertices, as well as some circuit polynomials on 7 vertices and some on 8 vertices.

The polynomials are saved in Mathematica's compressed .wdx format and have to be indivitually imported into a notebook.
A tutorial on how to import the poylnomials is presented in the ImportPolynomialTutorial.nb notebook.

---

<h1>Circuit polynomials in the database</h1>

A filename is followed by a description of the corresponding sparsity circuit

<h2>4 vertices</h2>

<b>k4.wdx</b> - complete graph on 4 vertices

<h2>5 vertices</h2>

<b>wheel4.wdx</b> - wheel on 4 vertices

<h2>6 vertices</h2>
  
<b>doubleBanana2D.wdx</b> - the two-dimensional "double banana"

<b>wheel5.wdx</b> - wheel on 5 vertices

<b>desarguesPlusOne.wdx</b> - the "Desargues" graph (a.k.a the Doublet, a.k.a. Prism or 3-Prism) together with an additional edge

<b>k33PlusOne.wdx</b> - the complete bipartite graph K(3,3) (a.k.a. the Utility graph, a.k.a the Thomsen graph) together with an additional edge

<h2>7 vertices</h2>

<b>dB+k4-16.wdx</b> - direct sum of doubleBanana2D and K4 on the vertices {1,5,6,7} with the edge 16 eliminated

<b>dB+k4-56.wdx</b> - direct sum of doubleBanana2D and K4 on the vertices {4,5,6,7} with the edge 56 eliminated

<h2>8 vertices</h2>

<b>dB+k4-56--8v.wdx</b> - direct sum of doubleBanana2D and K4 on the vertices {5,6,7,8} with the edge 56 eliminated

<b>dB+k4-45.wdx</b> - direct sum of doubleBanana2D and K4 on the vertices {4,5,7,8} with the edge 45 eliminated
