# Kvantitativ genetik

### Hans R. Siegismund

## Teoretisk baggrund

 
<figure>
  <img  align="right" src="KvantGenHoejdeKvinder.png" width=250 title="Højdefordeling">
 </figure>
 
Kvantitative karakterer er under indflydelse fra variationen fra et
større antal loci. Disse karakterer udviser fænotypisk variation, hvor
forskellene mellem individer ofte er så små, at de kan være svære at
måle, og hvor det er vanskeligt at beskrive den genetiske baggrund, der
bestemmer dem. Et eksempel er illustreret i figuren, som
viser fordelingen af højden hos 380 kvindelige delagere i kurset i evolutionsbiologi.
Til denne kategori hører også antal afkom, overlevelse og andre
egenskaber, der er knyttet til et dyrs eller en plantes evne til at
producere afkom til næste generation. De sidstnævnte karakterer er alle
komponenter af fitness, der i sig selv kan betragtes som en kvantitativ
karakter. Et kendskab til den genetiske baggrund af disse karakterer og
til deres genetiske diversitet i naturlige populationer er derfor
nødvendig for at forstå arters muligheder for at tilpasse sig til
ændringer i det fysiske eller biologiske
miljø.

For at beskrive en population må vi ty til statistiske metoder. Det mest
simple består i at afbilde fordelingen på en passende skala. Ud fra
denne beregnes så størrelser som middelværdi og varians. Kvantitative
karakterer deles ofte op i kontinuerte og tællelige karakterer. Som
navnet antyder, så vil fordelingen af kontinuerte karakterer kunne
beskrives med en sandsynlighedsfordeling langs en akse, der er
kontinuert. Hertil hører for eksempel vægt, længde eller diameter af
stammen på træer. Disse karakterer kan måles med forskellige fysiske
eller kemiske metoder, og deres størrelse vil være en funktion af den
anvendte skala og af “måleinstrumentets” nøjagtighed. I princippet vil
disse karakterer være kontinuert fordelt, men for det meste grupperes de
i klasser. Fordelingen vil ofte—såfremt man har valgt en passende
skala—være normalfordelt. Dette er vist med den røde kurve i figuren
ovenfor, hvor man har benyttet middelværdi og variansen af de
observerede fordeling og indsat i formlen for normalfordelingen.

Tællelige karakterer optræder som diskrete enheder, det vil sige, at de
kan tælles med hele tal. Hertil hører eksempler som antallet af
hvirvler, afkom, børster og hår. Skalaen er givet på forhånd. Når
antallet af observerede kasser er forholdsvist stort, vil deres
fordeling også kunne tilnærmes med en normalfordeling.

### Komponenter af den fænotypiske varians

Skal en karakter beskrives for en given population, afbildes fordelingen
af fænotypen, og dens middelværdi og varians beregnes. Spørgsmålet er
nu, hvor stor en del af den fænotypiske varians er genetisk betinget, og
hvor stor en del skyldes miljøet? Konkret kan det formuleres som

$$
V_P = V_G + V_E
$$

hvor *V<sub>P</sub>* er den fænotypiske, *V<sub>G</sub>* er den
genetiske og *V<sub>E</sub>* er miljø-variansen. (Forkortelserne er
engelske, de står for henholdsvis “phenotypic”, “genetic” og
“environmental variance”.) Vi vil nu opsplitte den genetiske varians i
dens komponenter og se på, hvorledes disse kan estimeres. Den genetiske
varians består af en additiv varians *V<sub>A</sub>*, en
dominans-varians *V<sub>D</sub>* og en interaktionsvarians
*V<sub>I</sub>* ,

$$
V_G = V_A + V_D + V_I
$$

Dominansdelen skyldes afvigelse fra additive effekter indenfor de
enkelte loci (se figuren nedenfor), medens interaktionsvariansen er
forårsaget af ikke-additive bidrag fra de forskellige loci. Et andet
navn for denne er epistatisk varians.

<figure>
  <img  align="center" src="KvantGenGenotypiskeVaerdier.png" 
       width=550 title="Genotypiske værdier">
 </figure>

