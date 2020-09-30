<!-- README.md is generated from README.Rmd. Please edit that file -->

![](maizePal.png)

\#\#\#Dear user,

About one year ago, my research took an unexpected turn & I found myself
studying maize. For better or worse, I was here, surrounded by corn & by
people who seemed to be obsessed with it. At first, I didn’t “get it”
because to me, corn was corn was corn. It was yellow and green and
covered vast swaths of the Midwest. Anyone who studies *traditional*
varieties of maize knows, however, that this is not a very generous
archetype. (NOTE: Traditional, or landrace, varieties are crops that
have been bred by farmers through artificial selection, outside of the
formal breeding sector and often associated with a particular
agroecosystem and cultural heritage).

The lab I recently joined ([GEMMAlab](https://www.gemmalab.org/))
studies maize landraces to ask fundamental questions about evolution and
adaptation, knowledge that we can then apply to practical applications
in breeding and conservation. In many ways, our lab’s research exists in
sharp contrast to my initial assessment of the crop. After one season
working in the nursery, I am now convinced that maize can be absolutely
beautiful, far more than I ever gave it credit for. I harvested cobs
with kernels that were shiny and red as rubies, and others that were
pink and purple and looked like they belonged in a candy shop. Further
searching into international collections online revealed cobs from
Oaxaca that were jade green, cobs from Peru that looked like cream pine
cones with purple speckles, and still others that were pitch black then
magenta when milled.

The variety seems endless, and I could wax poetic about how wrong I was
that corn is just yellow and green. Instead, I wrote an R package
inspired by the colors and cobs I’ve seen. This collection of color
palettes is not perfect nor complete, and I will continue to add to it
as I come across more cobs I would like to document and share. In the
meantime, I hope you find this package is useful, colorful, and fun.

Installation
------------

``` r
install.packages("MaizePal")
```

Usage
-----

``` r
library("MaizePal")

# See all palettes
names(maize_palettes)
#>  [1] "Anthocyanins1" "Anthocyanins2" "RubyGold"      "Sweetest"     
#>  [5] "GlassGem"      "Husk"          "HighlandMAGIC" "MaizAzul"     
#>  [9] "JimmyRed"      "FloweringTime" "HopiBlue"      "Painted"      
#> [13] "MaizMorado"    "OaxacaGreen"
```

Palettes
========

### Sweetest

``` r
maize_pal("Sweetest")
```

![](figure/Sweetest-1.png)

### Anthocyanins1

``` r
maize_pal("Anthocyanins1")
```

![](figure/Anthocyanins1-1.png)

### Anthocyanins2

``` r
maize_pal("Anthocyanins2")
```

![](figure/Anthocyanins2-1.png)

### RubyGold

``` r
maize_pal("RubyGold")
```

![](figure/RubyGold-1.png)

### JimmyRed

``` r
maize_pal("JimmyRed")
```

![](figure/JimmyRed-1.png)

### MaizAzul

``` r
maize_pal("MaizAzul")
```

![](figure/MaizAzul-1.png)

### HopiBlue

``` r
maize_pal("HopiBlue")
```

![](figure/HopiBlue-1.png)

### GlassGem

``` r
maize_pal("GlassGem")
```

![](figure/GlassGem-1.png)

### Painted

``` r
maize_pal("Painted")
```

![](figure/Painted-1.png)

### MaizMorado

``` r
maize_pal("MaizMorado")
```

![](figure/MaizMorado-1.png)

### OaxacaGreen

``` r
maize_pal("OaxacaGreen")
```

![](figure/OaxacaGreen-1.png)

### FloweringTime

``` r
maize_pal("FloweringTime")
```

![](figure/FloweringTime-1.png)

### Husk

``` r
maize_pal("Husk")
```

![](figure/Husk-1.png)

### HighlandMAGIC

``` r
maize_pal("HighlandMAGIC")
```

![](figure/HighlandMAGIC-1.png)

``` r
library("ggplot2")
ggplot(mtcars, aes(factor(cyl), fill=factor(gear))) +  geom_bar() +
  scale_fill_manual(values = maize_pal("Anthocyanins1"))
```

![](figure/ggplot1-1.png)
