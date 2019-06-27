# mds-zonen – Policyvorschläge für den Umgang mit Scootersharern

Hier werden öffentlich der Arbeitsstand mit den `Service Areas` gemäß [Mobility Data Specification](https://github.com/CityOfLosAngeles/mobility-data-specification) und die von der Digitalen Agenda beigetragenen Vorschläge für Vereinbarungen mit E-Scooter-Sharinganbietern festgehalten.

## Die Zonen

In [restricted.geojson](restricted.geojson) und [preferred.geojson](preferred.geojson) sind derzeit die Geometrien der `Service Areas` festgehalten, die den Typ `restricted` (Mietbeginn und -Ende hier nicht möglich) und `preferred_pick_up`/`preferred_drop_off` haben. Letztere sind im ersten Aufschlag räumlich identisch.

Der Datensatz ist noch _kein_ valides JSON-Objekt wie sie von der MDS-Schnittstelle ausgespielt werden würde.

## Die Policy-Vorschläge als Boilerplate-Texte

Hier finden sich der [allgemeine Teil](01_Allgemeiner_Teil.md) und die [technischen Wünsche](02_Technische_Wuensche.md) für die Anbieter. Die Texte sind Vorschläge der [Geschäftsstelle Digitale Agenda (Z/DA)](https://www.ulm.de/leben-in-ulm/digitale-stadt/geschaeftsstelle-digitale-agenda) bei der Zentralstelle des Oberbürgermeisters der Stadt Ulm. _Sie sind kein vollständiger Vereinbarungstext und stellen **nicht** sämtliche Wünsche der Stadt Ulm an die Mobilitätsdienstleister dar!_ Sie dürfen und sollen jedoch als Vorlage für Dritte dienen und stehen als Arbeit der öffentlichen Hand im öffentlichen Interesse unter der [Unlicense](LICENSE).
