# Maturita - Fyzika 

## 1 - Kinematika
- zjednodušení hmotný bod
  - hmotnost soustředěná bodově
  - není moment setrvačnosti atd
- polohový vektor: vektor mezi hm. bodem a počátkem soustavy
- pohyb je po trajektorii(křivce), její délka je dráha($m$)
- trajektorie:
  - kružnice
  - přímka
  - obecná křivka
- zrychlení:
  - tečné
  - normálové
    - na križníci dostředivé
- vzorce:
  - $v_p = \frac{s_{celková}}{t_{celkový}}$
  - $s = \frac{1}{2} a t^2$
  - $\omega = \frac{\phi}{t}$
  - $\alpha = \frac{\omega}{t}$ možná se úhlový zrychlení u nás značí jinak
  - $v_{dostredive} = \frac{v_{obvodová}^2}{r}$
  - $v_{obvodova} = \omega r$
- vrh:
- dělení
    - vodorovný - pád z letadla
    - svislý - hod míče nad sebe
    - šikmý - zbytek
- počítá se vždy přes dráhu, spočítá se čas dopadu, svislá složka, poté se dopočítá důsledek ve vodorovném směru.

### Dá se zmínit
  - výpočet 1. kosimické rychlosti: odstředivá síla při rychlosti =  gravitační, hmotnosti se pokrátí
  - ryhlosti je derivaci zrychlení, zpětně integrál, integrační konstanty jsou počáteční stavy

## 2 - Dynamika
- Započítává sílu, hybnost
- Srážky, newtonovy zákony
- Galileiho princip relativity:
  - $x = x' + vt$
  - zbylé souřadnice a **čas se rovnají**

### Hybnost:
- $p = mv$
- V izolované soustavě se zachovává hybnost
- srážky: 
  - pružné - zachovává se energie i hybnost
  - nepružné - zachovává se hybnost, energie se ztrácí
- $p = F t$ - moment sílý

### Newtonovy zákony
1. newtonův zákon
   - zákon setrvačnosti
2. newtonův zákon
   - zákon síly - $F=ma$
3. newtonův zákon
   - zákon akce a reakce - $F_1 = F_2$

### Pohybová rovnice
- Rovnice, která popisuje polohu v závolosti na něcem, normálně čase
- v Newtonově mechanice:
  - $F = ma = m\frac{d^2 s}{dt^2}$
-  Rovnice se řeší dvojtou integrací až se dojde k samostatnému $s$. Objeví se dvě konstanty, jedna samostatná, druhá násobena $t$, jedná se o počáteční rychlost a polohu

### Lagrangeovy rovnice
- Dělení:
  - 1. druhu
  - 2. druhu

### Hamiltonovy rovnice
- je to bordel
- využívá se to v kvantovce, je to v Shrodingerově rovnici, levá strana je hamiltonián krát vlastní vektor, na druhý straně hamiltoniáln krát vlastní čísla, vlastní vektor je kvantový stav, vlastní čísla řešení myslím

### Dá se zmínit
- Lagrangeova a Hamiltonovy rovnice
- Na akci a reakci jsou reakční motory, třeba odvodit raketovou rovnici, rekační systémy samonabíjecích zbraní, 

## 3 - Práce, energie
- práce je energie, která se uvolnila, může se dát do rovnosi, jedná se vlastně o to stejný (jen to nějakej magor dal na dvě veličiny)
- vzorce"
  - $W = Fs$
  - $P = Fv$
  - $E = mgh = \frac{1}{2}mv^2$
  - $\mu = \frac{P_{prikon}}{P_{vykon}}$
- tady asi není, co psát. Člověk nemůže být magor a otázka je na pohodu
- vždycky, když se někde neuvažuje čas, je dobrý to počítat přes energii. Mělo by to jít. 
- v osclátorech se zachovává energie, dá se to využít pro výpočty. I elektrických oscilátorech

