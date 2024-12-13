[:arrow_left: Magnetismus](./podkapitola_3.md)

[:arrow_right: Základní zákony](../kapitola_2/podkapitola_1.md)





# Pojmy a veličiny – Střídavý proud





## Obsah kapitoly
- Obsah
- [Střídavý proud](#střídavý-proud)
- [Činný odpor](#činný-odpor)
- [Reaktance (jalový odpor)](#reaktance-jalový-odpor)
- [Impedance (zdánlivý odpor)](#impedance-zdánlivý-odpor)
- [Fázový posuv](#fázový-posuv)
- [Zdroje](#zdroje-kapitoly)





## Střídavý proud
- Hlavní výhodou střídavého proudu je snadná transformace jeho napětí. Tím je energeticky efektivnější pro přenos energie na delší vzdálenosti.
- Střídavý proud vzniká otáčením cívky v magnetickém poli. Tento děj rozkmitá elektrony v cívce a na výstupu lze měřit střídavé napětí.
- Průběh kmitání elektronů lze graficky znázornit jako sinusovou funkci v závislosti na čase.
- Parametry sinusového funkce:
    - Perioda (T): určuje dobu, za kterou se dokončí jeden cyklus. Jednotkou je sekunda. (s)
    - Frekvenci (f): jde o inverzní veličinu periody, která udává počet cyklů za sekundu. Jednotkou je hertz. (Hz) 

<br>



**Fázorový diagram**

<br>

- Pro snazší výpočty je výhodné sinusový průběh znázornit na kružnici místo časového grafu.
- V rovině definované reálnou částí (x-ová osa) a imaginární částí (y-ová osa) se vykreslí jednotková kružnice (kružnice s poloměrem 1). Průběh sinusové funkce lze poté zaznamenávat na tuto kružnici.
- Fázor (neboli fázový vektor) představuje okamžitou hodnotu proudu nebo napětí a jeho směr odpovídá aktuální fázi sinusového průběhu.
- Úhel, který fázor urazil od počátku, se měří v radiánech. Celý obvod kružnice odpovídá 2π radiánům.
- Úhlová rychlost (ω) udává rychlost oběhu fázoru po kružnici a je definována vztahem:

$$
\omega = 2 \cdot \pi \cdot f
$$

```
ω = uhlová rychlost (rad/s)
f = frekvence (Hz)
```

- Pokud se na fázorovém diagramu vyskytuje více stejných veličin, pak se sečtou a pracuje se pouze s výslednou hodnotou.

<br>



**Hodnoty proudu a napětí**

<br>

- Maximální hodnota napětí nebo proudu je amplituda sinusové funkce – tedy rozdíl mezi nulou a nejvyšším bodem.
- Okamžitá hodnota napětí nebo proudu je hodnota v konkrétním bodě na sinusovém průběhu.

<br>

- Okamžitou hodnotu proudu lze vypočítat ze vztahu:

$$
i = I_m \cdot sin(\omega \cdot t + \phi)
$$

```
i = okamžitá hodnota proudu (A)
I_m = maximální hodnota proudu (A)
ω = uhlová rychlost (rad/s)
t = doba (s)
ϕ = fázový posuv (°)
```

<br>

- Zatím co okamžitou hodnotu napětí lze vypočítat ze vztahu:

$$
u = U_m \cdot sin(\omega \cdot t + \phi)
$$

```
u = okamžitá hodnota napětí (V)
U_m = maximální hodnota napětí (V)
ω = uhlová rychlost (rad/s)
t = doba (s)
ϕ = fázový posuv (°)
```

**Efektivní hodnota**

<br>

- Při práci se střídavým proudem se často používá efektivní hodnota. Anglicky RMS – root mean square.
- Efektivní hodnota střídavého proudu odpovídá velikosti stejnosměrného proudu, který vyvolá stejné tepelné účinky na odporu.
- Efektivní hodnotu lze vypočítat pomocí vztahu:

$$
I_e = \frac{I_m}{\sqrt{2}}
$$

```
I_e = efektivní hodnota proudu (A)
I_m = maximální hodnota proudu (A)
```

- Popřípadě napětí ze vztahu:

$$
U_e = \frac{U_m}{\sqrt{2}}
$$

```
U_e = efektivní hodnota napětí (V)
U_m = maximální hodnota napětí (V)
```

---



## Činný odpor
- **Značka: R**
- **Jednotka: ohm (&#937;)**

<br>

- Každá součástka je složena z vodičů, které se při průtoku proudu zahřívají, čímž vzniká odpor.
- Jelikož má odpor každá součástka tak kreslíme vektor odporu na reálnou část fázorového diagramu.
- Více o odporu najdete v podkapitole [elektrické pojmy a veličiny](./podkapitola_1.md) v části [elektrický odpor](./podkapitola_1.md#elektrický-odpor).

---



## Reaktance (jalový odpor)
- **Značka: X**
- **Jednotka: ohm (&#937;)**

<br>

- Reaktance je imaginární část impedance elektrického obvodu, a proto se znázorňuje na imaginární ose fázorového diagramu.
- Projevuje se změnou fáze proudu vůči napětí, konkrétně jeho zpožděním nebo předbíháním o polovinu π radiánu.

<br>

- Vliv reaktance se ve vztahu projevuje přičtením nebo odečtením poloviny π radiánu:

$$
i = I_m \cdot sin(\omega \cdot t + \frac{\pi}{2})
$$

- popřípadě:

$$
i = I_m \cdot sin(\omega \cdot t - \frac{\pi}{2})
$$

```
i = okamžitá hodnota proudu (A)
I_m = maximální hodnota proudu (A)
ω = uhlová rychlost (rad/s)
t = doba (s)
ϕ = fázový posuv (°)
```

<br>

**Kapacitní reaktance**
- Kapacitní reaktance vzniká v obvodech s kondenzátorem a projevuje se předbíháním proudu vůči napětí o polovinu π radiánu.
- Kapacitní reaktance je dána vztahem:

$$
X_C = \frac{1}{C \cdot \omega}
$$

```
X_C = kapacitní reaktance (Ω)
C = elektrická kapacita (F)
ω = uhlová rychlost (rad/s)
```

<br>

**Induktivní reaktance**
- Induktivní reaktance vzniká v obvodech s cívkou a chová se jako odpor způsobený indukovaným napětím.
- Indukované napětí vzniká v důsledku magnetického pole vytvořeného průchodem proudu cívkou. Toto napětí má opačný směr než proud a brání jeho průtoku.
- Induktivní reaktance je dána vztahem:

$$
X_L = L \cdot \omega
$$

```
X_l = induktivní reaktance (Ω)
L = indukčnost (H)
ω = uhlová rychlost (rad/s)
```

---



## Impedance (zdánlivý odpor)
- **Značka: Z**
- **Jednotka: ohm (&#937;)**

<br>

- Impedance je komplexní veličina vznikající kombinací činného odporu a reaktance.
- Výslednou impedanci lze rozložit na dvě složky:
    - Činný odpor: reálná složka, kde proud přeměňuje svou energii na jiný typ, například na tepelnou energii.
    - Jalový odpor (reaktance): imaginární složka, která se dále dělí na kapacitní a induktivní reaktanci.
- Jalový proud prochází jalovým odporem a nemění energii na teplo, ale ukládá ji do jiných forem, například do magnetického pole cívky nebo elektrického pole kondenzátoru.

---



## Fázový posuv
- **Značka: ϕ**
- **Jednotka: stupně (°)**

<br>

- Fázový posuv je úhel, který vyjadřuje rozdíl mezi proudem a napětím na fázorovém diagramu.
- Tento úhel umožňuje určit charakter obvodu:
    - Induktivní obvod: napětí předbíhá proud.
    - Kapacitní obvod: proud předbíhá napětí.
- Fázový posuv je také úzce spojen s **účiníkem**, který vyjadřuje efektivitu přeměny energie a je dán vztahem:

$$
cos(\phi) = \frac{R}{Z}
$$

```
cos(ϕ) = účiník
R = činný odpor (Ω)
Z = impedance (Ω)
```

---





## Zdroje kapitoly
- [Youtube](https://youtube.com/)
    - [Názorná elektrotechnika](https://youtube.com/@nazornaelektrotechnika)
        - [Základy Elektrotechniky](https://youtube.com/playlist?list=PL3r1xGSQfP9TBwvTqYEf6E-L9duHQbnir)
    - [ElectroBOOM](https://www.youtube.com/@ElectroBOOM)

- [ChatGPT](https://chatgpt.com/)

- [Wikipedie](https://wikipedia.org)
    - [Úhlová rychlost](https://cs.wikipedia.org/wiki/%C3%9Ahlov%C3%A1_rychlost)
    - [Reaktance](https://cs.wikipedia.org/wiki/Reaktance)

---





[:arrow_left: Magnetismus](./podkapitola_3.md)

[:arrow_right: Základní zákony](../kapitola_2/podkapitola_1.md)