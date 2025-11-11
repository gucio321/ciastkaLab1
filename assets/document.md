# Prawo Indukcji Faradaya

Opisuje związek między zmiennym polem magnetycznym a powstałym w ten sposób polem elektrycznym.

$$
\epsilon = - \frac{d\Phi_B}{dt} = - \frac{d}{dt} \int_S B \cdot ds
$$

gdzie:
- $\epsilon$ to siła elektromotoryczna (aka napięcie) wyindukowana w obwodzie (w woltach)
- $\Phi_B$ to strumień magnetyczny przez powierzchnię S (w weberach)
- $B$ to natężenie pola magnetycznego (w teslach)
- $S$ to powierzchnia przez którą przechodzi strumień magnetyczny (w metrach kwadratowych)

W postaci różniczkowej $\nabla \times E = - \frac{\partial B}{\partial t}

# Moment magnetyczny dipola

Dipolowy moment magnetyczny to wektor opisujący np. cewkę przez którą płynie prąd.

$$
\mu = N I S
$$

gdzie:
- $\mu$ to moment magnetyczny (w amperometrach razy metr kwadratowy)
- $N$ to liczba zwojów cewki
- $I$ to natężenie prądu (w amperach)
- $S$ to pole powierzchni cewki (w metrach kwadratowych)

```{admonition} Namagnesowanie
nazywamy tak stosunek momentu magnetycznego do objętości próbki.

$$
\vec{M} = \frac{\vec{\mu}}{V}
$$

Gdzie $\mu$ najczęściej wyznaczamy eksperymentalnie.
```

# Podatność magnetyczna

Podatność magnetyczna to wielkość opisująca jak bardzo dany materiał ulega namagnesowaniu pod wpływem zewnętrznego pola magnetycznego.

$$
\Chi = \frac{M}{H}
$$

gdzie:
- $\Chi$ to podatność magnetyczna (bez jednostek)
- $M$ to namagnesowanie (w amperometrach na metr)
- $H$ to natężenie pola magnetycznego (w amperach na metr)

## Typowe wartości $\Chi$

- Dla $\Chi > 0$ substancja jest paramagnetykiem (mniejsze wartości) lub ferromagnetykiem (większe wartości).
- Dla $\Chi < 0$ substancja jest diamagnetykiem (czyli jest odpychana przez pole).
- dla antyferromagnetyków $\chi << 1$ (bardzo mała podatność rzędu $10^{-3}$).

# Magnetyczne przejścia fazowe
Przy wystęþowaniu określonej temperatóry (zależy od materiału) materiały tracą swoją uporządkowaną strukturę magnetyczną i przechodzą w stan paramagnetyczny.
Temperatura Curie dotyczy ferromagnetyków, a temperatura Neéla antyferromagnetyków.
Jest to temperatura graniczna, powyżej któ©ej zachodzi przejście fazowe.
