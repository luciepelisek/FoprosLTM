**Situace**
Jsi zkušený webový vývojář a designér s expertízou v tvorbě moderních, responzivních a designově originálních webových stránek. Tvým úkolem je vytvořit kompletní web podle specifikací níže.

**Cíl**
Dodej uživateli kompletní, profesionální mobile-first webovou stránku, která je vizuálně atraktivní, funkční na všech zařízeních a připravená k okamžitému použití.

**Úkol**
Vytvoř funkční web, který bude obsahovat:
•	Strukturovaný komentovaný HTML5 kód s validní sémantikou
•	Responzivní design (mobile-first přístup)
•	CSS styly pro přizpůsobení všem obrazovkám (4K monitory, desktop, tablet, mobil)
•	Používej moderní CSS vlastnosti (CSS variables, transitions, animations)
•	CSS jednotky velikosti: pro běžný text použij rem, pro nadpisy použij clamp 
•	Základní JavaScript pro interaktivitu (na jemné oživení stránek)
•	Dbej na bezpečnost webu (nastavení bezpečnostní HTTP hlavičky, u kontaktního formuláře řeš ochranu proti spamu pomocí honeypot)
•	Nedávej do soubor .htaccess pokyny k přesměrování (to se řeší na úrovni hostingu)

**Znalosti**
•	Zajisti rychlé načítání a optimalizovaný výkon
•	Dodržuj best practices pro přístupnost (barevný kontrast, velikost písma, ARIA)
•	Vlož favicon ve formátu svg – najdeš ho ve složce Obrazky pod nazvem Favicon
•	Pokud je potřeba Cookie lišta, vytvoř ji v barvách webu

**Základní SEO**
•	Strukturuj nadpisy H1-H6
•	Přidej meta title a description na každé stránce
•	Vytvoř strukturovaná data – LocalBusiness, FAQ, Article (pokud je to relevantní)
•	Přidej do adresáře soubory sitemap.xml, robot.txt a llms.txt
•	Urči kanonickou url
•	Obrázkům dej alt popisky
•	Propoj stránky vnitřními odkazy
•	Vytvoř Open Graph meta tagy (náhled webu pro Facebook a další sociální sítě)

**Optimalizace obrázků**
•	Přidej lazy loading ke všem obrázkům, které nejsou vidět hned při načtení stránky (below the fold). Tj. u hero sekce lazy loading nedělej.
•	Obrázky ti dodám zkomprimované ve formátu jpg nebo png, ale kdyby se ti zdály velké, řekni si o formát avif.

**Vizuální hierarchie a čitelnost**
•	Jasná typografická hierarchie (nadpisy H1-H6, konzistentní velikosti)
•	Dostatečný kontrast mezi textem a pozadím (minimum 4.5:1 pro běžný text)
•	Čitelné fonty s českou diakritikou, minimální velikost 16px
•	Správné řádkování (line-height 1.5-1.8 pro odstavce)
•	Nikdy nezarovnávej text do bloku
•	Maximální šířka textu 70% obrazovky (nikdy nepiš od kraje po kraj)

**Layout**
•	Šířku celého webu dej na 85% obrazovky
•	Jasné oddělení sekcí a obsahových celků
•	Pokud mám v sekci 4 karty/boxy – dej je po dvou na řádek (ne 3+1)
•	Vyvážené použití bílého prostoru (white space)
•	Intuitivní navigace - logo vlevo, hamburger menu na mobilu pravo
•	Dej si záležet na patičce webu
•	U prvku accordion (př. pro otázky a odpovědi) dávej ikonu šipky dolů a nahoru a pokud je jich víc než 3, tak je rozděl do dvou sloupců
•	Jednopísmenové znaky (spojky, předložky) zalamuj na nový řádek
•	Jednotky (Kč, m, kg, Eur, atd.) spoj s číslem nedělitelnou mezerou
•	Datum piš ve formátu 1. 1. 2026 a mezery dej nedělitelné

**Obsah**
•	Stručné a srozumitelné texty
•	Výrazné nadpisy s klíčovými informacemi a CTA tlačítka
•	Vizuální prvky podporující obsah (ikony, obrázky, grafika)
•	Logické uspořádání informací (nejdůležitější nahoře)
•	Chybová stránka (místo „404“ dej ikonu <wa-icon name="face-frown" variant="regular"></wa-icon>) a přidej ji na web pomocí příkazu v souboru .htaccess: ErrorDocument 404 /404.html
•	Kontrola povinných údajů na webu: jméno, sídlo, IČ, zápis v rejstříku

**Konzistence**
•	Jednotný styl tlačítek, karet a komponent
•	Stejný padding/margin napříč podobnými elementy
•	Stejné zaoblení prvků – pro tento web chci 3px
•	Konzistentní ikonografie (používej font awesome, ne emotikony)
•	Stíny karet pouze velmi jemné
•	Jednotný projev značky (brand voice)
•	Konzistentní použití barev napříč celým webem
•	Jednotný spacing a odsazení (používej jednotný systém, např. 8px grid)

**Barevná paleta**
•	Omezený počet barev (2-3 hlavní + neutrální)
•	Primární barva pro CTA (call-to-action) tlačítka
•	Neutrální jemné barvy pro pozadí 
•	Pro text #333333
Barevná paleta:
#506145 – zvýraznění prvků
#FC735D - odkazy, ikony
#45721D - tlačítka
#A4C049 - ikony
#DAE49C - podkres
#F5F6F4 – podkres

**Fonty**
•	Nadpisy, podnadpisy, text v tlačítkách: GOLDMAN
•	Textové písmo: OPEN SANS

**Struktura**
•	Více stránkový web https://foprosltm.cz

Položky menu: 
1. Vítejte
2. Služby
3. Technologie
4. Pro autoservisy
5. Časté dotazy
6. O nás
7. Kontakt

**Další prvky na webu**
•	Vytvoř kontaktní formulář (stránka KONTAKT) včetně antispamu (honeypot), doporuč mi službu https://formspree.io/ 

Kontaktní formulář
Jméno a příjmení / Název firmy (povinné)
Telefon (povinné)
E-mail (povinné)
Typ vozidla / stroje (volitelně)
Zpráva (volitelně: popis problému)
Odeslat dotaz / poptávku

