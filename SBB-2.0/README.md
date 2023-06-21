# SBB 2.0

Wahrschienlich kennst du schon die SBB Mobile App und dessen Möglichkeit, nach Verbindungen zu suchen.
Das Ziel dieser Aufgabe ist es, eine Web-App zu erstellen, welche genau das kann. <br>
[Opendata.ch](https://opendata.ch) stellt dazu [Swiss Public Transport API](https://transport.opendata.ch/) in Form einer RESTful-API zur Verfügung. <br>

### Aufgabenbeschreibung

Deine Aufgabe ist es, mithilfe der oben genannten API und einer von dir frei gewählter Frontend-Technologie (z.B. Angular, Vue.js oder einfach Plain JS) eine eigene Version einer solcher App zu erstellen. <br>

###Die Anforderungen sind:
#### Priorität 1
- Der Benutzer muss einen Abfahrtsort und einen Ankunftsort eingeben können.
- Der Benutzer muss das Abreisedatum, bzw. das Ankunftsdatum eingeben können.
- Die App soll mit den oben genannten Angaben eine Liste von den nächsten 10 Verbindungen zurückliefern und diese ansprechend mit allen wichtigsten Infos (Abfahrtszeit, Gleis, Zug-NR etc.) anzeigen.

#### Priorität 2
- Beim Angeben des Abfahrts-/Ankunftsortes soll validiert werden, ob die Station/Haltestelle existiert, bevor nach Verbindungen gesucht wird.
- Beim Angeben des Abfahrts-/Ankunftsortes soll beim tippen eine Autocomplete-Option vorhanden sein, die dem Benutzer hilft, die passende Station/Haltestelle zu finden.

#### Priorität 37
- Nach der Auswahl einer Verbindung sollen genauere Informationen angezeigt werden (Jede Station/Haltestelle, bei der man vorbeifahrt.)
- Nach der Auswahl einer Verbindung soll beim Abfahrtsort & Ankunftsort eine Karte angezeigt werden, welche zeigt, wo die Station/Haltestelle sich befindet (Google Maps API)


