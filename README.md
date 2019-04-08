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

## Vypracovani a odevzdani

Tento repozitář je připraven pro řešení problémů v `javascript` (Node.js) prostředí. V souboru `index.js` je připravená metoda `completePath`, kterou je potřebné implementovat podle zadání. Celý porgram pak můžeš pustit v konzoli voláním `yarn start`.

Řešení ale také přijímáme v libovolném jazyky, ve ktrerem se ti pracuje pohodlně.

Své řešení nám pak můžeš nahrát prostřednictvím formuláře na http://represent.com/code-challenge.
