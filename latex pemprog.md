1. HTML
2. CSS
3. Javascript

- html
- css
- javascript

1. italic
2. bold
3. strikethrough

_Italic_
**BOLd**
 
~~strikethrough~~

_**bold italic**_

## Penurunan persamaan gelombang dalam bentuk diferensial

```math
y=A \sin (\omega t - kx )
```

A = amplitudo gelombang

$\omega$ = frekuensi sudut
($\omega = 2\pi/f$)

### turunan pertama terhadap waktu 

```math 
\frac{\partial y}{\partial t}= A
\cos {\omega t-kx}\cdot\omega
\tag {1}
```
---

turunan kedua terhadap waktu:

```math
\frac{\partial^2y}{\partial t^2}= -A \sin(\omega t-kx)\cdot\omega^2 
\tag {2}
```
---

turunan terhadap posisi x:
```math
\frac{\partial y}{\partial x}= A \cos (\omega t - kx) \cdot - k
\tag {3}
```
---
turunan kedua terhadap posisi x:
```math
\frac{\partial ^2y}{\partial ^2x}= -A \sin(\omega t - kx)\cdot\ k^2
\tag {4}
```
---
turunan:
```math
\frac {\frac {\partial ^2y}{\partial ^2t}} {\frac {\partial ^2y}{\partial ^2x}} = \frac {-\omega ^2y}{- k ^2y} = \frac {\omega}{k} \rightarrow \frac {1}{v^2} \frac {d^y}{d^t} = \frac {d^2y}{d^2x}
\tag {5}
```
---