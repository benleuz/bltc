# BLTC Mitgliederbefragung 2026

Interaktive Auswertung der Mitgliederbefragung als einzelne, eigenständige Seite (`index.html`).

- Die Umfragedaten sind in der Datei verschlüsselt (AES-256-GCM, Schlüssel per PBKDF2 aus dem Passwort). Ohne Passwort sind weder Zahlen noch Freitexte lesbar, auch nicht im Quelltext.
- Das Passwort steht bewusst nicht in diesem Repo. Es wird separat an den Vorstand weitergegeben.
- Keine externen Abhängigkeiten, Schriften sind eingebettet. Suchmaschinen werden per `noindex` ausgeschlossen.

## Veröffentlichen

Settings → Pages → Source: «Deploy from a branch», Branch `main`, Ordner `/ (root)`.
