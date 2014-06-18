Affiche l'horaire des prochains bus qui passent à un arrêt de la CTS, dans la
CUS (Communauté Urbaine de Strasbourg).

Utilisation:

$prochainbus 342
14h30: 71 Eckwersheim Hippodrome via Mund./Lamp./Vend.
15h00: 71 Eckwersheim Hippodrome via Mund./Lamp./Vend.
16h15: 71 Eckwersheim Hippodrome via Vendenheim
16h15: 71A Lampertheim Lorraine via Mundolsheim

$prochainbus 'Rue de mundo'
17h10: 71 Les Halles Sébastopol
17h25: 71 Les Halles Sébastopol
17h05: 71A Lampertheim Lorraine via Mundolsheim
17h21: 71A Lampertheim Lorraine via Mundolsheim

$prochainbus --list
Affiche tous les arrêts

$prochainbus --refresh
Réactualise la liste d'arrêts

Le code de votre arrêt habituel peut être stocké dans ~/.prochainbus/default, 
ce qui permet de lancer ce script sans arguments.

Ce script est en Perl, et a été conçu pour être utilisé sous Linux. Il
nécéssite l'installation des modules CPAN suivants:
    - JSON::PP
    - LWP::Simple
    - Getopt::Long
    - String::Approx
    - File::Slurp
    - Unicode::Normalize
    - HTML::TreeBuilder::XPath
    - I18N::Langinfo
    - Encode

copyright 2014 - Martijn van der Kwast <martijn@vdkwast.com> 

Utilisation à vos risques, l'auteur ne saura être tenu responsable
d'éventuelles informations erronées et des retards qui en suivraient.
Distribution libre à condition de laisser ce paragraphe. 
