================================================================================
README — COMPLETE CHANGELOG OF ALL 21 ANDROID APK VERSIONS (Plans-Tournees)
================================================================================
Folder : /home/rg/pCloudDrive/documents/poste/pdf tournée casier imcomplet/OLD/
Total APK Versions Documented : 21 versions (from V251026 to V0811260743)
Version Naming Convention     : V<DDMMYYHHMM> (Day / Month / 2-digit Year / Hour / Minute in GMT)
================================================================================


--------------------------------------------------------------------------------
SUMMARY TABLE (CHRONOLOGICAL ORDER: OLDEST -> NEWEST)
--------------------------------------------------------------------------------
 1. Plans-Tournees_V2510261635GMT.apk | 25/10/2026 16:35 GMT | 10 maps | Initial 10-map app, fluidity mode, Street View fix
 2. Plans-Tournees_V251026.apk        | 25/10/2026 17:58 GMT | 10 maps | Renamed Tournée 2402 & 2502 (removed Casier 1210/2308)
 3. Plans-Tournees_V2510261800GMT.apk | 25/10/2026 18:00 GMT | 10 maps | Auto-clear WebView cache on startup + versionCode 5
 4. Plans-Tournees_V2510261829GMT.apk | 25/10/2026 18:29 GMT | 10 maps | Added visible "version 251026" badge at top of home menu
 5. Plans-Tournees_V2710260719.apk    | 27/10/2026 07:19 GMT | 10 maps | Live GPS dot + Recenter button, linked opacity, 2310 depots
 6. Plans-Tournees_V2710261825.apk    | 27/10/2026 18:25 GMT | 11 maps | Added Tournée 1202 + depot, removed 500m scale bar, fixed 1401
 7. Plans-Tournees_V2810260725.apk    | 28/10/2026 07:25 GMT | 11 maps | Added REC/STOP red GPS track recording, 10s interval popup, GPX export
 8. Plans-Tournees_V2810260742.apk    | 28/10/2026 07:42 GMT | 11 maps | Added 2nd-tap AUTO GPS follow/center mode on GPS button
 9. Plans-Tournees_V2810261856.apk    | 28/10/2026 18:56 GMT | 11 maps | Added top-left GPX import button (yellow track) + 2 depots in 1202
10. Plans-Tournees_V2910261912.apk    | 29/10/2026 19:12 GMT | 12 maps | Added Tournée 1100 (Saint-Genest-Lerpt)
11. Plans-Tournees_V3010260648.apk    | 30/10/2026 06:48 GMT | 13 maps | Added Tournée 1101 (Saint-Genest-Lerpt) + updated 1100
12. Plans-Tournees_V3010260746.apk    | 30/10/2026 07:46 GMT | 14 maps | Added Tournée 1102 (Saint-Genest-Lerpt)
13. Plans-Tournees_V3010260808.apk    | 30/10/2026 08:08 GMT | 15 maps | Added combined map Tournées 1100 + 1101 + 1102 (2,090 stops)
14. Plans-Tournees_V3010260907.apk    | 30/10/2026 09:07 GMT | 15 maps | Simplified home menu descriptions to show only stop counts ("arrêts")
15. Plans-Tournees_V3010261138.apk    | 30/10/2026 11:38 GMT | 15 maps | Removed duplicate "752 VISIBLES / 58 BATTERIES" counters in 1100-1101-1102
16. Plans-Tournees_V3010261740.apk    | 30/10/2026 17:40 GMT | 15 maps | Updated 1100-1101-1102, removed startup popup, unified header ratios
17. Plans-Tournees_V0511260532.apk    | 05/11/2026 05:32 GMT | 15 maps | Moved REC button from top-right to top-left below GPX button
18. Plans-Tournees_V0611261759.apk    | 06/11/2026 17:59 GMT | 15 maps | Added new Depot (D) at Rue de l'Égalité / Rue Dorian in 1100 & 1100-1101-1102
19. Plans-Tournees_V0811260711.apk    | 08/11/2026 07:11 GMT | 15 maps | Smaller "☰ Filtres" button + new "WPT" (Waypoint) button & GPX waypoint support
20. Plans-Tournees_V0811260737.apk    | 08/11/2026 07:37 GMT | 15 maps | Added spinning loading logo & live 0%-100% progress bar when checking "Afficher les cases"
21. Plans-Tournees_V0811260743.apk    | 08/11/2026 07:43 GMT | 15 maps | Added spinning unloading logo & live 0%-100% progress bar when unchecking "Afficher les cases"


