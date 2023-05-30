# Vragen aan het TO na bijeenkomst 23  mei 2023

DMKS standaard is uitontwikkeld. Er is behoefte aan eenvoudiger standaard. Vragen voor het TO:
- Wat zijn de overeenkomsten en verschillen tussen de standaarden die gebruikt worden in de verschillende terugmeld-toepassingen en zouden de voordelen efficiënter/effectiever in 1 standaard opgenomen kunnen worden?
- Bieden APIs de gewenste vereenvoudiging? Ook bij toepassing van API koppelvlakken is authenticatie en authorisatie nodig. Zijn de use cases in de pilots niet simpeler gemaakt dan de praktijk kan worden?

Berichtenverkeer en inhoud
- Digikoppeling definieert berichtenverkeer (en niet de inhoud). Is Digikoppeling REST API standaard voldoende voor de (niet-inhoudelijke) terugmelding?
- Terugmelden heeft inhoudelijk aspect (code, annotatie etc.). Welke inhoudelijke informatie moet gedeeld worden?
- Inhoud van een melding is afhankelijk van de betreffende basisregistratie. Welke basisregistratie heeft informatie 
nodig die specifiek is voor die basisregistratie?
- Wat is het gewenste beveiligingsniveau voor de verschillende basisregistraties?
- Kan het inhoudelijke deel in een XML structuur gedeeld worden? (die overeenkomt met de huidige structuur in DMKS?) Moeten we de inhoud zoveel mogelijk gelijk houden of is dit een gelegenheid om ook de codering van de inhoud te moderniseren?

Semantische aspecten
- Wat is de rol van semantische (linked) data voor inhoud? De basisregistraties die Kadaster beheert zijn beschikbaar als [_knowledge graph_](https://labs.kadaster.nl/thema/Knowledge_graph). Is het zinvol om vooruit te kijken naar terugmelden op alle basisregistraties als _knowledge graph_?
- Welke standaarden worden toegepast voor terugmeldingen op linked data/knowledge graphs?
