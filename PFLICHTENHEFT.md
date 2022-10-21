# Pflichtenheft des Praxis Niederrhein, Inc.

Die "Praxis Niederrhein, Inc.", ein pharmazeutisches Unternehmen aus Krefeld, hat uns gebeten, eine neue Website für sie zu erstellen.

Das Zielpublikum sind Patienten aller Altersgruppen, und sie haben uns auch eine Liste von  technischen, als auch  inhaltlichen  Anforderungen gegeben, die die Website erfüllen soll.

Die Frist für dieses Projekt läuft bis spätestens Donnerstag, den 20. Oktober.

# Technischen Anforderungen

Das Unternehmen hat uns eine Reihe von technischen Anforderungen gestellt, die ihre Website erfüllen sollte: 
- die Website sollte eine schnelle Ladezeit haben
- eine Verfügbarkeit von mehr als 99,5%
- keine Fehler
- die Website sollte statisch sein
- die Website sollte über eine Domain erreichbar sein
- eine benutzerfreundliche Oberfläche
- die Website sollte nur mit HTML, CSS und Javascript erstellt werden

# Inhaltliche Anforderungen

Zu den inhaltlichen Anforderungen gibt es ein paar Anleitungen und Ideen, wie sich die Praxis Niederrhein ihre Website vorstellt. Die Website sollte Folgendes enthalten:

