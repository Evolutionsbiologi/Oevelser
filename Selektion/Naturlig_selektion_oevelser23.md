

## Naturlig Selektion

<br>

### Hans R. Siegismund
<br>

### Teoretisk baggrund
Darwin's evolutionsteori fra 1859 var i det væsentlige baseret på
naturlig selektion, som sker på baggrund af nogle simple observationer:

- **Variation:** Individerne i en population er forskellige fra hinanden
- **Arv:** Variationen er til dels arvelig.
- **Forskel i reproduktiv succes:** Individer med bestemt træk overlever
  og reproducerer sig med større succes end individer uden disse træk.

Med disse tre principper var Darwin i stand til at forklare evolutionen
ved naturlig selektion. Han argumenterede, at en population af en given
art indeholder individer, der varierer i karakterer af betydning for
tilpasningen til deres miljø. De bedst tilpassede individer har større
chancer for at overleve og reproducere sig. På grund af arv vil de
derfor delvist videregive egenskaberne til næste generation, som så vil
være bedre tilpasset til miljøet end forældrene var det i generationen
før

 <figure>
  <img  align="right" src="SelDarwin.png" width=225 title="Darwin">
 </figure>

Vi vil nu se på, hvorledes Darwin’s tre principper kan formuleres mere
præcist. Betragt en diploid organisme, der er polymorf i et autosomalt
locus med to alleler, *A*<sub>1</sub> og *A*<sub>2</sub>. Den antages at
have ikke-overlappende generationer. Vi ønsker at beskrive en model for,
hvordan naturlig selektion virker på polymorfien. Vi indskrænker os til
en model, hvor vi analyserer naturlig selektion, der virker gennem
forskellig overlevelse hos de tre mulige genotyper. Deres sandsynlighed
for at overleve til det voksne stadium er givet i form af deres
***fitness***, *W*<sub>11</sub>,*W*<sub>12</sub> og *W*<sub>22</sub>.
Det antages at hver generation starter med tilfældig sammensmeltning af
gameter. Vi får derfor, at zygoterne starter deres liv med
Hardy-Weinberg proportioner, se tabellen nedenfor. De overlevende f.eks.
for *A*<sub>11</sub> er så *p*<sup>2</sup>*W*<sub>11</sub>. For at finde
hyppighederne blandt de overlevende må vi dividere med summen af de
overlevende,

$$
 \overline{W} =p^2W_{11}+2pqW_{12}+q^2W_{12} 
$$

der sigende betegnes som ***populationens gennemsnitlige fitness***. Man
kan så finde næste generations frekvens for allel *A*<sub>1</sub> som

$$
\begin{aligned}
     p'&=(p^2W_{11}+2pqW_{12}/2)/\overline{W}\\  
       &= (p^2W_{11}+pqW_{12})/\overline{W}  
\end{aligned}
$$

Frekvensen for allel *A*<sub>2</sub> bestemmes tilsvarende. Det hele kan
sammenfattes i den følgende tabel

|                |*A*<sub>11</sub>|*A*<sub>12</sub>|*A*<sub>22</sub> |Sum          |
|----------------|:--------------:|:--------------:|:--------------: |:-----------:|
|Zygoter         |*p*<sup>2</sup> |2*p  q*         |*q*<sup>2</sup>  |1            |
|Fitness         | *W*<sub>11</sub>|*W*<sub>12</sub>| *W*<sub>22</sub>|             |
|Overlevende     |*p*<sup>2</sup>*W*<sub>11</sub>| 2*pqW*<sub>12</sub>|*q*<sup>2</sup>*W*<sub>22</sub>|$\overline{W}$|
|Frekvens        |*p*<sup>2</sup>*W*<sub>11</sub>/ $\overline{W}$ |2*pqW*<sub>12</sub>/ $\overline{W}$|*q*<sup>2</sup>*W*<sub>22</sub>/ $\overline{W}$ |1      |
|Næste generation| *p’*<sup>2</sup> |2*p’q’*|*q’*<sup>2</sup>| 1|

Vi kan nu gentage hele processen for at finde allelfrekvenserne i den
næste generation. Det foregår på tilsvarende vis som angivet foroven.
Man kan ikke finde en generel løsning på iterationsligningerne, hvor
allelfrekvenserne i en vilkårlig generation *n* kan udtrykkes som en
funktion af allelfrekvenserne i generation 0 samt de genotypiske
fitness-værdier *W*<sub>11</sub>, *W*<sub>12</sub> og *W*<sub>22</sub>.
Selv om man ikke kan finde en generel løsning, er det dog muligt at
analysere selektionens virkning på polymorfien. Dette gøres ved at se på
ændringen af allelfrekvensen. For allel *A*<sub>1</sub> kan denne
ændring beregnes som

