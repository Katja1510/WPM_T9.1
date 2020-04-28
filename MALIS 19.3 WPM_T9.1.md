# MALIS 19.3 WPM_T9.1
## MALIS 19.3 WPM_T9.1: Data Science / Data Librarianship / ITPraxis

### Beispiel A: Revision mit Excel – keine glückliche Lösung

#### 1. Gründe für die Revision
Ich arbeite als Bibliotheksleitung in der Bibliothek des Instituts für Archäologische Wissenschaften an der Ruhr-Universität Bochum. Sowohl das Institut als auch die Bibliothek setzen sich aus den beiden Fachbereichen der Klassischen Archäologie und der Ur- und Frühgeschichte zusammen. 

Eine Revision ist eine Methode, um festzustellen, ob alle Titel, die im OPAC für unsere beiden Fachbereiche eingepflegt wurden, auch im Regal vorhanden sind oder ob die im Regal vorhandenen Titel korrekt in den OPAC eingepflegt wurden. Die Revision erfolgt nach Möglichkeit alle zwei Jahre, damit ich als Bibliotheksleitung auf diese Weise einen Überblick über den momentanen Bestand erhalte und fehlerhafte OPAC-Eingaben sowohl kontrollieren als auch beseitigen kann. Um Fehlbestände handelt es sich, wenn Metadaten zu einem Titel im OPAC existieren, das Buch jedoch nicht im Regal steht und auch kein anderer Verbleib feststellbar ist. Fehlbestände sollten im OPAC kenntlich gemacht werden, damit die Nutzer darüber informiert sind, dass ein bestimmtes Buch in der Archäologischen Bibliothek nicht zur Verfügung steht und ggf. nachgekauft wird.

Für die Nutzer einer Bibliothek ist die Beseitigung von Fehlerquellen im OPAC essentiell, da sich die meisten Nutzer ausschließlich über den OPAC informieren. Dort suchen sie ihre Literatur und erfahren den Standort des benötigten Titels in der jeweiligen Bibliothek. Wenn also ein vorhandenes Buch nicht im OPAC eingetragen ist, existiert es für die Nutzer online nicht und sie können es dementsprechend nicht für ihre Forschung verwenden. Aus diesem Grund sollten diese Titel bei der Revision auffallen und nachgetragen werden. 

#### 2. Metadatenverarbeitung mit Excel
Das Einpflegen der Metadaten in den OPAC geschieht an der Ruhr-Universität Bochum mit Hilfe der Programme Aleph und Sisis. Für die Revision wird ein Teil dieser Metadaten aus Aleph und Sisis herausgezogen und als Excel-Dateien von der Universitätsbibliothek zur Verfügung gestellt. In den beiden Excel-Dateien – für jeden Fachbereich eine – sind Metadaten einzelner Titel wie Autor, Titel, Jahrgang, Verlag und Signatur vorhanden. Für die Revision müssen die Daten dann aufsteigend nach der Signatur sortiert werden, weil die Signatur meinen Hilfskräften und mir mitteilt, an welcher Stelle im Regal sich das betreffende Buch befindet. Die Regale müssen wir mit dieser Liste kontrollieren, damit wir das betreffende Buch in die Hand nehmen und überprüfen können, ob es vorhanden ist oder zum Fehlbestand gezählt werden muss.

Excel besitzt die Vorteile, dass - allgemein gesprochen - Daten umgeformt, kombiniert und mit ihnen in Formeln gerechnet werden können. Es ist also für Tabellenkalkulationen entwickelt worden, aber nicht, um mit großen Dateien und Datenmengen zu arbeiten. Die Datenverwaltung ist in diesem Programm nur „Mittel zum Zweck“, um überhaupt mit den Daten zu rechnen und Kalkulationen vornehmen zu können. Dies ist das vorrangige Ziel von Excel. Ein großer Nachteil des Programms stellt dagegen die daraus resultierende lange Bearbeitungszeit bei großen Datenmengen dar. Dass Dateien immer nur mit Excel selbst bearbeitet werden können, und dass es bei stetig wachsenden Datenmengen an seine Bearbeitungsgrenzen stößt, sind ebenfalls nicht unbeträchtliche Nachteile des Programms. Denn in den Dateien der beiden Fachbereiche werden keine Daten gelöscht, sondern stetig neue Einträge hinzu geschrieben, da wir aus forschungsgeschichten Gründen selten bzw. gar keine alten Bücher „entsorgen" - dafür aber stetig neue Literatur hinzukaufen.

