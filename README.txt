Affiche l'horaire des prochains bus qui passent à un arrêt de la CTS, dans la
CUS (Communauté Urbaine de Strasbourg).

Utilisation:

$prochainbus 342
14h30: 71 Eckwersheim Hippodrome via Mund./Lamp./Vend.
15h00: 71 Eckwersheim Hippodrome via Mund./Lamp./Vend.
16h15: 71 Eckwersheim Hippodrome via Vendenheim
16h15: 71A Lampertheim Lorraine via Mundolsheim


Le code de votre arrêt habituel peut être stocké dans ~/.prochainbus, ce qui
permet de lancer ce script sans arguments.

Ce script est en Perl, et a été conçu pour être utilisé sous Linux. Il
nécéssite l'installation des modules CPAN suivants:
    - LWP::Simple;
    - HTML::TreeBuilder::XPath;
    - Getopt::Long

copyright 2011 - Martijn van der Kwast <martijn@vdkwast.com> 

Utilisation à vos risques, l'auteur ne saura être tenu responsable
d'éventuelles informations erronées et des retards qui en suivraient.
Distribution libre à condition de laisser ce paragraphe. 
