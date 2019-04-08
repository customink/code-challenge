# Hledání kompletní cesty
Před sebou máme mapu (dvourozměrné pole o rozměrech 5x5), ve kterém se chceme dostat ze startovací pozice v levým horním rohu do cíle v pravým dolním rohu. K dispozici již také máme cestu (postupnost kroků), která nás do cíle dovede. Ta je však nekompletna a některé kroky v ní chybí. Naším úkolem je proto napsat funkci, která tyto kroky nalezne a vrátí kompletní cestu.

Cesta je zapsána jako řetězec, ve kterém každý znak představuje směr ve kterém se na mapě posouváme dál: `D` směrem dolů, `U` směrem nahor, `R` směrem vpravo a `L` směrem vlevo. Chybějící kroku jsou označeny symbolem `-`.

Příklady cest a výsledků

```
Vstupni cesta: ---RRURDR-
Kompletni cesta: DDDRRURDRD
```

```
Vstupni cesta: DRDR--RRDDD-
Kompletni cesta: DRDRUURRDDDD
```