Genotypiske værdier for en kvantitativ karakter. Foroven: additive
bidrag fra allelerne. Forneden: dominansinteraktion mellem allelerne,
til venstre ufuldstændig dominans, til højre overdominans.

For en given karakter, der analyseres, kan vi fra en stikprøve
udelukkende bestemme den ***fænotypiske middelværdi***, $\overline{x}$,
samt den ***fænotypiske varians***, $V_P$
(*P* står for det engelske phenotype). Variansen bestemmes som

$$
V_P = \sum_{i=1}^2\frac{(x_i-\overline{x})^2}{n-1}
$$

Hvor der er indsamlet *n* stikprøver. Vi er interesseret i, hvor stor en
brøkdel af den fænotypiske varians, der består af ***genetisk varians***, $V_G$,
og hvor stor en del, der består af ***miljøvarians***, $V_E$.
Dette kan læses i afsnit 1.3 “Fænotypisk variation” i “Introduktion til
Populationsgenetik”, hvor der gives en kort gennemgang og forklaring af
de vigtigste kvantitativ-genetiske begreber.

En af de vigtigste parametre er ***“narrow sense” heritabiliteten***, $h^2_N$.
Den er defineret som den brøkdel den ***additive genetiske varians***,
$V_A$, udgør af den totale fænotypiske varians, $V_P$, det vil sige

$$
h^2_N =\frac{V_A}{V_P}
$$


<figure>
  <img  align="right" src="KvantGenHeritabilitetKvinder.png" 
       width=300 title="Heritabilitet hos kvinder">
 </figure>

Heritabiliteten beregnes nemt ved regressioner mellem beslægtede
individer. Det kan vises, at heritabiliteten 
er lig med regressionskoefficienten *b* mellem afkommets værdi 
og *forældrenes middelværdi* for den observerede karakter, 
det vil sige

$$
h^2_N =b.
$$


Det er vist i figuren  for højde hos kvindelige studerende, der
har deltaget i kurset i evolutionsbiologi.

Laves en regression mellem afkom og *den ene forælder*, kan det vises,
at heritabiliteten er lig med to gange regressionskoefficienten *b*
mellem afkommets og forælderens værdi for den observerede karakter, det
vil sige

$$
h^2_N =2b.
$$

Regressionskoefficienten *b* findes som

$$
b =\frac{\mathrm{Cov}(x,y)}{V(x)}
$$

hvor $\mathrm{Cov}(x, y)$ er covariansen mellem *x* og *y*, der bestemmes som

$$
\mathrm{Cov}(x,y) = \sum_{i = 1}^{n}(x_i-\overline{x})(y_i-\overline{y})/(n-1)
$$

Her er der indsamlet *n* parvise kombinationer af *x* og *y* værdier.

## Selektion på kvantitativ karakter

Naturlig selektion i et autosomalt locus med to alleler kan opdeles i
tre forskellige typer

<figure>
  <img  align="right" src="KvantGenRetnigsSelektion.png" width=200 title="Retningsselektion">
 </figure>

1.  Retningsselektion, hvor de tre genotyper har fitnessværdier, enten
    som $W_{11} \ge W_{12} \ge W_{22}$ med højst ét lighedstegn eller som
    $W_{11} \le W_{12} \le W_{22}$ med højst ét lighedstegn. Der må højst være et lighedstegn, 
    for ellers vil der ikke være forskel i fitness mellem de tre genotyper.
    
<figure>
  <img  align="right" src="KvantGenOverdominans.png" width=90 title="Overdominans">
 </figure>
 
2.  Overdominans, hvor heterozygoten har en højere fitness end begge
    homozygoter, det vil sige $W_{12} > W_{11}$   og $W_{12} > W_{22}$.

<figure>
  <img  align="right" src="KvantGenUnderdominans.png" width=90 title="Underdominans">
 </figure>

3.  Underdominans, hvor heterozygoten har en lavere fitness end begge
    homozygoter, det vil sige $W_{12} < W_{11}$   og $W_{12} < W_{22}$.

For kvantitative karakterer har vi tilsvarende typer for selektion, der
illustreret i den efterfølgende figur. De tre typer er

