# Willkommen zum DevOps Camp 2023!

Link zur Webseite der Veranstaltung: [https://devops-camp.de/](https://devops-camp.de/)

## Session "Docs as Code" von Lukas

Dies war eine Live Demo des Tools ***mkdocs***!

Es dienst als anschauliches Beispiel des Ansatzes von "Docs as Code".

Wir haben über Schmerzen und Good Practices beim Schreiben von Software-Dokumentation gesprochen,
dabei live mit diesem Tool hier unsere Punkte dokumentiert und anschließend sofort on-the-fly über Github Pages veröffentlicht.

## Quellcode
Der entstandene Quellcode ist hier zu finden: [https://github.com/sourcefranke/dvoc23-docs-as-code](https://github.com/sourcefranke/dvoc23-docs-as-code)

## CLI Befehle

Kommandos, die wir während der Session benutzt haben:

### Installation

````
pip install mkdocs
````

#### Plugins, falls benötigt

````
pip install plantuml
pip install mkdocs-plantuml
pip install mkdocs-bootstrap386
````

### Neues Projekt initialisieren

````
python -m mkdocs new <project_name>
````

### Statische Webseite lokal starten

````
python -m mkdocs serve
````

### Auf GitHub Pages veröffentlichen

Direkt vom lokalen Terminal aus !! ;)

Macht wirklich alles - nichts muss mehr händisch getan werden!

````
python -m mkdocs gh-deploy
````

