# Hledání kompletní cesty
Před sebou máme mapu (dvourozměrné pole o rozměrech 5x5), ve kterém se chceme dostat ze startovací pozice v levém horním rohu do cíle v pravém dolním rohu. K dispozici již také máme cestu (postupnost kroků), která nás do cíle dovede. Ta je však nekompletní a některé kroky v ní chybí. Naším úkolem je proto napsat funkci, která tyto kroky nalezne a vrátí kompletní cestu.

Cesta je zapsána jako řetězec, ve kterém každý znak představuje směr, ve kterém se na mapě posouváme dál: `D` směrem dolů, `U` směrem nahoru, `R` směrem vpravo a `L` směrem vlevo. Chybějící kroky jsou označeny symbolem `-`.

Příklady cest a výsledků

```
Vstupni cesta: ---RRURDR-
Kompletni cesta: DDDRRURDRD
```

```
Vstupni cesta: DRDR--RRDDD-
Kompletni cesta: DRDRUURRDDDD
```

## Vypracování a odevzdání

Tento repozitář je připraven pro řešení problémů v `javascript` (Node.js) prostředí. V souboru `index.js` je připravená metoda `completePath`, kterou je potřebné implementovat podle zadání. Celý program pak můžeš pustit v konzoli voláním `yarn start`.

Řešení nám ale můžeš poslat v libovolném jazku, ve kterém se ti pracuje pohodlně.

Své řešení nám pak můžeš nahrát prostřednictvím formuláře na http://represent.com/code-challenge.
