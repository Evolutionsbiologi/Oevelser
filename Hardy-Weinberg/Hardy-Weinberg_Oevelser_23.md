# Hardy-Weinberg samt variation i to loci

### Hans R. Siegismund

## Teoretisk baggrund

### Hardy-Weinberg loven

Betragt en diploid population, hvor vi ser på variation i et autosomalt
locus med to allele gener *A*<sub>1</sub> og *A*<sub>2</sub>. Vi tager en stikprøve på *N* individer. Disse *N* fordeler sig på de tre genotyper som følger
</font>

</br>

 |Genotype |*A*<sub>1</sub>*A*<sub>1</sub>|*A*<sub>1</sub>*A*<sub>2</sub>|*A*<sub>2</sub>*A*<sub>2</sub>|Sum   |
 |---------|:----------------------------:|:----------------------------:|:----------------------------:|:----:|
 |Antal    |*N*<sub>11</sub>              | *N*<sub>12</sub>             |*N*<sub>22</sub>              | *N*  | 
 |Frekvens |*P*<sub>11</sub>              | *P*<sub>12</sub>             |*P*<sub>22</sub>              | 1    |   

</br>

***Genotypefrekvenserne** P<sub>ij</sub>* bestemmes ved at dividere
antallet af genotypen *N<sub>ij</sub>* med summen *N*

*P<sub>ij</sub>* = *N<sub>ij</sub>*/*N*.

***Allelfrekvenserne*** af *A*<sub>1</sub> (*p*) og *A*<sub>2</sub>
(*q*) bestemmes ved simpel optælling af de to alleler i stikprøven, og
ved at huske at homozygoter bærer to alleler af samme slags. Vi har
derfor, at

*p* = (2*N*<sub>11</sub> + *N*<sub>12</sub>) / (2*N*) =
*P*<sub>11</sub> + *P*<sub>12</sub>/2

*q* = (2*N*<sub>22</sub> + *N*<sub>12</sub>) / (2*N*) =
*P*<sub>22</sub> + *P*<sub>12</sub>/2

1 = *p* + *q*
 </span>

Populationen vil efter én generation under antagelse af tilfældig
parring, ingen selektion, Mendelsk udspaltning, osv. opnå en stabil
fordeling af genotypernes hyppigheder. Fordelingen af genotyperne blandt
afkommet bliver Hardy-Weinberg-ligevægten

</br>


| Genotype|*A*<sub>1</sub>*A*<sub>1</sub>|*A*<sub>1</sub>*A*<sub>2</sub>|*A*<sub>2</sub>*A*<sub>2</sub>|Sum  |
|---------|:----------------------------:|:----------------------------:|:----------------------------:|:---:|
|Antal    |*N*<sub>11</sub>              | *N*<sub>12</sub>             |*N*<sub>22</sub>              | *N* |
|Frekvens |*p*<sup>2  </sup>             |2*pq*                         |*q*<sup>2</sup>               |1    |

</br>

Allelfrekvensen er konstant. Vi beregner den som

*p´* = *P*<sub>11</sub> + *P*<sub>12</sub>/2
= *p*<sup>2</sup> + 2*pq*/2
= *p*(*p + q*)
= *p*.

Hardy-Weinberg ligevægten er en ***neutral ligevægt*** med hensyn til
allelfrekvenser, forstået på den måde, at hvis allelfrekvensen ændrer
sig fra *p* til *p’*, så opstår der en ny Hardy-Weinberg ligevægt med
den nye allel-frekvens. Det kan f.eks. være genetisk drift, der ændrer
allelfrekvensen på grund af tilfældige ændringer. Hardy-Weinberg
ligevægten er en ***stabil ligevægt*** med hensyn til
genotypefordelingen. Det skal forstås på den måde, at hvis
allelfrekvensen ændrer sig fra *p* til *p’*, så opstår der en ny
genotypeligevægt med den nye allel-frekvens:

</br>

|Genotype|*A*<sub>1</sub>*A*<sub>1</sub>|*A*<sub>1</sub>*A*<sub>2</sub>| *A*<sub>2</sub>*A*<sub>2</sub>|Sum  |
|--------|:----------------------------:|:----------------------------:|:-----------------------------:|:---:|
|Frekvens|*p'*<sup>2</sup>              |2*p'q'*                       |*q*'<sup>2</sup>               |1    |


</br>

### Test af Hardy-Weinberg proportioner

I en stikprøve på *N* individer er den genetiske variation i et autosomalt locus med to allele gener *A*<sub>1</sub> og *A*<sub>2</sub>
blevet bestemt. En test for overensstemmelse af de observerede gen­o­typefordelinger med de forventede Hardy-Weinberg proportioner kan
foretages på følgende måde (Det er en god idé både at bestemme *p* og *q*; hvis deres sum er lig med 1, har man regnet rigtigt!):


