# Adam Hassan · Portefølje

Personlig porteføljeside med prosjekter og tilbud om nettsider for bedrifter i Kristiansand.
Hele siden er én fil (`index.html`) uten rammeverk eller byggesteg, og publiseres med GitHub Pages.

Adresse: https://adamah1.github.io

## Hvordan siden ble laget

Jeg har planlagt innholdet, valgt hvilke prosjekter som skal være med og publisert siden selv.
Koden og tekstene ble laget med hjelp fra Claude, en AI-assistent fra Anthropic, og jeg har gått gjennom og tilpasset dem.
Jeg skriver dette fordi jeg mener det er riktig å være åpen om hvilke verktøy jeg bruker.

## Publisere første gang

1. Gå til https://github.com/new og lag et offentlig repo som heter nøyaktig `Adamah1.github.io`. Ikke huk av for README.
2. Åpne terminalen **i mappen der `index.html` ligger** (ikke i hjemmemappen), og kjør:

```bash
git init
git add index.html README.md
git commit -m "Første versjon av porteføljen"
git branch -M main
git remote add origin https://github.com/Adamah1/Adamah1.github.io.git
git push -u origin main
```

3. Gå til repoet på GitHub, åpne **Settings → Pages**, og sjekk at kilden er **Deploy from a branch**, med branch `main` og mappe `/ (root)`.
4. Etter et par minutter ligger siden på https://adamah1.github.io

## Oppdatere siden

Endre filene, og kjør dette fra den samme mappen:

```bash
git add index.html README.md
git commit -m "Beskriv hva du endret"
git push
```

Jeg legger til filene ved navn i stedet for med `git add .`, så Git aldri tar med noe annet enn det som hører til siden.

## Teste lokalt

Åpne `index.html` direkte i nettleseren, eller kjør en liten lokal server:

```bash
python -m http.server 8000
```

og gå til http://localhost:8000