$$
\begin{aligned}
\Delta p &= p'-p\\
&=(p^2W_{11}+2pqW_{12}/2)/\overline{W} -p\\  
&= pq[(p(W_{11} - W_{12}) -q(W_{22}-W_{12})]/\overline{W}  
\end{aligned}
$$

(Efter nogle udregninger.) Vi ønsker at finde eventuelle ligevægte, hvor
der må gælde at

$$
\begin{aligned}
\Delta p &= pq[(p(W_{11} - W_{12}) -q(W_{22}-W_{12})]/\overline{W}  \\
         &=0
\end{aligned}
$$

Der findes tre mulige ***ligevægte***. To trivielle, hvor enten *p* = 0,
eller hvor *q* = 0. Det vil sige, hvis det studerede locus er fikseret
for enten den ene eller den anden allel. Den tredje mulige ligevægt
eksisterer, hvis ligningen

$$
p(W_{11} - W_{12}) -q(W_{22}-W_{12})=0
$$

har en løsning med allelfrekvenserne i intervallet fra 0 til 1.
Ligningen kan løses efter *p* (hvor vi husker, at *q* = 1 – *p*).

$$
p= \frac{W_{22}-W_{12}}{ W_{11} - W_{12}+W_{22}-W_{12}}
$$

Der findes to løsninger med allelfrekvenserne i intervallet mellem 0 og
1, nemlig én hvis

$W_{11} > W_{12}$
og
$W_{22} > W_{12}$, 

det vil sige, at heterozygoten har mindre fitness end begge homozygoter.
En anden mulighed er, hvis

$W_{11} < W_{12}$
og
$W_{22} < W_{12}$, 

det vil sige, at heterozygoten har større fitness end begge homozygoter.
Vi vender tilbage til disse løsninger senere.

For et autosomalt locus med to alleler, hvorpå der virker
overlevelsesselektion på genotyperne, findes der fire principielle
muligheder for selektionens virkning.

**1) Retningsselektion** 
$W_{11} \ge W_{12} \ge W_{12}$
med højst ét lighedstegn.  

 <figure>
  <img  align="right" src="SelRetning1.png" width=150 title="Retning1">
 </figure>

Der må højst være ét lighedstegn i relationen mellem de tre
fitness-værdier, for ellers har alle tre genotyper de samme
fitness-værdier, og så virker naturlig selektion ikke på dette locus. I
dette tilfælde vil naturlig selektion øge frekvensen af allel
*A*<sub>1</sub>, indtil den fikseres i populationen. Der findes to
ligevægte for allel *A*<sub>1</sub>.

0: som er ***ustabil***, dvs, hvis man ændrer frekvensen af
*A*<sub>1</sub> lidt fra 0, vil den bevæge sig bort fra 0.

1: som er ***stabil***, dvs, hvis man ændrer frekvensen af allel
*A*<sub>1</sub> lidt fra 1, vil den bevæge sig tilbage til 1.


**2) Retningsselektion**  $W_{11} \le W_{12} \le W_{12}$
med højst ét lighedstegn
<figure>
  <img  align="right" src="SelRetning2.png" width=150 title="Retning2">
 </figure>
 
Dette system er ækvivalent til det første, nu vil naturlig selektion øge
frekvensen af allel *A*<sub>2</sub>. Der findes to ligevægte
for allel *A*<sub>1</sub>

0: som er ***stabil***, dvs, hvis man ændrer frekvensen af
*A*<sub>1</sub> lidt fra 0, vil den bevæge sig tilbage til 0.

1: som er ***ustabil***, dvs, hvis man ændrer frekvensen af allel
*A*<sub>1</sub> lidt fra 1, vil den bevæge sig bort fra
1.

**3) Underdominans** *W*<sub>11</sub> > *W*<sub>12</sub> og *W*<sub>22</sub> > *W*<sub>22</sub>

<figure>
  <img  align="right" src="SelUnderD.png" width=150 title="Under">
 </figure>

I dette tilfælde har heterozygoten en mindre fitness end begge
homozygoter. Der er tale om ***underdominans***. Evolutionen i et locus
med denne relation mellem genotypernes fitness forløber fundamentalt
anderledes end i de ovennævnte tilfælde. Vi har nu ***tre ligevægte***
for polymorfien.

0:som er ***stabil***, dvs, hvis man ændrer frekvensen af allel
*A*<sub>1</sub> lidt fra 0, vil den bevæge sig tilbage til 0.

1: som er ***stabil***, dvs, hvis man ændrer frekvensen af allel
*A*<sub>1</sub> lidt fra 1, vil den bevæge sig tilbage til 1

*p* = (*W*<sub>22</sub> - *W*<sub>12</sub>)/(*W*<sub>11</sub> - *W*<sub>12</sub> + *W*<sub>22</sub> - *W*<sub>12</sub>)
som er en ***ustabil ligevægt***, dvs, hvis man ændrer frekvensen af allel
*A*<sub>1</sub> lidt fra ligevægten, vil den bevæge sig bort fra den.

I dette system vil vi ende op med en allelfrekvens af *A*<sub>1</sub> på
enten 0 eller 1, afhængigt af, om ceder startes under eller over den
ustabile ligevægt.


**4) Overdominans**  *W*<sub>11</sub> < *W*<sub>12</sub> og *W*<sub>22</sub> < *W*<sub>22</sub>

<figure>
  <img  align="right" src="SelOverD.png" width=150 title="Over">
 </figure>
I dette tilfælde har heterozygoten en større fitness end begge
homozygoter. Der er tale om overdominans. Vi har nu igen tre
ligevægtee for polymorfien, men i modsætning til underdominans har vi
nu en indre ligevægt

*p* = (*W*<sub>22</sub> - *W*<sub>12</sub>)/(*W*<sub>11</sub> - *W*<sub>12</sub> + *W*<sub>22</sub> - *W*<sub>12</sub>)
som er en ***stabil ligevægt***, dvs, hvis man ændrer frekvensen af allel
*A*<sub>1</sub> lidt fra ligevægten, vil den bevæge sig tilbage til den.