1.  Retningsselektion, hvor sandsynligheden for at overleve stiger som
    funktion af karakterens værdi. Her vil middelværdien forskydes til
    højre efter selektionen har virket på karakteren. (Man kan
    selvfølgeligt også have det omvendte tilfælde, hvor
    sandsynligheden for at overleve aftager som funktion af
    karakterens værdi.)

2.  Stabiliserende selektion, hvor sandsynligheden for at overleve er
    størst for individer med intermediære værdier af karakteren. Her
    vil naturlig selektion i ligevægten sørge for at middelværdien for
    karakteren er konstant.

1.  Disruptiv selektion, hvor individer med ekstreme karakterer har en
    øget sandsynlighed for at overleve end individer, der har en
    karakter tæt på middelværdien. Med denne selektion øges variansen
    af karakteren.
    
<figure>
  <img  align="center" src="KvantGenSelektionsRetning.jpg" width=550 title="Genotypiske værdier">
 </figure>
    

# Kvantitativ Genetik Opgaver

## Formål

I de følgende opgaver fokuseres der på de følgende emner med baggrund i
kvantitativ genetik

- Assortativ parring
- Komponenter af fænotypiske varians
- Heritabilitet
- Breeders equation, *R = h*<sup>2</sup>*S*

### Opgave 1

I denne opgave analyseres to kvantitative karakterer hos mennesket,
nemlig højde og antal børn. Data er blevet indsamlet over flere år på
kurset i evolutionsbiologi. (Se de efterfølgende figurer og tabeller.

Den følgende figur viser sammenhængen mellem de studerendes forældres
højder. Vi kan benytte dette for at se om der er “assortativ parring”
med hensyn til højde hos mennesket, dvs., om der er en tendens til høje
mennesker finder en partner, der også er høj, samt at lave mennesker har
den samme tendens.
   
<figure>
  <img  align="center" src="KvantGenAssortativ.jpeg" width=500 title="Assortativ parring">
 </figure>

1)  Figuren indeholder regressionslinjen for mødres højde som funktion
    af fædres højde. Den har hældningen 0,061. Korrelationskoefficienten
    er 0,068, som ikke er signifikant på 0,05 niveauet. Er der tegn på
    “assortativ parring”?



De følgende figurer viser fordelingerne af højde for mandlige og
kvindelige studerendes højde, samt for deres forældres højde.
   
<figure>
  <img  align="center" src="KvanGenHoejdefordeling.jpeg" width=550 title="Højdefordelinger">
 </figure>

|Højde                       |Gennemsnit |Varians  |*N*    |
|----------------------------|:---------:|:-------:|:-----:|
|Kvindelige studerende       |169,33     |42,84    |503    |        
|Kvindelige studrendes mødre |167,35     |40.43    |503    |
|Mandlige studerende         |182,98     |47,24    |244    |
|Mandlige studerendes fædre  |181,24     |40,68    |244    |

2)  Hvordan ændres højden for de to køn sig mellem generationerne? Man
    kan vise, at forskellen er statistisk signifikant for begge køn.
    (Det skal ikke gøres her.)


<figure>
  <img  align="center" src="KvantGenFordelingBoern.jpeg" width=550 title="Fordeling af antal børn">
 </figure>

|           |Gennemsnit |Varians  |*N*    |
| ----------|:---------:|:-------:|:-----:|
| Mødre     |2,38       | 0,79    | 503   |
| Mormødre  |2,99       | 2,17    | 503   |
| Fædre     |2,51       | 0,89    | 244   |
| Farfædre  |3,10       |2,36     | 244   |


3)  Hvordan ændres antallet af børn for de to køn sig mellem
    generationerne? Man kan vise, at forskellen er statistisk
    signifikant for begge køn. (Det skal ikke gøres her.)


4)  Forklar **kort**, om forskellene i højden og antal børn skyldes
    genetiske eller miljømæssige forskelle mellem generationerne.