#### 3. Wiedergabe der Metadaten in Excel

Im Falle der letzten Revision ist aufgefallen, dass die Metadaten zwar korrekt wiedergegeben werden, aber nicht optimal für den Zweck der Revision sortiert werden können – oder ich konnte sie für mich nicht so sortieren, dass ich effizient mit ihnen arbeiten konnte. Eine Sortierung der Daten kann für meine Arbeitsaufgabe nicht nach Autorname erfolgen, da die Bücher im Regal nicht nach den Autoren, sondern nach alphanumerischen Signaturen aufgestellt sind. In Excel kann nur die komplette Signatur alphabetisch sortiert werden, notwendig wäre aber eine alpahbetische Sortierung nach einzelnen Unterblöcken der Signatur. Um eine effiziente Sortierung der Signaturen zu erreichen, müsste ich in Excel alle betreffenden Daten manuell abändern, damit die Signaturen in der richtigen Abfolge erscheinen.

##### Beispiel 1a) Ausgabe der Sortierung der Signaturen der Klassischen Archäologie in Excel:

| Signatur   | Autor              |  Titel      |
| --------   | -------------------|------------ |
|C Baal a 1  | Harding, Gerald    | Baalbek     |
|C Baal a 2  | Hampdor, Albert    | ¬L'acropole de Baalbek
|C Baal a 3  | Sader, Hélène      | Baalbek
|C Baal b 1  |	Ess, Margarete    | Baalbek
|C Baal b 2  |	Ess, Margarete    | Baalbek - Heliopolis
|C Baal b 3  |	Collart, Paul 	  | ¬Le petit autel de Baalbek
|C Baal d 	 | Frauberger, Hein   |¬Die Akropolis von Baalbek
|C Baby a 1  |	Koldewey, Robert  |¬Das wiedererstehende Babylon
|C Baby a 2  |	Oates, Joan 	  | Babylon
|C Baby a 3  |	Babelon, Ernest   | Manuel d'archéologie orientale

##### Beispiel 1b) Optimale Ausgabe der Sortierung der Signaturen der Klassischen Archäologie (und damit gleichzeitig, in welcher Reihenfolge die Aufstellung der Bücher im Regal erfolgt)

| Signatur   | Autor              |  Titel      |
| --------   | -------------------|------------ |
|C Baal a 1  | Harding, Gerald    | Baalbek     |
|C Baal a 2  | Hampdor, Albert    | ¬L'acropole de Baalbek
|C Baal a 3  | Sader, Hélène      | Baalbek
|C Baby a 1  |	Koldewey, Robert  | ¬Das wiedererstehende Babylon
|C Baby a 2  |	Oates, Joan 	  | Babylon 
|C Baby a 3  |	Babelon, Ernest   | Manuel d'archéologie orientale
C Baal b 1   |	Ess, Margarete    | Baalbek
|C Baal b 2  |	Ess, Margarete    | Baalbek - Heliopolis
|C Baal b 3  |	Collart, Paul 	  | ¬Le petit autel de Baalbek
|C Baal d 	 |  Frauberger, Hein  |¬Die Akropolis von Baalbek

##### Beispiel 2a) Ausgabe der Sortierung der Signaturen der Ur- und Frühgeschichte in Excel:

