# Exercise 1: Graph Models for Airline Routes

**Problem Statement:**
Draw graph models, stating the type of graph (from Table 1) used, to represent airline routes where every day there are:
*   Four flights from Boston to Newark.
*   Two flights from Newark to Boston.
*   Three flights from Newark to Miami.
*   Two flights from Miami to Newark.
*   One flight from Newark to Detroit.
*   Two flights from Detroit to Newark.
*   Three flights from Newark to Washington.
*   Two flights from Washington to Newark.
*   One flight from Washington to Miami.

---

### a) An edge between vertices representing cities that have a flight between them (in either direction).

**Graph Type:** Simple undirected graph.

**Representation:**
> *Note: Replace `route_a.png` with your actual image filename.*

![Graph part a](route_a.png)

---

### b) An edge between vertices representing cities for each flight that operates between them (in either direction).

**Graph Type:** Undirected multigraph.

**Representation:**
> *Note: Replace `route_b.png` with your actual image filename.*

![Graph part b](route_b.png)

---

### c) An edge between vertices representing cities for each flight that operates between them (in either direction), plus a loop for a special sightseeing trip that takes off and lands in Miami.

**Graph Type:** Undirected multigraph with loops.

**Representation:**
> *Note: Replace `route_c.png` with your actual image filename.*

![Graph part c](route_c.png)

---

### d) An edge from a vertex representing a city where a flight starts to the vertex representing the city where it ends.

**Graph Type:** Directed graph (Digraph).

**Representation:**
> *Note: Replace `route_d.png` with your actual image filename.*

![Graph part d](route_d.png)

---

### e) An edge for each flight from a vertex representing a city where the flight begins to the vertex representing the city where the flight ends.

**Graph Type:** Directed multigraph.

**Representation:**
> *Note: Replace `route_e.png` with your actual image filename.*

![Graph part e](route_e.png)