</br>

| Genotype  |*A*<sub>1</sub>*A*<sub>1</sub>   | *A*<sub>1</sub>*A*<sub>2</sub>| *A*<sub>2</sub>*A*<sub>2</sub>|Sum   |
|-----------|:-------------------------------:|:-----------------------------:|:-----------------------------:|:----:|
|Observeret |*N*<sub>11</sub>                 |*N*<sub>12</sub>               |*N*<sub>22</sub>               |*N*   |
|Forventet  |*E*<sub>11</sub>                 |*E*<sub>12</sub>               |*E*<sub>22</sub>               |*N*   |
|           |  =                              |  =                            |=                              |      |
|           |*p*<sup>2</sup>*N*               |2*pqN*                         |*q*<sup>2</sup>*N*             |*N*   |


</br>

Allelfrekvenserne bestemmes som beskrevet foroven. Når man angiver allelfrekvenser, bør man benytte et antal decimaler, der svarer til stikprøvens størrelse. For eksempel, hvis *N* \< 50 har det ingen mening at angive allelfrekvensen med mere end to decimaler. Det er dog vigtigt at beregne de forventede genotypefordelinger med værdier, der ikke afrundes.

Den observerede og den forventede fordeling kan sammenlignes med et “Goodness of fit”-test. Teststørrelsen

$$
\chi ^2=\sum_i \frac{(O_i-E_i)^2}{E_i}
$$

er tilnærmelsesvis χ<sup>2</sup>-fordelt med én enkelt frihedsgrad. Antallet af frihedsgrader fremkommer på følgende måde. Antallet af
frihedsgrader for at beskrive den observerede genotypefordeling er 2. Vi kender jo summen, og når vi kender de to, kan den tredje jo nemt
udledes. Antallet af frihedsgrader for at beskrive allelernes frekvens er én. Kender vi frekvensen af én allel, kan den andens frekvens jo bestemmes som dens difference fra 1. Testens frihedsgrader er differencen i antallet af frihedsgrader for at beskrive henholdsvis genotypefordeling og allelfordeling, hvilket er 2 – 1 = 1. Er
teststørrelsen større end 3,84 forkaster vi hypotesen på 5% niveauet; dvs., den genetiske variation i det betragtede locus anses for ikke at
være i overensstemmelse med Hardy-Weinberg proportioner. Hvis vi accepterer hypotesen, kan vi kun udtale at genotypefordelinger stemmer
overens med Hardy-Weinberg fordelingen; vi kan ikke sige noget om, hvorvidt der er Hardy-Weinberg ligevægt i populationen!!!

Et simpelt eksempel kan tjene som illustration: Antag, at begge homozygoter er sterile, så kun heterozygoter får afkom. Hvis vi betragter populationen af voksne, har vi en perfekt overensstemmelse til de forventede Hardy-Weinberg-proportioner, nemlig

</br>

| *A*<sub>1</sub>*A*<sub>1</sub> |*A*<sub>1</sub>*A*<sub>2</sub>|*A*<sub>2</sub>*A*<sub>2</sub> |
| :-----------------------------:|:----------------------------:|:----------------------------: |
| 1/4                            |1/2                           |1/4                            |

</br>

som er resultatet af udspaltningen af den eneste fertile kombination,
*A*<sub>1</sub>*A*<sub>2</sub> × *A*<sub>1</sub>*A*<sub>2</sub> i generationen
før. Vi ser, at selv med en særdeles hård selektion kan man have en
perfekt overensstemmelse med Hardy-Weinberg-frekvenser i en population.

</br>

### Afvigelser fra Hardy-Weinberg proportioner

Vi kan karakterisere afvigleser fra Hardy-Weinberg proportioner ved hjælp af indavlskoefficienten *F* (uddybes senere i kurset). Den kan defineres som

*F =* (*H<sub>e</sub> – H<sub>o</sub>*)/ *H<sub>e</sub>*,

hvor *H<sub>e</sub>* er lig med de forventede heterozygoter,
*H<sub>e</sub> = 2pq*, og *H<sub>o </sub>*er lig med de observerede
heterozygoter. (Man kan også benytte det observerede og forventede antal
heterozygoter, som i eksemplet forneden.) Der gælder så, at

*F \>* 0, hvis der er overskud af homozygoter

*F =* 0, hvis der er Hardy-Weinberg proportioner

*F \<* 0, hvis der er overskud af heterozygoter.


 <figure>
  <img  align="right" src="HWAvena.jpg" width=250 title="*Avena*">
 </figure>

*Eksempel:*
Marshall og Allard (1970)[^1] undersøgte genetisk variation i et locus
hos den vilde hvede *Avena barbata* i Californien. De fandt den følgende genotypefordeling for dette locus