| Signatur   | Autor              |  Titel      |
| --------   | -------------------|------------ |
| Fa 1 	     | Scollar, Irwin 	  | Archäologie aus der Luft
| Fa 10 	 | Sellnow, Irmgard   | Grundprinzipien einer Periodisierung der Urgeschichte
| Fa 100 	 | Herrmann, Joachim  | ARCHAEOLOGISCHE DENKMALE UND UMWELTGESTALTUNG
| Fa 111 	 | Gardin, Jean-Claude| ARCHAEOLOGICAL CONSTRUCTS, AN ASPECT OF THEORET. ARCHAEOLOGY

##### Beispiel 2b) Optimale Ausgabe der Sortierung der Signaturen der Ur- und Frühgeschichte (und damit gleichzeitig, in welcher Reihenfolge die Aufstellung der Bücher im Regal erfolgt)
 
| Signatur   | Autor              |  Titel      |
| --------   | -------------------|------------ | 
| Fa 1 	     | Scollar, Irwin 	  | Archäologie aus der Luft
| Fa 2	     | Preuss, Joachim 	  | Von der archäologischen Quelle
| Fa 3 	     |                    | Bericht von der          Restaurierung und Konservierung 
| Fa 10	     |  ...			      | ...
| Fa 11	     |  ...			      | ...


#### 4. Arbeiten mit den ausgegebenen Metadaten
Da bei der manuellen Änderung der Sortierung zu viel Zeit verloren geht und es sich dabei zusätzlich um eine gehaltlose Arbeit handelt, nehme ich die manuelle Sortierung gar nicht erst vor und belasse die Liste in der Sortierung, die Excel ausgibt. Der Nachteil dieser ineffizienten Sortierung ist ein ebenso ineffektiver Arbeitsprozess, da während der Revision die eigentliche Reihenfolge am Regal unterbrochen werden muss, um die Reihenfolge der Signaturen in der Liste einzuhalten. So müssen Wege doppelt abgelaufen werden, um die Titel zu überprüfen, die nicht in der gewünschten Reihenfolge in der Excel-Tabelle stehen. Dieser Aufwand kostet zu viel Zeit und die Gefahr von Fehlern ist groß, da Signaturen u. U. doppelt kontrolliert, dafür einige jedoch versehentlich ausgelassen werden, weil nicht mehr ersichtlich war, an welcher Stelle am Regal die Kontrolle unterbrochen wurde. So ist viel Potential verschenkt, da diese unnötigen Wege und Fehler mit der richtigen Sortierung der Signaturen vermeidbar wären.

#### 5. Sind Datenbanken die bessere Alternative?
Im Hinblick auf das fehlende Potential bei Excel-Tabellen bezüglich der Aufgabenstellung „Revision“ wäre eine Datenbankanwendung eventuell die bessere Alternative, um größere Datenmengen verarbeiten zu können. Da der Vorgang der Revision alle zwei Jahre durchgeführt wird und innerhalb dieser Zeitspanne immer wieder neue Metadaten in den OPAC eingetragen werden, wächst auch die Datenmenge für die Revision stetig an. Dass bei einer Datenbankanwendung nachhaltigere Anwendungen wie das Anlegen, Speichern, Abfrage und Zugriff auf die Metadaten möglich sind, ist für das Vorhaben der Revision ein klarer Pluspunkt. Während Excel mit der Bearbeitung von großen Datenmengen schnell an die Grenzen seiner Leistungskapazität gerät, sind Datenbanken sogar darauf ausgelegt, wachsende Datenmengen aufzunehmen und eine rasche Verarbeitung zu sichern. So dauert die Speicherung und Bearbeitung von Daten nicht so lang, wie es bei Excel-Dateien oftmals der Fall ist. Wobei darauf hingewiesen werden soll, dass Excel kein schlechtes Programm ist, sondern lediglich darauf abzielt, mit den vorhandenen Daten Kalkulationen durchzuführen. Auch liegt eine Datenbankanwendung auf dem Server, der von sich aus größeres Potential zu einer schnelleren Bearbeitung mit sich bringt, weil er eine größere Rechenkapazität als der Arbeits-PC oder Laptop besitzt, auf dem das Excel-Programm gespeichert ist. 

