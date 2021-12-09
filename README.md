# MyPi

Mein Raspberry pi OS Setup um ein wenig was auszuprobieren :)


## Vorbereitung

### Auf dem Pi

Nach dem boot erstmal händisch das ssh für den pi User freischalten.

Dieses kann man auch über eine config Datei tail automatiseren, sowas kann man am ende dann optimieren. Erstmal starten ;)

### Auf dem Notebook
von dem aus der PI provisoniert werden soll muss vorab erstmal Ansible installiert werden.
Zusätzlich benötigen wir erstmal ein SSH Schlüsselpaar mit dem wir ansible den weg auf den Pi erlauben.

Zusätzlich hab ich den key mit dem Hostnamen in der ssh config Datei hinterlegt damit ein einfacher ssh connect per hostname reicht und der Username  + private key gleich richtig ausgewählt wurden.


## Die Basics

Es wird per Ansible erstmal die Basics installiert, wie:
- docker
- docker-compose
- Benötigte Order für die Compose files

Als nächstes dann die comtainer starten und los gehts.
