# Základní principy budování AIS


Při budování informačních systémů ve veřejné správě a zejména při budování agendových informačních systémů je nutno dodržovat zejména:


-   Architektonické principy eGovernmentu (uvedené v Informační koncepci ČR)
-   Zásady pro řízení ICT (uvedené v Informační koncepci ČR)
-   Architektonické postupy podle tematických oblastí a celků NAP (uvedené v Národním architektonickém plánu)
-   Principy budování a skladby ISVS/AIS (uvedené v této kapitole metodiky)
-   Životní cyklus informačního systému (uvedený v Metodách řízení ICT)
-   Sběr, správa a vyhodnocení požadavků na IS (uvedený v materiálu Funkční a nefunkční požadavky na IS)


## Seznam dodržitelných principů pro budování a rozvoj IS


1.  Motivací pro informační systémy je legislativa a byznysová architektura
2.  Nebudovat monolitické informační systémy, ale budovat je jako modulové a komponentové
3.  Budujeme informační systémy jako "procesní" a nikoliv jako "evidenční"
4.  Žádný informační systém nežije samostatně, nesmí se zapomínat na jeho souvislosti s dalšími systémy, včetně systémů jiných správců
5.  Budovat systémy tak, aby byly nezávislé na provozní infrastruktuře, a tedy připravené na cloud
6.  Budovat systémy jako platformově nezávislé, pokud to je možné
7.  Poptávat samostatně dodávky na systémy a samostatně jejich implementaci a provoz
8.  Poptávat systémy tak, aby byl jejich provoz a rozvoj nezávislý na primárním dodavateli
9.  Při budování systémů využívat spíše síť služeb než proprietárních dodávek po zakázkách
10. Před budováním informačních systémů musí být vyřešeny i souvislosti, včetně dlouhodobého financování provozu a rozvoje
11. Při přípravě a budování informačního systému se nesmí zapomínat na související činnosti, jako je školení, správa rolí a podpora uživatelů
12. Budování a rozvoj informačních systémů je zdrojem pro optimalizaci procesů a standardizaci výkonu činností
13. Informační systémy se budují a rozvíjejí v souladu s Informační koncepcí ČR a s informační koncepcí úřadu


## Popis jednotlivých principů a kroky k jejich dodržení


Níže jsou rozvedeny jednotlivé principy a u každého z nich je jako kontrolní seznam uveden seznam kroků, které musí správce daného IS splnit, aby princip v praxi naplnil.


### Motivací pro informační systémy je legislativa a byznysová architektura


Motivací pro pořízení každého informačního systému musí být zákonné zmocnění, či zákonná povinnost vykonávat určité činnosti. Informační systém je pak technický nástroj pro podporu výkonu těchto činností. To znamená, že jsem-li gestorem určité agendy, musím být schopen vybudovat a provozovat příslušný agendový informační systém, a to nejen pro sebe, ale i pro všechny orgány veřejné moci, které v dané agendě vykonávají působnost. Na druhou stranu, jsem-li povinen vykonávat určité činnosti v rámci agendy veřejné správy, ke které již existuje pro podporu příslušný informační systém, sám si tento informační systém nebuduji, ale využívám informační systém centrálního správce. U takového informačního systému pak pouze zajistím vazbu na svoje informační systémy.


To platí obdobně i při rozvoji a změně ISVS, která vždy musí být v souladu s danou legislativou, či její změnou.


**Praktické naplnění:**


-   Pro každou funkcionalitu každého IS jsem schopen doložit zákonné zmocnění, či zákonné ustanovení, které naplňuji.
-   Jsem schopen pravidelně vyhodnocovat soulad funkcionalit svého informačního systému se zákonnými povinnostmi, a to nikoliv pouze u příslušných agendových zákonů, ale i obecných povinností plynoucích kupříkladu ze zákonů týkajících se EG.
-   Při každém budování nového informačního systému si předem řádně odůvodním, podle jakého právního předpisu bude informační systém podporovat jaké činnosti a zdůvodním si, zda budu pořizovat nový informační systém, či zda využiji rozšíření stávajícího informačního systému o nové funkcionality. To platí i v případech, kdy nejsem gestorem, ale pouze vykonávám činnosti v dané agendě.
-   U agendy, kde vykonávám činnosti jako uživatelské OVM primárně využívám informační systém poskytovaný jako centrální AIS.
-   Respektuji především zákonem stanovenou byznysovou architekturu.
-   Byznys funkce a požadavky si udržuji já jako správce, a nikoliv, že jejich znalosti nechám výhradně na dodavateli.