0: som er ***ustabil***, dvs, hvis man ændrer frekvensen af allel
*A*<sub>1</sub> lidt fra 0, vil den bevæge sig bort fra 0 og hen mod den
stabile ligevægt.

1: som er ***ustabil***, dvs, hvis man ændrer frekvensen af allel
*A*<sub>1</sub> lidt fra 1, vil den bevæge sig bort fra 1 og hen mod den
stabile ligevægt.

I dette system vil vi ende op med en frekvens af allel *A*<sub>1</sub>,
som er givet ved formlen foroven, uafhængigt af om der startes under
eller over den stabile ligevægt. Man kan vise, at det kun er de
***relative fitnessværdier***, der betyder noget for evolutionen: det
vil sige, det er lige meget om *A*<sub>11</sub>, *A*<sub>12</sub> og
*A*<sub>22</sub> har fitnessværdierne 10, 20, og 10 eller 1, 2 og 1.
Derfor kan vi normere værdierne, hvor vi sætter den højeste værdi til 1.
I det nævnte tilfælde bliver værdierne så ½, 1 og ½. Generelt kan vi
udtrykke fitnessværdierne som i følgende tabel

|Genotype             |*A*<sub>11</sub>|*A*<sub>12</sub> |*A..*<sub>22</sub>|
|---------------------|:--------------:|:---------------:|:----------------:|
|Fitness              |*W*<sub>11</sub>| *W*<sub>12</sub>|*W*<sub>22</sub>  |
|Relativ fitness      |1 – *s*         |1                | 1 – *t*          |
|Selektionskoefficient|*s*             | 0               | *t*              |

Fitnessværdiernes difference fra 1 betegner vi som
***selektionskoefficent***. Vi kan derfor udtrykke ligevægtspunktet for
overdominans ved hjælp af selektionskoefficienterne *s* og *t.*

$$
\begin{aligned}
p &= \frac{W_{22}-W_{12}}{W_{11} - W_{12}+W_{22}-W_{12}}\\
  &= \frac{1-t-1}{1-s-1+1-t-1}\\
  &= \frac{-t}{-s-t}\\
  &= \frac{t}{s+t}
\end{aligned}
$$

### Ændring i populationens gennemsnitlige fitness

Darwin’s grundlæggende observation var, at de bedst tilpassede individer
overlever og forplanter sig med en større sandsynlighed end andre. Da
forskellen er delvis genetisk betinget, må den følgende generation være
bedre tilpasset. En essentiel følge heraf er, at populationens
gennemsnitlige tilpasning vokser generation for generation. Vi vil her
se på, hvorledes dette er relateret til modellerne for zygotisk
selektion, som er beskrevet foroven.

Lad os tage et simpelt eksempel, hvor de tre genotypers fitness kan
beskrives som

|                     |*A*<sub>11</sub> |*A*<sub>12</sub>|*A*<sub>22</sub>|
| --------------------|:---------------:|:--------------:|:--------------:|
| Relativ fitness     |0,6              |1               |0,4             |
|Selektionskoefficient| 0,4             |0               | 0,6            |

<figure>
  <img  align="right" src="SelAveW.png" width=250 title="SelAve">
 </figure>
 
For dette simple system ses, at ligevægten er *p* = 0,6/(0,4 + 0,6) =
0,6. Ligegyldigt hvor vi starter med frekvensen af allel
*A*<sub>1</sub>, så ender vi op i ligevægtspunktet. Vi afbilder nu
populationens gennemsnitlige fitness

$$
 \overline{W} =p^2W_{11}+2pqW_{12}+q^2W_{12} 
$$

som funktion af allelfrekvensen, hvilket er gjort i figuren.
Når *p* = 0 er der udelukkende *A*<sub>22</sub> i populationen, som har
en
$\overline{W}$ på
0,4, og når populationen er fikseret for *A*<sub>1</sub>, så er
$\overline{W}$*=*
0,6. Vi ser, at
$\overline{W}$ 
har
sit maksimum i ligevægten 0,6. Dermed stemmer evolutionen i dette simple
system fint overens med vores intuition for evolution gennem naturlig
selektion. ***Naturlig selektion virker ved at øge den gennemsnitlige
fitness over tid. Den har sit maksimum i den stabile ligevægt.*** Dette
gælder også for de øvrige tilfælde, retningsselektion og underdominans.

I tilfældet med underdominans kan det dog hænde, at naturlig selektion
ikke ender med et ***globalt maksimum*** for $\overline{W}$,
men kan ende op i et ***lokalt maksimum*** for
$\overline{W}$.
Lad os tage et simpelt eksempel, hvor de tre genotypers fitness kan
beskrives som

|Genotype              |*A*<sub>11</sub>|*A*<sub>12</sub> |*A*<sub>22</sub>|
|----------------------|:--------------:|:---------------:|:--------------:|
|Relativ fitness       |1,4             |  1              |1,6             |
|Selektionskoefficient |–0,4            |0                |–0,6            |


<figure>
  <img  align="right" src="SelAveWUnderD.png" width=275 title="SelAve">
 </figure>
 
 Her
 skal vi ikke lade os forstyrre af de negative
