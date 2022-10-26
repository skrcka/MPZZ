# MPZZ

## Cv4

* Uzavreno -> Grupoid (A, O) O: AxA->A
* \+ Asociativni (nezalezi na zavorkach) -> Pologrupa
* \+ Existence jednotkoveho prvku (iRj = i) -> Monoid
* \+ Existence inverzniho prvku (iRi = jRj) -> Grupa
* \+ Existence nuloveho prvku (v relaci s cimkoliv je 0) -> pak nemuze mit inverzni
* \+ Komutativita (muzeme zamenit poradi) -> Abelova grupa
* \+ Identita (iRi = i) -> A. Grupa

Podgrupa - podmnozina z nosice (jednotkovy prvek, asociativni, uzavrene, komutativni)

Z_6 - zbytkova mnozina %6


Pr 4.5:

|                | UZ  | AS  | KO  | ID  | EN  | EJ   | EI  | Typ                  |
|:--------------:|-----|-----|-----|-----|-----|------|-----|----------------------|
| (Z,-)          | (/) | (X) |     |     |     |      |     | grupoid              |
| (Z_6,+)        | (/) | (/) | (/) | (X) | (X) | j=0  | (/) | a.g.                 |
| (Z_6,*)        | (/) | (/) | (/) | (X) | n=0 | j=1  | (X) | komutativni monoid   |
| (R,+)          | (/) | (/) | (/) | (X) | (X) | j=1  | (/) | a.g.                 |
| (R,*)          | (/) | (/) | (/) | (X) | n=0 | j=1  | (X) | komutativni monoid   |
| (R\\[0],*)     | (/) | (/) | (/) | (X) | (X) | j=1  | (/) | a.g.                 |
| (R^(n*n),*)    | (/) | (/) | (X) | (X) | n=0 | j=E  | (X) | monoid               |
| ({0,1},^)      | (/) | (/) | (/) | (/) | n=0 | j=1  | (X) | komutativni monoid   |
| ({0,1},v)      | (/) | (/) | (/) | (/) | n=1 | j=0  | (X) | komutativni monoid   |
| (&sum*,*)      | (/) | (/) | (X) | (X) | (X) | j=&e | (X) | monoid               |
| (P(AxA),o)     | (/) | (/) | (X) | (X) | &0  | j=id | (X) | monoid               |

Pr 4.6:

|                | DIS |
|:--------------:|-----|
| (R,+,*)        | (/) |
| (R,*,+)        | (X) |
| (R,*,-)        | (/) |
| (R,/,+)        | (X) |
| (R,/,*)        | (X) |
| (R,*,/)        | (X) |
| (R^(nxn),*,+)  | (/) |
| ({0,1},v,^)    | (/) |
| ({0,1},^,v)    | (/) |

Pr 4.7:

q=
|   | a | b | c |
|:-:|---|---|---|
| a | a | b | c |
| b | b | a | b |
| c | c | b | a |

|                | UZ  | AS  | KO  | ID  | EN  | EJ   | EI  | Typ                  |
|:--------------:|-----|-----|-----|-----|-----|------|-----|----------------------|
| a              | (/) | (X) | (/) | (X) | (X) | (X)  | (X) | grupoid              |
| b              | (/) | (/) | (/) | (X) | (X) | j=a  | (/) | A.g.                 |
| c              | (/) | (/) | (/) | (/) | n=a | j=c  | (X) | komutativni monoid   |
| q              | (/) | (X) | (/) | (X) | (X) | j=a  | (/) | grupoid              |

## Cv5

Pr 5.1:

(Z_3,+) -> 1^1 = 1, 1^2 = 1+1 = 2, 1^3 = 1+1+1 = 0

(Z_4,+) -> 1^1 = 1, 1^2 = 1+1 = 2, 1^3 = 1+1+1 = 0

Cayleyho tabulka

|   | 0 | 1 | 2 | 3 |
|:-:|---|---|---|---|
| 0 | 0 | 1 | 2 | 3 |
| 1 | 1 | 2 | 3 | 0 |
| 2 | 2 | 3 | 0 | 1 |
| 3 | 3 | 0 | 1 | 2 |

