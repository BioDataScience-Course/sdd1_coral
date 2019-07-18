# Science des données I : Visualisation et inférence
## Examen pratique : croissance des coraux en mésocosme
## Engels Guyliann & Philippe Grosjean

## Situation

Le Service d'écologie numérique des milieux aquatiques de l'Université de Mons a une thématique de recherche qui porte sur la capacité d'adaptation au changement du mileu des coraux hermatypiques. 

Ils ont mis en place 2 mésocosmes artificiels identiques d'une capacité de 1500 L pour étudier ces cnidaires. On retrouve par unité un aquarium principal de 500 L, avec deux cuves expérimentales de 300 L pouvant être isolées de l'aquarium principale. L'unité est pour finir complétée par plusieurs autres cuves afin de filtrer l'eau principalement. 

Les mésocosmes sont composés d'un ensemble d'organismes que l'on retrouve dans les milieux coralliens afin de représenter au mieux le milieu naturel. Il y a tout d'abord plusieurs espèces de coraux ainsi que des poissons, des mollusques ou encore des crustacés. La diversité de la faune et de la flore y est donc volontairement importante afin d'obtenir un système en équilibre dans chaque unité. 

Les mésocosmes sont lancés 2005 et acueillent les premiers organismes en 2006. Douze ans plus tard, les chercheurs s'intéressent tout particulièrement à la croissance de trois espèces de coraux que sont *Acropora millepora* Ehrenberg (1834), *Seriatopora hystrix* Dana (1846) et *Stylophora pistillata* Esper (1797). L'expérience débubte le 28 janvier 2018. Au bout de 7 jours les organismes sont pesés à nouveau. 


# Question

Les chercheurs font appel à vous afin de fournir un rapport comparant le taux de croissance de ces trois espèces.

# Matériels

Vous avez à votre disposition le jeu de données `growth_monitoring.csv` qui porte sur la croissance de ces espèces de coraux ainsi que toutes les ressources externes que vous souhaités (vos anciens projets, recherche sur internet,...)

Le jeu de données growth_monitoring comprend les variables suivantes :

- localisation

Cette variable recense la position de la bouture dans les mésocosmes. Cette variable comprend 2 niveaux A0 et B0 qui sont les cuves principales de chaque mésocosme.

- species

Cette variable recense le nom de l'espèce étudiée. 

- id

Cette variable recense le numéro attribué à chaque bouture lors de l'expérimentation.

- number_day

Cette variable recense le nombre de jours éccoulés depuis le début de l'expérience. L'unité est le jour

- growth 

cette variable est obtenue avec la formule suivante : 

$$growth = \frac{weight - weight[initial]}{weight[initial]}$$

Elle représente la croissance des organismes sur la période de temps étudiée.

- weight_gain

Cette variable représente le gain de masse entre la mesure initiale et la mesure finale. L'unité est le gramme.

$$weight_{gain} = weight - weight[initial]$$

- growth_day

Cette variable représente la croissance par jour exprimée en pourcent. 

$$ growth_{day} = \frac{growth}{number \ day} \times 100$$

# Attendu 

Vous devez fournir : 

- un projet respectant les conventions vues au cours, organisé en un ensemble de sous-dossiers et dont le contenu est entièrement **transportable** (chemin relatif).

- le rapport au sein de ce projet doit également avoir un nom évocateur qui respecte les conventions vues au cours. Il doit être organisé en sections cohérentes propres au rapport scientifique (introduction, but, ...). Il doit également contenir une description numérique et graphique des données ainsi que d'analyses statistiques.

