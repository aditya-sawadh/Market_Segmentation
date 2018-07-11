# Market Segmentation

Market segmentation divides a broad target market into subsets of consumers or businesses that have or are perceived to have common needs,
interests, and priorities. These segments help firms or businesses focus on their target groups effectively and allocate resources 
efficiently. In this project, we aim to find such market segments given social network data. 

## Data 
The datasets required for this project are in the data  folder. This dataset contains a facebook network of a US university (given as an edgelist) with each node corresponding to a user profile having the following attributes: student/faculty status, gender, major, second major, dorm, and year information. For the similarity convenience, these attribute values have been converted into asymmetric binary variables.

## Methodology 
The algorithm is based on research paper titled _"Community Detection based on Structural and Attribute Similarities"_.
The social relations for breaking down market segments can be captured in a graph framework where nodes represent customers/users and edges 
represent some social relationship. The properties belonging to each customer/user can be treated as node attributes. 
Hence, market segmentation becomes the problem of community detection over attributed graphs, where the communities are formed based on graph structure as well as attribute similarities.



