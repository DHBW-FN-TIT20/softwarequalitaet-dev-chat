# Grundwissen und Begriffe
## Definieren Sie die Begriffe Software-Qualität und Qualität und grenzen Sie diese gegeneinander ab.
### Software-Qualität
"degree to which a software product satisfies stated and implied needs when used under specified conditions" (ISO/IEC 25010:2011, S. 17)
Deutsch (übersetzt):
"Grad, in dem ein Softwareprodukt festgelegte und implizierte Anforderungen erfüllt, wenn es unter bestimmten Bedingungen verwendet wird" (ISO/IEC 25010:2011, S. 17)

#### Wesentliche Merkmale für die Beurteilung von Software-Qualität [Buch](https://books.google.de/books?id=XZEuBAAAQBAJ&lpg=PR5&ots=gMqkFldkYl&dq=Software%20qualit%C3%A4t&lr&hl=de&pg=PA7#v=onepage&q=Software%20qualit%C3%A4t&f=false)
- Qualitätssicht extern (Anwender): Funktionalität, Laufzeit, Zuverlässigkeit, Benutzbarkeit
- Qualitätssicht intern (Entwickler): Wartbarkeit, Transparenz, Übertragbarkeit, Testbarkeit, 

##### Funktionalität
- In welchem Maß wird der angeforderte Funktionsumfang tatsächlich erreicht?
- > Gründe:
  > Zeitmangel, ungenaue Anforderungen, Software-technische Probleme (Architektur / Sprache), Implementierungsfehler (Bugs)

##### Laufzeit (Performance)
- Echtzeitsysteme: Harte Definition / Kritisches Qualitätsmerkmal
- Jede Software hat (implizite) Laufzeit-Anforderungen
- Gleichrangige Bedeutung mit Funktionalität

##### Zuverlässigkeit (Reliability)
- Sicherheitskritische Systeme
- Zuverlässigkeit ergibt sich aus einer Kombination von Software-Qualitätsmerkmalen

##### Benutzbarkeit (Usability)
- Mensch-Maschine-Schnittstelle
- Relevanz abhängig von der Zielgruppe (Nische (Experten) / Massenmarkt)

##### Wartbarkeit (Maintainability)
- Für langlebige Software
- Wichtiger Aspekt für längere Konkurrenzfähigkeit am Markt
  
##### Transparenz
- Auf welche Art und Weise ist die nach außen sichtbare Programmfunktionalität intern umgesetzt?
- Code-Kompliziertheit
- Grad der Unordnung eines Programms = Software-Entropie

##### Übertragbarkeit
- Wie einfach ist es, die Software in eine andere Umgebung zu übertragen?

##### Testbarkeit
- Ergibt sich aus Komplexität, Verfügbarkeit von Daten/Hardware (Build for Test)

### Qualität
"Grad, in dem ein Satz inhärenter Merkmale eines Objekts Anforderungen erfüllt" (ISO/IEC 9000:2015, S. 17)

## Kano-Modell
- Modell zum systematischen Erringen der Kundenzufriedenheit
Fünf Ebenen:
### Basis-Merkmale =-
- Grundlegend und selbstverständlich, fallen nur bei Nichterfüllung auf (absolutes Minimum)
- Merkmale können mit der Zeit verschiedenen Kategorien zugeordnet werden
  - Begeisterungs-Merkmal -> Leistungs-Merkmal -> Basis-Merkmal (Gewöhnungseffekt)
- Merkmal-Zuordnung ist subjektiv
  - Merkmal kann gleichzeitig Basis- Begeisterungs- und Rückweisungs-Merkmal sein.
### Leistungs-Merkmale +=
- Dem Kunden bewusst, beseitigen Unzufriedenheit / schaffen Zufriedenheit abhängig vom Erfüllungsgrad
### Begeisterungs-Merkmale +=
- Nutzen-Stiftend
- Zeichnen das Produkt gegenüber der Konkurrenz aus (hebt sich darin ab)
- Differenz gegenüber kann gering sein, der Nutzen jedoch enorm (Bsp: Flüssige Bedienung von Software)
### Unerhebliche Merkmale ==
- Ohne Belangen für den Kunden
- Verursachen weder Zufriedenheit noch Unzufriedenheit
### Rückweisungs-Merkmale -=
- Verursachen Unzufriedenheit, jedoch bei Nichterfüllung nicht zu Zufriedenheit (bleibt neutral)

## 


## Warum ist Requirements Engineering essenziell für eine hohe Software-Qualität?