selektionskoefficienter. Det betyder blot, at de to homozygoter har en
højere fitness end heterozygoten. Her er ligevægten *p* = –0,6/(–0,4 –
0,6) = 0,6. Afbildes  som
funktion af frekvensen af allel *A*<sub>1</sub>, får vi figuren til
højre. Det ses, at når vi starter med en frevens af allel
*A*<sub>1</sub> under ligevægtsfrekvsensen, ender vi med en fiksering af
allel *A*<sub>2</sub>, medens vi får fikseret allel *A*<sub>1</sub>, når
vi starter med en frekvens over ligevægten. Naturlig selektion øger
altid den gennemsnitlige fitness i populationen, men vi kan til tider
ende op i et lokalt maksimum.

### Ligevægt mellem mutation og selektion

Langt de fleste mutationer i kodende gener viser sig at være skadelige.
De skadelige mutationer vil for den største dels vedkommende blive
elimineret gennem naturlig selektion. Efter “tilstrækkelig” lang tid vil
der i en uendelig stor population opstå en ***ligevægt mellem mutation
og naturlig selektion***. Sandsynligheden for tilbagemutation til den
oprindelige allel anses for at være så lille, at den kan negligeres. Vi
får derfor et system, hvor en “vildtype”-allel muterer med raten *μ* per
generation til en skadelig allel. Frekvenserne af vildtype- og
sygdomsallel er henholdsvis *p* og *q*. Vi antager, at effekten af de
skadelige alleler ytrer sig som nedsat overlevelse for bærerne eller i
værste fald som letalt hos de bærere, hvor allelen kommer til udtryk.
Antag, at allelfrekvensen blandt de overlevende, som producerer næste
generations zygoter, er *p*, der med raten *μ* muterer til den skadelige
allel. Mængden af ny-introducerede skadelige alleler i næste generation
er så

$$ \Delta  q(\mu) = p\mu$$

Samtidigt fjernes der i hver generation skadelige alleler på grund af
deres bæreres nedsatte overlevelse. Måden, det sker på, er forskelligt
for tilfældene med dominans eller recessivitet hos den skadelige allel.
De to tilfælde gennemgås derfor særskilt.

### Recessive skadelige gener 
Her kan de tre genotypers fitness beskrives som

|                     |*A*<sub>11</sub>  |*A*<sub>12</sub> |*A*<sub>22</sub>|
|---------------------|:----------------:|:---------------:|:--------------:|
|Relativ fitness      |1                 | 1               |1 – *s*         |
|Selektionskoefficient|0                 | 0               | *s*            |                      

Hvor *s* er selektionskoefficienten mod den recessive homozygote bærer.
Antag nu, at polymorfien befinder sig i ligevægt mellem mutation og
selektion. Zygoterne antages at være blevet produceret gennem tilfældig
sammensmeltning af gameter, som resulterer i Hardy-Weinberg
-proportioner blandt dem. Naturlig selektion vil i hver generation
fjerne det følgende antal skadelige alleler fra populationen


$$ \Delta q(sel) = q^2s$$

I ligevægt mellem mutation og selektion må vi have, at


$$
\begin{aligned}
\Delta q(sel) &= q^2s\\
q^2s&= p\mu  
\end{aligned}
$$

Da *p* er tæt på 1, vil vi have

$$q^2\approx \mu$$

som løses til

$$ q =\sqrt{ \mu/s}$$

### Dominante skadelige gener
Her er de tre genotypers fitness givet med

|                |*A*<sub>11</sub> | *A*<sub>12</sub> |*A*<sub>22</sub>|
| ---------------|:---------------:|:----------------:|:--------------:|
| Relativ fitness|1                |1 – *s*           |1 – *x*         |
|Selektionskoefficient| 0          |*s*               |*x*             |

Hvor *s* er selektionskoefficienten mod den dominante heterozygote
bærer, og *x* er selektionskoefficienten mod den dominante homozygote
bærer. Vi benytter *x*, som vi ikke kender, fordi *A*<sub>22</sub>
homozygoten forventes at være så sjælden, at den ikke optræder i
populationen. Som før, så antager vi, at polymorfien befinder sig i
ligevægt mellem mutation og selektion. Bidraget fra mutationer er det
samme som nævnt før, medens naturlig selektion i hver generation vil
fjerne det følgende antal skadelige alleler fra populationen

$$
\begin{aligned}
\Delta q(sel) &= 2pqs/2\\
s&= pqs  
\end{aligned}
$$

Her dividerer med 2, da hver heterozygot kun bærer en *A*<sub>2</sub>
allel. Vi husker på, at *p* er tæt på 1. I ligevægt mellem mutation og
selektion må vi have, at


$$ sq\approx \mu$$

som løses til

$$ q = \mu/s$$

Der er stor forskel i allelernes ligevægtsfrekvenser, afhængig om det er
en recessiv eller en dominant skadelig mutation. Betragt et autosomalt
locus med en letal allel, dvs. *s* = 1, hvor mutationsraten er
10<sup>-6</sup>. Her er

$$
\begin{aligned}
q_{rec}&=  \sqrt{\mu/s}\\
       &=  \sqrt{10^{-6}/1}\\
       &= 0,001\\
q_{dom}&=  \mu/s\\
       &=  10^{-6}/1\\
       &= 0,000.001
\end{aligned}
$$

Dvs., den dominante allel er tusind gange mere sjælden end en skadelig
recessiv allel.


## Naturlig Selektion øvelse

### Formål
- Analysere naturlig selektions virkning på det haploide og diploide
  niveau