Vaše údaje slouží pouze ke zpracování poptávky / zodpovězení dotazu. Vaše kontaktní údaje nebudou použity k marketingovým účelům.
Formulář z webu půjde na e-mail: info@foprosltm.cz se všemi informacemi z formuláře v těle e-mailu + subjekt e-mailu: „Zpráva z webu“
Po odeslání formuláře se zobrazí zpráva o úspěšném odeslání: 
Zpráva byla odeslána. Ozveme se co nejdříve zpět. FOPROS LTM

**Design**
Design celého webu vytvoř podle vzoru, který ti dám před začátkem tvorby ve formátu jpg. Dostaneš 5 vzorů, ze kterých se můžeš inspirovat. Chci originální design, který zaujme. Podpoří značku. Jedná se o velmi profesionální web, přesto do něj chci vnést i originalitu. Animace jemně. Do pozadí můžeme volit i zajímavé prvky z oboru čištění DPF filtrů a katalyzátorů, pokud nebudeš moci vytvořit, řekni si o fotku či prvek.

**Obrázky**
Na webu použij fotky a video, které najdeš ve složce Obrazky. Rozložení fotek a umístění videa najdeš v části **Texty**.

**Texty**
Na webu použij tyto texty pro jednotlivé sekce / stránky. Drž se jich doslova a nic ideálně neměň ani nepřidávej. Bude-li potřebná změna z důvodu délky / vzhledu / designu, změnu udělej, ale upozorni mě, co se změnilo. Vždy však zachovej smysl a podstatu obsahu stránky. V textu najdeš občas i instrukce – např. kam má tlačítko vést nebo jak by prvek měl vypadat. Pokud uznáš za vhodné z hlediska designu a UX/UI struktury stránky přehodit některé sekce na dané stránce, můžeš tak udělat.

1. Vítejte
Sekce: HERO (Video1)
H1: Profesionální čištění DPF filtrů a katalyzátorů do 240 minut
H2: Osobní, užitkové i nákladní vozy • Stavební stroje, autobusy • Úspěšnost až 98 %
TLAČÍTKO: Objednat čištění (proklik na stránku Kontakt)

Sekce: č.2
Čistíme DPF filtry rychle, odborně a bez zbytečných komplikací včetně svozu a diagnostiky

Sekce: č.3
Komu pomáháme
Čistíme DPF filtry všude tam, kde vozidlo musí fungovat spolehlivě, bez výpadků a zbytečných nákladů.
Naše služby využívají jednotlivci i firmy, které potřebují rychlé a technicky správné řešení.
•	Běžní řidiči
Řešení problémů s DPF bez zbytečných investic do nového filtru.
•	Autoservisy
Spolehlivý partner pro odborné čištění DPF filtrů.
•	Firmy a flotily
Minimalizace odstávek vozidel v provozu.
•	Zemědělci
Čištění DPF filtrů u traktorů a zemědělské techniky.
•	Stavební firmy
Servis DPF filtrů u strojů pracujících v náročných podmínkách.

Sekce: č.4 (zde použít Foto2)
Služby podle typu vozidla
Čistíme DPF filtry u široké škály vozidel a techniky. Každé čištění probíhá podle typu filtru a jeho skutečného stavu.

Čištění DPF – osobní auta
Čištění DPF – dodávky
Čištění DPF – nákladní vozidla
Čištění DPF – autobusy
Čištění DPF – stavební a pracovní stroje
Čištění DPF – zemědělské stroje
TLAČÍTKO: Více informací (proklik na stránku Služby)

Sekce: č.5
Jak to s námi probíhá
Celý proces je navržen tak, aby byl rychlý, přehledný a technicky správný.
→ časová osa / infografika
1.	Kontakt / objednávka
Telefonicky nebo přes formulář.
2.	Demontáž filtru v našem servisu
U vás, u nás nebo ve vašem servisu.
3.	Příjem & vstupní diagnostika
Kontrola stavu filtru před čištěním.
4.	Čištění na technologii Advanpure
Mokrá metoda s vysokou účinností až 98%.
5.	Sušení a výstupní kontrola
Ověření průchodnosti filtru + výstupní protokol.
6.	Vrácení a montáž zpět
Filtr připravený k dalšímu provozu.

Sekce: č.6
Proč čistit DPF filtr a nekupovat nový
•	Výrazná finanční úspora oproti pořízení nového filtru
•	Ekologičtější řešení bez zbytečné výroby nových dílů
•	Zachování originálního filtru vozidla
•	Pozitivní vliv na motor a spotřebu
•	Rychlost řešení – běžně do 240 minut

Sekce: č.7
Technologie & odborné know-how
Při čištění DPF filtrů používáme profesionální technologii mokrého čištění, která umožňuje odstranit usazeniny bez poškození filtru. Každý filtr prochází kontrolou před i po čištění.
TLAČÍTKO: Více informací (proklik na stránku Technologie)

Sekce: č.8
Čísla, která mluví za nás
•	98% úspěšnost čištění 
•	240 minut rychlost čištění 
•	1000+ vyčištěných filtrů ročně

Sekce: č.9
Výzva ke kontaktu
Máte problém s DPF filtrem?
Ozvěte se nám. Řekneme vám, zda má čištění smysl, kolik bude stát a jak rychle ho zvládneme vyřešit.
📞 Zavolat (proklik s aktivním odkazem tel:+420777550773)

2. SLUŽBY
Sekce: HERO (zde použít Foto3)
H1: Čištění DPF filtrů a katalyzátorů
H2: Rychlé, odborné a šetrné řešení pro osobní auta, užitkové i těžké stroje

Sekce: č.2
Přehled služeb podle typu vozidla
•	Čištění DPF – osobní auta
Pro koho je služba určena: Pro majitele osobních vozů s dieselovým motorem, u kterých se objevuje kontrolka DPF, časté regenerace nebo snížený výkon.
Doba čištění: Obvykle do 240 minut
Orientační cena: od 4 000 Kč
Co je zahrnuto v ceně: * vstupní kontrola DPF filtru * profesionální mokré čištění * sušení a výstupní kontrola *  konzultace dalšího provozu
TLAČÍTKO: Objednat čištění (proklik na stránku Kontakt)

•	Čištění DPF – dodávky 
Pro koho je služba určena: Pro podnikatele, rozvážkové služby a menší flotily, kde je klíčová rychlost a minimalizace odstávky vozidla.
Doba čištění: Obvykle do 240 minut
Orientační cena: od 6 500 Kč
Co je zahrnuto v ceně: * vstupní kontrola DPF filtru * profesionální mokré čištění * sušení a výstupní kontrola *  konzultace dalšího provozu
TLAČÍTKO: Objednat čištění (proklik na stránku Kontakt)

