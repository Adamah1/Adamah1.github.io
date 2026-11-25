# Adam Hassan · Portefølje

Personlig porteføljeside med prosjekter og tilbud om nettsider for bedrifter i Kristiansand.
Hele siden er én fil (`index.html`) uten rammeverk eller byggesteg, og publiseres med GitHub Pages.

Adresse når den er publisert: https://adamah1.github.io

## Publisere første gang

1. Gå til https://github.com/new og lag et **offentlig** repo som heter nøyaktig `Adamah1.github.io`. Ikke huk av for README.
2. Kjør dette i terminalen fra mappen der `index.html` ligger:

```bash
git init
git add .
git commit -m "Første versjon av porteføljen"
git branch -M main
git remote add origin https://github.com/Adamah1/Adamah1.github.io.git
git push -u origin main
```

3. Gå til repoet på GitHub, åpne **Settings → Pages**, og sjekk at kilden er **Deploy from a branch**, med branch `main` og mappe `/ (root)`.
4. Etter et par minutter ligger siden på https://adamah1.github.io

## Oppdatere siden

Endre `index.html`, og kjør:

```bash
git add .
git commit -m "Beskriv hva du endret"
git push
```

## Teste lokalt

Åpne `index.html` direkte i nettleseren, eller kjør en liten lokal server:

```bash
python3 -m http.server 8000
```

og gå til http://localhost:8000
