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
- [Výkon](#výkon)
- [Jalový výkon](#jalový-výkon)
- [Rezonance](#rezonance)
- [Tří fázový proud](#tří-fázový-proud)
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

- Převrácenou hodnotou reaktance je susceptance, značená B a s jednotkou siemens.

$$
B = \frac{1}{X}
$$

```
B = susceptance (S)
X = reaktance (Ω)
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

<br>

- Převrácenou hodnotou impedance je admitance, značená Y a s jednotkou siemens.

$$
Y = \frac{1}{Z}
$$

```
Y = admitance (S)
Z = impedance (Ω)
```

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





## Výkon
- **Značka: P**
- **Jednotka: watt (W)**

<br>

- Okamžitý výkon ve střídavých obvodech lze vypočítat z následujícího vztahu:

$$
p = u \cdot i
$$

```
p = okamžitý výkon (W)
u = okamžité napětí (V)
i = okamžitý proud (A)
```

- Pokud bychom násobili okamžité hodnoty napětí a proudu na sinusovém průběhu střídavého proudu, výsledný graf výkonu by měl sinusový průběh s dvojnásobnou frekvencí a střídal by kladné a záporné hodnoty.
- Z pohledu na tento graf vyplývá:
    - Pokud je graf v kladné části osy, energie proudí ze zdroje do zátěže.
    - Pokud je graf v záporné části osy, energie se z reaktivní zátěže (např. kondenzátoru nebo cívky) vrací zpět do zdroje.

<br>

- Kondenzátor a cívka ukládají energii (do elektrického nebo magnetického pole) a následně ji vracejí zpět do obvodu. Chovají se jako zdroj a zároveň jako spotřebič.
- Odpor se chová výhradně jako spotřebič, protože energii nevrací zpět do obvodu, ale trvale ji mění na teplo.

<br>

- Pro výpočet středního výkonu v obvodu lze použít vztah:

$$
P = U \cdot I \cdot cos(\phi)
$$

```
P = výkon (W)
U = efektivní napětí (V)
I = efektivní proud (A)
cos(ϕ) = účiník
```

<br>

---





## Jalový výkon
- **Značka: Q**
- **Jednotka: voltampér reakční (VAr)**

<br>

- Tento výkon je potřebný k vytvoření magnetického nebo elektrického pole v reaktivních součástkách, jako jsou cívky a kondenzátory.
- Jalový výkon nepřispívá k užitečné práci, ale je nezbytný pro správnou funkci obvodu.
- Vektorovým součtem reálného a jalového výkonu získáme zdánlivý výkon.





## Rezonance
- Rezonance nastává, pokud je frekvence dodávané energie shodná s vlastní frekvencí systému.
- V tomto stavu lze s minimálním množstvím energie na vstupu dosáhnout procesů s výrazně větším množstvím energie na výstupu.

<br>

- V elektrotechnických obvodech nastává rezonance, pokud se kapacitní a indukční reaktance navzájem rovnají.
- V tomto případě se na fázorovém diagramu reaktance vzájemně vyruší, což vede k tomu, že výsledná impedance obvodu je tvořena pouze činným odporem.
- Pro účiník platí:

$$
cos \phi = 1
$$

```
ϕ = fázový posuv (°)
```

<br>

- Vynesením proudu v závislosti na frekvenci získáme rezonanční křivku.
- Čím větší je odpor rezonančního obvodu, tím menší jsou špičkové hodnoty proudu a napětí.
- Při vysokých hodnotách proudu nebo napětí může dojít k porušení izolace součástek a následnému poškození obvodu.
- Z tohoto důvodu je rezonance v silnoproudé elektrotechnice zpravidla nevyužitelná, avšak nachází široké uplatnění v radiotechnice.

<br>

- Jednoduchý rezonanční obvod lze realizovat paralelním zapojením cívky a kondenzátoru.
- Po nabití kondenzátoru a následném uzavření obvodu s cívkou a kondenzátorem proud v obvodu osciluje. Amplituda oscilací se postupně zmenšuje, dokud není energie v obvodu pohlcena odporem vodičů.

<br>

**Thompsonův vztah**
- Slouží k výpočtu vlastní frekvence rezonančního obvodu.
- Tento vztah platí jak pro sériové, tak pro paralelní rezonanční obvody.

$$
f_0 = \frac{1}{2 \cdot \pi \cdot \sqrt{L \cdot C}}
$$

```
f_0 = vlastní frekvence (Hz)
L = indukčnost (H)
C = kapacita (F)
```





## Tří fázový proud
- Třífázový proud tvoří tři identické střídavé proudy, které jsou vůči sobě posunuty o fázový úhel 120°.

$$
120° = \frac{2 \pi}{3} rad
$$

- Třífázový proud lze generovat pomocí moderních generátorů, kde rotující magnet (rotor) vytváří indukci ve třech statických cívkách (stator), které jsou prostorově posunuty o 120°.
- Součtem okamžitých hodnot všech tří fázových proudů je v každém okamžiku nulový proud.

<br>



**Zapojení do hvězdy (Y)**

<br>

- Zapojením všech konců vinutí do jednoho společného bodu vzniká zapojení do hvězdy.
- Ve vinutí zapojeném do hvězdy lze měřit:
    - Fázové napětí: mezi uzlem a fází.
    - Sdružené napětí: mezi dvěma fázemi.

<br>

- Toto zapojení umožňuje přenos proudu ze zdroje na zátěž bez zpětného toku proudu do generátoru (za ideálních podmínek).
- Pro stabilitu systému je však využíván přídavný vodič vedený ze společného uzlu, který se nazývá nulový vodič.
- Aby nedocházelo k nadměrnému zatížení nulového vodiče, je nutné, aby spotřebiče připojené na jednotlivé fáze odebíraly proudy rovnoměrně.

<br>

- Poměr mezi sdruženým napětím a fázovým napětím lze vyjádřit vztahem:

$$
\frac{U_S}{U_1} = \sqrt{3}
$$

```
U_S = sdružené napětí (V)
U_1 = fázové napětí (V)
```

<br>



**Zapojení do trojúhleníku (D)**

<br>

- Zapojení do trojúhelníku vzniká propojením konce jedné fáze se začátkem fáze následující. Tímto způsobem všechny tři fáze tvoří uzavřený okruh.
- Ve vinutí zapojeném do trojúhelníku lze měřit pouze sdružené napětí. Fázové napětí zde není přístupné, protože chybí nulový bod.

<br>

- V zapojení lze měřit:
    - Fázový proud: proud, který prochází jednotlivými vinutími.
    - Sdružený proud: proud v přívodních vodičích, který je větší než fázový proud.
- Poměr mezi sdruženým proudem a fázovým proudem v trojúhelníkovém zapojení je:

$$
I_S = \sqrt{3} \cdot I_1
$$

```
I_S = sdružený proud (A)
I_1 = fázový proud (A)
```

<br>



**Výkon ve třífázových obvodech**
- Celkový zdánlivý výkon v třífázovém obvodu je dán součtem výkonů na jednotlivých fázích:

$$
S = S_1 + S_2 + S_3
$$

```
S = celkový zdánlivý výkon (VA)
S_1, S_2, S_3 = zdánlivý výkon jednotlivých fází (VA)
```

<br>

- Pro jednu fázi platí vztah:

$$
S_1 = U_1 * I_1
$$

```
S_1 = zdánlivý výkon fáze 1 (VA)
U_1 = fázové napětí (V)
I_1 = fázový proud (A)
```

<br>

- Celkový zdánlivý výkon v třífázovém obvodu lze také vyjádřit pomocí sdruženého napětí:

$$
S = \sqrt{3} \cdot U_S \cdot I_1
$$

```
S = celkový zdánlivý výkon (VA)
U_S = sdružené napětí (V)
I = sdružený proud (A)
```

<br>

- Činný výkon, který představuje užitečný výkon přeměněný na práci, se vypočítá ze vztahu:

$$
P = \sqrt{3} \cdot U \cdot I \cdot cos(\phi)
$$

- Jalový výkon, který je zodpovědný za tvorbu elektromagnetického pole, se vypočítá takto:

$$
Q = \sqrt{3} \cdot U \cdot I \cdot sin(\phi)
$$

```
P = činný výkon (W)
Q = jalový výkon (VAr)
U = sdružené napětí (V)
I = sdružený proud (A)
φ = fázový posun mezi napětím a proudem (°)
```





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