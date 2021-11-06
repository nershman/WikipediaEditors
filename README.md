# WikipediaEditors

In this report I rely on data on the time, user, and article edited on Wikipedia. From this data I generate temporal distances between edits in order to represent the edit chain of an article in a graph.

I tested the hypothesis that users and articles would develop into clusters: presumably around certain topics and areas of expertise. Measuring the modularity of k-means clusters, we cannot reject the hypothesis. However, hierarchical clustering lead to significantly higher modularity. This shows that a hierarchy exists between users, more strongly than clustering around specific topics.
