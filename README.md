# IMCM-3BHK

## Einleitung

### Markdown

*Markdown* ist eine Auszeichhnungssprache (*Markup Language*). Mit Auszeichnungssprachen wird Text strukturiert. Einige Markup-Languages sind z.B.:

- HTML (*Hypertext Markup Language*)
- XML (*Extennsible Markup Language*)
- MD (*Markdown*)
- YAML (*YAML Ain´t Markup Language bzw. Yet        another Markup Language*)

Markdown ist heutzutage weit verbreitet, insbesondere für die Erstellung von Dokumentationen, Blogs und Readme-Dateien in Softwareprojekten. ReadME.md-Dateien ist also die erste Anlaufstelle für Informationen über ein Projekt.

Um ein Git-Repository zu erstellen, sind folgende Schritte notwendig:

- im gewünschten Verzeichnis im Terminal(bzw. CLI - *Command Line Interface*) den Befehl `git init` ausführen, um ein neues
  Git-Repository zu erstellen.
  
> **Einschub zur Installation von Git:**
> Falls bei der Eingabe von `git init` eine Fehlermeldung erscheint, dass der Befehl nicht gefunden wurde, ist Git wahrscheinlich nicht installiert.
> In diesem Fall kann Git von der offiziellen Website [https://git-scm.com/](https://git-scm.com/) heruntergeladen und installiert werden. Bei der Installation wird der Befehl der Umgebungsvariable **Path** hinzugefügt. Darin sind die Bezeichnungen aller Programme enthalten, die im Terminal aufgerufen werden können.

- dann in GitHub-Desktop das lokale Repository hinzufügen(*File* -> *Add Local Repository*)
-nun kann über die Schaltfläche **Commit to master** und **Push origin** die Änderungen ins entfernte Repository auf GitHub übertragen werden.

## Statische und dynamische Websites

Wenn wir eine Anfrage stellen, stellt unser Computer die Anfrage an einen DNS-Server, der die Domain in die entsprechende IP-Adresse auflöst, damit die Verbindung zum richtigen Server hergestellt werden kann. Danach schickt der Computer eine Https-Request an den Server, um die gewünschten Daten abzurufen. Der Server antwortet mit einer Https-Response, die die angeforderten Daten enthält. Zurückgeschickt wird die Https-Response an den Computer, der die Daten dann entsprechend verarbeitet und darstellt.

![Funktionsweise von statischen Websites](image.png)
*Abbildung: Funktionsweise von statischen Websites*

In den 1990er Jahren waren die meisten Websites statisch. Das bedeutet, dass der Inhalt der Seiten fest auf dem Server gespeichert war und bei jeder Anfrage unverändert an den Client gesendet wurde. Statische Websites sind einfach zu erstellen und benötigen keine serverseitige Verarbeitung, eignen sich jedoch nur für Inhalte, die sich selten ändern.
Inhalte wurden als html-File auf dem Server gespeichert und bei jeder Anfrage unverändert an den Client gesendet.
