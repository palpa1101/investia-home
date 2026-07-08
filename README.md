# inVestia Home – Coming-Soon-Platzhalter

Statische Platzhalter-Landing-Page, bis die richtige Website online geht.

## Struktur
- `index.html` – die komplette Seite (HTML + CSS inline, keine Build-Schritte nötig)
- `assets/logo.png` – Logo (Coming Soon)
- `assets/team.jpg` – Team-Foto (fürs Web optimiert)

## Lokal ansehen
Einfach `index.html` im Browser öffnen – oder ein kleiner lokaler Server:
```bash
python3 -m http.server 8000
# dann http://localhost:8000 öffnen
```

## Über GitHub Pages hosten
1. Neues Repository auf GitHub anlegen (z. B. `investia-home-coming-soon`).
2. Diesen Ordner als Repo pushen:
   ```bash
   git init
   git add .
   git commit -m "Coming-Soon-Platzhalter"
   git branch -M main
   git remote add origin https://github.com/<DEIN-USER>/<REPO>.git
   git push -u origin main
   ```
3. Auf GitHub: **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: **main**, Ordner: **/ (root)** → **Save**
4. Nach ~1 Minute ist die Seite unter
   `https://<DEIN-USER>.github.io/<REPO>/` erreichbar.

### Eigene Domain (optional)
Unter **Settings → Pages → Custom domain** die Wunschdomain eintragen und beim
Domain-Anbieter einen `CNAME`-Eintrag auf `<DEIN-USER>.github.io` setzen.
