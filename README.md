# XYZ tile bounds generator

It is often helpful to know where the bounds of XYZ (also known as [slippy map](https://wiki.openstreetmap.org/wiki/Slippy_map_tilenames)) tiles are.
There are tools to generate those tile bounds (ie MapBox's [mercantile](https://github.com/mapbox/mercantile)). This plugin enables users to generate those bounds without leaving QGIS. After specifying which tile we want, we can add a polygon covering that tile:

![](https://i.imgur.com/tNA0dhD.png)

[This](https://zabop.github.io/tilecalc/3857.html) can be used to check whether the resulting polygon is at the correct location: [it is](https://lp-tools.toolforge.org/misc/bbox.html?sw=58.97266715450148,5.668945312499955&ne=58.99531118795089,5.624999999999965).