================================================================================
DETAILED VERSION-BY-VERSION CHANGELOG (CHRONOLOGICAL ORDER)
================================================================================

--------------------------------------------------------------------------------
1. Plans-Tournees_V2510261635GMT.apk
   Date / Time (GMT) : 25/10/2026 - 16:35 GMT
   File Size         : 386,419 bytes | Embedded Maps: 10
--------------------------------------------------------------------------------
- Initial multi-map Android APK release packaging 10 interactive delivery maps
  across 3 communes:
  * Saint-Just-Saint-Rambert (42170): 1401, 1501, 1401 & 1501, 2310
  * Andrézieux-Bouthéon (42160): 2402 (Casier 1210), 2502 (Casier 2308), 2402 & 2502
  * Veauche (42340): 1608, 2618, 1608 & 2618
- Unchecked "☐ Afficher les cases" by default across all 10 maps so panning and
  zooming are smooth on smartphones.
- Added startup explanation popup and permanent top banner in the home menu
  (index.html) explaining why "Afficher les cases" is unchecked by default.
- Added visible vertical scrollbars and mobile-friendly height (max-height: 45vh)
  for the top filter panel (.controls-panel) and bottom stops list (#stops-list).
- Fixed Street View and Google Maps Directions ("Itinéraire") links in
  MainActivity.java by intercepting intent://, geo:, and google.com/maps links
  to launch the native Google Maps / Street View Android app.

--------------------------------------------------------------------------------
2. Plans-Tournees_V251026.apk
   Date / Time (GMT) : 25/10/2026 - 17:58 GMT
   File Size         : 386,419 bytes | Embedded Maps: 10
--------------------------------------------------------------------------------
- Renamed route titles and badges in the home screen menu (index.html):
  * "Tournée 2402 — Casier 1210" ("🔵 TOURNÉE 2402 (1210)") -> "Tournée 2402" ("🔵 TOURNÉE 2402")
  * "Tournée 2502 — Casier 2308" ("🟢 TOURNÉE 2502 (2308)") -> "Tournée 2502" ("🟢 TOURNÉE 2502")
  * Combined description updated to "Plan combiné 2402 et 2502 avec sélecteur rapide".

--------------------------------------------------------------------------------
3. Plans-Tournees_V2510261800GMT.apk
   Date / Time (GMT) : 25/10/2026 - 18:00 GMT (built 18:27 GMT)
   File Size         : 386,419 bytes | Embedded Maps: 10
--------------------------------------------------------------------------------
- Confirmed removal of "— Casier 1210" and "— Casier 2308" on the menu cards
  so only "Tournée 2402" and "Tournée 2502" remain.
- Added automatic WebView cache clearing on app launch (webView.clearCache(true)
  in MainActivity.java) and incremented internal versionCode="5" in
  AndroidManifest.xml so smartphones no longer display old cached menu pages.

--------------------------------------------------------------------------------
4. Plans-Tournees_V2510261829GMT.apk
   Date / Time (GMT) : 25/10/2026 - 18:29 GMT (rebuilt 27/10/2026 06:46 GMT)
   File Size         : 386,419 bytes | Embedded Maps: 10
--------------------------------------------------------------------------------
- Added the visible version label "version 251026" (.version-top) at the very
  top of the home screen (index.html), directly above the "LOIRE 42 • 10 PLANS INTÉGRÉS" badge.
- Updated AndroidManifest.xml to versionCode="6" and versionName="251026".

--------------------------------------------------------------------------------
5. Plans-Tournees_V2710260719.apk
   Date / Time (GMT) : 27/10/2026 - 07:19 GMT (updated 17:50 GMT)
   File Size         : 402,803 bytes | Embedded Maps: 10
--------------------------------------------------------------------------------
- Added Live GPS Position (Google Maps style) & Top-Right GPS Recenter Button:
  * Added a real-time pulsing blue GPS dot (#gps-user-dot) with an accuracy halo
    across all 10 maps, powered by both Android native LocationManager in
    MainActivity.java and HTML5 Geolocation.
  * Added a top-right GPS Recenter button (#gps-recenter-btn) directly below the
    map layers button to center and zoom on the user's live GPS location.
- Linked map overlay buttons to the "Transparence bloc contrôles carte" slider.
- Added 2 new purple "D" Depot markers in Tournée 2310 (Saint-Just-Saint-Rambert):
  * Dépôt D7: Chemin des Vignes / Rue Jayol (45.503862, 4.265476)
  * Dépôt D8: Rue Waldeck Rousseau / Chemin des Bourrelières (45.498002, 4.265786)
- Updated app name (strings.xml), launcher label, and home screen header to
  "Plans-Tournees_V2710260719" (version 2710260719, versionCode="8").

--------------------------------------------------------------------------------
6. Plans-Tournees_V2710261825.apk
   Date / Time (GMT) : 27/10/2026 - 18:25 GMT (updated through 20:46 GMT)
   File Size         : 439,761 bytes | Embedded Maps: 11
--------------------------------------------------------------------------------
- Added 11th Map: Tournée 1202 (tournee-1202-andrezieux-boutheon-map.html, 980 stops):
  * Placed under the "📍 Andrézieux-Bouthéon (42160)" section in index.html
    ("LOIRE 42 • 11 PLANS INTÉGRÉS").
  * Added purple "D" Depot marker at the corner of Rue Alexander Fleming &
    Rue Molière (45.529983, 4.268667).
- Removed the OpenStreetMap scale bar ("500 m" / "300 m", L.control.scale) at the
  bottom-right across all 11 maps so it no longer overlaps the "Opacité tracé" slider.
- Linked all on-map buttons and sliders (+ / - zoom, "☰ Filtres & Liste", layer
  switcher, GPS recenter button, and bottom opacity/cases panels) to the
  "Transparence bloc contrôles carte" slider across all 11 maps.
- Fixed a JavaScript syntax issue in Tournée 1401 and Tournées 1401 & 1501 (Combiné)
  and rebuilt both maps with all latest controls.
- Updated app name and internal version to "Plans-Tournees_V2710261825" (versionCode="9").

--------------------------------------------------------------------------------
7. Plans-Tournees_V2810260725.apk
   Date / Time (GMT) : 28/10/2026 - 07:25 GMT
   File Size         : 480,721 bytes | Embedded Maps: 11
--------------------------------------------------------------------------------
- Added Live GPS Track Recording (REC / STOP) & GPX Export across all 11 maps:
  * Tapping "REC" records the user's real-time GPS track and draws it in bright
    red on the map.
  * Tapping "STOP" automatically generates a standard .gpx file
    (trace-gps-<tournee>_<date_heure>.gpx) and saves it in the phone's Download
    ("Téléchargements") folder via MainActivity.java.
- Added Recording Interval Selection Popup when clicking "REC":
  * Opens a modal ("🔴 Enregistrement Trace GPS") asking how many seconds between
    each recorded GPS point, with 10s preselected by default (plus quick buttons
    for 2s, 5s, 10s, 15s, 30s, 60s, or custom input).
- Removed the top "🔴 Trace GPS en cours (X pts)" status banner during recording
  while keeping the "✅ GPX enregistré dans Téléchargements" notification on stop.
- Updated app name and internal version to "Plans-Tournees_V2810260725".

--------------------------------------------------------------------------------
8. Plans-Tournees_V2810260742.apk
   Date / Time (GMT) : 28/10/2026 - 07:42 GMT
   File Size         : 484,817 bytes | Embedded Maps: 11
--------------------------------------------------------------------------------
- Added 2nd-Tap GPS Auto-Center / Follow Mode ("AUTO") across all 11 maps:
  * 1st tap on the GPS button: Recenters the map once on the current GPS position.
  * 2nd tap on the GPS button: Activates Auto-Center Follow Mode ("AUTO") — the
    button turns solid blue with a white crosshair and "AUTO" label, and the map
    automatically stays centered on the user's GPS position as they move.
  * 3rd tap (or dragging the map manually): Unlocks Auto-Center mode for free panning.
- Updated app name and internal version to "Plans-Tournees_V2810260742".

--------------------------------------------------------------------------------
9. Plans-Tournees_V2810261856.apk
   Date / Time (GMT) : 28/10/2026 - 18:56 GMT (updated through 29/10/2026 16:42 GMT)
   File Size         : 505,321 bytes | Embedded Maps: 11
--------------------------------------------------------------------------------
- Added Top-Left "GPX" File Open Button (#gpx-open-btn) across all 11 maps:
  * Placed at the top-left directly below the + / - zoom buttons and linked to
    the "Transparence bloc contrôles carte" slider.
  * Tapping "GPX" opens Android's file picker to load any .gpx file from the
    smartphone and draw its trajectory on the map.
  * Updated the imported GPX track color (from blue -> green -> bright yellow
    #facc15 with a dark contrast outline) for maximum visibility on the map.
- Added 2 new purple "D" Depots (D4 & D5) in Tournée 1202 (Andrézieux-Bouthéon):
  * D4: Avenue de Veauche / Rue de la Joaterie (45.540975, 4.272600, between B4 and B5)
  * D5: Place Victor Hugo / Passage Paul Verlaine (45.542061, 4.266536, in front
    of Pharmacie de Bouthéon, between B7 and C1)
- Updated app name and internal version to "Plans-Tournees_V2810261856".

--------------------------------------------------------------------------------
10. Plans-Tournees_V2910261912.apk
    Date / Time (GMT) : 29/10/2026 - 19:12 GMT
    File Size         : 542,251 bytes | Embedded Maps: 12
--------------------------------------------------------------------------------
- Added 12th Map: Tournée 1100 — Saint-Genest-Lerpt (tournee-1100-st-genest-lerpt-map.html, 677 stops):
  * Created new commune section "📍 Saint-Genest-Lerpt (42530)" in the home menu
    (index.html, "LOIRE 42 • 12 PLANS INTÉGRÉS").
- Updated app name and internal version to "Plans-Tournees_V2910261912" (versionCode="20").

--------------------------------------------------------------------------------
11. Plans-Tournees_V3010260648.apk
    Date / Time (GMT) : 30/10/2026 - 06:48 GMT
    File Size         : 579,205 bytes | Embedded Maps: 13
--------------------------------------------------------------------------------
- Added 13th Map: Tournée 1101 — Saint-Genest-Lerpt (tournee-1101-st-genest-lerpt-map.html, 752 stops)
  and updated Tournée 1100 inside the APK:
  * Added Tournée 1101 card under "📍 Saint-Genest-Lerpt (42530)" in index.html
    ("LOIRE 42 • 13 PLANS INTÉGRÉS").
- Updated app name and internal version to "Plans-Tournees_V3010260648" (versionCode="21").

--------------------------------------------------------------------------------
12. Plans-Tournees_V3010260746.apk
    Date / Time (GMT) : 30/10/2026 - 07:46 GMT
    File Size         : 607,967 bytes | Embedded Maps: 14
--------------------------------------------------------------------------------
- Added 14th Map: Tournée 1102 — Saint-Genest-Lerpt (tournee-1102-st-genest-lerpt-map.html, 661 stops):
  * Added Tournée 1102 card under "📍 Saint-Genest-Lerpt (42530)" in index.html
    ("LOIRE 42 • 14 PLANS INTÉGRÉS").
- Updated app name and internal version to "Plans-Tournees_V3010260746" (versionCode="22").

--------------------------------------------------------------------------------
13. Plans-Tournees_V3010260808.apk
    Date / Time (GMT) : 30/10/2026 - 08:08 GMT
    File Size         : 694,083 bytes | Embedded Maps: 15
--------------------------------------------------------------------------------
- Added 15th Map: Combined Tournées 1100 + 1101 + 1102 — Saint-Genest-Lerpt
  (tournee-1100-1101-1102-st-genest-lerpt-map.html, 2,090 stops):
  * Created combined map for 1100, 1101, and 1102 with quick-selector filter
    buttons (Toutes, 1100, 1101, 1102) in the sidebar and on the map.
  * Added combined card in index.html ("LOIRE 42 • 15 PLANS INTÉGRÉS").
- Updated app name and internal version to "Plans-Tournees_V3010260808" (versionCode="23").

--------------------------------------------------------------------------------
14. Plans-Tournees_V3010260907.apk
    Date / Time (GMT) : 30/10/2026 - 09:07 GMT (updated 11:35 GMT)
    File Size         : 689,987 bytes | Embedded Maps: 15
--------------------------------------------------------------------------------
- Simplified Home Menu Descriptions Across All Cities (index.html):
  * Replaced verbose descriptions on all 15 cards with just the stop count
    ("<N> arrêts") for every route across Saint-Just-Saint-Rambert,
    Andrézieux-Bouthéon, Veauche, and Saint-Genest-Lerpt.
- Removed duplicate static counter boxes ("752 VISIBLES" and "58 BATTERIES") from
  the combined map tournee-1100-1101-1102-st-genest-lerpt-map.html.
- Updated app name and internal version to "Plans-Tournees_V3010260907" (versionCode="24").

--------------------------------------------------------------------------------
15. Plans-Tournees_V3010261138.apk
    Date / Time (GMT) : 30/10/2026 - 11:38 GMT
    File Size         : 689,987 bytes | Embedded Maps: 15
--------------------------------------------------------------------------------
- Official version bump and APK rename following the cleanup of the duplicate
  "752 VISIBLES / 58 BATTERIES" counters in tournee-1100-1101-1102-st-genest-lerpt-map.html.
- Updated app name, AndroidManifest.xml, and index.html to
  "Plans-Tournees_V3010261138" (version 3010261138, versionCode="25").

--------------------------------------------------------------------------------
16. Plans-Tournees_V3010261740.apk
    Date / Time (GMT) : 30/10/2026 - 17:40 GMT (updated 18:34 GMT)
    File Size         : 694,083 bytes | Embedded Maps: 15
--------------------------------------------------------------------------------
- Updated tournee-1100-1101-1102-st-genest-lerpt-map.html and
  tournee-1100-st-genest-lerpt-map.html inside the APK with the latest stop/depot updates.
- Removed the startup fluidity popup modal ("Information importante : Fluidité &
  Affichage des cases") from index.html so the app opens directly onto the menu.
- Standardized the dark-blue sidebar header (.sidebar-header) dimension ratio,
  font sizes, and single yellow "🏠 Plans" button across the 3 combined maps
  (2402-2502, 1608-2618, and 1100-1101-1102) to match Tournée 1401.
- Updated app name and internal version to "Plans-Tournees_V3010261740" (versionCode="26").

--------------------------------------------------------------------------------
17. Plans-Tournees_V0511260532.apk
    Date / Time (GMT) : 05/11/2026 - 05:32 GMT
    File Size         : 702,275 bytes | Embedded Maps: 15
--------------------------------------------------------------------------------
- Repositioned the GPS Record Button ("REC" / gpsRecordControl) across all 15 maps:
  * Moved the "REC" button from the top-right to the top-left corner directly
    underneath the "GPX" button.
- Updated app name and internal version to "Plans-Tournees_V0511260532" (versionCode="27").

--------------------------------------------------------------------------------
18. Plans-Tournees_V0611261759.apk
    Date / Time (GMT) : 06/11/2026 - 17:59 GMT
    File Size         : 702,275 bytes | Embedded Maps: 15
--------------------------------------------------------------------------------
- Added a new purple "D" Depot marker (kind: "depot") in Saint-Genest-Lerpt at
  Rue de l'Égalité / Rue Dorian (45.444625, 4.339655, next to numbers 26 and 5)
  inside both tournee-1100-1101-1102-st-genest-lerpt-map.html and
  tournee-1100-st-genest-lerpt-map.html.
- Updated app name and internal version to "Plans-Tournees_V0611261759" (versionCode="28").

--------------------------------------------------------------------------------
19. Plans-Tournees_V0811260711.apk
    Date / Time (GMT) : 08/11/2026 - 07:11 GMT
    File Size         : 743,235 bytes | Embedded Maps: 15
--------------------------------------------------------------------------------
- Reduced the size of the top-left filter button across all 15 maps:
  * Shortened the label from "☰ Filtres & Liste" to "☰ Filtres" with reduced
    padding (6px 10px), smaller font size (0.74rem), and a 15x15px icon.
- Added the Top-Right Waypoint ("WPT") Button & GPX Waypoint Integration across all 15 maps:
  * Placed a new "WPT" button at the top-right directly below the GPS recenter/follow button.
  * Clicking "WPT" opens a popup window asking for the Waypoint Name (at current
    GPS position or map center).
  * Validated waypoints are displayed on the map with their name badge (draggable
    to adjust position and deletable via popup).
  * Waypoints (<wpt> + <name>) are saved inside the .gpx file when stopping REC,
    and are also rendered on the map when opening a .gpx file via the GPX button.
- Updated app name and internal version to "Plans-Tournees_V0811260711" (versionCode="29").

--------------------------------------------------------------------------------
20. Plans-Tournees_V0811260737.apk
    Date / Time (GMT) : 08/11/2026 - 07:37 GMT
    File Size         : 755,523 bytes | Embedded Maps: 15
--------------------------------------------------------------------------------
- Added Spinning Loading Logo & Live Percentage Progress Bar (0% -> 100%) when
  checking "Afficher les cases" across all 15 maps:
  * Replaced synchronous marker creation with progressive frame-by-frame batch
    rendering so the UI never freezes.
  * Displays a centered overlay card (#cases-loading-overlay) with a spinning
    logo, "Chargement des cases...", live percentage (0% to 100%), loaded case
    counter (e.g., "450 / 2090 cases"), and real-time progress bar until all
    cases appear on the map.
- Updated app name and internal version to "Plans-Tournees_V0811260737" (versionCode="30").

--------------------------------------------------------------------------------
21. Plans-Tournees_V0811260743.apk
    Date / Time (GMT) : 08/11/2026 - 07:43 GMT
    File Size         : 759,619 bytes | Embedded Maps: 15
--------------------------------------------------------------------------------
- Added Spinning Unloading Logo & Live Percentage Progress Bar (0% -> 100%) when
  unchecking "Afficher les cases" across all 15 maps:
  * When unmarking "Afficher les cases" (unloading the cases from the map),
    markers are now removed in progressive frame-by-frame batches.
  * Displays the centered overlay card (#cases-loading-overlay) with the spinning
    logo, "Déchargement des cases...", live percentage (0% to 100%), unloaded
    case counter, and real-time progress bar until all markers are removed.
- Updated app name and internal version to "Plans-Tournees_V0811260743" (versionCode="31").
================================================================================