- Analysere frekvensafhængig og frekvensuafhængig selektion
- Estimere fitness for genotyper under antagelse af ligevægt ved
  overdominant selektion
- Analysere samspil mellem naturlig selektion og mutation

### Opgave 1

<figure>
  <img  align="right" src="SelTrifolium.png" width=150 title="Trifolium">
 </figure>
 
 Mange plantearter har udviklet mekanismer, der forhindrer
selvbestøvning. I det gametofytiske selvuforeneligheds-system er det
pollenets egen genotype, der afgør, om det kan spire på en given plante.
I et autosomalt locus *S* kan der være allelerne *S*<sub>1,</sub>
*S*<sub>2</sub>, *S*<sub>3</sub>,...*S<sub>n</sub>*. Et pollenkorn, der
bærer allelen *S<sub>i</sub>*, vil ikke være i stand til at spire på
planter, der også bærer denne allel. Betragt for eksempel planterne
*S*<sub>1</sub>*S*<sub>2</sub> og *S*<sub>1</sub>*S*<sub>3</sub>. Her
vil der på *S*<sub>1</sub>*S*<sub>3</sub> planten kun kunne spire pollen
fra *S*<sub>1</sub>*S*<sub>2</sub> planten, hvis det har genotypen
*S*<sub>2</sub>. Det vil sige, at kun halvdelen af pollenet fra
*S*<sub>1</sub>*S*<sub>2</sub> planten vil være i stand til at spire på
*S*<sub>1</sub>*S*<sub>3</sub>
planten.

I nogle arter af kløver, *Trifolium*, styres befrugtningen af et
gametofytisk selvuforeneligheds-system som beskrevet ovenfor.

1)  Kan de forskellige genotyper i et locus med
    selvuforeneligheds-alleler forventes at optræde i Hardy-Weinberg
    proportioner? Hvorfor, eller hvorfor ikke?

<details><summary>Klik for at se svaret.</summary>
<p>

Det gametofytiske selvuforenelighedssystem er et eksempel på 
***selektion på det haploide niveau***. Med dette system, hvor 
pollen kun kan bestøve en plante, når det bærer en allel i 
selvuforenelighedssystemet, som ikke findes i denne plante i 
forvejen, vil der kun findes heterozygote individer. Det er 
også et eksempel på ***negativ frekvensafhængig selektion***, 
hvor pollen, der bærer en sjælden allel, stort set kan spire 
på alle andre planter end moderplanten.

</p>
</details>

2)  Hvad er det mindste antal selvuforeneligheds-alleler i et locus, som
    kræves for at en population af kløver kan formere sig alene ved
    krydsbestøvning?
<details><summary>Klik for at se svaret.</summary>
<p>
<figure>
  <img  align="right" src="SelSelvuforenelighed.png" width=350 title="">
 </figure>

Det minimale antal alleler er 3, med 2 kan der nemlig ikke produceres pollen med en genotype, der ikke i forvejen findes i et individ. Ligevægtsfrekvensen vil være ens for alle alleler i en population.  Ligevægten nås efter ret få generationer, se figuren, der illustrerer et system med 4 alleler, hvor der introduceres en ny mutation, så antallet af alleler bliver 5.
</p>
</details>

### Opgave 2


<figure>
  <img  align="right" src="SelAcrea.png" width=150 title="Trifolium">
 </figure>
 
 Hos fugle og sommerfugle bliver kønnet bestemt kromosomalt. Hunner er
heterogametiske *ZW* og hannerne er homogametiske *ZZ*. I nogle
populationer af den afrikanske sommerfugl *Acraea encedon* optræder der
en mutant af *W*-kromosomet, *W*<sup>\*</sup>. Hunner, der bærer denne
mutant, er fænotypisk normale, men deres afkom er udelukkende døtre. De
får lige så meget afkom som normale
hunner
1)  Hvad sker der med hyppigheden af *W*<sup>\*</sup>-kromosomet, når
    det introduceres i en population (der ses bort fra genetisk drift)?

<details><summary>Klik for at se svaret.</summary>
<p>

Vi har her et tilfælde af ***“meiotic drive”*** eller ***“segregation distortion”*** , hvor ***naturlig selektion virker på det haploide niveau***. Mendel’s første lov bliver ikke overholdt. (Meiotic drive betyder ikke, at vi får en 0 : 1 udspaltning i stedet for Mendelsk 1:1 udspaltning. Det betyder blot, at vi ikke har den normale Mendelske udspaltning.)
Hyppigheden af *W*<sup>\*</sup>-kromosomet vil stige, når det introduceres i en population

</p>
</details>

2)  Hvad sker der med en sådan population?

<details><summary>Klik for at se svaret.</summary>
<p>

Frekvensen af *W*<sup>\*</sup>-kromosomet vil til sidst nå 1, hvor der kun er hunner tilbage i populationen, der så vil uddø.
Polymorfien kan opretholdes i et system af metapopulationer, hvor der 
findes “inficerede” og “uinficerede” populationer. “Inficerede” 
populationer vil efter en tid uddø, hvorpå de koloniseres fra 
“uinficerede” populationer igen. De “uinficerede” populationer vil 
ligeledes med en vis rate modtage individer, der bærer 
*W*<sup>\*</sup>-kromosomet og vil derefter uddø.

</p>
</details>

Man behøver ikke regne for at besvare spørgsmålene!


