# IMCM-3BHK

## Einleitung

### Markdown

*Markdown* ist eine Auszeichhnungssprache (*Markup Language*). Mit Auszeichnungssprachen wird Text strukturiert. Einige Markup-Languages sind z.B.:

- HTML (*Hypertext Markup Language*)
- XML (*Extennsible Markup Language*)
- MD (*Markdown*)
- YAML (*YAML Ain´t Markup Language bzw. Yet        another Markup Language*)

Markdown ist heutzutage eine der beliebtesten Auszeichnungssprachen. Wenn eine README.md-Datei in einem GitHub-Repository vorhanden ist, wird diese automatisch auf der Startseite des Repositories angezeigt. Die README.md-Datei ist also die erste Anlaufstelle für alle, die sich über das Projekt informieren möchten.

Um ein Git-Repository zu erstellen, sind folgende Schritte notwendig:

- im gewünschten Verzeichnis im Terminal(bzw. CLI - *Command Line Interface*) den Befehl `git init` ausführen, um ein neues
  Git-Repository zu erstellen.
  
> **Einschub zur Installation von Git:**
> Falls bei der Eingabe von `git init` eine Fehlermeldung erscheint, dass der Befehl nicht gefunden wurde, ist Git wahrscheinlich nicht installiert.
> In diesem Fall kann Git von der offiziellen Website [https://git-scm.com/](https://git-scm.com/) heruntergeladen und installiert werden. Bei der Installation wird der Befehl der Umgebungsvariable **Path** hinzugefügt. Darin sind die Bezeichnungen aller Programme enthalten, die im Terminal aufgerufen werden können.

- dann in GitHub-Desktop das lokale Repository hinzufügen(*File* -> *Add Local Repository*)
-nun kann über die Schaltfläche **Commit to master** und **Push origin** die Änderungen ins entfernte Repository auf GitHub übertragen werden.

## Statische und dynamische Websites

In den 1990er Jahren wurden Websites überwiegend statisch erstellt. Inhalte wurden als html-File auf einen Webserver hochgeladen. Bei jedem Aufruf der Website wurde das html-File vom Server an den Browser des Nutzers übertragen. Die Inhalte waren also immer gleich, unabhängig davon, wer die Website aufrief.

![Funktionsweise von statischen Websites](image.png)
*Abbildung: Funktionsweise von statischen Websites*

Die Abbildung zeigt die Funktionsweise von statischen Websites. Zuerst muss der Domain-Name über das Domain Name System (DNS) in die IP-Adresse des Webservers aufgelöst werden (Schritt 1 und 2 in der Abbildung). Danach schickt der Client eine http-Anfrage an den entsprechenden Webserver und erhält von diesem eine http-Antwort, die überlicherweise zuerst die index.htmlenthält (Schritt 3 und 4).

Ab den 2000er Jahren setzten sich zunehmend dynamische Websites durch. Bei dynamischen Websites werden die Inhalte nicht mehr als fertige html-Files auf den Webserver hochgeladen, sondern in einer Datenbank gespeichert. Bei jedem Aufruf der Website werden die Inhalte aus der Datenbank abgerufen und in ein html-File eingebettet, das dann an den Browser des Nutzers übertragen wird. Die Inhalte können also je nach Nutzer unterschiedlich sein.


![alt text](image-1.png)

Die Abbildung zeigt die Funktionsweise von statischen Websites. Zuerst muss der Domain-Name über das DNS in die IP-Adresse des Webservers aufgelöst werden (Schritt 1 und 2 in der Abbildung). Danach schickt der Cleint eine HTTP-Anfrage an den entsprechenden Webserver und erhält von diesem eine HTTP-Antwort, die üblicherweise zuerst die index.html enthält (Schritt 3 und 4)

Ab den 2000er Jahren setzten sich zunehmend dynamische Websites durch. Bei dynamischen Websites werden die Inhalte nicht mehr ausschließlich als statische HTML-Dateien bereitgestellt, sondern dynamisch vom Server generiert, oft unter Verwendung von Datenbanken und serverseitigen Skriptsprachen wie PHP, Python oder Ruby. Bei jedem Aufruf der Website werden die Inhalte aus der Datenbank abgerufen und in ein html-File eingebettet, das dann an den Browser des Nutzers gesendet wird. Die Inhalte können also je nach Nutzer unterschiedlich sein.

VLOG = Video Blog;

BLOG = Weblog

Zu Beginn bestand das Web hauptsächlich aus statischen Websites, auf denen Inhalte nur vom Betreiber der Website erstellt und gepflegt wurden. Mit dem Aufkommen von Web 2.0 konnten Nutzer selbst Inhalte erstellen, kommentieren und teilen, wodurch das Internet interaktiver und dynamischer wurde. Damit sich Seiten auch von mehreren Menschen effizient nutzen ließen, wurden Technologien wie Content-Management-Systeme (CMS) entwickelt, die die gemeinsame Bearbeitung und Verwaltung von Inhalten erleichterten.

Der Ablauf der Seitenerstellung ist in der folgenden Abbildung dargestellt. Die URL-Auflösung mittels DNS-Anfrage funktioniert gleich wie bei statischen Websites (lila in der Grafik). Der Webserver braucht bei dynamischen Websites aber Unterstüzung durch eine serverseitige Programmier- bzw. Skriptsprache (z.B.: PHP, Python, JavaScript, usw.). Wenn der Webbrowser bzw. Webclient bei einem Restaurantbesuch als Gast gesehen wird, dann ist der Webserver der Kellner, der die Bestellung aufnimmt und sie an den Koch weitergibt. Die Köchin ist dann in diesem Fall die serverseitige Programmiersprache. Sie greift daraufhin auf die Zutaten in der Vorratskammer (Datenbank) und bereitet das Gericht nach einem Rezept (HTML-Template bzw. Vorlage) zu. Das fertige Gericht (HTML-File) wird dann vom Kellner (Webserver) an den Gast (Webbrowser) serviert.