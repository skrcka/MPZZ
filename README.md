# Cv4

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
| a | a | b | c |
| b | b | a | b |
| c | c | b | a |

|                | UZ  | AS  | KO  | ID  | EN  | EJ   | EI  | Typ                  |
|:--------------:|-----|-----|-----|-----|-----|------|-----|----------------------|
| a              | (/) | (X) | (/) | (X) | (X) | (X)  | (X) | grupoid              |
| b              | (/) | (/) | (/) | (X) | (X) | j=a  | (/) | A.g.                 |
| c              | (/) | (/) | (/) | (/) | n=a | j=c  | (X) | komutativni monoid   |
| q              | (/) | (X) | (/) | (X) | (X) | j=a  | (/) | grupoid              |

Pr 5.1:

(Z_3,+) -> 1^1 = 1, 1^2 = 1+1 = 2, 1^3 = 1+1+1 = 0

(Z_4,+) -> 1^1 = 1, 1^2 = 1+1 = 2, 1^3 = 1+1+1 = 0

Cayleyho tabulka

|   | 0 | 1 | 2 | 3 |
| 0 | 0 | 1 | 2 | 3 |
| 1 | 1 | 2 | 3 | 0 |
| 2 | 2 | 3 | 0 | 1 |
| 3 | 3 | 0 | 1 | 2 |

rad prvku 1 = 4
r.p(2) = 2 => netrivialni podgrupa ({0,2},+)
r.p(3) = 4
