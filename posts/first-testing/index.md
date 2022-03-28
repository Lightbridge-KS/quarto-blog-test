---
title: "Testing Things"
author: "Harlow Malloc"
date: "3/28/2022"
categories: [test]
image: "featured.jpg"
---

## Text

Some text, **bold,** *italics,* `code`

```r
print("hello word")
```

## Math

$$
\sigma = \sqrt{ \frac{1}{N} \sum_{i=1}^N (x_i -\mu)^2}
$$

## FootNotes

Footnotes use standard Pandoc markdown notation, for example [^1]. The number of the footnote will be automatically generated.

[^1]: This will become a hover-able footnote

## But first, panelsets with R code chunks

{{< panelset class="greetings" >}}
{{< panel name="Panel 1" >}}

Hello

{{< /panel >}}
{{< panel name="Panel 2" >}}


World

{{< /panel >}}
{{< /panelset  >}}