###  Opgave 3 

Betragt et autosomalt locus med to alleler, der har indflydelse på
bærerens fitness, som angivet i tabellen:

| Genotype  |*A*<sub>1</sub>*A*<sub>1</sub>| *A*<sub>1</sub>*A*<sub>2</sub> |  *A*<sub>2</sub>*A*<sub>2</sub>|
|--------|:----------------------------:|:---------------------:|:-----:|
|Fitness  |0.2                           |1| 0.8|

1)  Hvilken form for selektion foregår? Hvad er selektionskoefficenterne
    for de to homozygoter?
<details><summary>Klik for at se svaret.</summary>
<p>

Overdominant selektion. 	

*A*<sub>1</sub>*A*<sub>1</sub>: *s* = 0.8 

*A*<sub>2</sub>*A*<sub>2</sub>: *t* = 0.2
</p>
</details>

Betragt en population af dyr med tilfældig parring, hvor vi har zygoter
med Hardy-Weinberg proportioner og fitness som angivet ovenfor. Vi
antager at populationen er meget stor og derfor ikke udsættes for
genetisk drift.

2)  Hvor mange ligevægte findes i dette system? Hvor mange stabile, hvor
    mange ustabile? Angiv frekvensen for allel 1 (*p*) for alle mulige
    ligevægte.
<details><summary>Klik for at se svaret.</summary>
<p>

2 ustabile: *p* = 0 og *q* = 1 

1 stabil:  *p = t*/(*s* + *t*) = 0.2/(0.8 + 0.2) = 0.2


</p>
</details>


 Betragt nu en population af en selvbestøvende plante med fitness som
angivet ovenfor. De forplanter sig udelukkende ved selvbestøvning. Vi
betragter det samme locus. Antag, at vi starter med en 1/3 af hver
genotype. Der ses igen bort fra genetisk drift.

3)  Hvordan vil evolutionen i en sådan plante foregå?
<details><summary>Klik for at se svaret.</summary>
<p>

Populationen fikseres for *A*<sub>1</sub>*A*<sub>1</sub>: Heterozygoten har en selektiv fordel, men i hver generation vil den spalte ud med hver homozygot og vil efterhånden forsvinde. Genotype *A*<sub>1</sub>*A*<sub>1</sub> har højere fitness end *A*<sub>2</sub>*A*<sub>2</sub> og vil over tiden blive fikseret.
</p>
</details>


 Betragt nu en population af en apomiktisk plante (som mælkebøtter
f.eks.). I en apomiktisk population er alt afkom af en plante en klon af
moderens genotype. Antag, at vi starter med en 1/3 af hver genotype, og
at fitness er som angivet ovenfor. Der ses igen bort fra genetisk

4)  Hvordan vil evolutionen i en sådan plante foregå?
<details><summary>Klik for at se svaret.</summary>
<p>

Heterozygoten *A*<sub>1</sub>*A*<sub>2</sub> vinder. Den har den højeste fitness og bliver fikseret i populationen.
</p>
</details>

5)  I hvilken af de tre nævnte tilfælde har populationen den højeste
    fitness, når der er opnået en ligevægt?
<details><summary>Klik for at se svaret.</summary>
<p>

I tilfælde for den apomiktiske plante, der bliver fikseret for heterozygoten med fitness 1.

</p>
</details>


### Opgave 4

<figure>
  <img  align="right" src="SelKondor.png" width=300 title="Kondor">
 </figure>
 
Den californiske kondor 
[(*Gymnogyps californianus*)](https://en.wikipedia.org/wiki/California_condor) har efter
europæernes ankomst til Amerika været forfulgt. Det har resulteret i en
drastisk nedgang i bestandens størrelse, som kulminerede i 1987, da de
sidste vilde kondorer blev anbragt i fangenskab (fjorten individer).
Blandt afkommet af disse fjorten individer observeredes den arvelige
sygdom chondrodystrofi (en form for dværgvækst). Hos kondoren er denne
sygdom nedarvet i et autosomalt locus, hvor chondrodystrofien skyldes en
recessiv letal allel.

1)  Hvad har frekvensen af allelen for chondrodystrofi mindst været
    blandt de fjorten individer, der blev brugt til at grundlægge
    bestanden i fangenskab? Husk på, at en recessiv homozygot blandt
    afkommet har modtaget den recessive allel fra begge forældre.
<details><summary>Klik for at se svaret.</summary>
<p>

*q* ≥ 2/(2 x 14) = 0,071.

Der må mindst have været to heterozygoter blandt de fjorten individer.

</p>
</details>

Bestanden er siden hen vokset i antal og er nu oppe på omkring et par
hundrede. En beregning af allelfrekvensen for chondrodystrofi viste en
værdi på 0,09.

1)  Kan hyppigheden af denne letale allel skyldes én af de følgende tre
    kræfter hver for sig? (Der spørges efter en kombination af disse
    kræfter i spørgsmål c!)
- Mutation
- Genetisk drift
- Naturlig selektion
<details><summary>Klik for at se svaret.</summary>
<p>

- Mutation: Nej.
- Genetisk drift: Ja
- Naturlig selektion: Nej.

</p>
</details>

3)  Er det nødvendigt at antage, at to eller tre af disse kræfter virker
    sammen for at forklare hyppigheden af denne allel?
<details><summary>Klik for at se svaret.</summary>
<p>

