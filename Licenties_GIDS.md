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

| Onderdeel   | Doelen      | Karakteristieken licentie | Voorgestelde licentie | Opmerkingen |
|-------------|-------------|-------------|-------------|-------------|
| Protocol definities | De licentie of de IP-rechten mogen geen belemmering zijn voor het toepassen van het protocol, ook niet als het protocol in closed source producten wordt toegepast. De organisaties die bijdragen aan het protocol moeten gedeeld eigenaarschap voelen, ze moeten zich aangemoedigd voelen om wijzigingen voor te stellen en om bij te dragen aan nieuwe versies. Private wijzigingen aan de protocol definities of het forken van de protocol definities moeten ontmoedigd worden: een geforkte standaard is geen standaard meer. | Toepassen is vrij, ook commerciële en closed source toepassingen. Toepassingen van de protocol definities hoeven niet gedeeld te worden.  Bescherming tegen IP-claims. Wijzigen mag. Wijzigingen altijd op zelfde voorwaarden delen. Naam & logo van GIDS registreren, bepalen dat ze alleen gevoerd mogen worden voor het protocol als het door GIDS geautoriseerd is. | Copyright op naam van natuurlijke personen die het schrijven met vermelding “voor SamenBeter” er bij. Mozilla license. Contributers  agreement (lichte versie). Trademark policy voor GIDS die voorschrijft dat alleen de door [SamenBeter of GIDS] goedgekeurde versie een ‘GIDS open standaard’ genoemd mag worden. | Argumenten voor mozilla licentie: Geen ‘besmettings effect’, alleen wijzigingen aan het bestand zelf moeten wederkerig gedeeld worden. Krachtige patent bescherming. Het ontbreken van een contributers agreement is niet fataal bij deze licentie. |
||
| Libraries | De libraries moeten toegepast kunnen worden in producten, zonder dat het de juridische status van het prodoct (zelfs closed source) beïnvloed. De library is onderdeel van een community-effort en het gebruik van de library gaat gepaard met de verwachting ook bij te dragen aan de community. | Licentie die toepassing van libraries toestaat in commerciele software. Wijzigingen altijd delen en onder dezelfde voorwarden. | Copyright op naam van natuurlijke personen die het schrijven met vermelding “voor SamenBeter” er bij. LGPL. Contributers agreement (lichte versie) | Argumenten voor LGPL: Geen ‘besmettingseffect’ buiten de library. Wijzigingen aan de library zelf moeten wel gedeeld worden. NB: voor de overzichtelijkheid zouden we hier ook de Mozilla license kunnen gebruiken, maar die laat iets meer ruimte om wijzigingen aan de library niet te delen. Ook maakt die het moeilijker om de libraries op te nemen in GPL gelicenceeerde software, in dat geval zou er een dubbele licentie afgegeven moeten worden. |
||
| Documentatie bij protocollen en libraries | De documentatie moet intern vrijelijk verder verspreid kunnen worden, al dan niet met aanwijzingen, aanpassingen of toevoegingen die specifiek zijn voor de situatie. Feedback/bugfixes worden gewaardeerd. Attributie is niet noodzakelijk omdat de documentatie al verwijst naar het GIDS protocol. | Permissive license. Geschikt voor text- en beeldmateriaal. | Copyright op naam van natuurlijke personen die het schrijven met vermelding “voor SamenBeter” er bij. CC zonder verdere beperkingen | |
||
| Overige documenten | De documenten rond GIDS moeten vrijelijk gebruikt en verspreid kunnen worden. Ze zijn echter onderdeel van collectief leer- en ontwikkelproces en ze zijn ook deels uithangbord voor GIDS. | Permissive license. Geschikt voor text- en beeldmateriaal. Afgeleide werken openlijk delen. Bron blijven vermelden. | Copyright op naam van natuurlijke personen die het schrijven met vermelding “voor SamenBeter” er bij. CC-SA-BY ||


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


|             | Academic    | Permissive  | Closable    | Reciprocal  |
|-------------|-------------|-------------|-------------|-------------|
| Voorbeelden | BSD, MIT    | Apache      | LGPL, Mozilla | GPL, Open Software License |
||
| Wederkerig? | Nee         | Nee         | Alleen over bestand of library | Over alle producten waarin het verwerkt is |
||
| Bescherming  tegen patentclaims en trademark issues? | Geen | Ja | Ja | Ja |
||
| Compatibel met closed source licenties? | Ja | Ja | Ja, maar bestand/library zelf mag niet gesloten worden | Nee |
||
| Compatibel met Reciprocal licenties | Alleen naar GPL/OSL, niet terug | Alleen naar naar GPL/OSL, niet terug | Ja          | n.v.t. |
||
| Analyse voor SB/GIDS | Door het ontbreken van wederkerigheid kunnen leveranciers meeliften zonder deel te nemen aan de community. Het is de vraag of we dat willen. De bescherming tegen IP-claims is erg minimaal. Deze licenties maken het bijvoorbeeld mogelijk dat een leverancier een bijdrage levert waarover ze later onthullen dat ze een patent geclaimd hebben en vervolgens eisen dat er licentiekosten betaald worden over het implementeren van het protocol. Daardoor is deze licentie alleen geschikt voor organisaties die zelf software schrijven en vervolgens publiek ‘over de heg’ gooien, zoals universiteiten. Als er bijdragen van andere geaccepteerd worden, is deze licentie minder geschikt. | Door het ontbreken van wederkerigheid kunnen leveranciers meeliften zonder deel te nemen aan de community. Het is de vraag of we dat willen. De bescherming tegen IP-claims is wel voldoende om bijdragen van andere te accepteren. Daarmee zou deze licentie een optie zijn voor SB/GIDS | Deze licenties voorzien in wederkerigheid zonder dat alle producten waarin het gebruikt wordt ermee besmet worden. Daardoor zijn deze licenties zowel compatibel met closed source als met GPL. Implementatie in closed source vraagt wel dat library en het het product waarin het gebruikt wordt goed gescheiden worden. Deze licentie is dus een optie voor SB/GIDS en het versterkt de community gedachte en de wederkerigheid die achter SB/GIDS zit. | Dit zijn de licenties waar Steve Balmer op doelde toen hij zei: "Linux is a cancer that attaches itself in an intellectual property sense to everything it touches," Je kan van Steve Balmer vinden wat je vindt, maar op dit punt had hij gelijk. GPL en OSL mengen niet met closed source en is daarom geen optie voor SB/GIDS. |


**Conclusie:**

met academic style licenties lopen we te veel risico, met
reciprocal licenties sluiten we closed source buiten. Die twee vallen
dus sowieso af De keuze tussen een permissive licentie en een closable
licentie voor GIDS is vooral een vraag van hoeveel wederkerigheid we
willen afdwingen.
