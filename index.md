---
title       : Assigment for Cousera Course Data Products
subtitle    : Slidify Part of Assignment
author      : Thomas Tilli
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]      # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Illustration of the Gamma Distribution

1. The Gamma Distribution
2. Density Plots
3. The Software


--- .class #id 

## The Gamma Distribution

- The gamma is useful for describing a wide range or processes where the data are positively skew. 
- It is a two-parameter distribution, where the parameters are know as shape and rate 


- The density funtion of the damma distribution is defined as:
$$latex
\frac{1}{\beta^{\alpha }\Gamma(\alpha)} x^{\alpha-1} e^{-x/{\beta}}
$$
- The parameter $\alpha$ is the shape parameter and the parameter $\beta$ is the rate parameter.

- Special cases are the exponential ($\alpha=1$) and the chi-squared ($\alpha=\nu/2, \beta=2$)

---

## Density Plots 
- We illustrate the gamma distribution for two parameter sets. First: $\alpha=1, \beta=0.5$ gives an exponential distribution:

![plot of chunk block2](assets/fig/block2-1.png) 

Second: $alpha=1.2, \beta=0.5$ gives a  distribution with humped shape:

![plot of chunk block3](assets/fig/block3-1.png) 


-----


## The Software
- The interactive software can be found here:  http://ttilli.shinyapps.io/assignment .
- You can set the values for $\alpha$ and $\beta$ interactivly and the graph of the gamma distribution is redrawn when you move the silders.

----






