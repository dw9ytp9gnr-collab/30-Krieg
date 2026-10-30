# Dreißigjähriger Krieg – GitHub Pages

Die App ist eine einzelne statische HTML-Datei. Es sind keine Build-Schritte und keine Zusatzpakete nötig.

## Neue, separate GitHub-Pages-Seite

1. Lege auf GitHub ein neues Repository an, zum Beispiel `dreissigjaehriger-krieg`. Bei einem kostenlosen GitHub-Konto muss das Repository für GitHub Pages öffentlich sein.
2. Entpacke dieses ZIP und lade `index.html` sowie `.nojekyll` in das Hauptverzeichnis des Repositorys hoch.
3. Öffne im Repository **Settings → Pages**. Unter **Build and deployment** wählst du **Deploy from a branch**, dann den Branch `main` und den Ordner `/(root)`. Klicke **Save**.
4. Warte, bis der Pages-Workflow unter **Actions** erfolgreich ist. Danach steht die Seitenadresse unter **Settings → Pages**.

## In ein vorhandenes Pages-Repository einfügen

Überschreibe dort keine vorhandene `index.html`. Lege stattdessen den Ordner `dreissigjaehriger-krieg` an und kopiere `index.html` hinein. Wenn das Repository bereits aus `main` und `/(root)` veröffentlicht wird, erreichst du die App üblicherweise unter `https://DEIN-NAME.github.io/REPOSITORY/dreissigjaehriger-krieg/`.

## Hinweise

- GitHub-Pages-Seiten sind öffentlich im Internet erreichbar – auch dann, wenn dein GitHub-Tarif ein privates Repository für Pages erlaubt.
- Die historischen Bilder und die Schriftarten werden von externen Quellen geladen. Zum Anzeigen dieser Inhalte ist eine Internetverbindung nötig.
- Die App speichert keine persönlichen Lern- oder Nutzerdaten.

## App-Icon

Das Paket enthält `icon-192.png` und `icon-512.png` für Browser-Tabs und als App-Icons sowie `apple-touch-icon.png` für iPhone/iPad. Das Web-App-Manifest ist bereits in `index.html` eingebunden. Lade alle Dateien gemeinsam ins GitHub-Pages-Verzeichnis hoch.
