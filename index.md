---
title       : Pitch BMI App
subtitle    : Check your Body-Mass-Index (BMI)!
author      : rtorlow
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Intro

1. This app calculates your BMI.
2. BMI provides the most useful population-level measure of overweight and obesity as it is the same for both sexes and for all ages of adults. 
3. Using the app, you can calculate your BMI independent whether you familiar with metric measures (kilogram / centimeter) or standard measures (feet / pounds).

--- .class #id 

## Key facts

- Worldwide obesity has more than doubled since 1980.
- In 2014, more than 1.9 billion adults, 18 years and older, were overweight. Of these over 600 million were obese.
- 39% of adults aged 18 years and over were overweight in 2014, and 13% were obese.
- Most of the world's population live in countries where overweight and obesity kills more people than underweight.
- 42 million children under the age of 5 were overweight or obese in 2013.
- **Obesity is preventable.**

--- .class #id 


## Calculation

1. Choose the measure type: "standard" or "metric".
  
2. Enter your height and weight.

   *Metric measures: kilogram and centimeter
   
   *Standard measures: feet,inch, and pounds
   
   *Hint it might be necessary to write 5,2 (feet, inches) instead of 5.2.
   
3. Push the submit button.
4. The BMI will be calculated 
    $BMI = \frac{Weight}{Height ^2} = \frac{kg}{m ^2}$
5. The app displays the WHO classification of your BMI.

--- .class #id 

## Example for switching between metric and standard measures


```r
# e.g., switch from pounds to kilogram 
weight <- 150 # pounds

weight*0.45359237
```

```
## [1] 68.03886
```

```r
# result in kilogram
```

--- .class #id 

## Source

More information on BMI you can find at:
http://apps.who.int/bmi/index.jsp?introPage=intro_3.html

--- .class #id