Allelen er opstået gennem mutation og har gennem genetisk drift opnået den høje frekvens. (Naturlig selektion eliminerer denne allel og ville således ikke kunne forklares den høje frekvens af allelen.).
</p>
</details>

4)  Hvad forventes hyppigheden af allelen at blive, når der er opstået
    ligevægt mellem mutation, der har en rate på *μ* = 10<sup>-6</sup>,
    og selektion? (Det vil sige, at populationen har opnået en
    størrelse, hvor drift ikke spiller nogen større rolle. I dette
    tilfælde bestemmes ligevægtsfrekvensen som $q=\sqrt{\mu/s}$,
    hvor *s* er selektionskoefficienten mod den letale homozygot.)
<details><summary>Klik for at se svaret.</summary>
<p>

Ligevægtsfrekvensen mellem mutation og naturlig selektion er givet ved
	*q* = √(10<sup>-6</sup>/1) =0,001

</p>
</details>

### Opgave 5

Thalassemia major er en alvorlig anæmi, der ofte er letal tidligt i
barnealderen. Sygdommen, der forekommer ret hyppigt bl.a. i dele af
middelhavsområdet, skyldes homozygoti for et autosomalt gen, Th.
Heterozygoter med genotypen Thth har en mild anæmi (thalassemia minor).
Haldane foreslog i 1949[^1] at heterozygoten kunne være delvis resistent
mod malaria og derfor have en højere fitness end den normale homozygot.

I en population ved undersøgte man 10.000 voksne personer og fandt

- 9196 normale
- 800 med thalassemia minor
- 4 med thalassemia major

1)  Beregn på basis af denne prøve allelfrekvenserne i populationen.
<details><summary>Klik for at se svaret.</summary>
<p>

*p*(Th)  = (2 × 9196 + 800) / (2 × 10000) = 0.960

*q*(th) = (2 × 4 + 800) / (2 × 10000)       = 0.040

</p>
</details>

2)  Er der Hardy-Weinberg proportioner?
<details><summary>Klik for at se svaret.</summary>
<p>

Nej. De forventede antal under antagelse af Hardy-Weinberg proportioner er
	
|Genotype | *TthTh*      |*Thth*	| *thth*      | *N* |
|---------|:------------:|:------------:|:-----------:|:---:|
|O	  |9196	         |800           |   4	      |10000|
|E	  |$p^2 \times N$|$2pq \times N$|$q^2\times N$| $N$ |
|         |    =	 |       =      |   =         |     |
|         |	9208,32  | 775,36       |16,32        |     |

<figure>
  <img  align="center" src="SelChiTest.png" width=450 title="Chi2 test">
 </figure>
</p>
</details>