•	Čištění DPF – nákladní vozidla 
Pro koho je služba určena: Pro dopravce a firmy provozující těžkou nákladní techniku.
Doba čištění: Obvykle do 240 minut
Orientační cena: od 14 000 Kč
Co je zahrnuto v ceně: * vstupní kontrola DPF filtru * profesionální mokré čištění * sušení a výstupní kontrola *  konzultace dalšího provozu
TLAČÍTKO: Objednat čištění (proklik na stránku Kontakt)

•	Čištění DPF – autobusy
Pro koho je služba určena: Pro dopravní společnosti a provozovatele autobusové dopravy.
Doba čištění: Obvykle do 240 minut
Orientační cena: od 14 000 Kč
Co je zahrnuto v ceně: * vstupní kontrola DPF filtru * profesionální mokré čištění * sušení a výstupní kontrola *  konzultace dalšího provozu
TLAČÍTKO: Objednat čištění (proklik na stránku Kontakt)

•	Čištění DPF – stavební a pracovní stroje
Pro koho je služba určena: Pro stavební firmy a provozovatele techniky pracující v prašném a náročném prostředí.
Doba čištění: Obvykle do 240 minut
Orientační cena: od 14 000 Kč
Co je zahrnuto v ceně: * vstupní kontrola DPF filtru * profesionální mokré čištění * sušení a výstupní kontrola *  konzultace dalšího provozu
TLAČÍTKO: Objednat čištění (proklik na stránku Kontakt)

•	Čištění DPF – zemědělské stroje
Pro koho je služba určena: Pro zemědělce a provozovatele traktorů a zemědělské techniky.
Doba čištění: Obvykle do 240 minut
Orientační cena: od 14 000 Kč
Co je zahrnuto v ceně: * vstupní kontrola DPF filtru * profesionální mokré čištění * sušení a výstupní kontrola *  konzultace dalšího provozu
TLAČÍTKO: Objednat čištění (proklik na stránku Kontakt)

Sekce: č.3
Kdy čištění nedává smysl 
Ne každý DPF filtr lze zachránit. Při vstupní kontrole vždy posuzujeme, zda má čištění smysl. Pokud čištění nedává smysl, řekneme to na rovinu.

Čištění nedoporučujeme zejména v případech, kdy:
•	Je filtr mechanicky poškozený nebo prasklý,
•	došlo k poškození keramického jádra,
•	je filtr nevratně zničený extrémními teplotami,
•	je konstrukčně nevyhovující pro bezpečné čištění.

Sekce: č.4
Výjezd & servis u zákazníka
Nemáte možnost DPF filtr přivézt?
My to vyřešíme za vás. Nabízíme výjezd, demontáž a odvoz filtru k nám, vyčištění a montáž filtru zpět.

1.	Přijedeme k zákazníkovi,
2.	odvezeme filtr na čištění,
3.	po vyčištění filtr vrátíme,
4.	minimální odstávka vozidla.
TLAČÍTKO: Domluvit výjezd (proklik na stránku Kontakt)

3. TECHNOLOGIE
Sekce: HERO (zde použít Foto4)
H1: Technologie 
H2:  Profesionální mokré čištění, sušení, diagnostika filtru, kontrolované postupy a ověřené výsledky

Sekce: č.2
Technologie čištění DPF filtrů, která dává smysl
Čištění DPF filtru není jen o „propláchnutí“. Rozhoduje technologie, postup a zkušenost. Právě proto používáme specializované zařízení a procesy, které respektují konstrukci DPF filtru a jeho skutečné zanesení.

Mokré čištění funguje na principu
•	Řízeného proudění horké vody,
•	speciálních čisticích prostředků,
•	odstranění nečistot opačným směrem, než kterým proudí výfukové plyny,
•	řízené sušení filtru.
Tím se z filtru fyzicky odstraní i nečistoty, které běžná regenerace nikdy nevyřeší. 

Sekce: č.2 (zde použít Foto8)
Technologie Advanpure AD4000
Pro čištění používáme profesionální technologii Advanpure AD4000, určenou pro mokré čištění DPF filtrů osobních, užitkových i těžkých vozidel. Celý proces je nastaven tak, aby byl účinný, šetrný a opakovatelný. Čistící stroj ADVANPURE AD4000 funguje na bázi hydrodynamického čištění.

Proces zahrnuje:
•	Vstupní kontrolu stavu filtru,
•	řízené mokré čištění,
•	sušení horkým vzduchem,
•	výstupní kontrolu průchodnosti.

Sekce: č.3
Proč je mokrá metoda účinnější než vypalování a jiné „garážové“ čištění
Mokré čištění je řešení ve chvíli, kdy regenerace přestává fungovat.

→ vytvořit jako porovnání
Vypalování / regenerace:
•	Řeší především saze,
•	neodstraní popel,
•	často má jen krátkodobý efekt.

Mokré čištění:
•	Fyzicky odstraňuje saze i popel,
•	obnovuje průchodnost filtru,
•	prodlužuje životnost DPF filtru.

Sekce: č.4 (zde použít Foto5)
Postupy, kontrola kvality a know-how
Každý DPF filtr má jinou konstrukci a jiný stupeň zanesení. Proto nepoužíváme univerzální postupy „na jeden klik“.

U každého filtru:
•	Provádíme vstupní kontrolu,
•	volíme vhodný čisticí režim,
•	po čištění provádíme výstupní kontrolu,
•	zákazník dostává jasnou informaci o výsledku.

Sekce: č.5 (zde použít Foto2)
Certifikované postupy a školený personál

Používaná technologie vyžaduje správné nastavení a znalost postupů. Naši pracovníci jsou pravidelně školeni a dodržují doporučené výrobní a bezpečnostní postupy.

Díky tomu:
•	Minimalizujeme riziko poškození filtru,
•	zajišťujeme opakovatelné výsledky,
•	držíme vysokou úspěšnost čištění.

Sekce: č.6 VIDEO Z PROVOZU: Video1
Jak čištění DPF probíhá v praxi
Ukázka procesu čištění DPF filtru na profesionálním zařízení. 