### Nebudovat monolitické informační systémy, ale budovat je jako modulové a komponentové


Jednou z klíčových věcí v novém pojetí budování informačních systémů veřejné správy je postupně se zbavovat monolitických informačních systémů závislých pouze na jedné komponentě dodané jedním dodavatelem. Z tohoto důvodu je nanejvýš vhodné při rozmýšlení architektury informačních systémů tyto budovat tak, aby respektovaly princip modulárně orientované architektury skládající se z komponent a modulů, které jsou schopny provádět příslušné celky funkcionality a které mohou být dodány a rozvíjeny nezávisle.


**Praktické naplnění:**


-   Architekturu informačního systému stavím jako modulární.
-   Každý informační systém jsem schopen rozřezat na částečně funkčně samostatné moduly a komponenty a udržovat jejich vazby uvnitř systému standardizovaným rozhraním a službami.
-   Připravuji poptávání IS tak, aby každý z modulů mohl mít jiného dodavatele a soutěžím moduly a komponenty takovým způsobem, abych nebyl do budoucna závislý na jednom dodavateli jedné komponenty.
-   To, co mohu použít opakovaně, tak také použiji a nepoptávám komponenty se stejnou funkcionalitou.


### Budujeme informační systémy jako "procesní" a nikoliv jako "evidenční"


Dosud byly informační systémy ve veřejné správě koncipovány spíše jako evidenční. To začínalo samotnou konstatací a zákonným zakotvením vzniku informačního systému, která byla charakterizována spíše tak, že daný informační systém slouží pro evidenci údajů o něčem než pro podporu činnosti orgánů veřejné moci v rámci něčeho. Nyní chceme budovat procesně orientované a transakčně orientované agendové informační systémy schopné integrace mezi sebou i s jinými informačními systémy, a to včetně ISVS jiných správců. Za tímto účelem na legislativní, architektonické, ale především technické, vrstvě budujeme informační systém jako procesně orientovaný, a tedy zejména obsahující procesní workflow, které při dalším budoucím rozvoji IS využíváme k změně procesu realizovaných tímto systémem. Tím se zbavíme dosud zaběhlého konceptu, že procesní funkcionality informačního systému jsou naprogramovány napevno a každá, byť sebemenší, změna procesu tak vyžaduje údajně poměrně rozsáhlou analýzu a změnu příslušného IS.


**Praktické naplnění:**


-   AIS buduji primárně jako procesní a transakční, ne jako evidenční a funkční blackbox.
-   Jednou ze zásadních části architektury AISu je procesní workflow komponenta.
-   Procesy realizované AISem modeluji a rozvíjím já jako správce a nikoliv, že to nechám na znalostech dodavatele.
-   Já jsem ten, kdo určuje výkon jednotlivých procesů a zejména jejich přesahy a společné kroky a schopnosti.
-   Při procesní architektuře každého systému pamatuji na společné schopnosti úřadu, jako je ekonomika, správa dokumentů, správa identit a rolí. Takové věci využívám jako společné stavební bloky a nepořizuji je v rámci každého systému znovu.


### Žádný informační systém nežije samostatně, nesmí se zapomínat na jeho souvislosti s dalšími systémy, včetně systémů jiných správců


Zejména u informačních systémů, které slouží pro podporu výkonu agendy veřejné správy platí, že se nejedná o samostatně fungující a samostatně žijící informační systémy. Při každém výkonu činnosti v rámci agendy veřejné správy musí příslušný orgán veřejné moci naplňovat některé základní principy a povinnosti, jako je kupříkladu využívání referenčních údajů, výkon spisové služby, vazba svých činností na ekonomické činnosti úřadu, elektronická komunikace s klienty a poskytování elektronických klientských služeb, dodržování práva subjektu údajů apod. To znamená, že prakticky žádný agendový informační systém (zejména pokud se jedná o centralizovaný agendový informační systém pro výkonu agendy, v níž vykonávají působnost různé orgány veřejné moci) nelze budovat samostatně, ale je nutno již od počátku počítat s jeho silnou integrací na další informační systémy a na další komponenty eGovernmentu.


