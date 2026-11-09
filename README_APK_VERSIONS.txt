================================================================================
README — HISTORIQUE COMPLET DES 21 VERSIONS DE L'APK ANDROID (Plans-Tournees)
================================================================================
Dossier                       : /home/rg/pCloudDrive/documents/poste/pdf tournée casier imcomplet/OLD/
Nombre de versions APK        : 21 versions (de V251026 à V0811260743)
Règle de nommage des versions : V<JJMMAAHHMM> (Jour / Mois / Année sur 2 chiffres / Heure / Minute en GMT)
================================================================================


--------------------------------------------------------------------------------
TABLEAU RÉCAPITULATIF (ORDRE CHRONOLOGIQUE : DE LA PLUS ANCIENNE À LA PLUS RÉCENTE)
--------------------------------------------------------------------------------
 1. Plans-Tournees_V2510261635GMT.apk | 25/10/2026 16:35 GMT | 10 plans | Première application à 10 plans, mode fluidité, correctif Street View
 2. Plans-Tournees_V251026.apk        | 25/10/2026 17:58 GMT | 10 plans | Tournées 2402 et 2502 renommées (suppression de Casier 1210/2308)
 3. Plans-Tournees_V2510261800GMT.apk | 25/10/2026 18:00 GMT | 10 plans | Vidage automatique du cache WebView au démarrage + versionCode 5
 4. Plans-Tournees_V2510261829GMT.apk | 25/10/2026 18:29 GMT | 10 plans | Badge visible « version 251026 » en haut du menu d'accueil
 5. Plans-Tournees_V2710260719.apk    | 27/10/2026 07:19 GMT | 10 plans | Point GPS en direct + bouton Recentrer, opacité liée, dépôts 2310
 6. Plans-Tournees_V2710261825.apk    | 27/10/2026 18:25 GMT | 11 plans | Ajout de la tournée 1202 + dépôt, suppression de l'échelle 500 m, correctif 1401
 7. Plans-Tournees_V2810260725.apk    | 28/10/2026 07:25 GMT | 11 plans | Enregistrement de la trace GPS en rouge REC/STOP, fenêtre d'intervalle 10 s, export GPX
 8. Plans-Tournees_V2810260742.apk    | 28/10/2026 07:42 GMT | 11 plans | Mode suivi/centrage GPS AUTO au 2e appui sur le bouton GPS
 9. Plans-Tournees_V2810261856.apk    | 28/10/2026 18:56 GMT | 11 plans | Bouton d'import GPX en haut à gauche (trace jaune) + 2 dépôts dans la 1202
10. Plans-Tournees_V2910261912.apk    | 29/10/2026 19:12 GMT | 12 plans | Ajout de la tournée 1100 (Saint-Genest-Lerpt)
11. Plans-Tournees_V3010260648.apk    | 30/10/2026 06:48 GMT | 13 plans | Ajout de la tournée 1101 (Saint-Genest-Lerpt) + mise à jour de la 1100
12. Plans-Tournees_V3010260746.apk    | 30/10/2026 07:46 GMT | 14 plans | Ajout de la tournée 1102 (Saint-Genest-Lerpt)
13. Plans-Tournees_V3010260808.apk    | 30/10/2026 08:08 GMT | 15 plans | Ajout du plan combiné Tournées 1100 + 1101 + 1102 (2 090 arrêts)
14. Plans-Tournees_V3010260907.apk    | 30/10/2026 09:07 GMT | 15 plans | Descriptions du menu d'accueil simplifiées au nombre d'arrêts (« arrêts »)
15. Plans-Tournees_V3010261138.apk    | 30/10/2026 11:38 GMT | 15 plans | Suppression des compteurs en double « 752 VISIBLES / 58 BATTERIES » dans 1100-1101-1102
16. Plans-Tournees_V3010261740.apk    | 30/10/2026 17:40 GMT | 15 plans | Mise à jour 1100-1101-1102, suppression de la fenêtre de démarrage, en-têtes harmonisés
17. Plans-Tournees_V0511260532.apk    | 05/11/2026 05:32 GMT | 15 plans | Bouton REC déplacé d'en haut à droite vers en haut à gauche sous le bouton GPX
18. Plans-Tournees_V0611261759.apk    | 06/11/2026 17:59 GMT | 15 plans | Nouveau dépôt (D) rue de l'Égalité / rue Dorian dans 1100 et 1100-1101-1102
19. Plans-Tournees_V0811260711.apk    | 08/11/2026 07:11 GMT | 15 plans | Bouton « ☰ Filtres » plus petit + nouveau bouton « WPT » (waypoint) et prise en charge des waypoints GPX
20. Plans-Tournees_V0811260737.apk    | 08/11/2026 07:37 GMT | 15 plans | Logo de chargement animé et barre de progression 0 %-100 % en cochant « Afficher les cases »
21. Plans-Tournees_V0811260743.apk    | 08/11/2026 07:43 GMT | 15 plans | Logo de déchargement animé et barre de progression 0 %-100 % en décochant « Afficher les cases »