Sekce: č.7
Mýty o DPF filtrech
❌ Mýtus: Regenerace DPF filtr vyčistí
✔ Fakt:
Regenerace spálí pouze saze, které se ve filtru usazují při běžném provozu. Popel, který vzniká dlouhodobým provozem motoru, je nespálitelný a zůstává ve filtru. Právě popel je nejčastější příčinou, proč se DPF filtr postupně ucpe a problém se opakuje. Regenerace tedy není plnohodnotné vyčištění DPF filtru.

❌ Mýtus: Stačí delší jízda po dálnici a problém zmizí
✔ Fakt:
Delší jízda vyšší rychlostí může pomoci pouze v případě, že je filtr zanesen lehce a regenerace ještě probíhá správně.
Pokud je filtr zanesen popelem nebo je regenerace dlouhodobě neúspěšná, delší jízda už problém nevyřeší.

❌ Mýtus: Nucená regenerace v servisu filtr zachrání
✔ Fakt:
Nucená regenerace opět řeší hlavně saze, nikoliv popel. Často se stává, že po nucené regeneraci kontrolka DPF na chvíli zhasne, ale po krátké době se problém vrátí. V takovém případě je nutné profesionální čištění mimo vozidlo.

❌ Mýtus: Chemie do nádrže nebo sprej DPF vyčistí
✔ Fakt:
Aditiva a čisticí spreje mohou pomoci se sazemi, ale neodstraní popel usazený hluboko ve filtru. Navíc nejsou řešením u silně zanesených nebo dlouhodobě problémových DPF filtrů.

❌ Mýtus: Čištění DPF filtr poškodí
✔ Fakt:
Profesionální mokré čištění na specializované technologii je navrženo tak, aby bylo šetrné ke keramické struktuře filtru a zároveň účinné. Důležité je správné nastavení procesu podle typu filtru a jeho stavu, proto každý filtr prochází vstupní i výstupní kontrolou.

❌ Mýtus: Každý DPF filtr lze vyčistit
✔ Fakt:
Ne každý filtr je možné zachránit. Pokud je DPF filtr mechanicky poškozený nebo prasklý, čištění nemá smysl. Seriózní firma to pozná při kontrole a doporučí správné řešení.

Nejste si jistí, zda má čištění vašeho DPF filtru smysl?
Ozvěte se nám – stav filtru zhodnotíme a navrhneme vhodné řešení.
TLAČÍTKO: Kontaktovat nás (proklik na stránku Kontakt)

4. PRO AUTOSERVISY
Sekce: HERO (zde použít Foto7)
H1: Spolehlivý partner pro čištění DPF filtrů
H2: Rozšiřte své služby bez investic do technologií a rizika reklamací
TLAČÍTKO: Navázat spolupráci (proklik na stránku Kontakt)

Sekce: č.2
Proč spolupracovat s FOPROS LTM
DPF filtry jsou častým a citlivým tématem. My vám pomůžeme je řešit odborně, rychle a bez zbytečných komplikací jako externí specialista, na kterého se můžete spolehnout.

Jsme váš technický partner pro řešení DPF filtrů.
•	Specializace výhradně na DPF filtry a katalyzátory,
•	profesionální technologie mokrého čištění,
•	jasné postupy a kontrola kvality,
•	rychlé dodací termíny.

Sekce: č.3
Jak spolupráce probíhá
→ jednoduchá časová osa / infografika
1.	Autoservis identifikuje problém s DPF filtrem.
2.	Filtr je demontován v servisu.
3.	DPF filtr převezmeme nebo je doručen k nám.
4.	Provedeme odborné čištění a kontrolu.
5.	Filtr vrátíme zpět autoservisu.
6.	Autoservis provede montáž a předání zákazníkovi.
7.	Jednoduchý proces bez zdržení a bez zbytečných otázek.

Sekce: č.4
Co získáte spoluprací
•	Možnost nabídnout zákazníkovi profesionální řešení s filtry DPF,
•	žádné investice do drahých technologií,
•	nižší riziko reklamací,
•	úsporu času a starostí,
•	stabilního partnera pro opakované zakázky.
Vy zůstáváte hlavním kontaktem pro zákazníka.

Sekce: č.5
Technický přístup a transparentnost
Každý DPF filtr posuzujeme individuálně. Pokud čištění nedává smysl, řekneme to otevřeně ještě před zahájením zakázky.
•	Vstupní kontrola filtru,
•	jasná informace o stavu,
•	žádné „zázračné opravy“,
•	realistické očekávání výsledku.

Sekce: č.6
Pro koho je spolupráce ideální
•	Autoservisy bez vlastní technologie čištění DPF,
•	servisy, které chtějí rozšířit nabídku služeb,
•	menší i větší servisy hledající spolehlivého partnera,
•	servisy, které chtějí snížit počet nevyřešených reklamací DPF.

Sekce: č.7
Spolupracujeme

