# CleverClash
### Kahoot-Verschnitt

### Authors
- Mihajlo Djordjevic, 2210258119
- Lazar Zivkovic, 2210258091
- Boris Maksimovic, 2210258010

### Funktionsanforderungen

- Der Code sollte mit JavaDoc Kommentaren versehen sein.
- Eine readme.md sollte einen groben Überblick über das Projekt geben.
- Mehrere Klassen mit Vererbung, Overriding von Methoden und ggf mehren Konstruktoren in der Klasse
- Die Zugriffsrechte für Klassen, Methoden und Properties (Variablen) sollten sinnvoll gewählt werden
- Durchdachtes Exception Handling. Hierbei kann auf die Vorhandenen Exceptions zugegriffen werden, sofern diese für gerechtfertigt erscheinen.
- File IO in irgendeiner Art und Weise. (Logs, CSV Dateien, Properties, XML)
- Multithreading (Zeitintensive Berechnungen NICHT im Gui-Thread)
- Durchdachte und aufgeräumte GUI. (FXML oder Inline)
- Networking (Kommunikation von Server / Client Software über TCP / UDP)


## Projektspezifische Requirements

### Must haves (muss erfüllt sein um einen 4er zu bekommen)
- Das Spiel unterstützt unterschiedliche Schwierigkeitsgrade für die Fragen.
- Eine Highscore-Tabelle zeigt die besten Spieler an und motiviert so zu Wettbewerb.
- Das Spiel soll eine Suche von Spielern, welche bereits gespielt haben, zur Verfügung stellen. Anders als bei der Highscore-Tabelle sollen hier nur die Personen angezeigt werden.


### Should haves (muss erfüllt werden um einen 3er zu bekommen)

- Spieler können ihre eigenen benutzerdefinierten Quizfragen erstellen und der Fragenbank hinzufügen.
- Das Spiel ermöglicht es Spielern, eigene benutzerdefinierte Quiz-Kategorien zu erstellen.
- Das Spiel ermöglicht es ein erweitertes Profil zu erstellen darunter gehört auch fallen bspw. Profilbild/Icon und aktueller Wissenstand (Anfänger, Amateur, Fortgeschritten)


### Nice to haves (muss erfüllt werden um einen 2er zu bekommen)

- Spiel bietet einen “Schnellspiel”-Modus für eine schnelle Spielerfahrung, die gegen den eigenen Highscore stattfindet.
- Das Spiel kann durch Login verschiedenen Funktionen freischalten (User, Editor, Admin)
- User  Kann das Spiel spielen, Fragen erstellen
- Editor  Kann alles was der User macht + kann Fragen von anderen User prüfen und editieren/validieren
- Admin  Non plus ultra = Overpowered 😉
- Eine Suchfunktion ermöglicht es Spielern, gezielt nach bestimmten Fragen zu suchen, um diese zu lernen oder zu prüfen, was die passende Antwort wäre.


### Overkill (muss erfüllt werden um einen 1er zu bekommen)

- Ein Achievement-System, das Spieler für besondere Leistungen im Spiel auszeichnet, basierend auf den Namen, die genutzt werden.
- Ein Tutorial leitet neue Spieler durch die Benutzeroberfläche und Spielmechaniken.
- Das Spiel bietet dir einen Bot-Modus der drei Stufen hat (Anfänger, Amateur, Fortgeschritten). Diese drei Stufen unterscheiden sich anhand der Fragenmenge (10, 30, 50). Der Spieler gewinnt nur wenn er alle Fragen richtig beantwortet hat.