3)  Bestem indavlskoefficienten *F*. \[*F* = (*H<sub>e</sub>* –
    *H<sub>o</sub>*)/*H<sub>e</sub>*, hvor *H<sub>e</sub>* og
    *H<sub>o</sub>* er henholdsvis forventet og observeret hyppighed af
    heterozygoter.
<details><summary>Klik for at se svaret.</summary>
<p>

*F* = (775,36 – 800)/775,36 = –0,03,

d.v.s, at vi har et overskud af heterozygoter og et tilsvarende underskud af homozygoter i forhold til de forventede Hardy-Weinberg proportioner.


</p>
</details>

4)  Antag, at de voksne er dannet ud fra zygoter med samme allelfrekvens
    som dem selv. Beregn på basis af dette deres absolutte fitness ved
    at dividere antallet af de tre genotyper blandt voksne med deres
    respektive forventede antal som zygoter. Beregn den relative fitness
    ved at dividere værdierne for de to homozygoter med heterozygotens
    værdi.
<details><summary>Klik for at se svaret.</summary>
<p>

|Genotype             | *TthTh*  |*Thth* |   *thth* |*N*  |
|---------------------| :------: |:-----:| :------: |:---:|
|Overlevende (O)      | 9196     |800    |   4      |10000|
|Zygoter (Z)          | 9208,32  |775,36 |   16,32  |10000|
|Absolut fitness (O/Z)|	0,99866	 |1,03178|   0,2450 |     |
|Relativ fitness      |	0,9679   |1	 |   0,2375 |     |
	
<figure>
  <img  align="right" src="SelHaldane.png" width=100 title="Haldane">
 </figure>

Den relative fitness er beregnet ved at dividere med den højeste fitness, som observeres hos heterozygoten. Der er derfor tale om overdominans, hvor heterozygoten har højere fitness end de to homozygoter. Haldane’s gæt i 1949 var derfor rigtigt

</p>
</details>

### Opgave 6

<figure>
  <img  align="right" src="SelDelphinium.png" width=200 title="Ridderspore">
 </figure>

Riddersporen *Delphinium nelsonii* er medlem af ranunkelfamilien. Den
har normalt mørkeblå blomster. Hvid-blomstrede planter er homozygot
recessive for en allel, der ikke kan producere pigment. I en population
i Rocky Mountains forekommer der planter med hvide blomster med en
frekvens på 7,4 × 10<sup>-4</sup>. Hvid-blomstrede planter satte i
gennemsnit 143 frø per plante i modsætning til planter med blå blomster,
der i gennemsnit satte 229 frø. Forskellen skyldes at pollinatorer –
hovedsageligt humlebier og kolibrier – foretrak de blå blomster.

1)  Hvad er frekvensen af allelen for hvid? Antag, at der er
    Hardy-Weinberg proportioner i dette system.


<details><summary>Klik for at se svaret.</summary>
<p>

$$q^2 = 7,4 \times10^{-4}  \Leftrightarrow  q =\sqrt{7,4 \times10^{-4}}= 0,0272$$
</p>
</details>

2)  Antag at frøsætningen hos blå- og hvidblomstrede planter afspejler
    deres fitness. Hvad er den relative fitness af planter med hvide
    blomster i forhold til planter med blå blomster?
<details><summary>Klik for at se svaret.</summary>
<p>

*w*<sub>hvid</sub> = 143/229 = 0,624 
</p>
</details>

3)  Hvad er selektionskoefficienten mod den hvide allel?
<details><summary>Klik for at se svaret.</summary>
<p>

*s* = 1 – 0.624 = 0,376
</p>
</details>

Under antagelse af, at populationen er i mutations-selektionsligevægt,
skal mutationsraten bestemmes.

4)  Hvad er mutationsraten?
<details><summary>Klik for at se svaret.</summary>
<p>

$$\sqrt{\mu/s} \Leftrightarrow \mu = q^2s  =7,4 \times10^{-4}\times 0,376= 2,78\times \times10^{-4}$$
</p>
</details>

En sympatrisk slægtning til denne art, *Delphinium barbeyi*, har
betydeligt mindre blomster, og modtager langt færre besøg af bier. Den
er selvkompatibel, dvs, den kan selvbestøve. Ved en genetisk
undersøgelse fandt man et systematisk overskud af homozygoter blandt
frøplanter.

5)  Hvad er forklaringen på dette?
<details><summary>Klik for at se svaret.</summary>
<p>

En del af frøplanterne er produceret ved selvbestøvning og er dermed indavlede, hvilket medfører overskud af homozygoter i populationen.
</p>
</details>

### Opgave 7

En evolutionsbiolog har lavet fire simulationer, hvor populationens
størrelse har været sat til 100 i alle tilfælde. I tre af tilfældene
indgik der forskellig form for naturlig selektion. Frekvensen af allel A
var i alle tilfælde 0,1 i generation 0. Den anden allel er B.
Simulationerne varede 500 generationer, og der indgik 50 populationer i
hver af de fire simulationer. Resultaterne af simulationerne fremgår af
figuren.
<figure>
  <img  align="center" src="SelDrift1.png" width=2000 title="Kondor">
 </figure>

1.  Angiv for Figur I til IV om der foregår selektion og i givet fald,
    hvilken form for selektion, der foregår. Angiv fitnessværdierne for
    de tre genotyper *W*<sub>AA</sub>, *W*<sub>AB</sub> og
    *W*<sub>BB</sub> relativt til hinanden. (F.eks. *W*<sub>AA</sub> \>
    *W*<sub>AB</sub> og *W*<sub>BB</sub> \> *W*<sub>AB</sub>) Begrundes
    kort.
<details><summary>Klik for at se svaret.</summary>
<p>

I: Overdominant selektion. *W*<sub>AA</sub> < *W*<sub>AB</sub> og *W*<sub>BB</sub> < *W*<sub>AB</sub>. Allelfrekvenserne holder sig tæt omkring 0,1, men i de fleste populationer fikseres allel B.

II: Ingen selektion. *W*<sub>AA</sub> = *W*<sub>AB</sub> = *W*<sub>BB</sub>. Allelfrekvenserne bevæger sig tilfældigt op og ned. Desuden fikseres 5 populationer for allel A, hvilket er lig med forventningen, da 5/50 = 0,1, hvilket var allelfrekvensen til at starte med.

III: Retningsselektion. *W*<sub>AA</sub>  ≥ *W*<sub>AB</sub> ≥ *W*<sub>BB</sub> med højst ét lighedstegn. Langt de fleste populationer fikseres for allel A.

IV: Underdominant selektion.   *W*<sub>AA</sub> > *W*<sub>AB</sub> og *W*<sub>BB</sub> > *W*<sub>AB</sub> Vi ser, at når en population får en frekvens af A på over 0,5 bliver den altid fikseret for allel A. Ændringerne i allelfrekvenser er ikke så tilfældige, som man forventer med genetisk drift.

</p>
</details>

2.  Tre af simulationerne har et sammenfaldende ligevægtspunkt. Hvad er
    allelfrekvensen af det?
<details><summary>Klik for at se svaret.</summary>
<p>

0,1. I tilfældet for ingen selektion (II) vil ligevægten vil være 0,1, som er frekvensen i generation 0.  (For en uendelig stor population) Derfor må I og IV have det samme ligevægtspunkt.  For øvrigt, så viser det benyttede simulationsprogram (PopG) ligevægte som stiplede linjer for tilfældet, hvor der ikke virker genetisk drift.
</p>
</details>

3.  Hvilken form for ligevægt er der tale om i de tre tilfælde?

<details><summary>Klik for at se svaret.</summary>
<p>
I: stabil ligevægt
II: neutral ligevægt
IV: ustabil ligevægt 

</p>
</details>


[^1]: Haldane, J. B. S., 1949 Disease and evolution. Ric. Sci. Suppl. A
    19:68-76. \[often requoted, e.g., in Dronamraju, K. (Editor), 1990,
    Selected Genetic Papers of J.B.S. Haldane, Garland Publishing, New
York/London\]
