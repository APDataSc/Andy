---
title       : Estadística Aplicada a las Ciencias Sociales - Introducción al Uso de R
#subtitle    : ---
author      : Ing. Miguel Flores Ph.D
#job         : ---
framework   : io2012      # {io2012, html5slides, shower, dzslides, revealjs, deckjs, Landslide...}
#revealjs   :       {theme: moon, transition: concav}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap]            # {mathjax, quiz, bootstrap}
ext_widgets : {rCharts: [libraries/nvd3, libraries/dygraphs]}
mode        : selfcontained # {selfcontained, standalone, draft}
knit        : slidify::knit2slides
#logo        : logo.png
---



<style>
.title-slide {
  background-color: #B0E2FF; /* #EDE0CF; ; #CA9F9D*/
  background-image:url(assets/img/cec_cover1.png);
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
  background-position: center center;
  }

.title-slide hgroup {
  position: absolute;
  width: auto;
  height: auto;
  right: 30px;
  bottom: 40px;
  text-align: right;
}

.title-slide hgroup > h1, 
.title-slide hgroup > h2 {
  margin-top: -1em;
  color: white;
  font-size: 40px;
},
.title-slide hgroup > p {
  left: 10px;
  color: white;
  line-height: 0.8em;
}
</style>

## IPC Estratificado

### ¿Qué es el Índice de Precios al Consumidor Estratificado?

El Índice de Precios al Consumidor Estratificado, es una medida de variación del nivel general de precios de un conjunto representativo de bienes y servicios de consumo, adquiridos por los hogares clasificados en distintos segmentos socioeconómicos de la población. 

### Propósito:

Contribuye a una mejor representatividad socioeconómica frente a la heterogeneidad de precios a los que se enfrentan los hogares de distintas realidades. 

### Período base:

Diciembre 2015=100


---

## Matriz 

### ¿Qué es el Índice de Precios al Consumidor Estratificado?
Hola a todos

### Este es el ejemplo de código en R:


```r
(mtx <- matrix (1:12, nrow=3, ncol=4, byrow=FALSE))
```

```
##      [,1] [,2] [,3] [,4]
## [1,]    1    4    7   10
## [2,]    2    5    8   11
## [3,]    3    6    9   12
```

Toda la presentación fue realizada en <code>slidify</code> R package
</div>

--- {class: class1, bg: gray, id: id1}

## Gráfico 1


---

## Gráfico 2


---

## Gráfico 3


---

## Gráfico 4


---

## Gráfico 5


--- &slide_1 #custbg  

<style>
#custbg {
  background-image:url(assets/img/cec_cover2.png); 
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
}
</style>