rad prvku 1 = 4
r.p(2) = 2 => netrivialni podgrupa ({0,2},+)
r.p(3) = 4

Ukol 5.4

a)

| * | 0 | 1 | 2 | 3 |
|:-:|---|---|---|---|
| 0 | 0 | 0 | 0 | 0 |
| 1 | 0 | 1 | 2 | 3 |
| 2 | 0 | 2 | 0 | 2 |
| 3 | 0 | 3 | 2 | 1 |

UZ - (/), AS - (/), EJ - 1, IN - (1, 3)

grupa - ({1, 3}, *)

ord(1) = 1 => ({1}, *)

ord(3) = 2 => ({1, 3}, *)

b)

| * | 0 | 1 | 2 | 3 | 4 |
|:-:|---|---|---|---|---|
| 0 | 0 | 0 | 0 | 0 | 0 |
| 1 | 0 | 1 | 2 | 3 | 4 |
| 2 | 0 | 2 | 4 | 1 | 3 |
| 3 | 0 | 3 | 1 | 4 | 2 |
| 4 | 0 | 4 | 3 | 2 | 1 |

UZ - (/), AS - (/), EJ - 1, IN - (1, 2, 3, 4)

grupa - ({1, 2, 3, 4}, *)

ord(1) = 1 => ({1}, *)

ord(2) = 4 => ({Z5/0}, *)

ord(3) = 4 => ({Z5/0}, *)

ord(4) = 2 => ({1, 4}, *)

c)

| * | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
|:-:|---|---|---|---|---|---|---|---|---|
| 0 | 0 | 0 | 0 | 0 | 0 | 5 | 6 | 7 | 8 |
| 1 | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| 2 | 0 | 2 | 4 | 6 | 8 | 1 | 3 | 5 | 7 |
| 3 | 0 | 3 | 6 | 0 | 3 | 6 | 0 | 3 | 6 |
| 4 | 0 | 4 | 8 | 3 | 7 | 2 | 6 | 1 | 5 |
| 5 | 0 | 5 | 1 | 6 | 2 | 7 | 3 | 8 | 4 |
| 6 | 0 | 6 | 3 | 0 | 6 | 3 | 0 | 6 | 3 |
| 7 | 0 | 7 | 5 | 3 | 1 | 8 | 6 | 4 | 2 |
| 8 | 0 | 8 | 7 | 6 | 5 | 4 | 3 | 2 | 1 |

UZ - (/), AS - (/), EJ - 1, IN - (1, 2, 4, 5, 7, 8)

grupa - ({1, 2, 4, 5, 7, 8}, *)

ord(1) = 1 => ({1}, *)

ord(2) = 6 => ({1, 2, 4, 5, 7, 8}, *)

ord(4) = 3 => ({1, 4, 7}, *)

ord(5) = 6 => ({1, 2, 4, 5, 7, 8}, *)

ord(7) = 3 => ({1, 4, 7}, *)

ord(8) = 2 => ({1, 8}, *)

### Morfismy

* epimorfismus: zobrazen ́ı h je surjektivn ́ı,
* monomorfismus: zobrazen ́ı h je injektivn ́ı,
* izomorfismus: zobrazen ́ı h je bijektivn ́ı,
* endomorfismus: h je zobrazen ́ı z 𝐴 do 𝐴 (tj. 𝐴′ ⊆ 𝐴)
* automorfismus: h je zobrazen ́ı z 𝐴 na 𝐴 (tj. 𝐴′ = 𝐴)

Pr5.10:

a)

(Z, +) a ({0,1,2,3}, +4) a f(x)=2x mod 4

2(x+y) mod4 = (2x mod4 + 2y mod4) mod4 (/) - homomorfismus

b)

(Z, +) a ({0,1,2,3}, +4) a f(x)=2x mod4 + 1

0->1, 1->3, 2->1, 3->3

2(x+y) mod4 + 1 =  = ((2x mod4 + 1) + (2y mod4 + 1)) mod4 (X)

c)

(Z6, +) a (Z6, +6) a f(x)=2x mod6

0->0, 1->2, 2->4, 3->0, 4->2, 5->4, 6->0

...

Pr5.11:

a) neni svaz

b) je svaz
