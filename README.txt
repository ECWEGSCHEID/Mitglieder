EC Wegscheid Mitgliederverwaltung – GitHub Pages V29

Lade diese drei Dateien in das Hauptverzeichnis deines GitHub-Repositories:
- index.html
- manifest.json
- icon.png

index.html ist die V29 ohne eingebettete Mitglieder- und Spielerpassdaten. Die Daten werden aus Firebase/Firestore geladen. Ein fehlendes Firebase-Dokument wird nicht automatisch mit einem leeren Zustand überschrieben.

Wichtig: Die Sicherheit der Daten wird durch Firebase/Firestore Security Rules und Authentifizierung bestimmt. GitHub Pages selbst schützt die Firebase-Daten nicht.
