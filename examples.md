---
marp: true
theme: custom
paginate: true
size: 16:9
math: mathjax
footer: (c) by me
---
<!-- _class: title -->
<!-- _footer: '' -->
<!-- _paginate: false -->
# Using Marpit 
## ~~A tutorial~~ | Prof. Dr. Felix Zeidler

--- 
## Agenda

### Die folgenden Dinge werden in dieser Präsentation enthalten sein
1️⃣ Art der Hervorhebung von Text

2️⃣ Kapitelslides

3️⃣ Slides mit zwei Spalten

4️⃣ Tabellen und zentrieren von Objekten

5️⃣ Fußnoten und Quellenangaben
<br></br>

<div align='center'>
Auf geht's 😆
</div>

---
<!-- _class: chapter -->
<!-- _footer: '' -->
<!-- _paginate: false -->
# 1️⃣ Hervorhebung von Text 

---
# 1️⃣ Text 
## Wir können reguläre Markdown-Syntax nutzen, um Text hervorzuheben


Hier einige Beispiel:

- ein normaler Satz

- ein Satz mit einem **fetten** Wort

- ein Satz mit einem *kursiven* Wort

- ein Satz mit einem `code block`

- ein Satz mit einem ~~blauen Hintergrund~~

---
# 1️⃣ Text 
## Natürlich kann auch ein ganzer Block hervorgehoben werden...

> **Beispiel 1**: 
> Hier folgt ein langes Beispiel

<br></br>

### Das geht aber natürlich auch mit Code!

```python
# ein Kommentar

a = 13
b = 14
c = a * b
print(c)

>> 182
```

---
# 1️⃣ Text 
## Auch $Latex$ ist natürlich kein Problem

### Hier eine sehr komplexe Formel: 

$$
\begin{align*}
S(\omega) 
&= \frac{\alpha g^2}{\omega^5} e^{[ -0.74\bigl\{\frac{\omega U_\omega 19.5}{g}\bigr\}^{\!-4}\,]} \\
&= \frac{\alpha g^2}{\omega^5} \exp\Bigl[ -0.74\Bigl\{\frac{\omega U_\omega 19.5}{g}\Bigr\}^{\!-4}\,\Bigr] 
\end{align*}
$$
<br></br>

### Noch besser vielleicht eingebettet in einen Block?

> **Formel:** eine sehr komplexe Formel!
> $$\begin{align*}
S(\omega) 
&= \frac{\alpha g^2}{\omega^5} e^{[ -0.74\bigl\{\frac{\omega U_\omega 19.5}{g}\bigr\}^{\!-4}\,]} \\
&= \frac{\alpha g^2}{\omega^5} \exp\Bigl[ -0.74\Bigl\{\frac{\omega U_\omega 19.5}{g}\Bigr\}^{\!-4}\,\Bigr] \tag{1}
\end{align*} $$

---
<!-- _class: chapter -->
<!-- _footer: '' -->
<!-- _paginate: false -->
# Slides mit zwei Spalten

---
<!-- _footer: '' -->

![bg fit right](./assets/distribution.png)

<br></br>
#### Kommentar

Folgende Gründe sprechen dafür, dass es sich hier um eine Normalverteilung ($\approx N(\mu, \sigma)$) handelt. 

1. ....

2. ....

---
<!-- _class: chapter -->
<!-- _footer: '' -->
<!-- _paginate: false -->
# Zentrieren von Objekten

---
# Zentrierungen 
## Hier wird ein Text und eine Tabelle zentriert!
<div align='center'>
Dies ist ein zentrierter Text
</div>

<br></br>





<div align='center'>

| Header 1       	| Header 2       	|
|----------------	|----------------	|
| True negative  	| False negative 	|
| False negative 	| True positive  	|

</div>
<br></br>

Man kann auch sehr gut Fußnoten hinzufügen<sup>[1]</sup>. In diesem Fall muss man dann im Appendix ein Literaturverzeichnis manuell hinzufügen. 

Gut klappt allerings auch das hinzufügen von Quelle<sup>*</sup>

###### * die Information habe ich [hier](https://www.spiegel.de) gefunden

---

<!-- _class: lead -->
<!-- _backgroundColor: pink -->
<!-- _footer: "" -->
<!-- _paginate: false -->

##### Thanks for listening <!-- fit -->