**Praktické naplnění:**


-   Připravuji architekturu řešení daného AIS tak, abych splnil veškeré povinnosti týkající se eGovernmentu a výkonu veřejné správy.
-   Vytvářím pro AIS otevřenou architekturu schopnou respektovat nové vazby a povinnosti.
-   Uskutečňuji vazby se svými dalšími informační systémy, jako je elektronický systém spisové služby, ekonomický systém apod.
-   Technicky zajišťuji příslušný AIS tak, aby mohl využívat služeb referenčního rozhraní, rozhraní na základní registry, rozhraní na další ISVS.
-   Společné schopnosti realizuji integrací AISu na další IS, které tyto schopnosti zajišťují napříč celým úřadem.


### Budovat systémy tak, aby byly nezávislé na provozní infrastruktuře, a tedy připravené na cloud


Jedním ze základních architektonických principů uvedených také v rámci informační koncepce ČR je budování a postupný rozvoj eGovernment cloudu jako sdíleného prostředí pro provozování klíčových informačních systémů ve veřejné správě. všechny informační systémy ve veřejné správě by tedy jejich správci měli primárně budovat tak, aby byl možný jejich přechod do cloudu, a to ať už se bude jednat o státní části EGC, nebo o možnost využití cloudových služeb komerčních poskytovatelů.


Informační systémy musejí být poptávány a budovány tak, aby byly nezávislé na provozní infrastruktuře a aby bylo možné je v určitém časovém okamžiku převést do cloudu. To je možné buď jako celý informační systém v rámci funkčního kontejneru na vrstvě virtualizace, nebo jako aplikační řešení informačního systému, jež je plně funkční na cloudové aplikační platformě s využitím cloudových dalších platforem, jako jsou například databázové platformy, procesní workflow či uživatelské rozhraní.


**Praktické naplnění:**


-   Architektura IS musí být vytvořena tak, aby aplikační řešení nebylo závislé na provozní infrastruktuře
-   Architektura IS musí umožňovat cloudové řešení
-   Neomezuji informační systém výhradně na svoji provozní infrastrukturu
-   Odděluji poptávání informačního systému od budování a rozvoje provozní infrastruktury
-   Řešení IS musí být připraveno na přenos do jiné provozní infrastruktury, a to zejména do cloudového prostředí EGC
-   Již od počátku při budování a rozvoji IS počítám s jeho provozem v cloudu, ať už ve státní cloudu, nebo v komerčním prostředí podle standard EGC.
-   Omezuji budování vlastních datových center a vlastní výhradní provozní infrastruktury
-   Buduji informační systém na vrstvě operačního systému, platforem a aplikační vrstvě jako kontejnerové přenositelné řešení
-   Informační systém musí být schopen pracovat s cloudovými platformami, jako je database, workflow, či UX rozhraní.
-   Buduji informační systém tak, abych byl připraven na jeho integraci s dalšími informačními systémy provozované kdekoliv, včetně cloudu.


### Budovat systémy jako platformově nezávislé, pokud to je možné


Vezmeme-li v potaz všechno výše zmíněné týkající se nezávislosti informačních systémů, pak zcela klíčová je také nezávislost na konkrétních provozních platformách. Jedná se zejména o nezávislost na platformách virtualizace operačních systémů a virtualizace prostředků, ve většině případů na samotné platformě operačního systému, ale především na takových provozních platformách, jako jsou databáze, procesní workflow, workflow uživatelského rozhraní, integrační rozhraní pro integraci s ostatními informačními systémy a podobně. Informační systémy tedy budujeme a rozvíjíme tak, aby byly co nejvíce nezávislé na těchto platformách a aby byly přenositelné. Na rozdíl od výše zmíněné nezávislosti na konkrétním dodavateli a nezávislosti na konkrétní části veřejné zakázky je toto daleko složitější a musíme si uvědomit, že úplné nezávislosti na těchto provozních platformách prakticky nelze dosáhnout. Zejména u databázových platforem a platforem na monitoring a platforem na řízení procesů a workflow v celém systému je nutno vždy systém přizpůsobit konkrétní platformě. To je samozřejmě možné, avšak je nutné při tom myslet na to, že dodavatel musí systém vybudovat tak, aby bylo možno jej později přenést na jinou provozní platformu s pokud možno co nejmenšími, a hlavně realizovatelnými, úpravami.


