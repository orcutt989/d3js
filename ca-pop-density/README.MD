# ca-pop-density
Original, unprojected cb_2014_06_tract_500k.shp from U.S. Census. Yuck, let's project it with Albers.
<img src="https://raw.githubusercontent.com/orcutt989/d3js/master/ca-pop-density/png/ca-original.png" width="480" height="480">

Project to California Albers.

![](https://raw.githubusercontent.com/orcutt989/d3js/master/ca-pop-density/png/ca-albers.png)

Join census pop data to geometry and apply viridis color scheme with sequential scale.
![](https://raw.githubusercontent.com/orcutt989/d3js/master/ca-pop-density/png/ca-albers-color.png)

Square Root scale
![](https://raw.githubusercontent.com/orcutt989/d3js/master/ca-pop-density/png/ca-albers-sqrt.png)

Maybe log scale?
![](https://raw.githubusercontent.com/orcutt989/d3js/master/ca-pop-density/png/ca-albers-log.png)

How about quantile scale? Quantile showst the most variation in populated areas, but we need a new color scheme.
![](https://raw.githubusercontent.com/orcutt989/d3js/master/ca-pop-density/png/ca-albers-quantile.png)

Looks good, let's add the census tracts.
![](https://raw.githubusercontent.com/orcutt989/d3js/master/ca-pop-density/png/ca-tracts-threshold.png)

Bingo. Looks good. Now we just need a scale
![ca](https://raw.githubusercontent.com/orcutt989/d3js/master/ca-pop-density/png/ca.png)