5)  Hvad sker der med variansen af børn mellem de to generationer? (Man
    kan vise, at forskellen er statistisk signifikant for begge køn.
    \[Det skal ikke gøres her.\]) Hvilken effekt har det på genetisk
    drift? For at belyse dette, kan man se på ændringen af den effektive
    populationsstørrelse mellem generationerne. Hvis ikke man kan
    argumentere tilstrækkeligt med baggrund i sin intuition, kan man
    eventuelt benytte den følgende formel, der viser forholdet mellem
    den effektive populationsstørrelse og den aktuelle
    populationsstørrelse
    
$$\frac{N_e}{N} \approx \frac{2}{k-1 +\frac{\displaystyle V_k}{\displaystyle k}}
$$
    
  Her er *k* er det gennemsnitlige antal børn, og *V<sub>k</sub>* er
variansen af antal børn. Det er den effektive populationsstørrelse for
kvinder, der her er tale om. (Normalt er *N<sub>e</sub>* mindre end
*N*, men der kan ske det modsatte.) Tag udgangspunkt i mormødre og
mødre.


6)  Hvilke andre forhold end varians af antal børn spiller ind på
    genetisk drifts virkning i en population?


 <figure>
  <img  align="center" src="KvantGenHeritabilitetHoejde.jpeg" width=650 title="Heritabilitet af højde">
 </figure>

De følgende tabeller viser varianser og covarianser, som er nødvendige
for at beregne “narrow sense” heritabilitet for højde hos mennesket.

*Varianser og covarianser for højde hos kvinder*

|Varians                                                              |     |
|---------------------------------------------------------------------|:---:|
|Varians af forældrenes gennemsnitshøjde \[*V*(*x*)\]                 |24,82|
|Covarians af datters og forældres gennemsnitshøjde \[*Cov*(*x*,*y*)\]|19,23|
|Antal observationer                                                  |503  |

*Varianser og covarianser for højde hos mænd*

|Varians                                                               |      |
|----------------------------------------------------------------------|:----:|
| Varians af forældrenes gennemsnitshøjde \[*V*(*x*)\]                 |21,21 |
| Covarians af sønnens og forældres gennemsnitshøjde \[*Cov*(*x*,*y*)\]|17,77 |
| Antal observationer                                                  |244   |

7)  Beregn “narrow sense” heritabiliteten for højde hos mennesket (for
    kvinder og mænd).


De følgende figurer viser antallet af mødres antal børn som funktion af
mormødres antal børn, samt fædres antal børn som funktion af farfædres
antal børn. Sammenhængen mellem disse benyttes til at beregne
heritabiliteten af antal børn. Antallet af streger ud fra et punkt
viser, hvor mange observationer, der er gjort for dette punkt.

 <figure>
  <img  align="center" src="KvantGenHeritabilitetBoern.jpeg" width=550 title="Heritabilitet af børn">
 </figure>

De følgende tabeller viser varianser og covarianser, som er nødvendige
for at beregne “narrow sense” heritabilitet for antal børn hos
mennesket.

Varianser og covarianser for antal børn hos kvinder

| Varians                                                   |       |
|-----------------------------------------------------------|-------|
| Varians af mormors antal børn \[*V*(*x*)\]                | 2,175 |
| Covarians af mor og mormors antal børn \[*Cov*(*x*,*y*)\] | 0,176 |
| Antal observationer                                       | 747   |

Varianser og covarianser for antal børn hos mænd

|Varians                                                     |       |
|------------------------------------------------------------|-------|
| Varians af farfars antal børn \[*V*(*x*)\]                 | 2,360 |
| Covarians af fars og farfars antal børn \[*Cov*(*x*,*y*)\] | 0,306 |
| Antal observationer                                        | 747   |

8)  Beregn “narrow sense” heritabiliteten for antal børn hos mennesket.


Hos mange andre arter har man observeret lignende forskelle i
heritabilitet mellem karakterer, der er fitnessrelaterede (som antal
børn) og karakterer, der ikke er så direkte knyttet til fitness (som
højde).

9)  Hvad skyldes denne forskel?


I Frankrig er den gennemsnitlige højde for mænd 177 cm og 163 cm for
kvinder. Heritabiliteten for højde i Frankrig er af samme størrelse som
den, der er fundet i denne opgave.

