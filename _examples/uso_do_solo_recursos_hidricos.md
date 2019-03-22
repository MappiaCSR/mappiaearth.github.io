---
layout: example
title: Hydric resources influenced by Land use
summary: Show multiple simple maps together.
categories: [scale, startopened, hidestylechooser, enablequeries, visiblelayers]
featured-img: uso_do_solo_recursos_hidricos
type: Example
map-link: lang=eng&map=&queryid=78&extent=&tools=helpintro,layerchooser,zoomextent,customzoom,getfeature,hovershowlegend&options=scale,startopened,hidestylechooser,enablequeries&visiblelayers=1000
api: 
    - key: Sankey
    - key: Query
      tags: ['setQueryGlobalProperties']
    - key: LayerInternal
      tags: ['setCalculateLegend', 'changeLayers']
    - key: AsyncLoader
    - key: Timeline
    - key: Combobox
    - key: ConfigUrl
      tags: ['options', 'tools', 'visiblelayers']
    - key: Inputmanager
    - key: Highcharts
---
Show multiple simple maps together.