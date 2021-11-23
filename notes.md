# new
## raw
- Frequency 
    - from raw
    - probably choropleth but depends on data
## calculated
- No. of stations/stops (from a 15m walk, % of population)
    - calculated; Bar graph
- distance/walking time to nearest station/stop
    - calculated; raster
- Centrality analysis of the roads & trains & bus
    - calculated; line
    - Compare histograms, means, s.d. 
- Travel time or distance to city centre
    - likely calculated
    - from where? from individual buses? point data if yes
        - maybe to the point with the highest centrality

## S0966692321001848.pdf
### transit design
- number of routes;
- number of stops;
- average number of stops per route;
- average route length;
- average distance between stops;
### transit operation
- median bus speed;
- total daily bus trips;
- total daily vehicle-km (vkm).

### topological
- number of links
- number of nodes
- diameter of the network
- density
- travesty

### other properties of the network
- efficiency
- avg betweenness
- avg closeness
- max component size
- average path length

- clusters and modularity

# rode2017.pdf
- urban form (map of urban areas and railway transport)
- **modal share**

# old
10.1016@j.trd.2020.102387.pdf
- to-bus
    - number of bus stops within 500m
- by-bus
    - travel time to (old/new) city center
    - bus frequency

10.1061@ASCEUP.1943-5444.0000516.pdf
- on off ridership in every metro station
- betweenness (nx.betweenness_centrality)
- straightness (momepy.straightness_centrality)
    - https://docs.momepy.org/en/stable/generated/momepy.straightness_centrality.html
- closeness (nx.closeness_centrality)
    - used in practical

82011b6fac6b0da8038b3653d9604a92.pdf
- Number of metro stations within .5 miles
- Number of bus stops within .5 miles
- Number of available sharing bikes within 300 m

