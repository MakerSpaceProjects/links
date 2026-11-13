# Linktree-Seite

Eine einzelne `index.html` – keine Abhängigkeiten, kein Build-Schritt.

## Links eintragen
In `index.html` bei jedem Eintrag `href="#"` durch die echte URL ersetzen.
Einträge mit `href="#"` erscheinen ausgegraut mit „bald“. Unnötige Einträge (`<li>…</li>`) löschen.

## Auf GitHub Pages veröffentlichen
1. Neues Repository auf GitHub anlegen (z. B. `links` oder `<benutzername>.github.io` für die Haupt-URL).
2. `index.html` (und optional `avatar.jpg`) hochladen.
3. Repository → **Settings → Pages** → Source: *Deploy from a branch*, Branch `main`, Ordner `/ (root)` → Save.
4. Nach ca. 1 Minute ist die Seite unter `https://<benutzername>.github.io/<repo>/` erreichbar.
