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
<img width="815" height="330" alt="image" src="https://github.com/user-attachments/assets/3510fe90-877e-4501-a218-8335d1679f3c" />


---

### b) An edge between vertices representing cities for each flight that operates between them (in either direction).

**Graph Type:** Undirected multigraph.

**Representation:**
<img width="776" height="426" alt="image" src="https://github.com/user-attachments/assets/53dfcc2b-42b0-49b0-ae82-82529aaf8705" />


---

### c) An edge between vertices representing cities for each flight that operates between them (in either direction), plus a loop for a special sightseeing trip that takes off and lands in Miami.

**Graph Type:** Undirected multigraph with loops.

**Representation:**
<img width="894" height="369" alt="image" src="https://github.com/user-attachments/assets/b8c01d79-f291-42ef-b1d5-b1a0a1ddcf0f" />


---

### d) An edge from a vertex representing a city where a flight starts to the vertex representing the city where it ends.

**Graph Type:** Directed graph (Digraph).

**Representation:**
<img width="768" height="332" alt="image" src="https://github.com/user-attachments/assets/bda66c8a-4c2b-45ef-84bb-ea6b636d4647" />


---

### e) An edge for each flight from a vertex representing a city where the flight begins to the vertex representing the city where the flight ends.

**Graph Type:** Directed multigraph.

**Representation:**
<img width="705" height="322" alt="image" src="https://github.com/user-attachments/assets/294ad96c-ee68-406a-a21b-48c50f061a69" />

