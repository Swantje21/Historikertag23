<!--
author:   Sebastian Zug & André Dietrich

email:    LiaScript@web.de

version:  0.0.1

language: de

narrator: Deutsch Female

comment:  Try to write a short comment about
          your course, multiline is also okay.

-->






Alles vom Schreiben von Dokumenten bis hin zum Veröffentlichen

## Cheat Sheets

- MD: https://docs.github.com/en/github/writing-on-github
- Lia: https://aizac.herokuapp.com/liascript-cheet-sheet/

## Verfassen von Liascript-Dokumenten mit Atom

### Installieren von Atom

- Atom von hier beziehen und installieren:
- https://atom.io/
- Atom ist ein Texteditor welches mit Plugins erweiterbar ist

### Einrichten der Plugins

- Edit -> Preferences
- Auf den Reiter Install
- Pakete die zu Installieren sind:
	- liascript-preview
	- liascript-snippets

### Das erste Dokument

- File -> New File
- Markdown und Lia teilen sich die Dateiendung .md
- Ab hier macht es Sinn ein erstes Markdown Dokument zu schreiben.
- Dieses Dokument hier ist auch ein Markdown Dokument :)

- Eine Markdown Preview erhält man unter Packages -> Markdown Preview -> Toggle preview
	- oder "STRG + Umschalt + M"

- Eine Liascript Preview erhält man unter Packages -> liascript-preview -> Toggle
	- oder "ALT+L"

- Die Liascript Preview akutalisiert sich nach jedem Speichern, während die Markdown Preview sich fortlaufend selber aktualisiert.

- Ab hier kann man anfangen mit Liascript.

- Das Package liascript-preview sorgt für Vorschläge sobald man den Text "lia" eingibt. Aus den Vorschlägen darf man sich einen Beliebigen Eintrag aussuchen. Man darf natürlich auch von Hand schreiben.

## Liascript Beispiele:

?[alt-text](audio-url)


### Audio:
?[Eine Audio](https://www.myinstants.com/media/sounds/its-a-very-nice.mp3)

### Quiz:

Welche Aussage über Quizze trifft zu?
[[_*niemand braucht quizze*_|(*Quizze bereichern unser aller Leben*)]]

Vervollständige folgenden Satz:
Quizze sind...

[[cool]]
[[?]] Hinweis: Das Gegenteil von uncool

## Veröffentlichen von Dokumenten

### Als lia
Zwei Vorraussetzungen:

- Ein Öffentlich zugänglicher Speicher für Dokumente.
	- Todo: Hier nochmal schauen, was sich zu Testzwecken anbietet.
	- Können die anderen vielleicht Git?...
- Eine Liascript Instanz, online.
	- https://liascript.github.io/

- Link zur Datei angeben und fertig.
	- Sollte dann genauso aussehen wie in der Vorschau unter Atom.

### Konversion zu Scorm im OLAT

## Kollaboratives Arbeiten
- TODO: Nachdem wir festgestellt haben, dass es mit Lia überhaupt klappt.


## Troubleshooting
### Meine Datei wird nicht als MD/Lia geparst
Hinter Header gehören Leerzeichen.. Markdown nimmt das leider sehr genau...
