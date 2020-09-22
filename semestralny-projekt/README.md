# Semestrálny projekt - elektornický obchod

## Zadanie
Vytvorte webovú aplikáciu - eshop, ktorá komplexne rieši nižšie definované prípady použitia vo vami zvolenej doméne (napr. elektro, oblečenie, obuv, nábytok). Presný rozsah a konkretizáciu prípadov použitia si dohodnete s Vašim cvičiacim na cvičení.


## Tím
Projekt vypracovávate vo dvojici. Každý z dvojice sa musí podieľať na
projekte významným dielom (rovnomerné rozdelenie práce). Vypracovanie (takmer) celého projektu len jedným z dvojice autorov je neprípustné. Je potrebné, aby bol každý z autorov oboznámený s celým projektom, vrátane častí, na ktorých sám nepracoval. Autori sú hodnotení rovnakým získaným počtom bodov.


## Autorstvo
Je zakázané používať programy alebo časti projektov od iných študentov, alebo z minulého ročníka.
Všetky použité materiály z odbornej literatúry alebo z internetu musia byť citované. Ak
použijete cudzí materiál a neuvediete zdroj, práca môže byť považovaná za plagiát.


## Termíny odovzdania
* **Odovzdanie 1. fázy projektu: 3. týždňa - 11.10. do 23:59 v AIS, 4 body,** vytvorenie skíc jednotlivých stránok pre zariadenia extra small (< 600px)
* **Odovzdanie 2. fázy projektu: koniec 6. týždňa - 1.11. do 23:59 v AIS, 12 bodov (10 + 2 body),** vytvorenie responzívnych šablón (10 bodov); návrh dátového modelu (2 body) 
* **Kontrolný bod: 9. týždeň, na cvičení - 16.11. a 17.11, binárne hodnotenie 0/4 body**  implementácia klientskej časti eshopu so zostavením na serveri (server-side rendering) s využitím PHP rámca (odporúčaný Laravel) - so všetkými funkciami podľa požiadaviek 
* **Odovzdanie 3. fázy projektu: koniec 11. týždňa - 6.12. do 23:59 v AIS, 20 bodov** 
  * implementácia klientskej časti eshopu so zostavením na serveri (server-side rendering) s využitím PHP rámca (odporúčaný Laravel)
  * implementácia administrátorského panela/admin zóny so zostavením na klientovi (Single Page Application, client-side rendering) s využitím Vue.js rámca (odporúčaný Quasar)
  * finálna dokumentácia


## Termíny prezentovania
V čase cvičení tím predvedie na svojom počítači svoje riešenie (fázy projektu), a to:
* **Prezentovanie 1. fázy projektu, na cvičení: 4. týždeň - 12.10. a 13.10.**
* **Prezentovanie 2. fázy projektu, na cvičení: 7. týždeň - 2. a 3.11.**
* **Prezentovanie finálneho projektu: 12. týždeň - 7.12. a 8.12.**


## Aplikácia - eshop

**Aplikácia musí realizovať tieto prípady použitia:**

**Klientská časť (zostavenie na strane servera)**
* zobrazenie prehľadu všetkých produktov z vybratej kategórie používateľom
    * základné filtrovanie (aspoň podľa 3 atribútov, napr. rozsah cena od-do, značka, farba)
    * stránkovanie
    * preusporiadanie produktov (napr. podľa ceny vzostupne/zostupne)
* zobrazenie konkrétneho produktu - detail produktu
    * pridanie produktu do košíka (ľubovolné množstvo)
* plnotextové vyhľadávanie nad katalógom produktov
* zobrazenie nákupného košíka
    * zmena množstva pre daný produkt
    * odobratie produktu
    * výber dopravy
    * výber platby
    * zadanie dodacích údajov
    * dokončenie objednávky
* registrácia používateľa/zákazníka
* prihlásenie používateľa/zákazníka
* odhlásenie zákazníka

**Administrátorská časť (Single Page Application)**
* prihlásenie administrátora do administrátorského rozhrania eshopu
* odhlásenie administrátora z administrátorského rozhrania
* vytvorenie nového produktu administrátorom cez administrátorské rozhranie
* upravenie/vymazanie existujúceho produktu administrátorom cez administrátorské rozhranie

## Dátový model
V druhom kontrolnom termíne sa odovzdáva JPG (JPEG) obrázok logického dátového modelu reprezentovaného UML class diagramom.

