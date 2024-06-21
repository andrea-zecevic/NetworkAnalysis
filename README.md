# NetworkAnalysis

## Predicting New Stargazers on GitHub Repositories
GitHub is one of the largest platforms for open-source collaboration, enabling millions of developers to share, collaborate, and contribute to projects worldwide. Central to this ecosystem is the concept of "stargazers," individuals who express interest in a repository by "starring" it—similar to liking posts on social media. The number of stars a repository has reflects its relevance, quality, and community engagement. Repositories with higher star counts often indicate greater influence and success.

This project aims to predict the number of new stargazers for individual GitHub repositories. Inspired by methodologies from social network analysis, my approach involves constructing a network of stargazers. Within this network, I identify influential stargazers and compute their betweenness centrality—a measure of their importance in the network. These centrality measures are later used for training prediction models.

Additionally, community detection within the network will be conducted to identify clusters of stargazers with similar interests or interactions. This analysis will provide further insights into the structure and dynamics of stargazer engagement on GitHub repositories.
