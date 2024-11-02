[:arrow_left: Izolanty](./podkapitola_2.md)

[:arrow_right: Základní zákony](../kapitola_2/podkapitola_1.md)





# Pojmy a veličiny – Magnetismus
Tato kapitola se soustředí na základní fyzikální veličiny a pojmy nezbytné pro pochopení elektrotechniky. Konkrétně se podkapitola zaměřuje na magnetismus, magnetické pole a s nimi spojené veličiny.





## Obsah kapitoly
- Obsah
    - [Magnetismus a magnetické pole](#magnetismus-a-magnetické-pole)
    - [Magnetická indukce](#magnetická-indukce)
    - [Magnetický tok](#magnetický-tok)
    - [Vlastní indukčnost](#vlastní-indukčnost)
- [Zdroje](#zdroje-kapitoly)





## Magnetismus



### Magnetismus a magnetické pole
- Hmota má několik vlastností, jako například hmotnost, náboj nebo spin.
- Spin uplatňujeme především ve kvantové fyzice, a je to vlastnost, kterou má každá elementární částice.
- Spin je malé magnetické pole, kolem každé částice, ale u protonu je jeho velikost zanedbatelná, proto nijak neovlivňuje výsledné magnetické pole.
- Výsledné magnetické pole kolem atomu je tvořeno velikostí spinu a pohybem elektronu kolem protonu.

<br>

- Pro většinu látek platí:
    - Elektrony se pohybují kolem jádra (protony a neutrony) po několika orbitalách. 
    - Jejich pohybem po několika orbitalách se magnetické pole vzniklé pohybujícími se elektrony vyruší.
    - Na každé orbitale můžou být pouze elektrony opačného spinu tím se vyruší magnetické pole na stejných orbitalách.

<br>

- Ne všechny látky, s magnetickým polem musí být magnetické. (tj. reagovat na magnet)
- Aby byla látka magnetická nesmí magnetické pole jednotlivých atomů ukazovat všemi směry.
- Skupinu atomů se stejným směrem magnetického pole lze nazvat doménou.
- Domény mohou ukazovat různými směry ovšem pod působením silnějšího magnetického pole se domény usměrní a ukazují stejným směrem. Tím vzniknou pernamentní magnety a zesílí se magnetické pole.
- Magnetické materiály, které po odstranění z magnetického pole ztrácejí své magnetické vlastnosti, se nazývají magneticky měkké oceli.
- Materiály, které i po vyjmutí z magnetického pole zůstávají magnetické, označujeme jako magneticky tvrdé oceli.
- Některé materiály se po vložení do magnetického pole zmagnetizují, ale s opačnou polaritou než má původní pole, což vede k oslabení magnetického pole.

<br>

- Speciální teorie relativity umožňuje chápat vzájemné působení elektrických nábojů jako relativní pohled na magnetické působení elektrického náboje na pohybující se elektrický proud.
- Magnetické pole vzniká v okolí pohybujících se elektronů, tedy v přítomnosti elektrického proudu.
- Magnetické pole je, stejně jako elektrické pole, znázorňováno siločárami. Čím blíže jsou siločáry u sebe, tím je magnetické pole silnější.
- Na rozdíl od elektrických siločar jsou magnetické siločáry uzavřené.
- Siločáry magnetického pole směřují ze severního pólu magnetu k jižnímu pólu. Na základě toho lze definovat:
    - Severní pól je místo, odkud siločáry vystupují.
    - Jižní pól je místo, kam siločáry vstupují.
- Přirozené magnetické pole je homogenní, což znamená, že jeho intenzita je všude stejná.
- Siločáry mají tendenci ve vertikálním směru zkracovat své trajektorie a v horizontálním směru se navzájem odpuzovat.
- Póly opačné polarity se přitahují, zatímco stejné polarity se odpuzují.

<br>

- Na rozdíl od elektrického pole, kde stačí vložit elektrický náboj do elektrického pole, v magnetickém poli musí být náboj v pohybu, aby na něj působila síla.
- Výslednou sílu, která působí na elektrický náboj získáme součtem magnetické síly a síly způsobené intenzitou elektrického pole a nazýváme ji Lorentzova síla.

$$
F = F_m + F_e
$$

```
F = Lorentzova síla (N)
F_m = magnetická síla (N)
F_e = elektrická síla (N)
```

---



### Magnetická indukce
- **Značka: B**
- **Jednotka: tesla (T)**

<br>

- Magnetická indukce popisuje velikost magnetické síly, která vzniká v magnetickém poli a působí na elektrický proud.
- V elektrotechnice se hodnota magnetické indukce běžně pohybuje v jednotkách tesla. V současné době je lidstvo schopné vytvořit a využít magnetickou indukci o hodnotě až desítek tesla.
- Magnetická indukce charakterizuje magnetické pole v jednom bodě a je vektorovou veličinou.
- Směr působení magnetické síly je vždy kolmý na směr proudu elektrického náboje.

<br>

- Sílu, která je způsobena působením magnetického pole, které vzniklo proudem tekoucím ve vodiči jakéhokoliv tvaru, lze vypočítat pomocí Biot-Savartova zákona.
- Magnetická indukce působí na pohybující se elektrický náboj v magnetickém poli, přičemž směr této síly je vždy kolmý na směr pohybu náboje.
- Pro výpočet magnetické indukce lze použít následující vztah:

$$
B = \frac{F}{I \cdot l}
$$

```
B = magnetická indukce (T)
F = Lorentzova síla (N)
I = velikost elektrického proudu (A)
l = délka kolmého úseku, kterým náboj prochází přes magnetické pole (m)
```

---



### Magnetický tok
- **Značka: Φ**
- **Jednotka: weber (Wb)**

<br>

- Magnetický tok vyjadřuje celkovou magnetickou indukci procházející určitou plochou, protože magnetická indukce popisuje magnetické pole pouze v jednom bodě.
- Magnetický tok tak představuje součet magnetické indukce v celé ploše.
- Magnetický tok lze vypočítat pomocí následujícího vzorce:

$$
Φ = B * S
$$

```
Φ = magnetický tok (Wb)
B = magnetická indukce (T)
S = plocha (m²)
```

---



### Vlastní indukčnost
- **Značka: L**
- **Jednotka: henry (H)**

<br>

- Indukčnost je schopnost cívky vytvářet vlastní napětí v reakci na změnu proudu.
- Tato vlastnost závisí pouze na konstrukci cívky, respektive na počtu vinutí, průměru vodiče, délce, a použitém materiálu.
- Konstrukce cívky určuje indukčnost, díky čemuž může cívka pracovat na různých úrovních napětí a proudu. Avšak vysoké hodnoty napětí a proudu mohou ohrozit ochranu vodiče, což vede k riziku zkratu.
- Indukčnost umožňuje cívce vytvářet magnetické pole prostřednictvím proudu. Jakýkoli vodič, kterým protéká proud, má indukčnost a může magneticky ovlivňovat okolní objekty, čímž vykonává práci.
- Indukčnost lze vypočítat podle následujícího vztahu::

$$
L = \frac{Φ}{I}
$$

```
Φ = magnetický tok (Wb)
L = indukčnost (H)
I = elektrický proud (A)
```

<br>

- Vzájemná indukčnost popisuje vztah mezi dvěma cívkami, které mohou částečně sdílet své magnetické toky.
- Část magnetického toku, kterou cívky sdílí, se označuje jako rozptylový tok.

---





## Zdroje kapitoly
- [Youtube](https://youtube.com/)
    - [Názorná elektrotechnika](https://youtube.com/@nazornaelektrotechnika)
        - [Základy Elektrotechniky](https://youtube.com/playlist?list=PL3r1xGSQfP9TBwvTqYEf6E-L9duHQbnir)
    - [ElectroBOOM](https://www.youtube.com/@ElectroBOOM)

- [ChatGPT](https://chatgpt.com/)

- [Wikipedie](https://wikipedia.org)
    - [Magnetický tok](https://cs.wikipedia.org/wiki/Magnetick%C3%BD_tok)
    - [Indukčnost](https://cs.wikipedia.org/wiki/Induk%C4%8Dnost)

---





[:arrow_left: Izolanty](./podkapitola_2.md)

[:arrow_right: Základní zákony](../kapitola_2/podkapitola_1.md)