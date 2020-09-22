### Viewer/Content Engagement

The relationships between viewers and the content that they consume can be complex and cursory analysis of what viewers are watching will often fail to reveal the more intricate communities and sub-communities of viewers that exist at various levels that often cross traditional age/gender or genre based views of those relationships.

We might consider viewer and content communites as following a social network pattern; similiar to graph views of friendship cliques or professional relationships. In the case of content and viewing, there are various approaches to graphs  that could capture these relationships:

#### Viewer-Centric

In this approach, the viewers are nodes in the graph and the content that they engage with are the edges betwen those viewers.

#### Content-Centric

Program content are nodes and the viewers that engage with those nodes are edges between them.

#### Combined 

Both the viewers as nodes and content as nodes approaches are problematic because of the large number of many-to-many relationships between viewers and content.  Representing both viewers and content as nodes results in a more prgramatic network graph.

![Combined Network](/img/combined_network.png)

### Viewing Communities

Once a graph is created, communities of viewers and the content that they watch can be extracted.  But because of the distriubtion of program engagement between the most popular programs that a larger portion of viewers have some engagement with, and the less popular programs with smaller viewing communities; recursion can be used to break down the larger communities in to sub-communities. 

#### Use Cases
The resulting hierarchical 'taxonomy' of content and viewers is useful for analysis and understanding the intricacies of the content/viewing domain. 

There are several possible use cases for this network graph / community extraction approach:

##### Detailed Genres

By examining the vieiwing within general genres and contrasting the demographic charactersistic of the viewers between those groups, we can begin to give more detailed genre labels based on the real-world separation between revealed by the viewers' actual preferences.

Examples include the separation within genres like "reality" programming between documentary series like _EXPEDITION UNKNOWN_ (occupational/survival) and which can be demographically related and share viewers, but have distinctly different core viewers further down in the hierarchy.

![Combined Network](/img/genre_distinctions.png)

Additionally, if new sub-genres appear to be emerging over time they can be identified in the taxonomy as it changes over time.

##### Effective Advertising or Tune-in Promotions Without Direct Targeting

As more privacy restrictions make direct-targeting of viewers mor problematic, a detailed taxonomy of content viewing and and training on the attributes of samples of their viewers allow us to effectively reach the right consumers without targeting them directly.  For example, viewers in specific communites will have a much higher probability to drive a luxury vehical than other communities.

![Combined Network](/img/luxury_car.png)

##### Informing Content Acquisition and Optimization of Content Scheduling

The detaliled taxonomy of viewers and content communities allows for more informed decisions about content acquisition by identifying the specific types of programming that sub-groups of viewers are engaging with. This can be combined with attributions of the viewers that point to being more or less inclined to subscribe to any or more streaming services. Then solutions like __linear programming optimization__ can be applied to content schedule to maximize the engagement of over time to retain and increase subscriptions.







