# Chart type Report : Cartogram

## Definition
A cartogram is a map in which some thematic mapping variable – such as travel time, population, or Gross National Product – is substituted for land area or distance. The geometry or space of the map is distorted in order to convey the information of this alternate variable. They are primarily used to display emphasis and for analysis as nomographs.
Two common types of cartograms are area and distance cartograms. Cartograms have a fairly long history, with examples from the mid-1800s. 
![](https://wiki2.org/en/Cartogram#/media/File:Cartlinearlarge.png)
 
## Applications and Types

### The Density-Equalizing Cartogram
Density-equalizing (contiguous) cartograms are your typical cartograms. In density-equalizing cartograms, map features bulge out a specific variable. Even though each feature becomes distorted, it remains connected during its creation.

For example, in this density-equalizing cartogram, we use population as the main driver to exaggerate area. In QGIS, you can accomplish this with the QGIS Cartogram Plugin.

![](http://gisgeography.com/wp-content/uploads/2016/09/Density-Equalizing-Cartograms.png)
As we can see, it’s easy to get information at only a glance. Which states stick out like a sore thumb in this population map? Straightaway you can see that a high proportion of population live in California and New York. While states like Montana and North Dakota are dwarfed in it and shrink to bite-size proportions.

As objects shrink and grow in density-equalizing cartograms, cartographers have to consider resizing polygons appropriately while maintain their true geometry.

### The Non-Contiguous Cartogram

Features in non-contiguous cartograms don’t have to stay connected. Objects can freely move from adjacent polygons and be resized appropriately. Because of this free movement, shape remains in tact for non-contiguous cartograms such as in this population map of the United States below created in ArcGIS.


![](http://gisgeography.com/wp-content/uploads/2016/09/Non-Contiguous-Cartogram-2.png)

Again, the geometry and space of the map gets distorted to convey information of the population variable. For example, the state of California has grown significantly because of their large population.

The main difference between density-equalizing cartograms is that it moves each feature’s centroid to avoid any overlapping.

Although overlaps sometimes exist in non-contiguous cartograms, they can be more difficult to differentiate between resized polygons.


### The Dorling Cartogram
The Dorling Cartogram (named after professor Danny Dorling) uses shapes like circles and rectangles to depict area. These types of cartograms make it easy to recognize patterns. In the example below, we used GeoDa software to generate the Dorling cartogram.

![](http://gisgeography.com/wp-content/uploads/2016/09/Dorling-Cartogram.png)
As you can see, states are substituted with appropriately-sized circles to represent clusters of population in the United States. Without a doubt, it is highly effective at conveying information and patterns.

## Sources
<ul>
 <li>
<a href="https://fr.wikipedia.org/wiki/Diagramme_circulaire">Page Wikipedia</a>
 </li>
  <li>
<a href="https://www.google.fr/search?q=pie+chart+celebres&client=firefox-b&dcr=0&source=lnms&tbm=isch&sa=X&ved=0ahUKEwifvJDv-t_YAhUHXBQKHfmbD-8Q_AUICigB&biw=1366&bih=656#imgrc=DfYR5rS2rH8F2M:">Requête Google Pie chart célèbres</a>
 </li>

</ul>
