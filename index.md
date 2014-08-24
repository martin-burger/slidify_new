---
title       : Martin's Price Reduction App
subtitle    : 
author      : 
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Problem

I want to know how price reductions are influencing my sales.

---
## Proposed Solution

Calculating a Model which learns the effects of different attributes
including price variaties.

---
## Submitted Solution

An easy example, through manipulating the input variable
price the result changes.


```r
40 * 1
```

```
## [1] 40
```

```r
40 * 1.2
```

```
## [1] 48
```
1 representing the normal price, 1.2 represents a price reduction of 20 Percent.
A linear model would learn the reduction (as linear SVM's do) through regression which 
them makes simulations possible. (Also in context with other variables)

---
## Thanks and feedback location
I hope this helps 
Thanks you for your time.
