# LeafletFleetMap
Visualize spatial data, interactively with R  
`{leaflet}` `{tidyverse}` `{htmltools}` `{Shiny}`  

## The goal
The goal is to manage the fleet using visual components, furthermore, this tool is easy to use, and interactive.  

## UI
**Layers**  
Based on Client's needs, I made three layers, to be shown on the map.
* `Units`: Colored Markers to visualize the activity of each unit on the map
* `Groups of units`: Clusters of units, easy way to group the units geographicaly.
* `Inactive units`: Clusters of inactive units, useful to expose in just few seconds the inactive units for more than a certain time (customised)