================================================================================
HISTORIQUE DÉTAILLÉ VERSION PAR VERSION (ORDRE CHRONOLOGIQUE)
================================================================================

--------------------------------------------------------------------------------
1. Plans-Tournees_V2510261635GMT.apk
   Date / Heure (GMT) : 25/10/2026 - 16:35 GMT
   Taille du fichier  : 386 419 octets | Plans intégrés : 10
--------------------------------------------------------------------------------
- Première version de l'APK Android multi-plans, regroupant 10 plans de
  distribution interactifs sur 3 communes :
  * Saint-Just-Saint-Rambert (42170) : 1401, 1501, 1401 & 1501, 2310
  * Andrézieux-Bouthéon (42160) : 2402 (Casier 1210), 2502 (Casier 2308), 2402 & 2502
  * Veauche (42340) : 1608, 2618, 1608 & 2618
- « ☐ Afficher les cases » décoché par défaut sur les 10 plans pour que le
  déplacement et le zoom restent fluides sur smartphone.
- Ajout d'une fenêtre d'explication au démarrage et d'un bandeau permanent en
  haut du menu d'accueil (index.html) expliquant pourquoi « Afficher les cases »
  est décoché par défaut.
- Ajout de barres de défilement verticales visibles et d'une hauteur adaptée au
  mobile (max-height : 45vh) pour le panneau de filtres du haut (.controls-panel)
  et la liste des arrêts du bas (#stops-list).
- Correction des liens Street View et Itinéraire Google Maps (« Itinéraire »)
  dans MainActivity.java : les liens intent://, geo: et google.com/maps sont
  interceptés pour ouvrir l'application Android Google Maps / Street View.

--------------------------------------------------------------------------------
2. Plans-Tournees_V251026.apk
   Date / Heure (GMT) : 25/10/2026 - 17:58 GMT
   Taille du fichier  : 386 419 octets | Plans intégrés : 10
--------------------------------------------------------------------------------
- Titres et badges des tournées renommés dans le menu d'accueil (index.html) :
  * « Tournée 2402 — Casier 1210 » (« 🔵 TOURNÉE 2402 (1210) ») -> « Tournée 2402 » (« 🔵 TOURNÉE 2402 »)
  * « Tournée 2502 — Casier 2308 » (« 🟢 TOURNÉE 2502 (2308) ») -> « Tournée 2502 » (« 🟢 TOURNÉE 2502 »)
  * Description du plan combiné remplacée par « Plan combiné 2402 et 2502 avec sélecteur rapide ».

--------------------------------------------------------------------------------
3. Plans-Tournees_V2510261800GMT.apk
   Date / Heure (GMT) : 25/10/2026 - 18:00 GMT (compilée à 18:27 GMT)
   Taille du fichier  : 386 419 octets | Plans intégrés : 10
--------------------------------------------------------------------------------
- Suppression confirmée de « — Casier 1210 » et « — Casier 2308 » sur les cartes
  du menu : seules « Tournée 2402 » et « Tournée 2502 » restent.
- Ajout du vidage automatique du cache WebView au lancement de l'application
  (webView.clearCache(true) dans MainActivity.java) et passage du versionCode
  interne à « 5 » dans AndroidManifest.xml, pour que les smartphones n'affichent
  plus d'anciennes pages de menu en cache.

--------------------------------------------------------------------------------
4. Plans-Tournees_V2510261829GMT.apk
   Date / Heure (GMT) : 25/10/2026 - 18:29 GMT (recompilée le 27/10/2026 à 06:46 GMT)
   Taille du fichier  : 386 419 octets | Plans intégrés : 10
--------------------------------------------------------------------------------
- Ajout du libellé de version visible « version 251026 » (.version-top) tout en
  haut de l'écran d'accueil (index.html), juste au-dessus du badge
  « LOIRE 42 • 10 PLANS INTÉGRÉS ».
- AndroidManifest.xml mis à jour : versionCode="6" et versionName="251026".

--------------------------------------------------------------------------------
5. Plans-Tournees_V2710260719.apk
   Date / Heure (GMT) : 27/10/2026 - 07:19 GMT (mise à jour à 17:50 GMT)
   Taille du fichier  : 402 803 octets | Plans intégrés : 10
--------------------------------------------------------------------------------
- Ajout de la position GPS en direct (style Google Maps) et d'un bouton de
  recentrage GPS en haut à droite :
  * Ajout d'un point GPS bleu pulsant en temps réel (#gps-user-dot) avec un halo
    de précision sur les 10 plans, alimenté à la fois par le LocationManager
    natif d'Android dans MainActivity.java et par la géolocalisation HTML5.
  * Ajout d'un bouton de recentrage GPS en haut à droite (#gps-recenter-btn),
    juste sous le bouton des calques, pour centrer et zoomer sur la position GPS
    de l'utilisateur.
- Boutons superposés à la carte liés au curseur « Transparence bloc contrôles carte ».
- Ajout de 2 nouveaux marqueurs violets « D » (dépôts) dans la tournée 2310
  (Saint-Just-Saint-Rambert) :
  * Dépôt D7 : Chemin des Vignes / Rue Jayol (45.503862, 4.265476)
  * Dépôt D8 : Rue Waldeck Rousseau / Chemin des Bourrelières (45.498002, 4.265786)
- Nom de l'application (strings.xml), libellé du lanceur et en-tête de l'écran
  d'accueil mis à jour en « Plans-Tournees_V2710260719 » (version 2710260719,
  versionCode="8").

