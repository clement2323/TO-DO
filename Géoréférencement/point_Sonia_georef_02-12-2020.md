
# Explication des variables
voir fichier envoyé sur géoref

# Timing, relancr un truc entier fictif ?
3,5 jours, mettre les parcelles les étiquettes
charger v_geoloc, 1 jours avec le cadastre

# Les codes organisation

# La documentation à fournir ?

# is null en variables caractère ?  
oui ça marche

# changement zone code ? même résultat
# exist QP, (X,Y) qui ne se retrouve pas dans la commune 

# Expertise parcelles
# draw.io

# géocodage 
- iris, QP QVA


# Les bases organisations,
- parcelles_cdtr -> contour géométrique des parcelles que les - parcelles 2019
- centroides_parcelles -> centroides_parcelles, centroide avec booleen si centroide est dans la parcelle
- etiquettes_prcl_2019 -> ok
- historique_xy_prcl -> etiquettes + centroide ! 2016 à 2019
Quand on a fini on met dans archivage : histo
- rsl2019_arbitrage -> la vraie générée par anne thérèse
sous_schema avec contours ?
- 3 schémas : historique, tables en cours et contours géographiques, archivage !

- imputation : group by + moyenne X,Y !
- Explication rapide table historique
- centroide de parcelles projeté
- ne plus parler de flux et de stock, arbitrage historique RSL lourde à mettre en place.
- Geocodage..
- temps d'execution 3,5 jours et pas besoin d'attendre v_geoloc pour charger le reste (v_geoloc une demi journée).

- question v_geoloc ?
- Rappeler le calendrier
- slides...
- l'id des indicateurs de parcelle
- geoloc, rsl_2015 ?
- diapo Sonia, mettre + de détail de où viennent les données ?
- historique on a que les étiquettes
- On part du principe que si on charge 2018 on aura rien de neuf
- Pour les étiquettes on peut juste dire "on la prend dans ce fichier".

- l'idp parcelle contient la commune vérifier que le centre se trouve dans la commune, surface sur surface bounding box et centroide dans parcelle.
- géocodage à l'UP ?
- source xy très détaillé !