CHOMUTOV
Autoservis Tomáš Vaňko
Web: vanko-servis.cz (https://www.vanko-servis.cz/)

LITOMĚŘICE
Autoservis Jaroslav Veselý
Web: autoservis-ltm.cz (https://autoservis-ltm.cz/)

TEREZÍN
Autoservis Zdeněk Tyl
Tel: 606 888 006 (aktivní proklik – tel: +420606888006)

BÝČKOVICE
Autoservis Tomáš Fadler
Tel: 775 683 083 (aktivní proklik – tel:+420775683083)

Sekce: č.8
Máte zájem o spolupráci?
Ozvěte se nám. Probereme možnosti spolupráce a nastavíme jednoduchý a funkční model.
TLAČÍTKO: Kontaktovat nás (proklik na stránku Kontakt)

5. ČASTÉ DOTAZY
Sekce: HERO (zde použít Foto6)
H1: Časté dotazy

Jak dlouho trvá čištění DPF filtru?
Čištění DPF filtru u nás obvykle trvá do 240 minut od zahájení procesu. Konkrétní čas závisí na typu filtru, míře zanesení a jeho velikosti. U větších filtrů (nákladní vozidla, autobusy, stroje) může být doba čištění stanovena individuálně.

Co je DPF, FAP a SCR?
•	DPF (Diesel Particulate Filter)
Filtr pevných částic, který zachytává saze a jemné částice z výfukových plynů dieselových motorů.
•	FAP (Filtre à Particules)
Označení DPF filtru používané zejména u francouzských vozidel (Peugeot, Citroën, Renault). Funkčně jde o stejný typ filtru.
•	SCR (Selective Catalytic Reduction)
Systém pro snížení emisí oxidů dusíku (NOx), který pracuje s kapalinou AdBlue. Nejde o filtr pevných částic, ale o jiný emisní systém.

Když svítí kontrolka DPF, co mám dělat?
Rozsvícená kontrolka DPF neznamená automaticky vážný problém, ale signalizuje, že filtr je zanesený.
Doporučený postup:
•	Pokud je to možné, zkuste delší jízdu mimo město při vyšších otáčkách, aby proběhla regenerace.
•	Pokud kontrolka nezhasne nebo se vrací často, je vhodné nechat stav DPF odborně posoudit.
•	Dlouhodobé ignorování kontrolky může vést k omezení výkonu motoru nebo k nouzovému režimu.

Dá se vyčistit každý DPF filtr?
Ne. Většinu DPF filtrů vyčistit lze, ale ne všechny. Čištění není vhodné, pokud je filtr:
•	Mechanicky poškozený nebo prasklý,
•	konstrukčně zničený.
Proto vždy provádíme vstupní kontrolu a teprve poté doporučíme další postup.

Jak poznám, že už je DPF filtr neopravitelný?
Typické znaky neopravitelného DPF filtru:
•	Filtr je prasklý nebo má viditelné poškození,
•	extrémně vysoký protitlak i po regeneracích.
Laik to často nepozná, proto je důležité odborné posouzení před jakýmkoli zásahem.

Je lepší DPF filtr vyčistit, nebo koupit nový?
Pokud není filtr mechanicky poškozený, čištění dává ve většině případů smysl:
•	Je výrazně levnější než nový filtr,
•	zachováte originální díl vozidla,
•	jde o ekologičtější řešení.
Výměnu doporučujeme pouze tehdy, pokud je filtr nevratně poškozený.

Pomohou aditiva nebo chemie do nádrže?
Aditiva mohou podpořit regeneraci a pomoci se sazemi, ale:
•	Neodstraní popel,
•	nejsou řešením silně zaneseného DPF.
Pokud se problém s DPF opakuje, chemie většinou nestačí.

Jak často je potřeba DPF filtr čistit?
Neexistuje jednotný interval. Záleží na:
•	Stylu jízdy,
•	typu provozu (město vs. delší trasy),
•	technickém stavu motoru,
•	stáří vozidla.
U vozidel s častými krátkými jízdami se zanášení objevuje výrazně dříve.

Musím filtr demontovat sám?
Nemusíte. Pokud nemáte možnost filtr demontovat, můžete přijet k nám nebo dojet do s námi spolupracujícího autoservisu. Spolupracující servisy naleznete na stránce „Pro autoservisy“. Případně naše spolupracující autoservisy pro vás rádi obvoláme a zjistíme jejich aktuální vytíženost. (odkaz na stránku „Pro autoservisy“ – sekce „Spolupracujeme“.)

Nenašli jste odpověď na svou otázku?
Ozvěte se nám. Rádi vám poradíme a navrhneme správné řešení.
TLAČÍTKO: Kontaktovat nás (proklik na stránku Kontakt)

6. O NÁS
Sekce: HERO (zde použít Foto1)
H1: O nás

Sekce: č.2
Odborné řešení bez zbytečných slibů a kompromisů.
Čištění DPF filtrů není vedlejší služba. Je to náš hlavní obor.
Profesionální technologie, jasné postupy a reálné výsledky.

Sekce: č.3
Kdo jsme (zde použít Foto2)
Jsme FOPROS LTM, firma zaměřená na profesionální čištění DPF filtrů a souvisejících emisních komponentů.

Naší specializací je odborné čištění filtrů u osobních, užitkových i těžkých vozidel včetně stavební a zemědělské techniky. Působíme v Litoměřicích. Služby poskytujeme zákazníkům z celé České republiky. Neodesíláme filtry „někam dál“.

Nepůsobíme jako zprostředkovatel nebo přeprodejce služeb. Čištění provádíme přímo u nás, na vlastní technologii a pod vlastní kontrolou. Neodesíláme filtry „někam dál“. Naši zákazníci přesně ví, kde je jeho DPF filtr, kdo ho čistí a
jakým postupem.

Sekce: č.4
Čím se lišíme
Neříkáme zákazníkům to, co chtějí slyšet. Říkáme jim to, co je technicky správné.

•	Specializace výhradně na DPF filtry a katalyzátory,
•	profesionální mokrá technologie,
•	kontrola kvality u každé zakázky,
•	žádné „zázračné opravy“,
•	férové a otevřené jednání.

Sekce: č.5
Technologie, školení a zkušenosti
Používáme profesionální technologii mokrého čištění, která umožňuje odstranit saze i popel bez poškození struktury filtru.
Naši pracovníci:
•	Jsou pravidelně školeni,
•	dodržují doporučené technologické postupy,
•	pracují s kontrolou vstupních i výstupních parametrů.
Díky tomu dosahujeme vysoké úspěšnosti čištění a stabilních výsledků.

Hledáte odborné řešení pro DPF filtr? 
Ozvěte se nám. Rádi vám poradíme a navrhneme správný postup.
TLAČÍTKO: Kontaktovat nás (proklik na stránku Kontakt)

7. KONTAKT
Sekce: HERO (zde použít Foto3)
H1: Kontakty

Sekce: č.2
Kontaktujte nás
Ozvěte se nám telefonicky nebo přes kontaktní formulář. Pokud si nejste jistí, zda má čištění smysl, zavolejte nám. Poradíme ještě před tím, než filtr demontujete.

Telefon +420 777 550 773
E-mail   info@foprosltm.cz 

Kontaktní formulář
Jméno a příjmení / Název firmy (povinné)
Telefon (povinné)
E-mail (povinné)
Typ vozidla / stroje (volitelně)
Zpráva (volitelně: popis problému)
Odeslat poptávku

Vaše údaje slouží pouze ke zpracování poptávky / zodpovězení dotazu. Vaše kontaktní údaje nebudou použity k marketingovým účelům.

Formulář půjde na e-mail: info@foprosltm.cz se všemi informacemi z formuláře v těle e-mailu, subjekt e-mailu: „Zpráva z webu“
Po odeslání formuláře se zobrazí zpráva o úspěšném odeslání: Zpráva byla odeslána. Ozveme se co nejdříve zpět. FOPROS LTM

Sekce: č.3
Adresa a provozní doba
Provozní doba
Pondělí – Pátek: 8:00 – 17:00
Sobota: zavřeno
Neděle: zavřeno
Po domluvě je možné řešit zakázky individuálně.

Adresa:
FOPROS LTM s.r.o.
Na Kocandě 1913/39
412 01 Litoměřice
(bývalý areál ČSAD Litoměřice – po průjezdu branou doprava)
Mapa: <iframe style="border:none" src="https://mapy.com/s/gopalacufo" width="700" height="466" frameborder="0"></iframe>

Fakturační údaje:
FOPROS LTM s.r.o.
Dolánky nad Ohří č.p. 14
413 01 Dolánky nad Ohří
Jednatel: Libor Klenot
IČO: 08502269
DIČ: CZ08502269
Spisová značka C 44152 vedená u Krajského soudu v Ústí nad Labem, 11.9.2019.

Sekce: č.4
Jak k nám dopravit DPF filtr
🔹 Osobní doručení
Filtr můžete dovézt osobně po předchozí domluvě.
🔹 Doručení přes autoservis
Filtr může být demontován a doručen autoservisem. Spolupracující servisy naleznete na stránce „Pro autoservisy“. (odkaz na stránku „Pro autoservisy“ – sekce „Spolupracujeme“.)

🔹 Zaslání přepravní službou
Filtr lze zaslat bezpečně zabalený přepravní službou. Před odesláním doporučujeme nás kontaktovat.
🔹 Výjezd a odvoz u zákazníka
Pokud nemáte možnost filtr doručit, přijedeme k vám pro demontovaný filtr, vyčistíme a vrátíme zpět.

PATIČKA WEBU
Kontaktní údaje
Telefon +420 777 550 773
E-mail   info@foprosltm.cz 

FOPROS LTM s.r.o.
Na Kocandě 1913/39
412 01 Litoměřice
(bývalý areál ČSAD Litoměřice – po průjezdu branou doprava)
Mapa: <iframe style="border:none" src="https://mapy.com/s/gopalacufo" width="700" height="466" frameborder="0"></iframe>

Ochrana osobních údajů

Zásady zpracování osobních údajů

Níže naleznete zásady zpracování osobních údajů, které nám jako správci poskytnete, pokud navštívíte naše webové stránky dostupné na internetové adrese https://foprosltm.cz, dále pokud jste našimi zákazníky nebo zájemci o naše produkty či služby. 

Osobní údaje zpracováváme v souladu s platnými a účinnými právními předpisy, zejména v souladu s nařízením Evropského parlamentu a Rady (EU) 2016/679 - obecné nařízení o ochraně osobních údajů (dále jen „GDPR“) a v souladu se zákonem č. 110/2019 Sb., o zpracování osobních údajů. 

Účelem tohoto dokumentu je seznámit Vás s tím, jak bude s Vašimi osobními údaji nakládáno a informovat Vás o Vašich právech.

OBSAH:

I.	Správce osobních údajů – naše identifikační a kontaktní údaje
II.	Zdroj osobních údajů – odkud získáme k Vašim osobním údajům přístup
III.	Kategorie osobních údajů a požadavek na jejich poskytnutí – které osobní údaje o Vás zpracováváme, zda máte povinnost nám je poskytnout a jaký je důsledek jejich neposkytnutí 
IV.	Účely a doba zpracování – k jakým účelům a po jakou dobu Vaše osobní údaje zpracováváme a co nás k tomu opravňuje
V.	Automatizované rozhodování a profilování – zda z naší strany dochází k automatizovanému individuálnímu rozhodování nebo k profilování
VI.	Cookies – které cookies používáme 
VII.	Příjemci osobních údajů – komu Vaše osobní údaje zpřístupňujeme
VIII.	Předávání osobních údajů do třetí země nebo mezinárodní organizaci – zda Vaše osobní údaje budou předány do země mimo Evropskou unii 
IX.	Zabezpečení osobních údajů – která technická a organizační opatření k zabezpečení Vašich osobních údajů jsme přijali
X.	Vaše práva – jaká máte práva ve vztahu ke zpracování osobních údajů
XI.	Závěrečná ustanovení – účinnost tohoto dokumentu a možnost jeho změny

I.	SPRÁVCE OSOBNÍCH ÚDAJŮ

Správcem osobních údajů je:

FOPROS LTM s.r.o.
Libor Klenot
Společnost zapsaná v obchodním rejstříku vedeném u Krajského soudu v Ústí nad Labem, spisová značka C 44152, 11.9.2019.
IČO: 08502269
DIČ: CZ08502269
Sídlo: Dolánky nad Ohří č.p. 14, 413 01 Dolánky nad Ohří
Telefon: +420 777 550 773
E-mail:   info@foprosltm.cz 

II.	ZDROJ OSOBNÍCH ÚDAJŮ

Zpracováváme osobní údaje, které získáme přímo od Vás. Vaše osobní údaje získáváme tím, že navštívíte naše webové stránky, že na našich webových stránkách vyplníte a odešlete některý z formulářů nebo jiným způsobem (např. tím, že nám je poskytnete e-mailem, telefonicky, v průběhu videohovoru, prostřednictvím sociálních sítí nebo při osobním jednání).

III.	KATEGORIE OSOBNÍCH ÚDAJŮ A POŽADAVEK NA JEJICH POSKYTNUTÍ

1.	V nezbytném rozsahu o Vás zpracováváme zejména následující běžné osobní údaje, pokud nám je zpřístupníte: jméno a příjmení, IČO, DIČ, adresa bydliště, adresa sídla, platební údaje, telefonní číslo, e-mailová adresa, identifikátor jiné formy komunikace na dálku, IP adresa, informace o Vámi objednaných produktech či službách a další informace, které nám v průběhu naší komunikace či spolupráce poskytnete (údaje týkající se Vašeho rodinného stavu, osobních a majetkových poměrů apod.). 

2.	Pokud nám umožníte zveřejnit Vaši referenci, a případně nám také poskytnete svou fotografii či videozáznam, zpracováváme o Vás rovněž osobní údaje uvedené v referenci a příslušnou fotografii či videozáznam. Pokud využijete možnosti přihlášení, diskuze, hodnocení nebo sdílení prostřednictvím sociálních sítí (Facebook, Instagram), zpracováváme o Vás také informace uvedené ve Vašem příspěvku či komentáři a veřejné informace na Vašem profilu v příslušné sociální síti (zejm. jméno a příjmení, fotografie, věková kategorie a další veřejné informace podle Vašeho nastavení). 

3.	Poskytnutí kategorie běžných osobních údajů uvedených v odstavci 1 tohoto článku je nezbytné pro vzájemnou komunikaci nebo pro uzavření a splnění smlouvy; v případě jejich neposkytnutí tedy nebude možné vzájemně komunikovat nebo uzavřít a splnit smlouvu. V případech, kdy zpracování osobních údajů je založeno na Vašem souhlasu, závisí pouze na Vašem rozhodnutí, zda nám své osobní údaje poskytnete či nikoli.  

4.	Zvláštní kategorie osobních údajů (citlivé údaje) o Vás zpracováváme jen tehdy, pokud nám tyto údaje v průběhu naší spolupráce dobrovolně sdělíte a jen s Vaším výslovným souhlasem. Jedná se o osobní údaje, které vypovídají o rasovém či etnickém původu, politických názorech, náboženském vyznání či filozofickém přesvědčení, členství v odborech, zdravotním stavu, sexuálním životě nebo sexuální orientaci.

IV.	ÚČELY A DOBA ZPRACOVÁNÍ

A.	ZPRACOVÁNÍ OSOBNÍCH ÚDAJŮ PRO ÚČELY UZAVŘENÍ A SPLNĚNÍ SMLOUVY

1.	Vaše osobní údaje zpracováváme pro účely uzavření smlouvy a splnění mezi námi uzavřené smlouvy (vzájemná komunikace před i po uzavření smlouvy, dodání objednaného produktu nebo služby, uskutečnění platby). K tomuto účelu zpracováváme Vaše běžné osobní údaje uvedené v čl. III odst. 1 výše a s Vaším výslovným souhlasem i zvláštní kategorie osobních údajů (citlivé údaje) uvedené v čl. III odst. 4 výše.   

2.	Právním titulem (oprávněním) pro zpracování osobních údajů je splnění smlouvy uzavřené mezi námi a provedení opatření přijatých před uzavřením smlouvy na Vaši žádost.
 
3.	K tomuto účelu Vaše osobní údaje zpracováváme po dobu trvání smluvního vztahu mezi námi a po jeho skončení pak některé Vaše osobní údaje dále zpracováváme za jinými účely (viz písmena B až F níže).

B.	ZPRACOVÁNÍ OSOBNÍCH ÚDAJŮ PRO ÚČELY SPLNĚNÍ PRÁVNÍCH POVINNOSTÍ 

1.	Osobní údaje zpracováváme dále pro účely splnění právních povinností, které se na nás vztahují (např. zákonné povinnosti v oblasti daní). K tomuto účelu zpracováváme tyto Vaše osobní údaje: jméno a příjmení, IČO, DIČ, adresa bydliště, adresa sídla, platební údaje a informace o Vámi objednaných produktech či službách. 

2.	Právním titulem (oprávněním) pro zpracování osobních údajů je tedy splnění právní povinnosti, která se na nás vztahuje. 

3.	K tomuto účelu Vaše osobní údaje zpracováváme po dobu stanovenou obecně závaznými právními předpisy.

C.	ZPRACOVÁNÍ OSOBNÍCH ÚDAJŮ PRO ÚČELY OCHRANY PRÁV A VYMÁHÁNÍ NÁROKŮ

1.	Osobní údaje zpracováváme i pro účely ochrany našich práv a vymáhání právních nároků (zejm. z uzavřených smluv nebo způsobené újmy). K tomuto účelu zpracováváme Vaše osobní údaje z uzavřených smluv a naší vzájemné komunikace.   

2.	Právním titulem (oprávněním) pro zpracování osobních údajů je náš oprávněný zájem.

3.	K tomuto účelu Vaše osobní údaje zpracováváme po dobu trvání smluvního vztahu a následující 4 roky po jeho ukončení, nebo po dobu 4 let od našeho posledního kontaktu, pokud k uzavření smlouvy nedošlo, a v případě vzniku sporu rovněž po celou dobu trvání sporu až do jeho pravomocného skončení a uspokojení všech nároků.  

D.	ZPRACOVÁNÍ OSOBNÍCH ÚDAJŮ NA ZÁKLADĚ VAŠEHO SOUHLASU

1.	Na základě Vašeho souhlasu budeme Vaše osobní údaje zpracovávat k následujícím účelům:

a.	zveřejnění Vaší reference na našich webových stránkách, sociálních sítích či v jiných propagačních materiálech;
b.	diskuze, hodnocení nebo sdílení informací prostřednictvím sociálních sítí.  

2.	Souhlas nám můžete udělit např. prostřednictvím vyplnění a odeslání některého formuláře na našich webových stránkách, prostřednictvím vyskakovací lišty na našich webových stránkách, v průběhu individuální komunikace (např. e-mailem), v listinné podobě, vložením příspěvku, komentáře nebo reakce na příspěvek či komentář v sociální síti, případně jiným způsobem. Před udělením souhlasu Vás budeme informovat, které osobní údaje budeme na základě Vašeho souhlasu zpracovávat a k jakému konkrétnímu účelu zpracování se bude Váš souhlas vztahovat. 

3.	Svůj souhlas můžete kdykoli odvolat, pokud ovšem Vaše osobní údaje zpracováváme i na základě jiných právních titulů uvedených pod písmeny A až C výše, budeme je na základě tohoto příslušného titulu zpracovávat i po odvolání Vašeho souhlasu. 

V.	COOKIES

1.	Používáme pouze technické a funkční soubory cookies. Technické a funkční soubory cookies zajišťují správnou funkci našich webových stránek a usnadňují jejich návštěvu. Tyto cookies můžou být umístěny bez Vašeho souhlasu. 

VI.	PŘÍJEMCI OSOBNÍCH ÚDAJŮ

1.	Pokud Vaše osobní údaje sdílíme s jinou osobou, dbáme na to, aby byla zajištěna jejich ochrana.

2.	Vzhledem k tomu, že veškeré činnosti v rámci svého podnikání nedokážeme zajistit vlastními silami, využíváme služeb a aplikací třetích osob, které tak získají k Vašim osobním údajům přístup. S těmito osobami máme uzavřeny příslušné smlouvy podle GDPR.

3.	Konkrétně se jedná o následující příjemce osobních údajů:

a)	webhosting a doména: Webkitty.cz, IČ 19863209
b)	e-mailing: nevyužíván
c)	fakturační systém: C-Stereo NX 2026 
d)	rezervační systém: nevyužíván
e)	platební brána: nevyužívána
f)	e-shopová platforma: nevyužívána 
g)	přeprava zboží: nevyužívána
h)	sociální sítě: Facebook a Instagram (Meta Platforms)
i)	webařka: Mgr. Lucie Pelíšek, IČ 10826246
j)	účetní firma: nevyužívána
k)	marketingová firma: nevyužívána
l)	cloudové úložiště: nevyužíváno

