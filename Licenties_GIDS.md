# Voorstel Licenties GIDS
(c) 2019 Winfried Tilanus - This is written as part of GIDS open standards. CC-SA-BY 4.0

**Voorstel:**

Code & protocol: MPL

Tekst & artwork: CC-SA-BY

Uitgangspunten van GIDS:

-   Protocol en libraries moeten door elke organisatie, onafhankelijk
    van met welke andere licentie ze werken, bruikbaar zijn voor hun
    producten.
-   Samenwerking en wederkerigheid zijn centrale waarden van het
    project, daarom moet de licentie dat ondersteunen.
-   Juridisch zaken zo eenvoudige mogelijk regelen.
-   Bescherming van de organisaties die het implementeren tegen
    patentclaimen en andere IP-claimen.
-   Erkenning van de individuen die hebben bijgedragen.
-   Erkenning van de opdrachtgever.

**Afweging licentie:**

Er zal altijd een balans gevonden moeten worden tussen de eis van
implementeerbaar door elke organisatie en de eis van wederkerigheid.
Voor GIDS geldt dat de licentie de toepassing in closed source
applicaties zeker niet in de weg mag staan. De wederkerigheid is een
onderdeel van het opbouwen van de community, maar geen doel zich. De
wederkerigheid kan gelden voor de complete toepassing van het product
(AGPL), voor het gehele product waarin het protocol of de library in
verwerkt is (GPL), voor het protocol of de library los van het product
waar het in verwerkt wordt (LGPL) of voor individuele bestanden in de
library (MPL). Die laatste variant heeft het minste kans om te
conflicteren met de policies van bedrijven die hun product closed source
aanbieden. Daarom is de MPL te prefereren. MPL-gelicenseerde code is ook
op te menen in software die GPL gelicenseerd is. Alleen de route terug
(code die is problematisch. Dat is op te lossen door

Voor documentatie en artwork geldt iets vergelijkbaars: het moet
bruikbaar zijn in elke omgeving en de wederkerigheid en de attributie
moeten zichtbaar blijven. Daarom is voor zaken die geen code zijn een
CC-SA-BY licentie het beste.

Voor beiden geldt: mocht er een organisatie zijn die problemen heeft met
de licentie, kunnen er op individuele basis afwijkende spraken gemaakt
worden. In die afspraken kunnen dan de uitgangspunten alsnog gewaarborgd
worden.

**Afweging tenaamstelling copyright en attributie:**

De copyright op de naam van de contributors te zetten, is een mooi
signaal van waardering en vergroot het gemeenschappelijke gevoel. De
administratie daarvan is echter lastig. Dat kan opgelost worden door de
auteur van het eerste deel te vermelden in de copyrights met een
verwijzing naar 'and contributors' en de dan git te gebruiken om de
commits te volgen. Of contributors in dienst van een bedrijf bijdragen
op naam van het bedrijf of op persoonlijke titel kunnen ze met het
bedrijf afspreken. Een ander punt is dat de copyright houder bij
schending van de licentie in principe verantwoordelijk is voor het
aanspreken van de schenders of het starten van procedures. Dat kan
opgevangen worden als GIDS namens de contributors daar zorg voor draagt.

Verder is het goed om te vermelden dat het werk onderdeel is van GIDS
open staandaarden.

De copyright notice zou er dan als volgt uit kunnen zien:

© Copyright \[oorspronkelijke auteur\] and contributors \[first
published year\] -- \[current year\]. This is written as part of GIDS
open standards.

MPL regelt intellectueel eigendom zaken uitgebreid, maar bij bijdragen
door derden aan een project met een MPL licentie, zijn er alsnog een
paar voetangels mogelijk:

-   de derde draagt code bij van een derde en heeft niet het recht
    daartoe
-   de derde voegt een nieuw bestand toe onder een andere licentie

Door te checken dat elke nieuw bestand een MPL licentie heeft, zijn de
meeste van deze problemen op te lossen. Een extra overeenkomst voor
mensen die bijdragen is dan niet nodig.

Offerte checklist:

-   De copyrights van de bijdragen blijven bij de auteur of medewerker
    van de auteur persoonlijk
-   Alle code en protocol definities worden ter beschikking gesteld
    onder de 'Mozilla Public License'
-   Alle tekst en artwork wordt ter beschikking gesteld onder de
    CC-SA-BY (3.0) licentie.

**Achtergrondinformatie over licenties en mogelijkheden bij GIDS:**

|-------------|-------------|-------------|-------------|-------------|
| Onderdeel   | Doelen      | Karakterist | Voorgesteld | Opmerkingen |
|             |             | ieken       | e           |             |
|             |             | licentie    | licentie    |             |
|-------------|-------------|-------------|-------------|-------------|
| Protocol    | De licentie |             |             | Argumenten  |
| definities  | of de       |             |             | voor        |
|             | IP-rechten  |             |             | mozilla     |
|             | mogen geen  |             |             | licentie:   |
|             | belemmering |             |             |             |
|             | zijn voor   |             |             |             |
|             | het         |             |             |             |
|             | toepassen   |             |             |             |
|             | van het     |             |             |             |
|             | protocol,   |             |             |             |
|             | ook niet    |             |             |             |
|             | als het     |             |             |             |
|             | protocol in |             |             |             |
|             | closed      |             |             |             |
|             | source      |             |             |             |
|             | producten   |             |             |             |
|             | wordt       |             |             |             |
|             | toegepast.  |             |             |             |
|             |             |             |             |             |
|             | De          |             |             |             |
|             | organisatie |             |             |             |
|             | s           |             |             |             |
|             | die         |             |             |             |
|             | bijdragen   |             |             |             |
|             | aan het     |             |             |             |
|             | protocol    |             |             |             |
|             | moeten      |             |             |             |
|             | gedeeld     |             |             |             |
|             | eigenaarsch |             |             |             |
|             | ap          |             |             |             |
|             | voelen, ze  |             |             |             |
|             | moeten zich |             |             |             |
|             | aangemoedig |             |             |             |
|             | d           |             |             |             |
|             | voelen om   |             |             |             |
|             | wijzigingen |             |             |             |
|             | voor te     |             |             |             |
|             | stellen en  |             |             |             |
|             | om bij te   |             |             |             |
|             | dragen aan  |             |             |             |
|             | nieuwe      |             |             |             |
|             | versies.    |             |             |             |
|             |             |             |             |             |
|             | Private     |             |             |             |
|             | wijzigingen |             |             |             |
|             | aan de      |             |             |             |
|             | protocol    |             |             |             |
|             | definities  |             |             |             |
|             | of het      |             |             |             |
|             | forken van  |             |             |             |
|             | de protocol |             |             |             |
|             | definities  |             |             |             |
|             | moeten      |             |             |             |
|             | ontmoedigd  |             |             |             |
|             | worden: een |             |             |             |
|             | geforkte    |             |             |             |
|             | standaard   |             |             |             |
|             | is geen     |             |             |             |
|             | standaard   |             |             |             |
|             | meer.       |             |             |             |
|-------------|-------------|-------------|-------------|-------------|
| Libraries   | De          |             |             | Argumenten  |
|             | libraries   |             |             | voor LGPL:  |
|             | moeten      |             |             |             |
|             | toegepast   |             |             | NB: voor de |
|             | kunnen      |             |             | overzichtel |
|             | worden in   |             |             | ijkheid     |
|             | producten,  |             |             | zouden we   |
|             | zonder dat  |             |             | hier ook de |
|             | het de      |             |             | Mozilla     |
|             | juridische  |             |             | license     |
|             | status van  |             |             | kunnen      |
|             | het prodoct |             |             | gebruiken,  |
|             | (zelfs      |             |             | maar die    |
|             | closed      |             |             | laat iets   |
|             | source)     |             |             | meer ruimte |
|             | beïnvloed.  |             |             | om          |
|             |             |             |             | wijzigingen |
|             | De library  |             |             | aan de      |
|             | is          |             |             | library     |
|             | onderdeel   |             |             | niet te     |
|             | van een     |             |             | delen. Ook  |
|             | community-e |             |             | maakt die   |
|             | ffort       |             |             | het         |
|             | en het      |             |             | moeilijker  |
|             | gebruik van |             |             | om de       |
|             | de library  |             |             | libraries   |
|             | gaat        |             |             | op te nemen |
|             | gepaard met |             |             | in GPL      |
|             | de          |             |             | gelicenceee |
|             | verwachting |             |             | rde         |
|             | ook bij te  |             |             | software,   |
|             | dragen aan  |             |             | in dat      |
|             | de          |             |             | geval zou   |
|             | community.  |             |             | er een      |
|             |             |             |             | dubbele     |
|             |             |             |             | licentie    |
|             |             |             |             | afgegeven   |
|             |             |             |             | moeten      |
|             |             |             |             | worden.     |
|-------------|-------------|-------------|-------------|-------------|
| Documentati | De          |             |             |             |
| e           | documentati |             |             |             |
| bij         | e           |             |             |             |
| protocollen | moet intern |             |             |             |
| en          | vrijelijk   |             |             |             |
| libraries   | verder      |             |             |             |
|             | verspreid   |             |             |             |
|             | kunnen      |             |             |             |
|             | worden, al  |             |             |             |
|             | dan niet    |             |             |             |
|             | met         |             |             |             |
|             | aanwijzinge |             |             |             |
|             | n,          |             |             |             |
|             | aanpassinge |             |             |             |
|             | n           |             |             |             |
|             | of          |             |             |             |
|             | toevoeginge |             |             |             |
|             | n           |             |             |             |
|             | die         |             |             |             |
|             | specifiek   |             |             |             |
|             | zijn voor   |             |             |             |
|             | de          |             |             |             |
|             | situatie.   |             |             |             |
|             |             |             |             |             |
|             | Feedback/bu |             |             |             |
|             | gfixes      |             |             |             |
|             | worden      |             |             |             |
|             | gewaardeerd |             |             |             |
|             | .           |             |             |             |
|             |             |             |             |             |
|             | Attributie  |             |             |             |
|             | is niet     |             |             |             |
|             | noodzakelij |             |             |             |
|             | k           |             |             |             |
|             | omdat de    |             |             |             |
|             | documentati |             |             |             |
|             | e           |             |             |             |
|             | al verwijst |             |             |             |
|             | naar het    |             |             |             |
|             | GIDS        |             |             |             |
|             | protocol.   |             |             |             |
|-------------|-------------|-------------|-------------|-------------|
| Overige     | De          |             |             |             |
| documenten  | documenten  |             |             |             |
|             | rond GIDS   |             |             |             |
|             | moeten      |             |             |             |
|             | vrijelijk   |             |             |             |
|             | gebruikt en |             |             |             |
|             | verspreid   |             |             |             |
|             | kunnen      |             |             |             |
|             | worden. Ze  |             |             |             |
|             | zijn echter |             |             |             |
|             | onderdeel   |             |             |             |
|             | van         |             |             |             |
|             | collectief  |             |             |             |
|             | leer- en    |             |             |             |
|             | ontwikkelpr |             |             |             |
|             | oces        |             |             |             |
|             | en ze zijn  |             |             |             |
|             | ook deels   |             |             |             |
|             | uithangbord |             |             |             |
|             | voor GIDS.  |             |             |             |
|-------------|-------------|-------------|-------------|-------------|

Algemene noot:

SamenBeter wil zelf zo min mogelijk copyrights hebben om problemen met
valuatie en procedures te voorkomen. Juridisch gezien is het echter veel
makkelijker om alles op naam van SamenBeter te zetten.

**Notities bij licenties (shortlist):**

Apache license:

-   Zeer permissive en daardoor geschikt voor software *en protocollen*
    die breed geïmplementeerd moeten worden, zoals bijvoorbeeld de KAME
    IPv6 stack (die nu bijna overal gebruikt wordt)
-   Geen wederkerigheid

Mozilla license (MPL):

-   Juridisch sterk opgezette licentie die het gebruik van open source
    in corporate omgevingen goed faciliteert.
-   Vraagt wederkerigheid op bestandsniveau, niet op project niveau.
    Daardoor kan je een closed source project mengen open source werk
    onder de Mozilla licentie -- zolang je de bestanden maar gescheiden
    houdt.
-   Zeer geavanceerde patentclausules die het mogelijk maken om, zonder
    de rest van je uitgegeven licenties op de patenten teniet te doen
    wel gebruik ervan in de open software te licenceren. Bevat ook een
    patent gifpil: als je een patentschendingsprocedure begint tegen
    Mozilla gelicenceeerde software begint vervallen *alle* via de
    Mozilla licentie aan jou gegeven rechten om patenten in *alle
    *Mozilla gelicenceerde software te gebruiken. Met andere woorden: je
    mag dan waarschijnlijk niets een meer de computer en de telefoon die
    gebruikt voor de procedure gebruiken\.... :-D
-   Niet compatibel met GPL, deze code mag niet opgenomen worden in een
    GPL-gelicenseerd project, dual-licencering wel mogelijk.

LGPL:

-   Heel vergelijkbaar (en vaak inwisselbaar) met de MPL, maar richt
    zich op hele library/software. Een aanpassing aan de library als
    geheel moet gepubliceerd worden.
-   Wel GPL compatibel
-   Hoort bij een groot deel van de open source community

**Overzicht open licentietypen:**

|-------------|-------------|-------------|-------------|-------------|
| Licentie    | Academic    | Permissive  | Closable    | Reciprocal  |
| typen       |             |             |             |             |
|-------------|-------------|-------------|-------------|-------------|
| Voorbeelden | BSD, MIT    | Apache      | LGPL,       | GPL, Open   |
|             |             |             | Mozilla     | Software    |
|             |             |             |             | License     |
|-------------|-------------|-------------|-------------|-------------|
| Wederkerig? | Nee         | Nee         | Alleen over | Over alle   |
|             |             |             | bestand of  | producten   |
|             |             |             | library     | waarin het  |
|             |             |             |             | verwerkt is |
|-------------|-------------|-------------|-------------|-------------|
| Bescherming | Geen        | Ja          | Ja          | Ja          |
| tegen       |             |             |             |             |
| patentclaim |             |             |             |             |
| s           |             |             |             |             |
| en          |             |             |             |             |
| trademark   |             |             |             |             |
| issues?     |             |             |             |             |
|-------------|-------------|-------------|-------------|-------------|
| Compatibel  | Ja          | Ja          | Ja, maar    | Nee         |
| met closed  |             |             | bestand/lib |             |
| source      |             |             | rary        |             |
| licenties?  |             |             | zelf mag    |             |
|             |             |             | niet        |             |
|             |             |             | gesloten    |             |
|             |             |             | worden      |             |
|-------------|-------------|-------------|-------------|-------------|
| Compatibel  | Alleen naar | Alleen naar | Ja          | n.v.t.      |
| met         | GPL/OSL,    | GPL/OSL,    |             |             |
| Reciprocal  | niet terug  | niet terug  |             |             |
| licenties   |             |             |             |             |
|-------------|-------------|-------------|-------------|-------------|
| Analyse     | Door het    | Door het    | Deze        | Dit zijn de |
| voor        | ontbreken   | ontbreken   | licenties   | licenties   |
| SB/GIDS     | van         | van         | voorzien in | waar Steve  |
|             | wederkerigh | wederkerigh | wederkerigh | Balmer op   |
|             | eid         | eid         | eid         | doelde toen |
|             | kunnen      | kunnen      | zonder dat  | hij zei:    |
|             | leverancier | leverancier | alle        | \"Linux is  |
|             | s           | s           | producten   | a cancer    |
|             | meeliften   | meeliften   | waarin het  | that        |
|             | zonder deel | zonder deel | gebruikt    | attaches    |
|             | te nemen    | te nemen    | wordt ermee | itself in   |
|             | aan de      | aan de      | besmet      | an          |
|             | community.  | community.  | worden.     | intellectua |
|             | Het is de   | Het is de   | Daardoor    | l           |
|             | vraag of we | vraag of we | zijn deze   | property    |
|             | dat willen. | dat willen. | licenties   | sense to    |
|             |             |             | zowel       | everything  |
|             | De          | De          | compatibel  | it          |
|             | bescherming | bescherming | met closed  | touches,\"  |
|             | tegen       | tegen       | source als  | Je kan van  |
|             | IP-claims   | IP-claims   | met GPL.    | Steve       |
|             | is erg      | is wel      |             | Balmer      |
|             | minimaal.   | voldoende   | Implementat | vinden wat  |
|             | Deze        | om          | ie          | je vindt,   |
|             | licenties   | bijdragen   | in closed   | maar op dit |
|             | maken het   | van andere  | source      | punt had    |
|             | bijvoorbeel | te          | vraagt wel  | hij gelijk. |
|             | d           | accepteren. | dat library | GPL en OSL  |
|             | mogelijk    |             | en het het  | mengen niet |
|             | dat een     | Daarmee zou | product     | met closed  |
|             | leverancier | deze        | waarin het  | source en   |
|             | een         | licentie    | gebruikt    | is daarom   |
|             | bijdrage    | een optie   | wordt goed  | geen optie  |
|             | levert      | zijn voor   | gescheiden  | voor        |
|             | waarover ze | SB/GIDS     | worden.     | SB/GIDS.    |
|             | later       |             |             |             |
|             | onthullen   |             | Deze        |             |
|             | dat ze een  |             | licentie is |             |
|             | patent      |             | dus een     |             |
|             | geclaimd    |             | optie voor  |             |
|             | hebben en   |             | SB/GIDS en  |             |
|             | vervolgens  |             | het         |             |
|             | eisen dat   |             | versterkt   |             |
|             | er          |             | de          |             |
|             | licentiekos |             | community   |             |
|             | ten         |             | gedachte en |             |
|             | betaald     |             | de          |             |
|             | worden over |             | wederkerigh |             |
|             | het         |             | eid         |             |
|             | implementer |             | die achter  |             |
|             | en          |             | SB/GIDS     |             |
|             | van het     |             | zit.        |             |
|             | protocol.   |             |             |             |
|             |             |             |             |             |
|             | Daardoor is |             |             |             |
|             | deze        |             |             |             |
|             | licentie    |             |             |             |
|             | alleen      |             |             |             |
|             | geschikt    |             |             |             |
|             | voor        |             |             |             |
|             | organisatie |             |             |             |
|             | s           |             |             |             |
|             | die zelf    |             |             |             |
|             | software    |             |             |             |
|             | schrijven   |             |             |             |
|             | en          |             |             |             |
|             | vervolgens  |             |             |             |
|             | publiek     |             |             |             |
|             | 'over de    |             |             |             |
|             | heg'        |             |             |             |
|             | gooien,     |             |             |             |
|             | zoals       |             |             |             |
|             | universitei |             |             |             |
|             | ten.        |             |             |             |
|             | Als er      |             |             |             |
|             | bijdragen   |             |             |             |
|             | van andere  |             |             |             |
|             | geaccepteer |             |             |             |
|             | d           |             |             |             |
|             | worden, is  |             |             |             |
|             | deze        |             |             |             |
|             | licentie    |             |             |             |
|             | minder      |             |             |             |
|             | geschikt.   |             |             |             |
|-------------|-------------|-------------|-------------|-------------|

**Conclusie:**
met academic style licenties lopen we te veel risico, met
reciprocal licenties sluiten we closed source buiten. Die twee vallen
dus sowieso af De keuze tussen een permissive licentie en een closable
licentie voor GIDS is vooral een vraag van hoeveel wederkerigheid we
willen afdwingen.
