# Anleitung für GitHub Pages

## GitHub Pages ist jetzt eingerichtet!

Die Webseite wird unter folgender Adresse verfügbar sein:
**https://demogorgi.github.io/Rechtschreibtrainer/**

## Wie geht es weiter?

### Option 1: Rechtschreibtrainer.html als index.html verwenden (empfohlen)
Wenn Sie Ihre Datei `Rechtschreibtrainer.html` hochladen, benennen Sie sie einfach in `index.html` um oder ersetzen Sie die bestehende `index.html` Datei mit Ihrem Inhalt.

### Option 2: Rechtschreibtrainer.html separat hochladen
Sie können auch `Rechtschreibtrainer.html` als separate Datei hochladen. Die Seite wäre dann unter:
**https://demogorgi.github.io/Rechtschreibtrainer/Rechtschreibtrainer.html**

erreichbar.

## Automatische Veröffentlichung

Die Seite wird automatisch veröffentlicht, wenn Sie Änderungen in den `main` oder `master` Branch pushen. Der GitHub Actions Workflow kümmert sich um die Bereitstellung.

## Erste Schritte

1. Laden Sie Ihre `Rechtschreibtrainer.html` Datei in dieses Repository hoch
2. Pushen Sie die Änderungen in den main/master Branch
3. GitHub Actions wird die Seite automatisch veröffentlichen
4. Nach wenigen Minuten ist Ihre Seite unter der oben genannten URL erreichbar

## GitHub Pages aktivieren

Falls GitHub Pages noch nicht aktiviert ist:
1. Gehen Sie zu den Repository-Einstellungen
2. Navigieren Sie zu "Pages" in der linken Seitenleiste
3. Unter "Build and deployment" wählen Sie "Source: GitHub Actions"
