# Gutschein-App

Kleine statische Web-App fuer einen Gutschein mit drei auswaehlbaren Erlebnissen:

- Brunch-Schiff
- Zmorge-Gondel
- Berg-Brunch

## Hosting auf GitHub Pages

Empfohlener Repository-Name: `gutschein-brunch`

1. Auf GitHub ein neues oeffentliches Repository erstellen.
2. Repository leer erstellen, ohne README, ohne `.gitignore`, ohne Lizenz.
3. Lokales Repository pushen:

```powershell
git remote add origin https://github.com/Frostwritter/gutschein-brunch.git
git push -u origin main
```

4. In GitHub: `Settings` -> `Pages`.
5. Unter `Build and deployment` die Quelle `Deploy from a branch` waehlen.
6. Branch `main` und Ordner `/ (root)` auswaehlen und speichern.

Danach ist die Seite normalerweise unter dieser Adresse erreichbar:

```text
https://frostwritter.github.io/gutschein-brunch/
```

Diese URL kann fuer den QR-Code verwendet werden.