- Videos und Bilder von der Praxis
- ein neues Logo
- wie günstig ihre Preise sind
- wie freundlich die Mitarbeiter sind
- eine "Kontakt"-Seite mit einem Formular und einer Adresse 
- eine "Leistungen"-Seite, auf der man sehen kann, was das Unternehmen seinen Kunden bieten kann
- eine "Home"-Seite, die den Besucher willkommen heißt 
- eine Farbpalette, die auch die Farben '#2ea3f0' ("Picton Blue") und '#004aad' ("Cobalt) enthält
- eine Kopfzeile und eine Fußzeile, die Informationen wie die sozialen Medien, die Qualität der Dienstleistungen, die Erschwinglichkeit der Preise und die Freundlichkeit des Personals enthält.


# Das Konzept

Der Kunde wünschte sich, dass die Website einige Anforderungen erfüllt (z. B. eine schnelle Ladezeit, sie sollte statisch sein und nur mit HTML und CSS erstellt werden), sowie obligatorische ästhetische Elemente (z. B. Farben wie "Picton Blue" und "Cobalt").

Wir wollen, dass die Website ein minimalistisches Aussehen hat, aber dennoch einige Elemente von Professionalität und "moderner Architektur" für die drei Seiten (Home, Leistungen und Kontakt) aufweist.
### Das Format der Seiten

Das folgende Design soll auf jeder Seite als Standardvorlage implementiert werden. Je nach Kontext und Zweck dieser Seiten sollte der Inhalt implementiert, geändert oder sogar entfernt werden: 

- Das neu gestaltete Logo für den Kunden sollte in eine Navigationsleiste eingebunden werden, die auch drei verschiedene Buttons enthält, die beim Anklicken jeweils auf die entsprechende Seite führen sollen (Home, Leistungen und Kontakt). Diese Buttons sollten aber auch einem runden Rahmen haben - das kann durch den CSS-Befehl "border-radius" erreicht werden. Die dominierenden Farben des Logos sollten die vom Kunden vorgegebenen sein ("Cobalt" und "Picton-Blue").

- Die Navigationsleiste sollte sich ganz oben auf jeder Seite befinden, aber nicht an einer festen Position, so dass sie auch nach dem Herunterscrollen der Seite sichtbar ist.

- Unter der Navigationsleiste (die ein wenig transparent sein sollte, und einen Schatten auf den unteren Rand werfen sollte) muss ein Hintergrundbild sein, das uns von der Praxis Niederrhein, Inc. zur Verfügung gestellt wird. Dieses Hintergrundbild kann jedoch später auch zu einem Hintergrundvideo werden (wenn das Team dies für ästhetisch ansprechender hält).

- In der Mitte des Bildschirms sollte ein großer Begrüßungstext stehen (z. B. Praxis Niederrhein), der einen besonderen Effekt erhält, wenn man mit dem Mauszeiger darüberfährt.

- Am unteren Ende der Seite sollte sich eine Fußzeile befinden, mit zusätzlichen Buttons für die Navigation zwischen allen Seiten, dem Copyright und Links zu den sozialen Netzwerken des Unternehmens, genau so, wie es der Kunde wollte.
Für Leistungen und Kontakt sollte die Fußzeile gleich sein und nur die zusätzlichen Navigationsschaltflächen, die sozialen Netzwerke des Unternehmens und das Copyright enthalten. 

### Die HOME-Seite

- Vor allem die Home-Seite sollte der Blickfang sein. Hier könnten wir, wie oben erwähnt, ein Hintergrundvideo anstelle eines statischen Hintergrundbildes verwenden. Der Grund für diese Entscheidung ist, das minimalistische Design, das wir gewählt haben, zu kompensieren.  

- Unterhalb des großen Begrüßungstextes in der Mitte sollte noch ein zusätzlicher Button, ebenfalls mit rundem Rahmen, implementiert werden, der den Besucher beim Anklicken auf die Leistungen-Seite weiterleiten soll. Diese spezielle Button könnte mit einem Text versehen werden, ähnlich wie "Erfahren Sie über uns".

- Ebenfalls nur für diese Seite sollte die Fußzeile viel mehr Informationen enthalten als die Fußzeile von Leistungen und Kontakt. Dabei sollte erwähnt werden, wie gut ihre Dienstleistungen sind, wie niedrig ihre Preise sind und wie freundlich und professionell ihr Personal ist. Der Rest ist der Kreativität unseres Teams überlassen.

![Concept1](concept1.png)
### Die LEISTUNGEN-Seite

- Für diese Seite benötigen wir eines der vielen Bilder, die uns der Kunde zur Verfügung gestellt hat, das wir als Hintergrundbild verwenden werden. 

- Der große Text in der Mitte sollte in "Wer sind wir?" geändert werden, und anstelle der Button darunter, die wir normalerweise auf der Home-Seite haben, werden wir einen Container mit einem runden Rand erstellen. Innerhalb dieses Containers werden wir alle Dienstleistungen erwähnen, die die Praxis Niederrhein, Inc. ihren Kunden anbietet.

- Die Ränder dieses Behälters sollten ebenfalls einen glatten Schatten ("border-box" in CSS) aufweisen, um einen "dreidimensionalen Effekt" zu erzeugen.

- Am unteren Ende der Seite sollte die Fußzeile stehen, deren Gestaltung am Ende [dieses Abschnitts](#das-format-der-seiten) beschrieben wird.

![Concept2](concept2.png)
### Die KONTAKT-Seite

- Der große Text in der Mitte sollte sich jetzt links in der Mitte der Seite befinden, und zwar unter "Kontakt".

- Direkt neben diesem Text sollte sich auf der rechten Seite ein leicht transparentes Kontaktformular befinden.  

- Jeder einzelne Abschnitt sollte einen Platzhalter haben (wie zum Beispiel "Name und Vorname", "Telefon", "E-Mail" und "Ihre Nachricht"), der auch wieder verschwinden sollte, sobald der Benutzer etwas eintippt. Wenn der Benutzer auf einen Abschnitt klickt, sollten die Ränder dieses Abschnitts auch ein schwaches Licht in der Farbe Picton-Blau nach außen abgeben.   

- Unten rechts in diesem Kontaktformular sollte eine Button "Senden" in der Farbe "Cobalt" zu sehen sein. Sie sollte jedoch auch ihre Farbe in "Picton-Blau" ändern, wenn der Besucher mit der Mauszeiger über ihr schwebt.

- Ähnlich wie bei der Leistungen-Seite werden wir auch ein Hintergrundbild verwenden, und die Fußzeile sollte auch identisch sein. 

![Concept3](concept3.png)
