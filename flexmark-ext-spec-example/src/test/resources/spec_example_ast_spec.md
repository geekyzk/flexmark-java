---
title: SpecExample Extension Spec
author: 
version: 
date: '2016-06-06'
license: '[CC-BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/)'
...

---

## SpecExample  

Converts spec example text to SpecExample nodes.  

Plain and simple

```````````````````````````````` example SpecExample: 1
```````````````` example
````````````````
.
.
Document[0, 42]
  SpecExampleBlock[0, 41] openingMarker:[0, 16] exampleKeyword:[17, 24] optionsOpeningMarker:[25, 25] closingMarker:[25, 41]
````````````````````````````````


Plain and simple with nbsp for space on first line

```````````````````````````````` example SpecExample: 2
```````````````` example
````````````````
.
.
Document[0, 42]
  SpecExampleBlock[0, 41] openingMarker:[0, 16] exampleKeyword:[17, 24] optionsOpeningMarker:[25, 25] closingMarker:[25, 41]
````````````````````````````````


Plain and simple

```````````````````````````````` example SpecExample: 3
```````````````` example
…
````````````````
.
.
Document[0, 44]
  SpecExampleBlock[0, 43] openingMarker:[0, 16] exampleKeyword:[17, 24] optionsOpeningMarker:[25, 25] closingMarker:[27, 43]
````````````````````````````````


Plain and simple

```````````````````````````````` example SpecExample: 4
```````````````` example
…
…
````````````````
.
.
Document[0, 46]
  SpecExampleBlock[0, 45] openingMarker:[0, 16] exampleKeyword:[17, 24] optionsOpeningMarker:[25, 25] closingMarker:[29, 45]
````````````````````````````````


```````````````````````````````` example SpecExample: 5
```````````````` example
…
…
…
````````````````
.
.
Document[0, 48]
  SpecExampleBlock[0, 47] openingMarker:[0, 16] exampleKeyword:[17, 24] optionsOpeningMarker:[25, 25] closingMarker:[31, 47]
````````````````````````````````