</br>


|    Genotype| *A*<sub>1</sub>*A*<sub>1</sub> | *A*<sub>1</sub>*A*<sub>2</sub>| *A*<sub>2</sub>*A*<sub>2</sub>|Sum   |
|------------|:------------------------------:|:-----------------------------:|:-----------------------------:|:----:|
|Observeret  | 66                             |6                              |15                             |87    |
|Forventet   |54,72                           |28,55                          |  3,72                         |87    |

</br>

Hvor de forventede genotypefrekvenser er beregnet ud fra
Hardy-Weinberg-proportioner med frekvenserne for allel *A*1 og *A*2 på
henholdsvis *p* = 0.79 og *q* = 0.21. Indavlskoefficienten beregnes som

*F* = (28,55 *–* 6)/ 28,55 = 0,79.

Vi ser en stor afvigelse fra Hardy-Weinberg-proportioner med et stort
overskud af homozygoter (*F* \> 0). Årsagen hertil er, at *Avena
barbata* hovedsageligt forplanter sig ved selvbestøvning.

### Hardy-Weinberg proportioner med flere alleler

Det er let at udvide Hardy-Weinberg-loven til situationer med flere
alleler i et locus. Findes der for eksempel tre alleler i et autosomalt
locus, er Hardy-Weinberg-proportionerne givet i tabellen længere nede.
Det ses, at antallet af genotyper som funktion af antallet af alleler
*n* er givet ved *n*(*n* + 1)/2. Antallet af mulige genotyper vokser
hurtigt, og det er derfor lidet sandsynligt at alle genotyper, som
findes i populationen, repræsenteres i en given stikprøve. Bestemmelsen
af allelfrekvenser foretages analogt til det tidligere viste eksempel
for et locus med to alleler. Man tæller simpelt hen antallet af en given
allel og dividerer med det totale antal gener, som findes i stikprøven,
dvs. to gange det observerede antal individer.

Den forventede fordeling af genotyperne ved Hardy-Weinberg-ligevægt med
tre alleler er givet ved

</br>

|                |*A*<sub>1</sub>            |*A*<sub>2</sub>                |*A*<sub>3</sub>                |
|:--------------:|:-------------------------:|:-----------------------------:|:-----------------------------:|
|*A*<sub>1</sub> |*p*<sub>1</sub><sup>2</sup>|2*p*<sub>1</sub>*p*<sub>2</sub>|2*p*<sub>1</sub>*p*<sub>3</sub>|
|*A*<sub>2</sub> |                           | *p*<sub>2</sub><sup>2</sup>   |2*p*<sub>2</sub>*p*<sub>3</sub>|
|*A*<sub>3</sub> |                           |                               |*p*<sub>3</sub><sup>2</sup>    |

</br>

### Variation i loci med dominante alleler

Bestemmelsen af allelfrekvenser i en population er forholdsvis enkel for
codominante alleler, hvor vi for hvert individ kan observere, hvilke
alleler det bærer. Situationen bliver lidt mere vanskelig, når der er
dominans mellem allelerne. Vi betragter et autosomalt locus med to
alleler, *D* og *d*, hvor *D* dominerer over *d*. Der findes derfor to
fænotyper i populationen, nemlig *D−* og *dd*, hvor vi kun hos den
sidste entydigt er i stand til at bestemme dens genotype. Fænotypen *D−*
er enten homozygot *DD* eller heterozygot *Dd*. Hvis vi antager, at
betingelserne for Hardy-Weinberg-ligevægten er opfyldt i populationen,
og at allelerne *D* og *d* optræder med hyppighederne *p* og *q*, kan
populationens sammensætning beskrives på følgende måde


| Genotype       |*DD*  *Dd*                |*dd*               |     |
| :--------------|:------------------------:|:-----------------:|:---:|
|                |└───┬───┘                 |                   |     |
|Fænotype        |*D-*                      |  *dd*             | Sum |
| Observeret     |*N*<sub>*D*-</sub>        |*N*<sub>*dd*</sub> | *N* |
| HW-Frekvens    |*p*<sup>2</sup>+2*pq*     |*q*<sup>2</sup>*N* | *N* |
| HW-Forventet   |(*p*<sup>2</sup>+2*pq*)*N*|*q*<sup>2</sup>*N* | *N* |

</br>

Allelfrekvenserne beregnes ud fra relationen mellem frekvensen af den
recessive allel og frekvensen af den recessive homozygot. Da vi har, at

*q*<sup>2</sup>× *N* = *N<sub>dd</sub>*

får vi dermed, at

$$
q=\sqrt{N_{dd}/N}
$$

og

$$
p = 1 – q.
$$

