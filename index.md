---
title: "Szkolenie Markdown"
permalink: /
layout: default
---


# Hello world!

Whats up
Cos dalej

*Krzywy tekst*  
**Pogrubiony tekst**  
_krzywy tekst inaczej_  
**_krzywy gruby tekst_**  
***krzywy gruby tekst inaczej***

## Punkty i listy

- Punkt 1
- Punkt 2
* Punkt 3
* Punkt 4 _**pogrubiony**_

1. Pierwszy punkt listy  
Witam cos tam cos tam  
cos cos  
cos cos jeszcze
2. Witam jeszcze raz
3. 
4. 
5. 

:car:

:cat:

_Adam Mickiewicz_ powiedział kiedyś 
>**Litwo ojczyzno moja**
>
>Ty jesteś jak zdrowie
> * Ile cię trzeba cenić
> - Ten tylko się dowie
> 1. Co cię stracił

[^1]: My_reference.

[zmienna1]: https://www.google.com

Here is a footnote[^1]. With some additional text after it.

[linkacz](zmienna1)

![zdjecie jakies](https://leopardus.pl/data/include/img/news/1689082690.jpg)

2^3^

$x+12$ zapis matematyczny x+12

$$\int_{-\infty}^\infty e^{-x^2} = \sqrt{\pi}$$

Kod jakiś `int main()` tutaj napisalem

```python
#Block code
for i in range(1,10):
    Do_something()
```
```
#zwykly blok kodowy bez koloru
```

```mermaid
  graph LR;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```

```mermaid
quadrantChart
    title Reach and engagement of campaigns
    x-axis Low Reach --> High Reach
    y-axis Low Engagement --> High Engagement
    quadrant-1 We should expand
    quadrant-2 Need to promote
    quadrant-3 Re-evaluate
    quadrant-4 May be improved
    Campaign A: [0.3, 0.6]
    Campaign B: [0.45, 0.23]
    Campaign C: [0.57, 0.69]
    Campaign D: [0.78, 0.34]
    Campaign E: [0.40, 0.34]
    Campaign F: [0.35, 0.78]
```

```mermaid
flowchart TD
    A[Christmas] -->|Get money| B(Go shopping)
    B --> C{Let me think}
    C -->|One| D[Laptop]
    C -->|Two| E[iPhone]
    C -->|Three| F[fa:fa-car Car]
```

```mermaid
journey
    title My working day
    section Go to work
      Make tea: 5: Me, Ania, Basia
      Go upstairs: 3: Me
      Do work: 10: Me, Cat
    section Go home
      Go downstairs: 5: Me
      Sit down: 3: Me
```

```mermaid
    xychart-beta
    title "Sales Revenue"
    x-axis [jan, feb, mar, apr, may, jun, jul, aug, sep, oct, nov, dec]
    y-axis "Revenue (in $)" 4000 --> 11000
    bar [5000, 6000, 7500, 8200, 9500, 10500, 11000, 10200, 9200, 8500, 7000, 6000]
    line [5000, 6000, 7500, 8200, 9500, 10500, 11000, 10200, 9200, 8500, 7000, 6000]
```