Für die Revision in der Archäologischen Bibliothek bedeutet es, dass alle bereits vorhandenen Daten wieder verwendbar sind und sich neue Daten durch einen automatischen Import problemlos in die vorhandene Struktur einpflegen lassen oder sich selbst in die Struktur eingliedern, ohne dass man als Nutzer eingreifen muss. Die Datei soll also fortlaufend erweiterbar sein, da die vorhandenen Metadaten nie gelöscht, sondern stetig neue hinzukommen werden. Die Anforderung der benötigten Datenbankanwendung für meine Bedürfnisse ist die effektive Sortierung der Metadaten nach der alphanumerischen Signatur in der gewünschten Reihenfolge, so dass eine effektivere Arbeitsweise als bisher möglich ist.

### Beispiel B: Automatisierungsprozesse bei der Rechnungsbearbeitung (paperless office)
#### 1. Einleitung
Am Institut für Archäologische Wissenschaften in Bochum werden alle eingehenden Rechnungsbeträge im Sekretariat vorkontiert und die bearbeitete Rechnung an die Finanzbuchhaltung der Universitätsverwaltung per Hauspost gesendet. Die Rechnung muss im Original vorhanden sein, damit sie bezahlt werden kann. Elektronische Rechnungen, z. B. Pdf-Dokumente als Mail-Anhang zählen nicht als Originalrechnung und dürfen dementsprechend nicht bearbeitet werden. Der gesamte Prozess von der Rechnungsbearbeitung ausgehend, über die Vorkontierung im Institut und zur endgültigen Verbuchung des Betrags auf das korrekte Konto in der Universitätsverwaltung bis hin zur abschließenden Zahlung des Rechnungsbetrags an den Lieferanten ist veraltet und kann mitunter einige Wochen dauern.

#### 2. Wünschenswerter Zustand
Für die Rechnungsbearbeitung wünsche ich mir sowohl eine Vereinfachung als auch eine Beschleunigung durch Automatisierungsprozesse, durch ein elektronisches Datenmanagement. Beispielsweise eine Umstellung auf ausschließlich elektronische Rechnungen, da diese schnell zugesendet, abgespeichert und wieder aufgerufen werden können. Auch die Weiterverarbeitung der Rechnung ist effizienter, da weder eine Bearbeitung von Papierrechnungen mit Stempel und Vorkontierungsblatt nötig ist, noch Wege zum Sekretariat oder Dekanat, die die Vorkontierung vornehmen müssen, und auch keine Transportwege durch die Hauspost zur Verwaltung, wo die Beträge dann erst richtig verbucht werden. Die Prozesse können auf diese Weise abgekürzt und Rechnungsbeträge schneller verbucht werden. So erhält der Lieferant nicht erst nach ein paar Wochen, sondern bereits nach wenigen Tagen sein Geld. Die Arbeitsvorgänge sind so innerhalb der Universität effizienter, als auch zwischen Lieferant und Besteller. Hinzu kommt, dass elektronische Rechnungen nachhaltiger in Bezug auf die Umwelt sind, weil der Lieferant keine Papierrechnung mehr ausdrucken muss und auch der Transport der Originalrechnungen mit der Hauspost entfällt. Dies ist ein sowohl zeitlicher als auch umweltschonender Vorgang, da unser Institut nicht mehr am RUB-Campus ansässig ist, sondern vor 10 Jahren in die Bochumer Stadtmitte gezogen ist und der RUB-Fahrdienst die Post anliefern und abholen muss.

#### 3. Vorschlag für Entwicklungspotential
Es existieren Buchhaltungsprogramme wie z. B. Collmex, die elektronische Rechnungen automatisch einlesen. Beim Buchungsvorgang zeigt das Programm das betreffende Pdf-Dokument und den zu verbuchenden Betrag an. Dann schlägt das Programm eine Buchung zur Rechnung vor – welcher Betrag soll auf welches Konto gebucht werden? Wenn der Anwender den Vorschlag bestätigt, wird die Buchung vollzogen und der Lieferant erhält seine Zahlung, ohne dass mehrere Wochen vergehen und die Umwelt unnötig belastet wird. 

