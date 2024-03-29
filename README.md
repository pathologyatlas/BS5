

```
r language BS5, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis lenfositik gastrit , echo = (language == "TR")
## BS5 - lenfositik gastrit {#sec-BS5 }
```


```
asis lymphocytic gastritis , echo = (language == "EN")
## BS5 - lymphocytic gastritis {#sec-BS5 }
```






```
r BS5 screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS5-HE_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS5/HE.html",
  file = "./screenshots/BS5-HE_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link







```
asis, echo = (language == "TR")

**lenfositik gastrit**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS5-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS5/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS5/HE.html)
```

```
asis, echo = (language == "EN")

**lymphocytic gastritis**

[![Click for Full Screen WSI](./screenshots/BS5-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS5/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS5/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS5/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS5/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

lenfositik gastrit

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

lymphocytic gastritis

:::

```









:::::

<hr>