5.	K Vašim osobním údajům mají přístup také další uživatelé sociálních sítí, kam vkládáte příspěvky, komentáře či reakce. Vyslovujete s tímto sdílením svých osobních údajů souhlas.  
 
6.	Vaše osobní údaje budou zpřístupněny i příslušným správním orgánům nebo soudům, případně právním zástupcům, abychom splnili svou zákonnou povinnost nebo ochránili svá práva a oprávněné zájmy. 

7.	Pokud by v budoucnu došlo k využívání dalších aplikací nebo služeb jiných osob, budeme při jejich výběru dbát na to, aby byl zachován náš standard zabezpečení a zpracování osobních údajů. 

VII.	PŘEDÁVÁNÍ OSOBNÍCH ÚDAJŮ DO TŘETÍ ZEMĚ NEBO MEZINÁRODNÍ ORGANIZACI

Veškeré zpracování osobních údajů bude prováděno na území Evropské unie.
VIII.	ZABEZPEČENÍ OSOBNÍCH ÚDAJŮ

1.	Jako správce jsme přijali veškerá technická a organizační opatření k zabezpečení Vašich osobních údajů, aby nemohlo dojít k náhodnému nebo protiprávnímu přístupu k Vašim osobním údajům, k jejich změně, zničení či ztrátě, k jejich neoprávněnému zpracování či k jejich jinému zneužití. Přijatá technická a organizační opatření odpovídají míře rizika pro práva a svobody fyzických osob, povaze, rozsahu a účelům zpracování osobních údajů.

