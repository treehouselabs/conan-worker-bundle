Getting started
===============

Example cms.xml:

```xml

<!-- add this to you menu -->
<item action="workers"/>

<!-- Queue -->
<action type="custom" class="TreeHouse\ConanWorkerBundle\Action\Workers" title="workers" slug="workers"/>
```

Config:

```yml
# ConanBundle
fm_conan:
  ...
  stylesheets:
    - /bundles/treehouseconanstatistico/css/metricsgraphics.css
    - /bundles/treehouseconanworker/css/workers.css
  javascripts:
    - https://cdnjs.cloudflare.com/ajax/libs/d3/3.5.0/d3.js
    - /bundles/treehouseconanstatistico/js/metricsgraphics.js
    - /bundles/treehouseconanstatistico/js/statistico.js
```