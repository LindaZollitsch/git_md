<!--

author:   Linda Zollitsch
email:    zollitsch@ub.uni-kiel.de
version:  0.1.0
language: de
narrator: UK English Female

icon:     images/Logo_cau-norm-de-lilagrey-rgb-0720_2022.png

link: https://raw.githubusercontent.com/RDM4CAU/Intro-to-RDM/refs/heads/main/cau-style.css

comment:  This document provides a brief introduction to Markdown.

-->


# Markdown

hier können Basics für Markdown über einen Editor genutzt (und gecheated) werden

https://liascript.github.io/LiveEditor/?/edit/XARqDa105TNmxurx8ZWFVlhR


## Überschriften

Überschriften werden durch (#) gekennzeichnet und können bis zu 6 Stufen haben:


```
 # H1      
 ## H2     
 ### H3    
 #### H4   
 ##### H5  
 ###### H6  

```



## Text formatieren

alles, was nicht mit Markdown geht, kann mit html ausgezeichnet werden

https://web.stanford.edu/group/csp/cs21/htmlcheatsheet.pdf



### Schriftformatierung

{{1-2}}
************
```
kursiv: *italic*

fett: **bold**

kursiv und fett: ***bold and italic***

durchgestrichen: ~strike~
```
************

{{2}}
************

kursiv: *italic*

fett: **bold**

kursiv und fett: ***bold and italic***

durchgestrichen: ~strike~

************

### Listen

Einfache Aufzählungen mit * zu Beginn der Zeile

{{1-2}}
************

```
* Apfel

* Birne

* Kiwi

```
************

{{2-3}}
************

* Apfel

* Birne

* Kiwi

************

{{3-4}}
************

```
1. Apfel
2. Birne

    * Helene
1. Kiwi


```
************

{{4}}
************

1. Apfel
2. Birne

    * Helene
3. Kiwi

************


### Tabellen

| Spalte 1  | Spalte 2  | Spalte 3  |
| --------- | :-------: | --------: |
| Text 1    |   Text 1  |    Text 1 |
| Text 2    |   Text 2  |    Text 2 |


### Textfarbe

{{1-3}}
************
mit html - wird allerdings in Markdown nicht angezeigt (bei LiaScript jedoch schon)

```
<span style="color:red">
Dieser Text ist rot
</span>
```
************

{{2-3}}
************
<span style="color:red">
Dieser Text ist rot
</span>

************

{{3}}
************

oder alternativ für LiaScript auch so möglich

```
Text in dunkelblau <!-- style="color: darkblue" -->
```

Text in dunkelblau <!-- style="color: darkblue" -->

************

### Textgröße

```
Text in  <font size=7>groß</font> 

Text in etwas <font size=+3>größer</font>

Text in etwas <font size=-2>kleiner</font>
```

Text in  <font size=7>groß</font> 

Text in etwas <font size=+3>größer</font>

Text in etwas <font size=-2>kleiner</font>


## Einfügen von Inhalten

es können verschiedene Inhalte eingebunden werden.

### Einfügen von Bildern

{{1-2}}
************
```
![alt-text](path)
```

************

{{2}}
************
```
Galerie: 
![img1](url) ![img2](url) ![img3](url)
```
************


#### Bildgröße und Position

{{1-3}}
************

```
![FDM-Lebenszyklus](/images/img_fdm-zyklus_2022_CM.jpg)
```
************

{{2-3}}
************
![FDM-Lebenszyklus](/images/img_fdm-zyklus_2022_CM.jpg)

************

{{3-5}}
************
```
![FDM-Lebenszyklus](/images/img_fdm-zyklus_2022_CM.jpg) <!-- width="150px" -->
```
************

{{4-5}}
************
![FDM-Lebenszyklus](/images/img_fdm-zyklus_2022_CM.jpg) <!-- width="150px" -->

************

{{5}}
************
```
![FDM-Lebenszyklus](/images/img_fdm-zyklus_2022_CM.jpg) <!-- width="350px" align="right" -->
```
************

{{6}}
************
![FDM-Lebenszyklus](/images/img_fdm-zyklus_2022_CM.jpg) <!-- width="350px" align="right" -->

************

### Einfügen von Audio:

```
?[alt-text](url)
```

### Einfügen von Videos

```
!?[alt-text](path or url)
```

### Einfügen von Links

{{1-2}}
************

```
https://www.google.com

[inline-style link](https://www.google.com)

[inline-style link with title](https://www.google.com "Google's Homepage")

[relative reference to a repository file](../blob/master/LICENSE)

```
************

{{2}}
************

https://www.google.com

[inline-style link](https://www.google.com)

[inline-style link with title](https://www.google.com "Google's Homepage")

[relative reference to a repository file](../blob/master/LICENSE)

************



# genutze Literatur / Vorlagen

https://github.com/adam-p/markdown-here/wiki/markdown-cheatsheet#headers

https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md#1
