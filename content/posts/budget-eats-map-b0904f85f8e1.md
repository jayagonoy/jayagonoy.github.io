---
title: "Budget Eats Map?"
date: 2016-10-31
categories: [Food]
slug: /budget-eats-map-b0904f85f8e1
---

{{< gist jayagonoy b7adf411676829356fe8796e8b47dba1 MallOfAsia.geojson>}}


Hi guys! First of all, I don’t have much updates to share with you at the moment, but I would like to introduce you to a side-project that I did a long time ago. I’ll make this quick for everyone, I promise.

The map above was rendered over GitHub gists and uses the GeoJSON format, as follows:

```
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {
        "marker-color": "#7e7e7e",
        "marker-size": "medium",
        "marker-symbol": "star-stroked",
        "name": "KFC",
        "offering": "Flavor Shots a la carte, Php50"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -239.01712238788605,
          14.534527915006434
        ]
      }
    }
  ]
}
```

The list contains the meals that cosplayers can afford, and the plotting was done manually. If you know a place inside Mall of Asia (or in places where there are cosplay events), let me know on Twitter (@jayagonoy — photos with the price do a big help on this) so we can track them down.

Update (July 14, 2025): GitHub Gist has an issue with data not parsing into the map. Copy the raw and post it on GeoJSON.io to see the details.