V poslednej, 3. fáze projektu, sa databáza odovzdáva kompletná (dáta aj schéma, resp. DDL).


## Spôsob odovzdávania
Výstupy všetkých kontrolných bodov sa odovzdávajú do AISu. Odovzdáva iba jeden zo študentov v tíme. Dohodnite sa vopred, aby sa nestalo, že neodovzdá ani jeden.

Odovzdávajú sa všetky zdrojové kódy aplikácie, okrem samotných rámcov a knižníc z manažéra balíkov (composer, npm). V prípade, že študent modifikoval používanú knižnicu, je potrebné pribaliť aj zmenené knižnicu a uviesť zmenu s odôvodnením v dokumentácii.

Odovzdáva sa ZIP alebo RAR archív.


## Oneskorenie odovzdania
V kontrolnom termíne sa môže odovzdanie oneskoriť maximálne o 3 dni.

Za každý deň oneskoreného odovzdania je tímu odobratých 25% bodov z pôvodného maxima (deň po termíne tím získa 3/4 bodov, dva dni po termíne 1/2, atď.) 

 Neskoršie odovzdanie nie je možné. Neodovzdanie niektorej časti projektu znamená nesplnenie podmienok absolvovania predmetu.
 
 
## Kontrolná fáza progresu implementácie
V kontrolnej fáze - v 9. týždni - sa očakáva implementovaná klientská časť aplikácie. Fáza je hodnotená 4 bodmi, a to binárne. Tím letmo predvedú cvičiacemu funkčnosť klientskej aplikácie s ohľadom na požadované prípady použitia. Ak aplikácia umožňuje realizovať všetky prípady použitia, každý študent z tímu získa 4 body.


## Implementačné prostredie
Odporúčané technológie:
* Klientská časť: PHP - Laravel rámec
* Aministrátorská časť: Vue.js - Quasar rámec
* PostgreSQL relačný databázový systém

Použitie iných technológií, napr. iný PHP rámec alebo relačný databázový systém je podmienené súhlasom cvičiaceho (jazyk PHP je povinný).


## Dokumentácia
Dokumentácia musí obsahovať minimálne tieto časti:
* zadanie
* vytvorené skice rozhrania 
* diagram fyzického dátového modelu spolu s ich opisom (pozor - nie diagram logikého modelu z 2. fázy)
* opis návrhu / návrhové rozhodnutia
* opis implementácie jednotlivých prípadov použitia, snímky obrazoviek (angl. screenshot, snapshot) konečného rozhrania


## Spôsob hodnotenia
### 2. fáza
- šablóny vytvorené pre všetky požadované prípady použitia - 5b
- správne použitie HTML5 elementov - 2b
- responzívny dizajn - 2b
- formátovanie a logická štruktúra zdrojového kódu,
konzistencia/jednotná konvencia pri názvosloví identifikátorov - 1b
- logický dátový model - 2b

### 3. fáza

#### Klientská časť - 10 bodov
* zoznam produktov - 3 body
  * filter
  * preusporiadanie
  * stránkovanie
* detail produktu - 1 bod
  * pridanie/odobratie z košíka
* plnotextové vyhľadávanie nad katalógom produktov - 3 body
* košík - 3 body
  * zmena množstva
  * odobratie
  * doprava/platba
  * údaje (s validáciou)
* zákazník - 1 bod
  * registrácia, prihlásenie, odhlásenie

#### admin časť - 6 (+4?) bodov
* prihlásenie/odhlásenie - bonus 4b
* zoznam produktov - 1 bod
* pridanie produktu - 2 body
   * s uploadom obrázkov
   * aspoň jeden číselník (viem si zo select-u vybrať napr. farbu)
* odobratie produktu - 1 bod
   * fyzické vymazanie obrázku
* edit - 2 body
   * s uploadom obrázkov
   * zoznam obrázkov - s delete tlačídlom

#### dokumentácia - 3 body
* zadanie
* vytvorené skice rozhrania
* diagram logického a fyzického dátového modelu spolu s ich stručným opisom - 1 bod
* stručný opis návrhu / návrhové rozhodnutia - 1 bod
* prog. prostredie
* strunčný opis implementácie jednotlivých prípadov použitia, snímky obrazoviek konečného rozhrania - 1 bod


**Každý študent musí vedieť vysvetliť ktorúkoľvek časť (kód) riešenia svojho tímu.**