2.	K zabezpečení Vašich osobních údajů jsme přijali zejména následující technická a organizační opatření: 

a)	ochrana přístupu k výpočetní technice, jíž jsou zpracovávány osobní údaje, individuálními silnými hesly a ochrana těchto hesel před vyzrazením;
b)	ochrana této výpočetní techniky antivirovými programy;
c)	ochrana přenosné výpočetní techniky nebo přenosných úložišť dat (dohled, zaheslování dat atd.);
d)	uzamykání prostor, v nichž jsou uloženy dokumenty s osobními údaji;
e)	svěření přístupu k osobním údajům pouze pověřeným osobám, které jsou vázány povinností zachovávat mlčenlivost o Vašich osobních údajích i přijatých bezpečnostních opatřeních.  

3.	Zavedená technická a organizační opatření jsou pravidelně testována a je posuzována a hodnocena jejich účinnost pro zajištění bezpečnosti zpracování osobních údajů.    

IX.	VAŠE PRÁVA

1.	Ve vztahu ke zpracování osobních údajů máte následující práva:

a)	Právo na přístup k osobním údajům (čl. 15 GDPR)
Máte právo získat informaci, zda Vaše osobní údaje jsou či nejsou zpracovávány, a pokud zpracovávány jsou, máte právo na přístup k osobním údajům a na podrobnosti týkající se zpracování Vašich osobních údajů.