Forudsætningen herfor er, som allerede nævnt, at der er
Hardy-Weinberg-proportioner for dette locus i populationen. Såfremt
dette ikke er opfyldt, vil denne fremgangsmåde ikke resultere i et
meningsfyldt resultat. Vi har ingen mulighed for at teste for
Hardy-Weinberg-proportioner, da fænotypefordelingen beskrives med én enkelt frihedsgrad. De beregnede allelfrekvenser beskrives ligeledes med én enkelt frihedsgrad, så der er ingen frihedsgrader til en test.

### Variation i kønsbundne loci

Hardy-Weinberg loven blev udledt for variation i et autosomalt locus. Kønsbundne loci opfører sig lidt anderledes. Vi vil nu se på et simpelt system, hvor kønnet bestemmes af to forskellige kønskromosomer, *X* og *Y*, som det blandt andet kendes fra pattedyr og hos få særkønnede planter som humle og hamp. Her hører bærere af to *X*-kromosomer til det homogametiske køn (hunner), medens bærere af et *X*- og et *Y*-kromosom tilhører det heterogametiske køn (hanner).

Vi ser på variation, der bestemmes af gener, som sidder på *X*-kromosomet. Hunnerne bærer to kopier af sådanne gener, medens hannerne kun har én kopi, de er hemizygote. Betragt en population, hvor der i et locus A er observeret to alleler, *X*<sub>1</sub> og *X*<sub>2</sub>. Hos hunnerne findes derfor tre genotyper,
*X*<sub>1</sub>*X*<sub>1</sub>, *X*<sub>1</sub>*X*<sub>2</sub> og
*X*<sub>2</sub>*X*<sub>2</sub>, medens der hos hannerne kun forekommer
to genotyper, *X*<sub>1</sub>*Y* og *X*<sub>2</sub>*Y*. Frekvenserne af
de to alleler bestemmes hos hunnerne som i et autosomalt locus, se
tidligere. Hos hannerne er det lidt nemmere at bestemme frekvenserne af
*X*<sub>1</sub> og *X*<sub>2</sub>, de er lig med frekvenserne af hanner
med genotyperne *X*<sub>1</sub>*Y* og *X*<sub>2</sub>*Y*. Vi antager nu, at allelfrekvenserne er ens hos hanner og hunner, nemlig *p* og *q* for allel *X*<sub>1</sub> og *X*<sub>2</sub>. Hvis vi antager, at der foregår tilfældig gametsammensmeltning, så vil de forventede frekvenser af de mulige fem genotyper være givet ved

</br>

|         |Hunner </style>               |                              |                              |Hanner            |                  |
|---------|:----------------------------:|:----------------------------:|:----------------------------:|:----------------:|:----------------:|
|Genotype |*X*<sub>1</sub>*X*<sub>1</sub>|*X*<sub>1</sub>*X*<sub>2</sub>|*X*<sub>2</sub>*X*<sub>2</sub>|*X*<sub>1</sub>*Y*|*X*<sub>2</sub>*Y*|
|Forventet|*p*<sup>2</sup>               |2*pq*                         |*q*<sup>2</sup>               |*p*               |*q*               |
</br>

