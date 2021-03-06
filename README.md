# Web-Workflow (2020)

Neuer Workflow für Webprojekte (HTML, CSS, JavaScript).

## Features

*  SASS/CSCSS zu CSS
*  ES6 zu JavaScript
*  jp(e)g, png, svg Grafiken optimieren
*  JSON Dateien minimieren
*  HTML cleanup, minimieren, optimieren, Cachebusting
*  Browser Reload

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
*  `IMAGE_QUALITY` `0` bis `100`
*  `ENABLE_JSON` `true` oder `false`
*  `SRC` Hauptordner, wo die Source Dateien liegen (HTML)
*  `ASSETS` Ordner für SCSS/SASS, JS, Images, ...
*  `ASSETS_JSON` Ordner für JSON Dateien
*  `DIST_STAGE` Ordner für die Ausgabe der Testumgebung
*  `DIST_PROD` Ordner für die Ausgabe der Live Version
*  `DIST` Verweist auf Stage oder Production (Muss nicht angepasst werden)
*  `DIST_JSON` Ordner für Speicherung der minifizierten JSON Dateien

## Usage

**Dev Server starten**
`gulp dev`

**Build**
`gulp` oder `gulp build`

## ToDo

* [ ]  TypeScript Compiler
* [ ]  Modulare Features