10) Er forskellen i højde mellem danske og franske befolkning genetisk
    betinget?

### Opgave 2

Betragt en eksperimentel population af rotter, hvor man i 40
generationer har selekteret for hårlængde, som i løbet af forsøget
øgedes fra et gennemsnit på 8 mm til 16 mm. I den første generation, som
havde en gennemsnitlig hårlængde på 8 mm, udvalgtes forældre med en
gennemsnitlig hårlængde på 10 mm. Deres afkom havde en gennemsnitlig
hårlængde på 9 mm.

1)  Bestem heritabiliteten (narrow sense) for denne karakter i den
    første generation.


I generation 39 var den gennemsnitlige hårlængde 15,8 mm, hvoraf man
udvalgte forældre med en gennemsnitlig hårlængde på 17 mm. I generation
40 var gennemsnittet 16

2)  Bestem heritabiliteten på dette tidspunkt.


3)  Forklar forskellen i heritabiliteten mellem de to tidspunkter.


Man stoppede selektionseksperimentet og observerede i de følgende
generationer et fald i hårlængden.

4)  Giv en forklaring på dette fald.


### Opgave 3

 <figure>
  <img  align="right" src="KvantGenDrosophila.jpg" width=100 title="Drosophila">
 </figure>

Den efterfølgende figur illustrerer et forsøg, hvor man i 60
generationer kunstigt har selekteret for et øget antal børster på
abdomen hos bananfluen *Drosophila melanogaster.* Selektionen foregik
ved at man i hver generation udvalgte de 10 % af hannerne og hunnerne,
som havde det højeste antal børster til at være forældrene til næste
generation. Som det ses, så øgedes antallet af børster gennem kunstig
selektion. Det foregik imidlertid ikke jævnt. Perioder med stigende
antal børster afløstes af perioder med næsten konstant antal, som så
efterfulgtes af en pludselig stigning som respons på selektionen.

<figure>
  <img  align="center" src="KvantGenRetnigsSelektionDrosophila.png" 
   width=550 title="Retningsselektion hos Drosophila">
 </figure>

1)  Hvorledes ændres heritabiliteten sig under forløbet?


2)  Hvilke biologiske fænomener kan have forårsaget at et plateau
    afløses af en periode med stigende respons på selektionen?


### Opgave 4
 <figure>
  <img  align="right" src="KvantGenFinke.jpg" width=300 title="Pyrenestes ostrinus">
 </figure>

Den afrikanske finke *Pyrenestes ostrinus* er blevet studeret af
Thomas Bates Smith. Fugle i denne art findes i to grupper med forskellig
næbstørrelse; en gruppe med store næb og en gruppe med små næb. Figuren
til højre viser en fordeling af næbstørrelsen i en naturlig population i
Cameroun (som størrelse for næbstørrelsen er vist bredden af næbbet).

Bates Smith analyserede udspaltningen af afkom fra forskellige parringer
i en population. Der foregår tilfældig parring med hensyn til
næbstørrelse. Den følgende figur viser stamtavler for forskellige
krydsninger. I stamtavlen får hunner en cirkel,  medens hanner får
en firkant. Er kønnet ukendt, angives det som . Individer med
stor næbstørrelse er angivet med L (Large), medens individer med små næb
er angivet med S
(Small).

<figure>
  <img  align="center" src="KvantGenFinkeStamtavle.png" width=550 title="Stamtavle af finke">
 </figure>

1)  Benyt stamtavlerne til at udlede den genetiske baggrund for
    fænotyperne S og L. Angiv hvilke genotyper, der bestemmer de to
    fænotyper og angiv dominansforhold. Begrundes ***kort***.


2)  Angiv genotyperne for forældrene i stamtavle nr. 4.


3)  Hvad er indavlskoefficienten af individet, der er angivet med en
    pil, hvis vi antager at olde- og bedsteforældrene er ubeslægtede?