Forskellen i genotypefordelingen mellem hanner og hunner bliver specielt
tydeligt i tilfælde, hvor den ene allel dominerer over den anden. Her
vil den recessive fænotype være langt hyppigere hos hannerne. Hvis vi
antager, at *X*<sub>2</sub> er recessiv over for *X*<sub>1</sub>, vil
den forekomme med en frekvens, der er 1/*q* større end
*X*<sub>2</sub>*X*<sub>2</sub> homozygoten hos hunnerne. Hos sjældne
arvelige sygdomme som hæmofili (blødersygdommen) hos mennesket er det
derfor meget sjældent at observere syge kvinder. Det er stort set kun
mænd, der lider af denne sygdom.


 <figure>
  <img  align="right" src="HWFarveblind.png" width=250 title="Farveblindhed">
 </figure>

*Eksempel*: Rød-grøn farveblindhed nedarves kønsbundet hos mennesket.
Personer, der er rød-grøn farveblinde, kan ikke se tallene 6 og 45 i de
to figurer.

</br>


# Hardy-Weinberg øvelser

## Formål

Disse øvelser har deres fokus på

- at beregne genotype-og allelfrekvenser   for autosomale og kønsbundne loci med codominans mellem allelerne 
  for autosomale loci med dominans mellem allelerne
- at beregne forventede Hardy-Weinberg frekvenser
- at teste for afvigelser fra Hardy-Weinberg frekvenser
- at kvantificere afvigelser fra Hardy-Weinberg frekvenser ved hjælp af   indavlskoefficienten *F*

</br>

### Opgave 1

Betragt de følgende genotypefordelinger i fem autosomale loci (I-V).

</br>


|Locus |11  |12  |22 |Sum |
|:-----|---:|---:|--:|---:|
|I     |100 |0   |0  |100 |
|II    |81  |18  |1  |100 |
|III   |0   |100 |0  |100 |
|IV    |0   |0   |100|100 |
|V     |50  |0   |50 |100 |
 

</br>

Bemærk: Hvis der er afvigelser fra Hardy-Weinberg proportioner i
forskellige loci, kan de selvfølgeligt ikke være noget, der foregår i
den samme population.

1)  Hvad er frekvensen for allel 1 i de fem fordelinger?

<details><summary>Klik for at se svaret (Tænk lidt før du gør det)</summary>
<p>

|Locus  |      |
|:------|:-----|
|I      |1,0   |
|II     |0,9   | 
|III    |0,5   |
|IV     |0,0   | 
|V      |0,5   |
</p>
</details>

2)  Hvilke af de ovenstående fordelinger udviser Hardy-Weinberg
    proportioner og hvilke gør ikke? (Test burde ikke være nødvendig.)
 fem fordelinger?

<details><summary>Klik for at se svaret.</summary>
<p>

|Locus |                                                                        |
|:-----|:---------------------------------------------------------------------- |
|I     | Ja, men kan ikke testes, da antallet af frihedsgrader er 0 til testen  |
|II    | Ja, perfekt overensstemmelse                                           |
|III   | Nej, forventede er ¼, ½, ¼. Stor afvigelse,  χ<sup>2</sup>  = 100      |
|IV    |	Ja, men kan ikke testes, da antallet af frihedsgrader er 0 til testen  | 
|V     | Nej, forventede er ¼, ½, ¼. Stor afvigelse,  χ<sup>2</sup>  = 100      |
</p>
</details>


3)  Hvad kan have forårsaget afvigelser fra Hardy-Weinberg proportioner?

<details><summary>Klik for at se svaret.</summary>
<p>

|Locus|                                                      |
|:----|:---------------------------------------------------- |
|III  |Naturlig selektion i form af overdominant selektion   |
|V    |Indavl eller populationsblanding                      |
</p>
</details>


</br>

###  Opgave 2

Rhesus-systemet er af stor betydning ved blodtransfusioner og kan
forvolde komplikationer ved graviditeter, hvor kvinde og foster har
uforenelige blodtyper. Der findes to fænotyper i Rhesus-systemet:
Rhesus-positiv (Rh+) og Rhesus-negativ (Rh−). Den følgende tabel viser
udspaltninger i Rhesus-systemet hos de tre mulige forældrekombinationer:

</br>


|                     |                | Børn |     |     |
|---------------------|----------------|------|-----|-----|
| Forældrekombination | Antal familier | Rh+  |     | Rh− |
| Rh+ × Rh+           | 73             | 248  |     | 16  |
| Rh+ × Rh−           | 20             | 54   |     | 23  |
| Rh− × Rh−           | 7              | −    |     | 34  |
|                     | Sum hos børn   | 302  |     | 73  |

</br>

 1) Beregn allelfrekvenserne blandt børnene. (Benyt det totale antal
 børn, og husk at nedarvningen af variationen i Rhesus systemet blev
 gennemgået i første øvelsesgang.)
 2) Hvilken antagelse hviler beregningen på?


<details><summary>Klik for at se svaret på de to første spørgsmål.</summary>
<p>

Blandt de 375 børn har vi 302 Rh+ og 73Rh− individer. Under antagelse af Hardy-Weinberg-proportioner kan vi beregne frekvensen af den recessive allel. Det forventede antal rhrh individer, N(Rh−), er givet ved

Rh- = *Nq*<sup>2</sup>

så vi kan beregne allelfrekvensen som

*q* = √(N(Rh-)/N)
 

 Frekvensen af Rh-allelen findes som
 
*q* = √(73/375)=0,441

Vi har ingen mulighed for at teste for Hardy-Weinberg-proportioner blandt børnene, da vi beskriver deres fænotypefordeling med en enkelt frihedsgrad; summen af de to fænotyper er jo givet. Ligeledes beskrives allelfrekvensen med en enkelt frihedsgrad, da deres sum er 1. Der er ingen frihedsgrad tilovers til testen. De observerede og forventede er lig med hinanden. 

</p>
</details>


Ved fødsler brister placentabarrieren, hvorved der trænger lidt af
fostrets blod over i moderen. En Rhesus-negativ kvinde, som føder sit
første Rhesus-positive foster, bliver derved immuniseret mod fostrets
antigen og danner antistoffer. Ved næste graviditet transporteres disse
antistoffer til fostret via placentaen og skader fostret. Nu til dags
kan man dog forebygge de fleste forekomster af sygdommen.

 c\) Mod hvilken genotype virker selektionen, som skyldes Rhesus-sygdommen?

<details><summary>Klik for at se svaret.</summary>
<p>

Selektionen opstår, når Rhesus-negative kvinder får Rhesus-positive børn. Moderens genotype er jo rhrh, og da hun altid afleverer allelen rh til sit barn, må det have genotypen Rhrh, når det har fænotypen Rhesus-positiv. Naturlig selektion virker derfor mod heterozygoter, der er tale om underdominant selektion. Denne form for selektion er ustabil, hvor vi forventer at systemet fikseres for enten den ene eller den anden allel. Det er uklart, hvad der har opretholdt polymorfien. Med de medicinske behandlinger, der findes i dag, må man nok antage, at der ikke længere er forskel i de tre genotypers fitness.
</p>
</details>


</br>

### Opgave 3
 <figure>
  <img  align="right" src="HWSilene.png" width=100 title="*Avena*">
 </figure>

Nikkende limurt (*Silene nutans*) er en hermafroditisk selvkompatibel[^2] plante. I en under­søgelse af planten fandt man den følgende genotypefordeling i et enzymlocus hos henholdsvis nyspirede frøplanter samt hos
frøproducerende voksne planter i en population fra Langtved:

</br>

|                 | 11     |  12   |22 |Sum|
|:--------------- | ------ | ----- |-- |---|
|Frøplanter       | 79     |  43   |21 |143|
|Voksne           | 55     |  47   |10 |112|

</br>


 a\) Bestem allelfrekvenserne hos begge grupper.

<details><summary>Klik for at se svaret.</summary>
<p>

Frøplanter: 

*p*(1)  = (2 × 79 + 43) / (2 × 143) = 0,703

*q*(2)  = (2 × 21 + 43) / (2 × 143) = 0,297

Tilsvarende beregning for voksne.

*p*(1)  = (2 × 55 + 47) / (2 × 112) = 0,701

*q*(2)  = (2 × 10 + 47) / (2 × 112) = 0,299
</p>
</details>

b\) Er allelfrekvenserne forskellige hos de to grupper? (Test er ikke
nødvendig)

<details><summary>Klik for at se svaret.</summary>
<p>
Nej. Man kunne lave en 2 × 2 kontingenstest på antallet af alleler i de to grupper. Den ville acceptere at de er ens.
</p>
</details>

 c\) Stemmer genotypefordelingerne overens med Hardy-Weinberg proportioner for hver af grupperne?
 
<details><summary>Klik for at se svaret.</summary>
<p>

De forventede antal under antagelse af Hardy-Weinberg proportioner beregnes på følgende måde (for frøplanter):

|Genotype |11                      | 12                  | 22                     |Sum  |
|-------- |:---------------------: |:-------------------:|:----------------------:|:---:|
|O        |79                      | 43                  | 21                     |143  |
|E        |*p*<sup>2</sup>*N*      | 2*pqN*              |*q*<sup>2</sup>         |*N*  |
|         |=                       |  =                  | =                      |     |
|         |0,703<sup>2</sup> × 143 |  2×0,703 ×0,297×143 | 0,297<sup>2</sup> × 143|143  |
|         |=                       |  =                  | =                      |     |
|         |70,63                   |  59,74              | 12,63                  |143  |
</br>

Bemærk det store overskud af homozygoter – som er lige store for hver af homozygoterne. Overensstemmelse med Hardy-Weinberg proportioner testes ved hjælp af en χ<sup>2</sup> test, hvor teststørrelsen findes som

$$
\chi^2 =\sum_{i=1}^3\frac{(O_i-E_i)^2}{E_i}
$$
som for frøplanternes tilfælde bliver
$$
\chi^2 =\frac{(79-70,63)^2}{70,63}+\frac{(43-59,74)^2}{59,74}+\frac{21-12,63}{12,63}=12,23
$$
Teststørrelsen er derfor signifikant på 5% niveauet, når den overstiger 3,84. Dette er tilfældet for frøplanterne, så vi forkaster hypotesen om Hardy-Weinberg proportioner for dem.

For de voksne er resultatet 

|Genotype|      |11   |	12   |	22    |
|--------|:---- |:----|:-----|:------|
|Voksne	 |O	    |55   |	47   |	10    |
|        |E     |55,02| 46,96|	10,02 |

χ<sup>2</sup> = 0,00, dvs. der er HW-proportioner.
</p>
</details>

 d\) Bestem indavlskoefficienten *F* for begge grupper. [*F* =
 (*H<sub>e</sub>* – *H<sub>o</sub>*)/*H<sub>e</sub>*, hvor
 *H<sub>e</sub>* og *H<sub>o</sub>* er henholdsvis forventet og
 observeret hyppighed af heterozygoter. Når *F* er positiv, er der
 overskud af homozygoter i forhold til Hardy-Weinberg proportioner, og
 hvis den er negativ, er der overskud af heterozygoter i forhold til
 Hardy-Weinberg proportioner.

<details><summary>Klik for at se svaret.</summary>
<p>

Indavlskoefficient

Frøplanter:  *F* =  (59,74 – 43)/ 59,74 =   0,280

Voksne: *F* =  (46,96 – 47)/ 46,96 = –0,001

</p>
</details>

e) Hvad kan have forårsaget en eventuel afvigelse fra Hardy-Weinberg
 propor­tioner?


<details><summary>Klik for at se svaret.</summary>
<p>

*Silene nutans* er selvkompatibel. Den har produceret frø ved delvis selv-bestøvning, hvilket forklarer overskuddet af homozygoter blandt frøplanter.

</p>
</details>

Antag, at de voksne som frøplanter havde samme afvigelse fra
Hardy-Weinberg proportioner, som observeres hos frøplanter.

 f\) Forklar, hvad der sker fra frøplante-stadiet til voksenstadiet.

<details><summary>Klik for at se svaret.</summary>
<p>

Fra frøplantestadiet til voksenstadiet bliver alle individer, der produceret ved selvbestøvning, elimineret. De lider af så meget indavlsdepression, at de dør inden de når voksenstadiet.
</p>
</details>

</br>

### Opgave 4

En stikprøve af katte i Singapore havde følgende fordeling af pelsfarven:

</br>


|        | Mørk | Middel | Lys | Sum |
|--------|------|--------|-----|-----|
| Hunner | 63   | 55     | 12  | 130 |
| Hanner | 74   | 0      | 38  | 112 |

</br>

Der er åbenlys forskel på hanner og hunner. Lad derfor være med at slå
dem sammen. Start med at analysere hunnerne for sig:

a\) Bestem allelfrekvenserne, *p*(♀, M) og *p*(♀, L), og test om genotypefordelingen stemmer overens med Hardy-Weinberg forventningerne.

<details><summary>Klik for at se svaret.</summary>
<p>

Vi bestemmer allelfrekvenserne som

p(♀, M) = (2 × 63 + 55) / (2 × 130) = 0,696

p(♀, L)  = (2 × 12 + 55) / (2 × 130) = 0,304

Lad os så teste, om hunnernes genotypefordeling stemmer overens med den forventede Hardy-Weinberg-fordeling.

|           |MM	   |ML	  |LL   |Sum |
|:----------|:-----|:----|:----|:---|
|Observeret	|63	   |55   |	12	 |130 |
|Forventet	 |63,00	|55,00|12,00|130 |

Vi ser en perfekt overensstemmelse med Hardy-Weinberg proportioner, så en test er unødvendig. Den ville resultere i en χ<sup>2</sup>-værdi på 0.


</p>
</details>

Hos hannernes observeres der slet ikke fænotypen Middel.

b\) Bestem frekvensen af de to observerede fænotyper hos hannerne.

<details><summary>Klik for at se svaret.</summary>
<p>

*f*(♂, mørk) = 74/112 = 0,661

*f*(♂, lys)  = 38/112 = 0,339


</p>
</details>

c)  Sammenlign frekvensen af de to alleler hos hunnerne med frekvensen    af de to fænotyper hos hannerne. (Kvalitativt – en test skal ikke     laves.) Giv en forklaring på, hvordan farverne nedarves hos katte.

<details><summary>Klik for at se svaret.</summary>
<p>

Allelfrekvenserne hos hunnerne er meget tæt på fænotypefrekvenserne for mørk og lys hos hannerne.
Da fænotypen Middel slet ikke observeres hos hannerne, tyder det på, at genet for farver er kønsbundet på X-kromosomet. Hunnerne og hannerne har så genotyperne givet i den følgende tabel

|Køn      |	Mørk	|Middel|	Lys|
|---      |:-------:|:------:|:---:|
|Hunner	|*X*<sub>M</sub>*X*<sub>M</sub>M|*X*<sub>M</sub>*X*<sub>L</sub>|*X*<sub>L</sub>*X*<sub>L</sub>
|Hanner	|*X*<sub>M</sub>*Y*||	  	*X*<sub>L</sub>*Y*|


</p>
</details>


</br>

### Opgave 5 (for nørder)
 <figure>
  <img  align="right" src="HWJaera.jpg" width=130 title="*Jaera*">
 </figure>

På danske strande med forekomst af sten, på høfder og i algebevoksninger
kan man finde arter af isopod-slægten *Jaera*. De er ret små; hannerne
op til 3 mm og hunnerne op til 5 mm. (Billedet viser en hun.) I en prøve
indsamlet i Nivå bugt fandtes den følgende fordeling af variation i et
enzymlocus hos arten *Jaera ischiosetosa*:

</br>

|Køn      |11| 12| 22 |Sum|
|:--------|--:|---:|---:|--:|
|Hunner |0 |99| 0| 99|
|Hanner | 0| 0| 93| 93|

</br>

a)  Er genotypefordelingerne i de to køn betragtet uafhængigt af  hinanden og som sum over de to køn i overensstemmelse med  Hardy-Weinberg proportioner? (Det er ikke nødvendigt, at udføre en   formel *χ*<sup>2</sup>-test.)
<details><summary>Klik for at se svaret.</summary>
<p>

Hunner: Nej; der kan ikke observeres lutter heterozygoter under antagelse af HW-fordeling i et autosomalt locus.

Hanner: Ja; men vi kan ikke fortage en formel test, da df = 0.

Samlet: Nej, vi kan ikke have 99 heterozygoter og 93 homozygote 22 uden at observere nogen 11 homozygoter.


</p>
</details>


Der er også undersøgt tre andre loci, der alle viste overensstemmelse
med Hardy-Weinberg proportioner, så man kan gå ud fra, at der synes at
være tilfældig parring i populationen.

b)  Forklar, hvordan den i tabellen fundne variation nedarves.

<details><summary>Klik for at se svaret.</summary>
<p>

Da der er forskel mellem kønnene må vi formode, at det studerede locus er kønsbundet.  Hunnerne er alle heterozygote, medens hannerne alle er homozygote. Vi konkluderer derfor, at hunnerne er det heterogametiske køn (*ZW*) og hannerne det homogametiske køn (*ZZ*). De to kønskromosomer er blevet fikseret for henholdsvis allel 2 (*Z*) og allel 1 (*W*). Vi får derfor fordelingen 

Køn |			11	|	12	|	22	|	Sum|
|:-----|:------:|:-----:|:------:|:------:|
|Hunner	|  	  0|		*Z*<sub>2</sub>*W*<sub>1</sub>|		  0	|	   99|
|Hanner	|	  0|		  0	|	*Z*<sub>2</sub>*Z*<sub>2</sub>|		   93|


</p>
</details>


</br>

## Variation i to loci
Disse opgaver har deres fokus på

- at beregne haplotypefrekvenser for to loci ud fra allelfrekvenser i de   enkelte loci for tilfældet med koblingsligevægt (*D* = 0).

- at undersøge populationsstrukturens effekt på dannelse af   koblingsuligevægt

### Opgave 6

Betragt en population, hvor der variation i to loci. Frekvensen af allel
*A* i locus *A* er 0.7. Frekvensen af allel *a* er 0.3. I det andet
locus, *B*, er frekvensen af allel *B* 0.8, og frekvensen af allel *b*
er 0.2. De to loci er i koblingsligevægt.

a)  Hvad er frekvensen af de fire mulige haplotyper?
<details><summary>Klik for at se svaret.</summary>
<p>


*f*<sub>AB</sub> = 0.7 × 0.8 = 0.56

*f*<sub>Ab</sub> = 0.7 × 0.2 = 0.14

*f*<sub>aB</sub>  = 0.3 × 0.8 = 0.24

*f*<sub>ab</sub>  = 0.3 × 0.2 = 0.06


</p>
</details>


</br>


### Opgave 7

En uerfaren biolog har taget en stikprøve fra to populationer I og II. Population I er fikseret for allel *A* i locus *A*, d.v.s alle er *AA*. Den er ligeledes fikseret for allel *B* i locus *B*, d.v.s alle er *BB*. Den anden population (II) er fikseret for forskellige alleler i de to loci, d.v.s alle er *aa* og *bb*. Problemet er, at han ikke vidste, at der var to forskellige populationer. Han har taget det samme antal stikprøver i hver population.

a)  Hvilke haplotyper findes i den samlede stikprøve og hvad er deres
    frekvens?
<details><summary>Klik for at se svaret.</summary>
<p>

*f*<sub>AB</sub> = 0.5

*f*<sub>Ab</sub> = 0.0

*f*<sub>aB</sub>  = 0.0

*f*<sub>ab</sub>  = 0.5


</p>
</details>



b)  Hvad er “coefficient of linkage disequilibrium” *D* i dette  tilfælde?
<details><summary>Klik for at se svaret.</summary>
<p>

 *D* = *f<sub>AB</sub> - *p*<sub>A</sub> x p<sub>B</sub> = 0,5-0,5 x 0,5 = 0,25

</p>
</details>


 
[^1]: Marshall & Allard (1970) Maintenance of isozyme polymorphism in
    natural populations of *Avena barbata*. *Genetics* 66: 393–399.

[^2]: Dvs, den er i stand til at bestøve sig selv.
