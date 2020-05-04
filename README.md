# Web-Workflow (2020)

Neuer Workflow für Webprojekte (HTML, CSS, JavaScript).

## Requirements

*  NodeJS 12.13.0
*  Glup-CLI 2.2.0

## Installation

**Projekt klonen:**
`git clone https://github.com/jens260181/web-workflow.git`

**Module installieren**
`npm i`

## Config

Aktuell sind nur Basis Einstellungen möglich:

*  `PRODUCTION` `true` oder `false`
*  `SRC` Hauptordner, wo die Source Dateien liegen (HTML)
*  `ASSETS` Ordner für SCSS/SASS, JS, Images, ...
*  `DIST_STAGE` Ordner für die Ausgabe der Testumgebung
*  `DIST_PROD` Ordner für die Ausgabe der Live Version
*  `DIST` Verweist auf Stage oder Production (Muss nicht angepasst werden)

## Usage

**Dev Server starten**
`gulp dev`

**Build**
`gulp` oder `gulp build`

## ToDo

* [ ]  Task für Bildoptimierung
* [ ]  Task für JSON Minifizierung
* [ ]  Bootstrap als Dependency
* [ ]  Bootstrap als SCSS Module bereitstellen
* [ ]  remove_logging als Dependency
* [ ]  remove_logging als Dependency
* [ ]  gulp-clean-old als Dependency