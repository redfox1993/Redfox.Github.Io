# Redfox Testseiten

Öffentliche, statische Testseiten. Jede Anwendung liegt in einem eigenen Unterordner.

- `haikyuu/`: Haikyu Testlabor mit 153 Charakteren, Erinnerungen, Potential-Sets, Resonanzattributen und kontrolliertem Tanaka-Bufftest.

## GitHub Pages aktivieren

Settings → Pages → Build and deployment → Source: **Deploy from a branch** → Branch: **main**, Ordner **/(root)** → Save.

Die von GitHub angezeigte Website-Adresse enthält derzeit den Repository-Namen `Redfox.Github.Io`. Die Haikyu-Seite ist darunter im Ordner `haikyuu/` erreichbar. Alle Links sind relativ und funktionieren auch nach einer Umbenennung des Repositorys.

## Umfang und Daten

Die Seite enthält die für die Oberfläche benötigten extrahierten Charakterdaten und läuft ohne Backend. Sie ist öffentlich. APK-Dateien, native Bibliotheken und Analyse-Zwischendateien sind nicht enthalten.

Noch keine vollständige Matchsimulation: aktive Kampfskillketten, automatische Cooldown-Fortschreibung und Angriffsergebnisse sind nicht vollständig rekonstruiert. Der Tanaka-Test benötigt ausdrücklich vorgegebene Ereignisse und Cooldown-Entscheidungen.

Die veröffentlichte HTML-Datei entspricht dem mit 104 Tests sowie Desktop-/Mobil-Browsertests geprüften Build. Herkunft und Versionsstand stehen in `haikyuu/build-info.json`.

## Weitere Seiten

Neue Projekte als weitere Ordner neben `haikyuu/` hinzufügen und auf der Startseite verlinken. Für Updates am Haikyu-Testlabor nur dessen Dateien ersetzen.

## Manuelle Buffs

Unter „Manuelle Buffs“ stehen 8.824 originale APK-Konfigurationseinträge zur Verfügung. Suche mit Buff-ID, Attribut oder direkt verknüpftem Skillnamen, wähle ein manuelles Ziel und aktiviere mehrere unterschiedliche Buffs. Die Liste bleibt über manuell weitergeschaltete Ballwechsel bestehen; einzelne Einträge lassen sich entfernen. Doppelte ID/Ziel-Paare sind gesperrt. Diese Vorgabe prüft keine Trigger/Cooldowns und verändert die Charakterwerte nicht. Automatische Wirkungsverrechnung, Stapelung und Ablauf bleiben ungeklärt.
