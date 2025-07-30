---
layout: default
title: Statistikk
---

# Statistikk

Statistikk vil si å observere og trekke slutninger ut fra det vi observerer.

Noen slutninger kan fortelle oss hvordan noe sannsynligvis er.  
Vi kan for eksempel få et anslag på hvor mange velgere som vil stemme på et bestemt parti.

Andre slutninger kan fortelle oss om sammenhenger, for eksempel om det er en sammenheng mellom røyking og kreft.

## Hva skal vi lære?

I dette kapitlet skal vi se hvordan vi kan:

- registrere det vi observerer  
- ordne dataene  
- framstille dataene grafisk  
- gjøre beregninger, slik at vi får et grunnlag for å trekke slutninger

---

## Frekvenstabell

Vi vil vite hvor mange som kjører privatbil til jobb.  
Derfor stiller vi oss opp en morgen ved en av innfartsveiene.

Vi registrerer hvor mange personer som sitter i hver personbil som passerer.

Når vi er ferdige, har vi masse tall.  
Hvert tall representerer antall personer i én bil.

Tallene, som i dette eksemplet er oppdiktet, kan vi redigere slik:

| Antall personer i bilen | Tellekolonne                                | Antall biler |
|-------------------------|---------------------------------------------|--------------|
| 1                       | `|||| |||| |||| |||| |||| ||||`             | 60           |
| 2                       | `|||| |||| |||| |`                          | 20           |
| 3                       | `|||| ||`                                   | 10           |
| 4                       | `|||| |`                                    | 6            |
| 5                       | `|||`                                       | 3            |
| 6                       | `|`                                         | 1            |
|                         |                                             | **100**      |

---

## Tømmermannstelling

Når vi registrerer, markerer vi registreringene i grupper på fem slik:

```
|||| ← "tømmermannstelling"
```

---

## Renskrevet tabell

En statistiker vil nå renskrive tabellen slik:

| x | f  |
|---|----|
| 1 | 60 |
| 2 | 20 |
| 3 | 10 |
| 4 | 6  |
| 5 | 3  |
| 6 | 1  |
|   | **n = 100** |

---

## Symbolforklaringer

**x**  
er navnet (variabelnavnet) på den verdien vi observerer og registrerer.  
I dette tilfellet er det antall personer.

Vi har registrert seks forskjellige x-verdier.

**f**  
betyr **frekvens**.  
Det antall ganger vi registrerer en gitt x-verdi, kaller vi frekvensen for den x-verdien.  

Noen lærebøker bruker bokstaven `h`, som står for "hyppighet".  
En gitt h-verdi angir hvor mange ganger x-verdien forekommer.

**n**  
er summen av alle frekvensene (f-verdiene).  
Summen av det antall ganger hver x-verdi er observert, er lik antall observasjoner totalt.  
`n` er altså også lik antall observasjoner totalt.

---

## Sigma: Summetegnet ∑

At antall observasjoner er lik summen av alle frekvensene, kan vi skrive slik:

$$
n = \sum f
$$

- \( \sum \) er den greske bokstaven **sigma**.
- Som matematisk symbol betyr det “summen av”.

Altså:

**\( n = \sum f \)** betyr at **n er summen av alle f-verdiene**, altså alle frekvensene.
