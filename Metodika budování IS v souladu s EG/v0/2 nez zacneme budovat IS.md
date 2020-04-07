# Co vědět před budováním agendového informačního systému


Než vůbec začneme budovat nový IS či rozvíjet stávající, měli bychom si vyjasnit pár věcí.


## Proč budujeme a rozvíjíme AIS?


Měli bychom mít jasno, proč chceme či musíme budovat informační systém, jakého druhu daný IS bude a co budeme potřebovat. Zejména musíme mít znalost o tom:


-   K čemu budeme řešení informačního systému skutečně využívat,
-   o jaký druh informačního systému se bude jednat,
-   podle jakého zákonného zmocnění IS budujeme,
-   zda máme splněny veškeré podmínky pro to nutné.


### Vzniká nový, nebo se upravuje stávající?


Přestože tato metodika hovoří o budování informačního systému, lze ji vztáhnout i na změnu stávajícího IS. Ve skutečnosti jsou jak podle legislativy, tak podle dalších motivačních dokumentů kroky pro tvorbu i rozvoj IS poměrně podobné.


Budování nového informačního systému je z tohoto pohledu samozřejmě jednodušší, protože se začíná de facto od začátku. Od počátku se tedy dá postupovat správně a efektivně, od počátku lze počítat s naplněním všech principů a uvedení do souladu s eGovernmentem.


Obecně mohou nastat tyto tři situace:


1.  Vybudování zcela nového informačního systému
2.  Rozvoj stávajícího informačního systému
3.  Náhrada stávajícího informačního systému novým technickým řešením


V prvním případě lze v kombinaci se správně konstruovanou legislativou vytvořit opravdu moderní informační systém splňující všechny požadavky eGovernmentu a poskytující opravdu moderní sdílené služby. Takového komfortu při budování lze dosáhnout i ve třetím případě, kdy se rozhodneme nahradit stávající řešení celého IS novým technickým řešením. Pak lze postupovat shodně jako při budování zcela nového IS. Naopak není vhodné se omezovat jen na kopírování funkcionalit nahrazovaného řešení. Nejsložitější z tohoto pohledu je tedy druhá možnost, tedy rozvoj stávajícího technického provedení informačního systému, kdy je jeho správce nejvíce svázán dosavadními dodavateli a funkcionalitami. I zde je ale nutnost dodržet vše níže uvedené a zbavit se tak problémů.


Při rozvoji informačního systému se musíme snažit:


-   Omezit závislost na jediném stávajícím dodavateli
-   Změnit postupně architekturu IS na modulární a komponentovou
-   Postupně oddělovat funkcionality do samostatných modulů a komponent nezávislých na stávajícím dodavateli a stávajících technologiích
-   Zavést otevřenou integraci mezi jednotlivými komponentami systému
-   Oddělit aplikační a datovou vrstvu


### Kde najít otázky, na něž bychom měli znát odpověď?


Před samotnou akcí je vhodné si zodpovědět několik základních otázek, jako kupříkladu:


-   Vím přesně, co chci?
-   Znám povinnosti, které musím splnit?
-   Znám požadavky EG, s nimiž musím být v souladu?
-   Vím, jak budu postupovat?
-   Vím, kdo má v procesu pořízení či změny tohoto IS klíčovou roli?
-   Vím, s kým a jak budu spolupracovat?
-   Nezapomněl jsem na něco?


Zejména u té poslední dvojice by pak mohlo pomoci si prostudovat některé klíčové dokumenty, jako je Národní architektonický plán, Metody řízení ICT, Informační koncepce ČR a Informační koncepce úřadu apod.


V rámci nástrojů k "zásadám digitálně přívětivé legislativy" je vypracován soubor 21 otázek, které by si gestor legislativy a architekt řešení IS měli zodpovědět. Řada z těchto otázek se týká až realizační fáze, proto jsou vhodné ke zodpovězení právě před zahájením nebo těsně po zahájení interního projektu tvorby či rozvoje informačního systému. Níže je výběr těch pro realizaci IS zásadních:


xxxsemotázky


Podrobněji se otázkám věnuje část "Ověřovací otázky" v rámci portálu k DPL na webu digilegislativa.cz


Je také nanejvýše vhodné si podrobně prostudovat kapitoly "Životní cyklus IS" a související z materiálu "Metody řízení ICT ve veřejné správě". A pro správný postup při sběru a vyhodnocení požadavků na informační systém také materiál "Funkční a nefunkční požadavky na ISVS".


Xxxsemodkazynasouvisejícívěci


## Druhy budovaných informačních systémů


Ve veřejné správě se obecně můžeme setkat zejména s následujícími druhy informačních systémů. Každý ze zde uvedených druhů má svá specifika a k jeho pořízení a rozvoji a provozu musíme přistupovat odlišně. Proto je nutno si je vyjasnit a zejména si vyjasnit, kdo a jak jej bude spravovat:
                                                                                                                                                                                                        
Table: Základní druhy informačních systémů ve veřejné správě podle jejich gestora a využití 


| Druh    |                                                             Kdo buduje    |                                           Popis |
|-----|-----|-----|
|  Informační systém centrální sdílené služby                        |   Gestor sdílené služby (většinou MV)                    |  Speciální Kategorie informačního systému, který slouží pro provoz centrální sdílené služby eGovernmentu, kterou mohou či musí všichni využívat
| Centralizovaný agendový informační systém pro přenesenou působnost |  Gestor agendy přenesené působnosti (ministerstvo)      |  Agendový informační systém sloužící všem OVM působícím v agendě pro podporu výkonu agendy a jejich činností. Spravuje jeden správce, využívají OVM působící v agendě, a to včetně územních samospráv
|  Centralizovaný AIS pro specifické činnosti nejen pro OVM            | Gestor za danou agendu či za část výkonu (ministerstvo |  ISVS, který slouží OVM pro výkon činností, které vykonávají nikoliv jako OVM pouze, ale také slouží pro výkon činností ostatních subjektů
|  Informační systém samosprávy                                       |  Orgány územní samosprávy                               |  Informační Systém sloužící k výkonu výhradně činností v samosprávných agendách
| Informační systémy zajišťující obecnou schopnost úřadu             |  Každý povinný subjekt sám                              |  IS pro podporu činností v rámci povinně vykonávané schopnosti. Je sice nařízen zákonem, avšak neexistuje jako centrální, ale každý subjekt jej musí mít a využívat podle daného zákona
                                                                                                                                                                                                       
Tato metodika se vztahuje zejména na centralizované agendové informační systémy, některé její části lze ale úspěšně využít alespoň jako inspiraci při řešení i jiných typů IS.


