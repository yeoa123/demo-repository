# Projekt mit SFML bauen

#### SFML = simple fast multimedia library
- library ist quasi eine art liste aus funktionen + variablen die du benutzen kannst, und die dann komplizierte dinge in einem tieferen Level machen
- tieferes level = grafikkarte bzw maschinen level (also zeug was nicht interessiert wenn man einfach schnell ein fenster machen will)
- besteht aus 5 modulen (audio graphic network system window)

#### API = application programming interface
- ist die schnittstelle mit der wir auf die SFML zugreiffen

#### SFML und VS
- was du dir an SFML runtergeladen hast sind im prinzip mehrere Sachen:
    - /include : header dateien, ist im prinzip einfach nur eine Aufzähung von Funktionen mit Erklärung. kannst du mal überfliegen um ein Gefühl zu bekommen. diesselbe information ist eigentlich aber auch im internet auf der API seite (dazu komm ich später)
    - /bin : kompliziert
    - /lib : kompliziert
    - /examples : wie der name sagt (sehr cool zu lesen aber erst nachdem du basics kannst, wie zB fenster öffnen)
- wie du VS dazu bekommst zu kapieren dass es SFML benutzen soll: https://www.sfml-dev.org/tutorials/2.5/start-vc.php#creating-and-configuring-a-sfml-project
- den scheiss musst du ziemlich genau lesen, aber eigentlich ists easy af.
- vielleicht ist es doch die 64bit version aber probier erstmal so
- wichtig: in vs gibt es auf dem normalen bildschirm die debug/release konfiguration (obere leiste links neben dem grünen start button) !!!!!!!!!!
- dort musst du debug und x64 einstellen! wenn du dann in den einstellungen rummachst, musst du auch immer drauf achten das du die einstellungen für debug & 64bit machst! sonst machst du einstellungen aber du kannst nciht sehen obs geht weil du eine andere konfig benutzt
- auch hilfreich: https://www.youtube.com/playlist?list=PL21OsoBLPpMOO6zyVlxZ4S4hwkY_SLRW9

#### wenn SFML läuft
- entweder youtube playlist von da oben gucken
- das durchlesen: https://www.sfml-dev.org/tutorials/2.5/
- examples durchlesen (auf deinem pc)

#### wenn du genaue fragen hast
- https://www.sfml-dev.org/documentation/2.5.1/modules.php
- dort kannst du die module durchsuchen. die rangordnung ist so: modul (oberstes) -> namespaces, classes, enums (einzelteile)
- classes -> funktionen und variablen
- enums -> aufzählungstypen (zB rot, grün, gelb)
- namespaces -> kompliziert zu erklären aber eigentlich total einfach und manchmal useless. ist nur zum scheibarbeit sparen, hat keine logische funktion
