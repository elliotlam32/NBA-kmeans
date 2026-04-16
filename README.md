# NBA-kemans
Topic: NBA K-Means Clustering for Big Men Archetypes


**Dataset**

The individual players selected/determined for this project were made through my jurisdiction. I deemed anyone traditionally categorized as a Center on Basketball Reference as a Big Man, but excluded “Large Forwards” such as Paolo Banchero and Jalen Johnson. Additionally, I also tried to exclude tall players who moved more like a guard than a forward or center, despite their height. The most prominent example of this is Will Riley(Highlights found in Highlights Folder). The player list can be found within the code. However, this could have been a new archetype that I excluded completely. Once I had determined the list, I webscraped the dataset from Basketball Reference using Cloudscraper. 


**Purpose**

As the game of basketball has progressed over the years, we’ve seen many new tactics and evolutions to the game, such as the emergence of the 3-point shot. These new innovations have ultimately changed and shifted the purpose of one of the most quintessential positions in basketball, being the Big Man/Center. Traditionally associated with having a high 2pt% and volume near the rim, and usually putting up high rebounding numbers. This role has shifted significantly over the years. We now see centers facilitating entire offensives, while some have developed a 3-point shot and are able to space the floor, but others still fill the traditional role. This project aims to determine the new archetypes of the “Big Man” and group players into them using K-Means Clustering.


**Issues/Solutions**

1. K-Means Graph: The K-Means graph is quite difficult to understand, especially since the centroids aren’t labeled, and the graph tends to pick dots that are very similar in color. - still have yet to fix
2. Overly Specialzied clusters: picking individuals that excel at their archetype to cluster around creawteas a cluster that almost always excludes average players of that archetype - for example choosing wemby to cluster around almost always produced a cluster of just Wemby and Chet Holmgren


**Improvements/Potential Areas to Build**

1. Execute the same project but on data from the 2018-2019 season, to see which players changed groups/archetypes Also, provide qualitative analysis as to how and potentially why? Any pioneers in the field?
Pull more advanced data + more players from previous years in order to create a larger and more in-depth model. I could pull pick and roll data from the NBA site, and more seasons from SportsReference. Some more in-depth data that would lead to a more complex model would be, DFG%, On Ball%, PnR%, Hustle Metrics.


