# edge-embedding
Skim through edge embedding and how it's adopted simultaneously with node embedding

## Starting Notion
network embedding models typically consider the
social relation between nodes as a binary variable. Accordingly,
the objective of many network embedding algorithms is to predict
the existence of edge between two nodes [14]. This objective is
sometimes extended to consider the co-occurrences between nodes

## Literatures
https://arxiv.org/pdf/1805.03280.pdf

### edge embedding with semantic label or knowledge-based annotations (somewhat pedagogical approaches for edge embedding)
https://www.researchgate.net/publication/328437153_Enhanced_Network_Embeddings_via_Exploiting_Edge_Labels :: network embedding models typically consider the
social relation between nodes as a binary variable. Accordingly,
the objective of many network embedding algorithms is to predict
the existence of edge between two nodes [14]. This objective is
sometimes extended to consider the co-occurrences between nodes
##### Goal
1. Let we can search through our interested edge relations with semantic query which represented a bit differently. Trained with few words annotation, but finally become to be able to query "edges::to boost the political activity" 
2. Also we need to let node embedding learned better by leveraging the edge labels
"There are also a number of methods that utilize edge labels
for learning better node representations. SNE [18] presents a logbilinear model that incorporates two vectors to capture the positive
or negative relationships between nodes respectively. TransR [9]
learns a projection matrix for each relation type in knowledge graph,
which is used for projecting entity embeddings from entity space
to relation space. These work generally assume that each edge is
associated with a single type of label: it could be the sign of edges in
signed networks, or relation types in knowledge graphs."

## Edge Annotation Techniques
0. Assuming Edges are associated with a single type of label
0-1. SNE [18] presents a logbilinear model that incorporates two vectors to capture the positive
or negative relationships between nodes respectively.

0-2. y. TransR [9]
learns a projection matrix for each relation type in knowledge graph,
which is used for projecting entity embeddings from entity space
to relation space.

1. Assuming Edges are associated with a multi type of label
Enhanced Network Embeddings via Exploiting Edge Labels
