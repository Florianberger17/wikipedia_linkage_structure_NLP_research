# Wikipedia Linkage Structure NLP Research
## by F. Berger

The project consists of two programs, which were created as part of a master's thesis at the Chair of Communication Networks at the University of Hagen. The programs make it possible i) to build semantic graphs based on the linking structure of Wikipedia and ii) to determine the network growth from a central node of the network.

## Semantic Graphs
The term graph refers to a data structure in which a network is represented as a combination of nodes and edges. The structure of semantic graphs is based on the structure of established co-occurrence graphs, with the titles of articles under consideration forming the nodes. The linking relationships between the articles represent the edges in the graph.

## Program "1_Program_Creation_Linkage_Graph"
The program builds linkage graphs based on a selection of Wikipedia categories. The output of the program is a project directory and output files that enable the link graphs to be imported into the graph database Neo4j.

## Program "2_Program_Evaluate_Network_Growth_Over_Time"
The program is based on the project directory created using the "1_Program_Creation_Linkage_Graph" program and determines the network structure, starting from a defined, central point in the network. The result is the extension of the project directory and a file containing the network growth per time step.

## Further Research
The programs can be used to create linkage graphs and import them to the graph database Neo4j in order to investigate semantic relationships between wikipedia sites. A possible starting point in further research is, for example, the investigation of text-representing centroids (TRCs) for created link graphs.

