[:arrow_left: Magnetismus](../kapitola_1/podkapitola_3.md)

[:arrow_right: Zapojení odporů](./podkapitola_2.md)





# Zákonitosti a vztahy - Základní zákony
Druhá kapitola se zaměřuje na základní fyzikální vztahy a zákonitosti, které vysvětlují interakce mezi fyzikálními veličinami, jejich chováním a dalšími principy elektrotechniky a magnetismu. V rámci této podkapitoly se konkrétně soustředíme na základní zákony elektrotechniky a magnetismu.





## Obsah kapitoly
- Obsah
    - [Ohmův zákon](#ohmův-zákon)
    - [Columbův zákon](#columbův-zákon)
    - [Kirchhoffovy zákony](#kirchhoffovy-zákony)
        - [První Kirchhoffův zákon](#první-kirchhoffův-zákon)
        - [Druhý Kirchhoffův zákon](#druhý-kirchhoffův-zákon)
    - [Zákon elektromagnetické indukce](#zákon-elektromagnetické-indukce)
    - [Lenzův zákon](#lenzův-zákon)
- [Zdroje kapitoly](#zdroje-kapitoly)





## Základní zákony



### Ohmův zákon
- Ohmův zákon vyjadřuje vztah mezi elektrickým napětím, proudem a odporem.

<br>

**Vzorec**

$$
U = I \cdot R
$$

kde: 

```
U = elektrické napětí
I = elektrický proud
R = elektrický odpor
```

---



### Columbův zákon
- Columbův zákon popisuje síly působící mezi nabitými elektrickými náboji.

<br>

**Vzorec**

$$
F = k \cdot \frac{Q_1 \cdot Q_2}{r^2}
$$

kde: 

```
F = výsledná síla
Q = velikost na sebe působících elektrických nábojů
r = vzdálenost mezi elektrickými náboji
k = konstanta úměrnosti
```

<br>

**Konstanta úměrnosti**

$$
k = \frac{1}{4 \cdot \pi \cdot \eta_0}
$$

- $\eta_0$ je v tomto případě permitivita vákua.

---



### Kirchhoffovy zákony
- Kirchhoffovy zákony popisují chování elektrického náboje a energie v elektrických obvodech.
- Slouží k analýze elektrických obvodů.



#### První Kirchhoffův zákon
- Součet proudů vstupujících do uzlu se rovná součtu proudů vystupujících z uzlu.
- Elektrický náboj, tedy tok nábojů (elektrický proud), se nemůže nikam ztratit.

![První Kirchhoffův zákon](../../img/kapitola_2/ilustrace_3.png)

- Pro výše uvedený obrázek platí:

$$
I_1 + I_2 + I_3 = I_4 + I_5 + I_6
$$



#### Druhý Kirchhoffův zákon
- V uzavřeném obvodu je součet napětí na zdrojích roven součtu úbytků napětí na spotřebičích.
- Elektrický obvod si vezme tolik napětí, kolik mu zdroj poskytne.

![Druhý Kirchhoffův zákon](../../img/kapitola_2/ilustrace_4.png)

- Pro výše uvedený obrázek platí:

$$
U = U_1 + U_2 + U_3
$$

---



### Zákon elektromagnetické indukce
- Faradayův zákon elektromagnetické indukce popisuje, že změna magnetického pole indukuje elektrické pole, což způsobuje tok proudu ve vodiči.
- Tento zákon říká, že změna magnetického toku (Φ)(Φ) indukuje elektrické napětí (Ui)(Ui​) ve vodiči, což vyvolá proud, pokud je obvod uzavřený.
- Indukované napětí je přímo úměrné rychlosti změny magnetického toku.

$$
U_i = -\frac{\Delta Φ}{\Delta t}
$$

```
U_i = indukované napětí (V)
Φ = magnetický tok (Wb)
t = čas (s)
```

**Odvození indukovaného napětí**

<br>

- Elektrická síla působící na náboj je dána vztahem:

$$
    F_e = E \cdot Q  
$$

```
F_e = sílá elektrického pole (N)
E = intenzita elektrického pole (V/m)
Q = elektrický náboj (C)
```

:arrow_down:

- Síla magnetického pole působící na pohybující se náboj je:

$$
    F_m = Q \cdot v \cdot B   
$$

```
F_m = sílá magnetického pole (N)
Q = elektrický náboj (C)
v = rychlost elektrického náboje (m/s)
B = magnetická indukce (T)
```

:arrow_down:

- Intenzitu elektrického pole lze vyjádřit vztahem: 

$$
    E = v \cdot B
$$

```
E = intenzita elektrického pole (V/m)
v = rychlost elektrického náboje (m/s)
B = magnetická indukce (T)
```

:arrow_down:

- V případě rovnováhy platí, že síla elektrického pole je vyrovnána silou magnetického pole.

$$
    F_e = F_m
$$

```
F_e = sílá elektrického pole (N)
F_m = sílá magnetického pole (N)
```

:arrow_down:

- Indukované napětí​ lze vyjádřit vztahem:

$$
    U_i = v \cdot B \cdot l
$$

```
U_i = indukované napětí (V)
v = rychlost elektrického náboje (m/s)
B = magnetická indukce (T)
l = délka (m)
```

:arrow_down:

- Rychlost změny plochy magnetického toku za čas lze vyjádřit vztahem:

$$
    U_i = \frac{\Delta S \cdot B}{\Delta t}
$$

```
U_i = indukované napětí (V)
S = obsah plochy (m²)
B = magnetická indukce (T)
t = rozdíl časů (s)
```

:arrow_down:

- Pokud zohledníme změnu magnetického toku v čase, dostáváme obecný vztah Faradayova zákona:

$$
    U_i = \frac{\Delta Φ}{\Delta t}
$$

```
U_i = indukované napětí (V)
Φ = rozdíl magnetických toků (Wb)
t = rozdíl časů (s)
```

---



### Lenzův zákon
- Lenzův zákon říká, že indukovaný proud v obvodu má takový směr, že svými účinky působí proti změně magnetického toku, která tento proud vyvolala.
- Jinými slovy, indukovaný proud působí proti změně, která jej způsobila, a snaží se „zachovat“ původní stav systému.
- Tento zákon odráží přirozenou tendenci systému setrvat ve svém aktuálním stavu a bránit se změně.

---





## Zdroje kapitoly
- [Youtube](https://youtube.com/)
    - [Názorná elektrotechnika](https://youtube.com/@nazornaelektrotechnika)
        - [Základy Elektrotechniky](https://youtube.com/playlist?list=PL3r1xGSQfP9TBwvTqYEf6E-L9duHQbnir)
    - [ElectroBOOM](https://www.youtube.com/@ElectroBOOM)

- [ChatGPT](https://chatgpt.com/)

- [Wikipedie](https://wikipedia.org)
    - [Columbův zákon](https://cs.wikipedia.org/wiki/Coulomb%C5%AFv_z%C3%A1kon)
    - [Kirchhoffovy zákony](https://cs.wikipedia.org/wiki/Kirchhoffovy_z%C3%A1kony)

---





[:arrow_left: Magnetismus](../kapitola_1/podkapitola_3.md)

[:arrow_right: Zapojení odporů](./podkapitola_2.md)