Finken lever hovedsageligt af frø, hvor størrelsen af de frø, der
spises, er korreleret med næbstørrelsen. Finker med små næb spiser små
bløde frø, medens finker med store næb spiser store hårde frø.
Fordelingen over næbstørrelsen vises for unge fugle, hvor de mørke
søjler er dem, der overlever til voksenstadiet, medens de lyse søjler
viser fugle, som ikke overlever til voksenstadiet.

4)  Hvilken form for naturlig selektion virker, når man betragter begge
    størrelsesklasser af finken?


5)  Hvilken form for naturlig selektion virker, når man betragter de to
    størrelsesklasser af finken hver for sig?


### Opgave 5

Fra en meget stor population af bananfluer indfanges der en stikprøve,
der bruges til et kvantitativt genetisk forsøg. De holdes på en konstant
populationsstørrelse i hver generation (*N* = 15). Man analyserer en
kvantitativ genetisk karakter, hvis fænotypiske varians
(*V<sub>P</sub>*) udelukkende består af additiv genetisk varians
(*V<sub>A</sub>*) og miljøvarians (*V<sub>E</sub>*),

$$V_P = V_A + V_E.$$

Additiv genetisk varians aftager på samme måde som gendiversitet som
følge af genetisk drift,

$$V_A(t) = V_A(0)\left(1 – \frac{1}{2N}\right)^t,$$

Hvor *V<sub>A</sub>*(*t*) og *V<sub>A</sub>*(0) er henholdsvis den
additive genetiske varians i generation *t* og i generation 0.

1)  Hvor stor en brøkdel af den additive genetiske varians er der
    tilbage efter 16 generationer?


2)  Forventes *V<sub>A</sub>* at gå mod nul, når tiden går mod uendelig,
    eller er der andre ting, der modvirker dette?


Man laver et selektionseksperiment med fluer, der stammer fra den 16.
generation og med fluer, der indsamles fra den store vilde population.
Man selekterer ved, at man udvælger en gruppe individer, der i
gennemsnit har fire enheder mere end populationens gennemsnit, der er 10
enheder (gælder for begge populationer.). Heritabiliteten er 0,75 i den
vilde population. Den fænotypiske varians for karakteren er 8 i
populationen.

3)  Hvad er miljøvariansen i den vilde population?


4)  Hvad er middelværdien af afkomsgenerationen i populationen, der har
    været i laboratoriet, og den, der er indsamlet på ny?


Man indsamler fluer fra en anden population, der viser sig at have den
samme heritabilitet for karakteren, nemlig 0,75. Her er gennemsnittet af
karakteren 14

5)  Kan man på denne baggrund sige, at forskellen mellem de to
    populationer genetisk betinget?


### Opgave 6

Fie er forsker og arbejder med at fremavle kalkuner med hurtigere vækst.
Den egenskab Fie selekterer på er, hvor hurtigt kalkunerne opnår en
slagtevægt på 6 kg. I gennemsnit tager det almindelige kalkuner 12 uger
at opnå en vægt på 6 kg. Heritabiliteten i snæver forstand,
*h*<sup>2</sup>, for dette træk er 0,4. Fie vil etablere en avlsstamme
for hurtigere vækst. Hun udvælger en gruppe kalkuner, som i gennemsnit
vejer 6 kg efter kun 11 uger, og deres afkom udgør første
afkomsgeneration.

1)  Hvor stort er selektionsdifferentialet?


2)  Hvor mange uger vil det i gennemsnit tage for den første
    afkomsgeneration, at opnå en vægt på 6 kg?


Fie har brugt en del SNP-markører i sit avlsarbejde. Når hun
sammenligner nukleotiddiversiteten i udgangspopulationen med
nukleotiddiversiteten efter 8 generationer, opdager hun at diversiteten
er faldet til det halve.

3)  Ud fra det slutter hun, at den effektive populationstørrelse i
    avlspopulationen har været ca. 6 under selektionseksperimentet.
    Hvordan kommer hun til det resultat?


4)  Fie mener, at det er vigtigt at bevare så meget af den genetiske
    variation som muligt i avlsstammen. Hvilke(n) faktor(er) vil påvirke
    tabet af genetiske variation i avlsstammen og hvordan kan Fie
    modvirke dette?

