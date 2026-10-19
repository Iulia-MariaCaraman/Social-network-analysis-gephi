# Social Network Analysis: Les Miserables Character Co-occurrence

Network analysis and graph visualization project created using Gephi.

## Overview
This project explores relationship dynamics and community clusters within the classic Les Miserables social network. The undirected graph consists of 77 character nodes and 254 interaction edges based on co-occurrence across narrative scenes.

## Network Metrics and Features
* Node Centrality: Character significance is scaled by dynamic degree centrality, identifying Valjean as the primary structural bridge with a degree of 36, followed by Gavroche, Marius, and Javert.
* Community Detection: Implements modularity clustering to identify distinct narrative communities, visually separated by color-coded modularity classes.
* Edge Weighting: Connection thickness represents interaction co-occurrence frequency, ranging from single meetings up to 31 shared narrative moments.
* Visual Topologies: Includes force-directed layout arrangements alongside density cluster representations.

## Repository Contents
* les_miserables_network_map.jpg: Network topology visualization highlighting clusters and weighted co-occurrence edges.
* les_miserables_density_clusters.png: Density area layout showcasing community interactions.
* les_miserables_data_table.png: Data laboratory snapshot detailing node metrics, degree scores, sizes, and modularity attributes.
* Les Miserables.gexf: Graph exchange XML file containing original node and edge attributes if exported from your local Gephi workspace.

## Tools Used
* Gephi Open Graph Visualization Platform
* Network modularity and degree centrality algorithms