**Praktické naplnění:**


-   Architektonicky konstruuji informační systémy co možná nejvíce nezávislé.
-   Tam, kde se nevyhnu závislosti programu na platformě, si tuto závislost jsem schopen řádně odůvodnit a mám ji zdokumentovanou.
-   Mám k dispozici dostatečnou dokumentaci a práva, abych v případě potřeby byl schopen zadat úpravy systému pro přenos na jinou platformu či pro spolupráci s jinou platformou.
-   Tam, kde je to možné, buduji zejména integrační komponenty systému podle mezinárodních otevřených standardů.


### Poptávat samostatně dodávky na systémy a samostatně jejich implementaci a provoz


Do oblasti závislosti na konkrétních dodavatelích patří i správné rozdělení projektu pořízení a rozvoje informačního systému na vhodně členěné veřejné zakázky. Neznamená to, že bychom měli jednu veřejnou zakázku na systém účelově dělit tak, aby byla rozdrobená do více menších veřejných zakázek, ale měli bychom být schopni rozdělit veřejné zakázky podle určitých projektových celků, kterých chceme dosáhnout. To kupříkladu znamená zavedení principu, že samostatně poptáváme pořízení informačního systému, samostatně jeho provoz, samostatně jeho podporu, a samostatně integraci více informačních systémů v rámci úřadu. Tam, kde je to vhodné a účelné (třeba u provozu), můžeme poptávat pro více informačních systémů.


**Praktické naplnění:**


-   Rozdělujeme projekt IS tak, abychom samostatně poptávali pořízení/dodávku IS, samostatně jeho podporu, provoz atd.
-   Tam, kde je to účelné (třeba u provozu či integrační platformy), poptáváme nezávisle na zakázkách na systémy pro více IS.


### Poptávat systémy tak, aby byl jejich provoz a rozvoj nezávislý na primárním dodavateli


Vendor lock-in je stále velkou hrozbou pro efektivní správu informačních systémů a zejména pro jejich ekonomickou efektivitu. Při budování nových řešení IS je nutno se samozřejmě závislosti na jediném dodavateli vyvarovat, je ale nutno to řešit i v případě rozvoje stávajících řešení. K řešení tohoto problému přispívá také naplňování zde uvedených principů, jako jsou procesně orientované IS, rozdělení po modulech a komponentách apod.


**Praktické naplnění:**


-   Postupuji tak, abych u nových řešení zcela odboural závislost na jediném dodavateli.
-   Postupuji tak, že využiji rozvoj stávajících IS k jejich modularizaci a rozdělení do více zakázek s omezením závislosti na jediném stávajícím dodavateli.


### Při budování systémů využívat spíše síť služeb než proprietárních dodávek po zakázkách


**Praktické naplnění:**


### Před budováním informačních systémů musí být vyřešeny i souvislosti, včetně dlouhodobého financování provozu a rozvoje


Při budování informačních systémů veřejné správy se často zapomíná na to, že náklady určené pro budování jsou jenom jedním z druhů nákladů souvisejících s daným informačním systémem. obecně se na architektonické, projektové, ale zejména ekonomické, stránce zapomíná na to, že jednou vybudovaný informační systém bude nutno také prakticky nepřetržitě provozovat. To pochopitelně zahrnuje i přemýšlení o nákladech souvisejících s provozem a podporou daného technického řešení informačního systému, s rozvojem infrastruktury, respektive s postupným přechodem do cloudové infrastruktury pro zefektivnění nákladů na provoz, s rozvojem a úpravou komponent informačního systému, a s dalšími záležitostmi jako je vyhodnocování efektivity informačního systému, monitoring, školení, a podobně. Tyto věci nejsou často systémově řešeny a při výpočtu TCO se většinou podceňují, výsledkem čehož je pak nedostatek finančních prostředků na zajištění kontinuálního provozu a rozvoje celého informačního systému a jeho nutných integrací.




**Praktické naplnění:**


- Od počátku si uvědomuji potřeby související s kontinuálním provozem IS a jeho zajištěním 
- Od počátku si uvědomuji i nutnost kontinuální potřeby reakce na změny, díky nimž bude nutno rozvíjet a měnit informační systém
- Při výpočtu TCO (což dělám pro každé řešení IS) nezapomínám ani na výpočet a zahrnutí souvisejících nákladů, jako je rozvoj, údržba, změnové požadavky, projektové řízení apod.
- Mám nastaven mechanismus, že po skončení projektu pořízení IS navazuje kontinuální projekt jeho provozu a vyhodnocování a přípravy jeho rozvoje změn
- Po spuštění systému do provozu efektivně řídím jeho rozvoj změnovými požadavky