### Dá se zmínit
- spočítat různé možnosti uložení elektrické energie - ohřev vody, tuhnutí kovů, treba cínu
- výhřevnost se dá zmínit, spočítat kolik toho padne na dojetí někam

## 4 - Gravitace
- působí mezi každými dvěma hmotnými tělesy
- rozlišujeme pole:
  - radiální
  - homogenní
- Newtonův gravitační zákon:
  - $F = G \frac{mM}{r^2}$
  - pro zrychlení se to vydělí $m$
- Keplerovy zákony:
  - jsou uplná blbost
  - 1. planety obíhají po elipsách, v jednom ohnisku je obíhaný objekt
  - 2. plochy opsané za stejný čas josu stejné
  - 3. $\frac{T_1^2}{T_2^2} = \frac{a_1^3}{a_2^3}$
- Kosmické rychlosti:
  - 1. rychlost potřebná, aby těleso obíhalo přio povrchu Země
  - 2. úniková rychlost

### Dá se zmínit
  - pád Země ke slunci, jak douho by trval
  - odvození první kosmické rychlosti
  - měření gravitace kvantově, jen že to jde a součástka existuje, elektrony se dostanou do vyšších kvantových stavů a padají do nižších podle gravitace cca

## 5 - Mechanika tuhého tělesa
 - tuhé těleso má hmotnost a rozměry
 - síly se sčítají vektorově, sčítají se momenty sil
 - momentová věta: můřeš sčítat momenty síly
 - těžíště je hmotný bod, na který jdou aproximovat účinky gravitace na tělaso
 - hmotný střed: těžiště, které nezohledňuje změny v gravitačním poli, pole by bylo homogenní
 - rovnovážná poloha: suma sil je 0
 - moment setrvačnosti je ekvivalent hmotnosti pro rotační pohyb
 - Steinerova věta: $J = J_0 + mr^2$
 - moment hybnosti je ekvivalent hybnosti
 - Vzorce:
   - $I = mr^2$
   - $J = I\omega$
   - $E = \frac{1}{2}J\omega^2$
   - $M = \frac{dJ}{dt}$ - druhá impulzová veta, první je to stejný, co impulz síly
 - setrvačník skladuje energii, je jako mechanický kondenzátor, uvolňuje energii, kdy je potřeba, nebo naopak zrychluje, je v motoru, setrvačníkový lis, startér
 - smykové tření: $F = fF_n$
 - valivý odpor: $M = \xi F_n$

### Dá se zmínit
 - výpočet energie v setrvačníku
 - gyroskop
 - gyroskopický efekt u jízdního kola
 - odvodit nějaký momenty setrvačnosti, tyč chycená v kraji, ve středu, válec

# Atomová fyzika

## Experimenty

### Brownův pohyb
- pylová zrna na povrchu vody
- hýbou se, pohyb způsobuje pohyb molekul
- pyl je dost velký, aby šel pozorovat a dost malý, aby ho rozhýbal pohyb atomů
- důkaz pohybu atomů a tepelného pohybu
- adůvodněn Einsteinem 1905, pozorováno Brownem 1927

### Objev elektronu
- katodová trubice - katodobé záření
- Thompson 1897
- určil $\frac{Q}{m}$, zlomek vyšel výrazně zápornější - větší absolutní hodnota, nová částice

### Určení hodnoty elementárního náboje
- Millikan 1909
- levitace kapiček v elektrickém poli
- kapičky levitují v $kQ_e$
- $1.6\cdot 10^{-19}$ C

### Ruthefordův experiment
- Rutherford 1911
- objev jader atomů
- ostřelování zlaté destičky $\alpha$ čísticemi
- určil velikost a náboj jádra

### Objev přirozené akticity
- Becquerel 1896
- fotografický papír se zbarví přes odstínění

## Izotopy
- stabilní izotopy mají stejný počet protonů a neutronů
- počet nukleonů násobený vazebnöu energií je celková vazebná energie v $MeV$
- $^2H \rightarrow 2$ $MeV$, vazevná energie z tabulky násobená počtem nukleonů