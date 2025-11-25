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


https://liascript.github.io/LiveEditor/?/edit/XARqDa105TNmxurx8ZWFVlhR 

https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md#1



## Überschriften

Überschriften werden durch (#) gekennzeichnet


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

```
kursiv: *italic*

fett: **bold**

kursiv und fett: ***bold and italic***

durchgestrichen: ~strike~

```

### Listen

Einfache Aufzählungen mit * zu Beginn der Zeile


```
* Apfel

* Birne

* Kiwi

```


* Apfel

* Birne

* Kiwi

 oder mit Nummern

```
1. Apfel
2. Birne

    * Helene
3. Kiwi

```


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

mit html - wird allerdings in Markdown nicht angezeigt (bei LiaScript jedoch schon)

```
<span style="color:red">
Dieser Text ist rot
</span>
```

<span style="color:red">
Dieser Text ist rot
</span>



### Textgröße

```
Text in  <font size=7>groß</font> 

Text in etwas <font size=+1>größer</font>

Text in etwas <font size=-2>kleiner</font>

```

Text in  <font size=7>groß</font> 

Text in etwas <font size=+1>größer</font>

Text in etwas <font size=-2>kleiner</font>



## Einfügen von Inhalten

### Einfügen von Bildern

![alt-text](path)

Gallerie: 
![img1](url) ![img2](url) ![img3](url)
![img4](url)
![img5](url)

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
