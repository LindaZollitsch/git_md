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

# git




# Markdown

## Überschriften

Überschriften werden durch (#) gekennzeichnet

{{1-2}}
************

```
 # H1      
 ## H2     
 ### H3    
 #### H4   
 ##### H5  
 ###### H6  

```

************

{{2}}
************

# H1
## H2
### H3
#### H4
##### H5
###### H6

************

## Text formatieren


### Schriftformatierung


kursiv: der Begriff italic mit je einem Sternchen * * links und rechts → *italic*

fett: der Begriff bold mit je zwei Sternchen ** ** links und rechts → **bold**

kursiv und fett: die Begriffe bold and italic ausgeschrieben mit je drei Sternchen ***  *** links und rechts → ***bold and italic***

durchgestrichen: der Begriff strike mit je ~ ~ links und rechts → ~strike~


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
1. Kiwi

************


### Tabellen


| Column 1 | Column 2 | Column 3 |
| -------- | :------: | -------: |
| Text     |   Text   |     Text |


### Textfarbe



## Einfügen von Inhalten

### Einfügen von Bildern

![alt-text](path)

Gallerie: 
![img1](url) ![img2](url) ![img3](url)
![img4](url)
![img5](url)


#### Bildgröße und Position

![FDM-Lebenszyklus](/images/img_fdm-zyklus_2022_CM.jpg)

{{1-3}}
************
```
![FDM-Lebenszyklus](/images/img_fdm-zyklus_2022_CM.jpg) <!-- width="350px" -->
```
************

{{2-3}}
************
![FDM-Lebenszyklus](/images/img_fdm-zyklus_2022_CM.jpg) <!-- width="350px" -->

************

{{3-5}}
************
```
![FDM-Lebenszyklus](/images/img_fdm-zyklus_2022_CM.jpg) <!-- width="350px" align="right" -->
```
************

{{4-5}}
************
![FDM-Lebenszyklus](/images/img_fdm-zyklus_2022_CM.jpg) <!-- width="350px" align="right" -->

************

### Einfügen von Audio:

?[alt-text](url)

### Einfügen von Videos

!?[alt-text](path or url)

### Einfügen von Links

```
[inline-style link](https://www.google.com)

[inline-style link with title](https://www.google.com "Google's Homepage")

[relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com>.

```
[inline-style link](https://www.google.com)

[inline-style link with title](https://www.google.com "Google's Homepage")

[relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com>.





# genutze Literatur / Vorlagen

https://github.com/adam-p/markdown-here/wiki/markdown-cheatsheet#headers

https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md#1
