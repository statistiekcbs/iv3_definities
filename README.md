# iv3_modellen
sjablonen, controlebestanden en hulp-info betreffende iv3 leveringen via json

De naamgeving is als volgt: "iv3_definities_[overheidslaag]_[boekjaar].json".

In elk sjabloon bevinden zich de verplichte codes voor levering van iv3 data van overheidsinstanties aan derden zoals het CBS.
Elk sjabloon heeft in de naam de overheidslaag (Gemeente, Provincie, GR, Waterschap) 
en het boekjaar waarop het sjabloon betrekking heeft.

In eerste instantie leek een indeling conform de vertrouwde iv3-excel-indeling in 3 tabbladen (lasten, baten en balans) 
van de afgelopen jaren een ideale. Bij nader inzien echter lijkt een indeling in 5 afdelingen (lasten, baten, BalansLasten, 
BalansBaten en BalansStanden) logischer en overzichtelijker. 

In januari 2019 zijn 2 wijzigingen in de vormgeving van een sjabloon doorgevoerd (die van Gemeente_2017) Hierin is de 
splitsing in 5 afdelingen gerealiseerd en is binnen het sjabloon een opsomming van Grijze Cellen opgenomen.

Inmiddels is ook de eerste controle binnen de sjablonen opgenomen, zodat elk sjabloon uiteindelijk het totaal aan informatie bevat die nu is terug te vinden in de Excel-sjablonen.
Voorlopig zullen niet alle controles in de bestanden worden opgenomen, vanwege de arbeidsintensiteit hiervan.

inmiddels is ook een JSON-Schema toegevoegd: de controles zijn gesplitst in 2 bestanden een schema, voor de 'grammatica' van alle leveringen en een definitie bestand voor de jaarlijks in te stellen controles en codelijsten.

Voor meer informatie over iv3 leveringen via json, zie:
https://www.cbs.nl/kredo
en klik vervolgens op de tegel "Inzendinstructie"