--------------------------------------------------------------------------------
6. Plans-Tournees_V2710261825.apk
   Date / Heure (GMT) : 27/10/2026 - 18:25 GMT (mises à jour jusqu'à 20:46 GMT)
   Taille du fichier  : 439 761 octets | Plans intégrés : 11
--------------------------------------------------------------------------------
- Ajout d'un 11e plan : Tournée 1202 (tournee-1202-andrezieux-boutheon-map.html, 980 arrêts) :
  * Placée dans la section « 📍 Andrézieux-Bouthéon (42160) » de index.html
    (« LOIRE 42 • 11 PLANS INTÉGRÉS »).
  * Ajout d'un marqueur violet « D » (dépôt) à l'angle de la rue Alexander
    Fleming et de la rue Molière (45.529983, 4.268667).
- Suppression de l'échelle OpenStreetMap (« 500 m » / « 300 m », L.control.scale)
  en bas à droite sur les 11 plans, pour qu'elle ne chevauche plus le curseur
  « Opacité tracé ».
- Tous les boutons et curseurs de la carte (zoom + / -, « ☰ Filtres & Liste »,
  sélecteur de calques, bouton de recentrage GPS, panneaux du bas opacité/cases)
  liés au curseur « Transparence bloc contrôles carte » sur les 11 plans.
- Correction d'une erreur de syntaxe JavaScript dans la tournée 1401 et dans les
  tournées 1401 & 1501 (combiné), et recompilation des deux plans avec toutes les
  dernières commandes.
- Nom de l'application et version interne mis à jour en « Plans-Tournees_V2710261825 » (versionCode="9").

--------------------------------------------------------------------------------
7. Plans-Tournees_V2810260725.apk
   Date / Heure (GMT) : 28/10/2026 - 07:25 GMT
   Taille du fichier  : 480 721 octets | Plans intégrés : 11
--------------------------------------------------------------------------------
- Ajout de l'enregistrement de la trace GPS en direct (REC / STOP) et de l'export
  GPX sur les 11 plans :
  * Un appui sur « REC » enregistre la trace GPS en temps réel et la dessine en
    rouge vif sur la carte.
  * Un appui sur « STOP » génère automatiquement un fichier .gpx standard
    (trace-gps-<tournee>_<date_heure>.gpx) et l'enregistre dans le dossier
    « Téléchargements » du téléphone via MainActivity.java.
- Ajout d'une fenêtre de choix de l'intervalle d'enregistrement en cliquant sur « REC » :
  * Ouvre une fenêtre (« 🔴 Enregistrement Trace GPS ») qui demande le nombre de
    secondes entre chaque point GPS enregistré, avec 10 s présélectionné par
    défaut (boutons rapides 2 s, 5 s, 10 s, 15 s, 30 s, 60 s, ou saisie libre).
- Suppression du bandeau d'état « 🔴 Trace GPS en cours (X pts) » en haut pendant
  l'enregistrement, en gardant la notification « ✅ GPX enregistré dans
  Téléchargements » à l'arrêt.
- Nom de l'application et version interne mis à jour en « Plans-Tournees_V2810260725 ».

--------------------------------------------------------------------------------
8. Plans-Tournees_V2810260742.apk
   Date / Heure (GMT) : 28/10/2026 - 07:42 GMT
   Taille du fichier  : 484 817 octets | Plans intégrés : 11
--------------------------------------------------------------------------------
- Ajout du mode centrage/suivi GPS automatique au 2e appui (« AUTO ») sur les 11 plans :
  * 1er appui sur le bouton GPS : recentre une fois la carte sur la position GPS actuelle.
  * 2e appui sur le bouton GPS : active le mode suivi automatique (« AUTO ») — le
    bouton devient bleu plein avec une mire blanche et le libellé « AUTO », et la
    carte reste automatiquement centrée sur la position GPS pendant le déplacement.
  * 3e appui (ou déplacement manuel de la carte) : désactive le centrage
    automatique pour se déplacer librement.
- Nom de l'application et version interne mis à jour en « Plans-Tournees_V2810260742 ».

--------------------------------------------------------------------------------
9. Plans-Tournees_V2810261856.apk
   Date / Heure (GMT) : 28/10/2026 - 18:56 GMT (mises à jour jusqu'au 29/10/2026 16:42 GMT)
   Taille du fichier  : 505 321 octets | Plans intégrés : 11
--------------------------------------------------------------------------------
- Ajout d'un bouton « GPX » d'ouverture de fichier en haut à gauche (#gpx-open-btn) sur les 11 plans :
  * Placé en haut à gauche, juste sous les boutons de zoom + / -, et lié au
    curseur « Transparence bloc contrôles carte ».
  * Un appui sur « GPX » ouvre le sélecteur de fichiers d'Android pour charger
    n'importe quel fichier .gpx du smartphone et dessiner son tracé sur la carte.
  * Couleur de la trace GPX importée modifiée (bleu -> vert -> jaune vif #facc15
    avec un contour sombre) pour une visibilité maximale sur la carte.
- Ajout de 2 nouveaux dépôts violets « D » (D4 et D5) dans la tournée 1202 (Andrézieux-Bouthéon) :
  * D4 : Avenue de Veauche / Rue de la Joaterie (45.540975, 4.272600, entre B4 et B5)
  * D5 : Place Victor Hugo / Passage Paul Verlaine (45.542061, 4.266536, devant
    la Pharmacie de Bouthéon, entre B7 et C1)
- Nom de l'application et version interne mis à jour en « Plans-Tournees_V2810261856 ».

--------------------------------------------------------------------------------
10. Plans-Tournees_V2910261912.apk
    Date / Heure (GMT) : 29/10/2026 - 19:12 GMT
    Taille du fichier  : 542 251 octets | Plans intégrés : 12
--------------------------------------------------------------------------------
- Ajout d'un 12e plan : Tournée 1100 — Saint-Genest-Lerpt (tournee-1100-st-genest-lerpt-map.html, 677 arrêts) :
  * Création d'une nouvelle section de commune « 📍 Saint-Genest-Lerpt (42530) »
    dans le menu d'accueil (index.html, « LOIRE 42 • 12 PLANS INTÉGRÉS »).
- Nom de l'application et version interne mis à jour en « Plans-Tournees_V2910261912 » (versionCode="20").

--------------------------------------------------------------------------------
11. Plans-Tournees_V3010260648.apk
    Date / Heure (GMT) : 30/10/2026 - 06:48 GMT
    Taille du fichier  : 579 205 octets | Plans intégrés : 13
--------------------------------------------------------------------------------
- Ajout d'un 13e plan : Tournée 1101 — Saint-Genest-Lerpt (tournee-1101-st-genest-lerpt-map.html, 752 arrêts)
  et mise à jour de la tournée 1100 dans l'APK :
  * Ajout de la carte Tournée 1101 sous « 📍 Saint-Genest-Lerpt (42530) » dans
    index.html (« LOIRE 42 • 13 PLANS INTÉGRÉS »).
- Nom de l'application et version interne mis à jour en « Plans-Tournees_V3010260648 » (versionCode="21").

--------------------------------------------------------------------------------
12. Plans-Tournees_V3010260746.apk
    Date / Heure (GMT) : 30/10/2026 - 07:46 GMT
    Taille du fichier  : 607 967 octets | Plans intégrés : 14
--------------------------------------------------------------------------------
- Ajout d'un 14e plan : Tournée 1102 — Saint-Genest-Lerpt (tournee-1102-st-genest-lerpt-map.html, 661 arrêts) :
  * Ajout de la carte Tournée 1102 sous « 📍 Saint-Genest-Lerpt (42530) » dans
    index.html (« LOIRE 42 • 14 PLANS INTÉGRÉS »).
- Nom de l'application et version interne mis à jour en « Plans-Tournees_V3010260746 » (versionCode="22").

--------------------------------------------------------------------------------
13. Plans-Tournees_V3010260808.apk
    Date / Heure (GMT) : 30/10/2026 - 08:08 GMT
    Taille du fichier  : 694 083 octets | Plans intégrés : 15
--------------------------------------------------------------------------------
- Ajout d'un 15e plan : Tournées combinées 1100 + 1101 + 1102 — Saint-Genest-Lerpt
  (tournee-1100-1101-1102-st-genest-lerpt-map.html, 2 090 arrêts) :
  * Création d'un plan combiné 1100, 1101 et 1102 avec des boutons de filtre
    rapide (Toutes, 1100, 1101, 1102) dans le panneau latéral et sur la carte.
  * Ajout de la carte combinée dans index.html (« LOIRE 42 • 15 PLANS INTÉGRÉS »).
- Nom de l'application et version interne mis à jour en « Plans-Tournees_V3010260808 » (versionCode="23").

--------------------------------------------------------------------------------
14. Plans-Tournees_V3010260907.apk
    Date / Heure (GMT) : 30/10/2026 - 09:07 GMT (mise à jour à 11:35 GMT)
    Taille du fichier  : 689 987 octets | Plans intégrés : 15
--------------------------------------------------------------------------------
- Descriptions du menu d'accueil simplifiées pour toutes les communes (index.html) :
  * Les descriptions détaillées des 15 cartes sont remplacées par le seul nombre
    d'arrêts (« <N> arrêts ») pour chaque tournée de Saint-Just-Saint-Rambert,
    Andrézieux-Bouthéon, Veauche et Saint-Genest-Lerpt.
- Suppression des compteurs fixes en double (« 752 VISIBLES » et « 58 BATTERIES »)
  du plan combiné tournee-1100-1101-1102-st-genest-lerpt-map.html.
- Nom de l'application et version interne mis à jour en « Plans-Tournees_V3010260907 » (versionCode="24").

--------------------------------------------------------------------------------
15. Plans-Tournees_V3010261138.apk
    Date / Heure (GMT) : 30/10/2026 - 11:38 GMT
    Taille du fichier  : 689 987 octets | Plans intégrés : 15
--------------------------------------------------------------------------------
- Changement officiel de version et renommage de l'APK après le nettoyage des
  compteurs en double « 752 VISIBLES / 58 BATTERIES » dans
  tournee-1100-1101-1102-st-genest-lerpt-map.html.
- Nom de l'application, AndroidManifest.xml et index.html mis à jour en
  « Plans-Tournees_V3010261138 » (version 3010261138, versionCode="25").

--------------------------------------------------------------------------------
16. Plans-Tournees_V3010261740.apk
    Date / Heure (GMT) : 30/10/2026 - 17:40 GMT (mise à jour à 18:34 GMT)
    Taille du fichier  : 694 083 octets | Plans intégrés : 15
--------------------------------------------------------------------------------
- Mise à jour de tournee-1100-1101-1102-st-genest-lerpt-map.html et de
  tournee-1100-st-genest-lerpt-map.html dans l'APK avec les derniers arrêts et dépôts.
- Suppression de la fenêtre de démarrage sur la fluidité (« Information importante :
  Fluidité & Affichage des cases ») dans index.html : l'application s'ouvre
  directement sur le menu.
- En-tête bleu foncé du panneau latéral (.sidebar-header) harmonisé (proportions,
  tailles de police et bouton jaune unique « 🏠 Plans ») sur les 3 plans combinés
  (2402-2502, 1608-2618 et 1100-1101-1102), sur le modèle de la tournée 1401.
- Nom de l'application et version interne mis à jour en « Plans-Tournees_V3010261740 » (versionCode="26").

--------------------------------------------------------------------------------
17. Plans-Tournees_V0511260532.apk
    Date / Heure (GMT) : 05/11/2026 - 05:32 GMT
    Taille du fichier  : 702 275 octets | Plans intégrés : 15
--------------------------------------------------------------------------------
- Déplacement du bouton d'enregistrement GPS (« REC » / gpsRecordControl) sur les 15 plans :
  * Le bouton « REC » passe du coin en haut à droite au coin en haut à gauche,
    juste sous le bouton « GPX ».
- Nom de l'application et version interne mis à jour en « Plans-Tournees_V0511260532 » (versionCode="27").

--------------------------------------------------------------------------------
18. Plans-Tournees_V0611261759.apk
    Date / Heure (GMT) : 06/11/2026 - 17:59 GMT
    Taille du fichier  : 702 275 octets | Plans intégrés : 15
--------------------------------------------------------------------------------
- Ajout d'un nouveau marqueur violet « D » (dépôt, kind : "depot") à
  Saint-Genest-Lerpt, rue de l'Égalité / rue Dorian (45.444625, 4.339655, à côté
  des numéros 26 et 5), dans tournee-1100-1101-1102-st-genest-lerpt-map.html et
  dans tournee-1100-st-genest-lerpt-map.html.
- Nom de l'application et version interne mis à jour en « Plans-Tournees_V0611261759 » (versionCode="28").

--------------------------------------------------------------------------------
19. Plans-Tournees_V0811260711.apk
    Date / Heure (GMT) : 08/11/2026 - 07:11 GMT
    Taille du fichier  : 743 235 octets | Plans intégrés : 15
--------------------------------------------------------------------------------
- Réduction de la taille du bouton de filtres en haut à gauche sur les 15 plans :
  * Libellé raccourci de « ☰ Filtres & Liste » à « ☰ Filtres », avec une marge
    réduite (6px 10px), une police plus petite (0.74rem) et une icône de 15x15 px.
- Ajout d'un bouton Waypoint (« WPT ») en haut à droite et prise en charge des
  waypoints GPX sur les 15 plans :
  * Nouveau bouton « WPT » en haut à droite, juste sous le bouton de
    recentrage/suivi GPS.
  * Un clic sur « WPT » ouvre une fenêtre demandant le nom du waypoint (à la
    position GPS actuelle ou au centre de la carte).
  * Les waypoints validés s'affichent sur la carte avec leur nom (déplaçables
    pour ajuster la position et supprimables depuis leur fenêtre).
  * Les waypoints (<wpt> + <name>) sont enregistrés dans le fichier .gpx à
    l'arrêt du REC, et s'affichent aussi sur la carte à l'ouverture d'un
    fichier .gpx avec le bouton GPX.
- Nom de l'application et version interne mis à jour en « Plans-Tournees_V0811260711 » (versionCode="29").

--------------------------------------------------------------------------------
20. Plans-Tournees_V0811260737.apk
    Date / Heure (GMT) : 08/11/2026 - 07:37 GMT
    Taille du fichier  : 755 523 octets | Plans intégrés : 15
--------------------------------------------------------------------------------
- Ajout d'un logo de chargement animé et d'une barre de progression en direct
  (0 % -> 100 %) en cochant « Afficher les cases » sur les 15 plans :
  * La création des marqueurs se fait maintenant par lots progressifs, image par
    image, pour que l'interface ne se fige jamais.
  * Affiche une carte centrée (#cases-loading-overlay) avec un logo animé,
    « Chargement des cases... », le pourcentage en direct (0 % à 100 %), le
    compteur de cases chargées (par ex. « 450 / 2090 cases ») et une barre de
    progression en temps réel jusqu'à ce que toutes les cases soient affichées.
- Nom de l'application et version interne mis à jour en « Plans-Tournees_V0811260737 » (versionCode="30").

--------------------------------------------------------------------------------
21. Plans-Tournees_V0811260743.apk
    Date / Heure (GMT) : 08/11/2026 - 07:43 GMT
    Taille du fichier  : 759 619 octets | Plans intégrés : 15
--------------------------------------------------------------------------------
- Ajout d'un logo de déchargement animé et d'une barre de progression en direct
  (0 % -> 100 %) en décochant « Afficher les cases » sur les 15 plans :
  * En décochant « Afficher les cases » (retrait des cases de la carte), les
    marqueurs sont maintenant supprimés par lots progressifs, image par image.
  * Affiche la carte centrée (#cases-loading-overlay) avec le logo animé,
    « Déchargement des cases... », le pourcentage en direct (0 % à 100 %), le
    compteur de cases retirées et une barre de progression en temps réel jusqu'à
    ce que tous les marqueurs soient supprimés.
- Nom de l'application et version interne mis à jour en « Plans-Tournees_V0811260743 » (versionCode="31").
================================================================================
