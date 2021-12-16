# Social-Network-Analysis
Facebook Large Page-Page Network Analysis
Data Source: https://snap.stanford.edu/data/facebook-large-page-page-network.html

A page-page graph of verified Facebook sites. Nodes represent official Facebook pages while the links are mutual likes between sites. 
Node features are extracted from the site descriptions that the page owners created to summarize the purpose of the site. 
This graph was collected through the Facebook Graph API in November 2017 and restricted to pages from 4 categories which are defined by Facebook. These categories are: politicians, governmental organizations, television shows and companies

### Analysis includes:
- Dataset import and preprocessing
- Degree Analysis
- ECDF and ECCDF
- Comparison with an Erdos-Renyi random graph G(N, p)
- Hubs and isolated nodes detection
- Transitivity and local clustering coefficient
- Centrality
- Assortativity
- Community detection
- Network visualization with Gephi