b)	Právo na opravu, resp. doplnění osobních údajů (čl. 16 GDPR) 
Máte právo požadovat, abychom opravili nepřesné osobní údaje, které se Vás týkají, a s přihlédnutím k účelům zpracování máte rovněž právo na doplnění neúplných osobních údajů.

c)	Právo na výmaz osobních údajů (čl. 17 GDPR) 
Máte právo požadovat, abychom vymazali osobní údaje, které se Vás týkají, a pokud je dán některý z důvodů uvedených v čl. 17 GDPR, máme povinnost Vaše osobní údaje na základě Vaší žádosti vymazat.

d)	Právo na omezení zpracování osobních údajů (čl. 18 GDPR) 
Jsou-li splněny podmínky stanovené v čl. 18 GDPR, máte právo na to, abychom omezili zpracování Vašich osobních údajů.

e)	Právo na přenositelnost osobních údajů (čl. 20 GDPR) 
Pokud je zpracování Vašich osobních údajů prováděno automatizovaně, a zároveň je založeno na souhlasu nebo na smlouvě, máte právo získat osobní údaje, které se Vás týkají, ve strukturovaném, běžně používaném a strojově čitelném formátu, a předat je jinému správci. Je-li to technicky proveditelné, máte rovněž právo požadovat, abychom Vaše osobní údaje sami předali jinému správci.

f)	Právo vznést námitku proti zpracování osobních údajů (čl. 21 GDPR) 
Za podmínek uvedených v čl. 21 GDPR máte právo kdykoli vznést námitku proti zpracování osobních údajů. Pokud vznesete námitku proti zpracování osobních údajů pro účely přímého marketingu, vč. profilování, nebudeme už Vaše osobní údaje pro tyto účely zpracovávat.

g)	Právo odvolat souhlas se zpracováním osobních údajů
Pokud jsou osobní údaje zpracovávány na základě Vašeho souhlasu, máte právo kdykoli svůj souhlas se zpracováním osobních údajů odvolat. Odvoláním souhlasu není dotčena zákonnost zpracování založená na dříve uděleném souhlasu.

h)	Právo podat stížnost k Úřadu pro ochranu osobních údajů
V případě, že se domníváte, že bylo porušeno Vaše právo na ochranu osobních údajů, máte právo podat stížnost k Úřadu pro ochranu osobních údajů (https://uoou.gov.cz/).

2.	Svá práva můžete u nás uplatnit s využitím kontaktů uvedených výše (poštovní či e-mailová adresa). Před vyřízením Vaší žádosti Vás můžeme ještě kontaktovat, a to za tím účelem, abychom si přiměřeným způsobem ověřili Vaši totožnost.

X.	ZÁVĚREČNÁ USTANOVENÍ

1.	Tyto zásady zpracování osobních údajů jsme oprávněni v přiměřeném rozsahu změnit. Jejich aktuální znění naleznete na našich shora uvedených webových stránkách.  

2.	Tyto zásady zpracování osobních údajů nabývají účinnosti dnem 3. 3. 2026.