### Při přípravě a budování informačního systému se nesmí zapomínat na související činnosti, jako je školení, správa rolí a podpora uživatelů


Příprava informačního systému nespočívá pouze ve vybudování technického řešení informačního systému a jeho spuštění do provozu. Nutností jsou také souvislosti s přípravou, integrací na další systémy, testovacím provozem, ověřením úplné funkčnosti. Ale také věci kolem školení budoucích uživatelů, tvorby a aktualizace provozní dokumentace a podobně. Na tyto věci se při vypočítávání TCO často zapomíná a jsou ekonomicky i projektově podceněny.


**Praktické naplnění:**


- Projekt zahrnuje i činnosti netechnického charakteru, jako je tvorba dokumentace, školení a podpora uživatelů apod.


### Budování a rozvoj informačních systémů je zdrojem pro optimalizaci procesů a standardizaci výkonu činností


Při zachování principu, že budujeme procesně a transakčně orientované informační systémy namísto evidencí, je nutno vzít v potaz i možnosti zlepšování a optimalizace procesů vykonávaných prostřednictvím těchto informačních systému. Zejména při rozvoji stávajících IS, ale i při budování informačních systémů, které nahrazují stávající řešení, je vhodné se zamyslet nad využitím tohoto informačního systému pro automatizaci maximálního množství činností v rámci procesu, a tím i pro omezení administrativní a procesní činnosti jednotlivých úředníků.


To se pochopitelně netýká pouze automatizovaných činností v rámci procesu, ale především automatizovaného získávání údajů z propojeného datového fondu, a to ať už se jedná o údaje vedené v jiných informačních systémech stejného správce, či o údaje poskytované informačním systémem jiného správce. Procesně orientované informační systémy by měly sloužit jako průvodce procesem pro úředníka a to tak, aby systém byl schopen automatizovaně co největší okruh údajů sám dohledat a v případě možností také posoudit vstupy pro jednotlivé kroky procesu, a tím co nejvíce usnadnil práci jeho uživateli.


**Praktické naplnění:**


-   Znám procesy, které se budou příslušným informačním systémem realizovat a mám procesy zmapované
-   Vím, kdo a jak vykonává procesy a jak lze informačním systémem nahradit či optimalizovat
-   Vím, jak dojde rozvojem IS k optimalizaci procesů a jaké dosavadní ruční kroky svým řešením IS eliminuji
-   Mám jistotu, že pokrývám svým IS všechny procesní úřední kroky a že maximálně dodržuji principy pro DPL a pro nezatěžování klientů
-   Při rozvoji IS z jiných důvodů to využiji i k optimalizaci procesů


### Informační systémy se budují a rozvíjejí v souladu s Informační koncepcí ČR a s informační koncepcí úřadu


Základním dokumentem určujícím pravidla a zásady pro pořizování a rozvoj informačních systémů je "informační koncepce". Každý úřad musí mít informační koncepci a naplní se tím povinnost stanovenou v zákoně o ISVS. Informační koncepce obsahuje mimo jiné jednotlivé zásady pro pořízení a rozvoj ISVS. Každou záležitost s rozvojem a budováním informačních systémů pak musí mít v souladu s těmito zásadami. To se do značné míry týká i jiných informačních systémů, než jsou informační systémy veřejné správy, a to zejména těch, na které jako na specifické hledí zákon o ISVS.


IK úřadu pak musí být v souladu s Informační koncepcí ČR a souvisejícími dokumenty, jako je Národní architektonický plán, Metody řízení pro ICT.


**Praktické naplnění:**


-   Mám svoji informační koncepci, u které vím, že je v souladu s IKČR a obsahuje vše, co obsahovat má.
-   Ve své IK mám dobře nadefinované zásady pro pořizování a rozvoj informačních systémů. Jakékoliv pořízení a rozvoj IS realizuji v souladu se svojí IK, včetně zpracování sedmibodového plánu změny.


## Kdy a jak k naplnění principů přistoupit


