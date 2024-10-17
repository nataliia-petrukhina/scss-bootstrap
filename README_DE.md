# SCSS Boilerplate

- Ein Projekt-Boilerplate mit Sass-Unterstützung

- Entwicklungs-Server betrieben von [parcel](https://parceljs.org/) mit Sass-Kompilierung und Auto-Reload.

## Inhaltsverzeichnis

- [SCSS Boilerplate](#scss-boilerplate)
  - [Inhaltsverzeichnis](#inhaltsverzeichnis)
  - [Einrichtung](#einrichtung)
  - [Nützliche Befehle](#nützliche-befehle)
    - [Entwicklung](#entwicklung)
    - [Produktion](#produktion)
  - [Projektstruktur](#projektstruktur)
    - [`README.md`](#readmemd)
    - [`package.json` \& `package-lock.json`](#packagejson--package-lockjson)
    - [`src` \& `index.html`](#src--indexhtml)
    - [`main.scss`](#mainscss)
    - [`dist`(Distribution) wird automatisch generiert](#distdistribution-wird-automatisch-generiert)
  - [`Deployments`](#deployments)

## Einrichtung

1. Erstelle ein neues Repo von diesem Template (klicke auf den grünen Button "Use this template" oben rechts)
2. Klone das Repo auf deinen Computer wie gewohnt

   ```bash
   git clone GITHUB_REPO_URL
   ```

3. Bearbeite `src/index.html`, vielleicht füge den Namen deines Projekts hinzu

4. Installiere die Abhängigkeiten

```
npm install
```

5. Viel Spaß beim Coden!

## Nützliche Befehle

### Entwicklung

- Starte den **parcel-live-server** und fang an zu coden!

```
npm start
```

### Produktion

- Kompiliere den Quellcode aus **src** und erstelle ein optimiertes Produktions-Bundle im **dist**-Ordner, bereit für das **Deployment**.

```
npm run build
```

## Projektstruktur

- Jedes mit diesem Boilerplate erstellte Projekt wird der untenstehenden Struktur folgen:

```
Projekt
│   README.md
│   package.json
|   package-lock.json
└───src
│   │   index.html
│   |   sassy-css.scss
|   └───images
└───dist
```

### `README.md`

- Das README sollte eine kurze Beschreibung deines Projekts enthalten, fühle dich frei, diese Anleitung zu löschen oder umzubenennen, um deine eigene Beschreibung hinzuzufügen.

### `package.json` & `package-lock.json`

Diese Dateien enthalten verschiedene Informationen über dein Projekt und seine Abhängigkeiten sowie nützliche Skripte, die dir im Entwicklungsprozess helfen.

### `src` & `index.html`

- Der `src`-Ordner enthält alle Dateien, die du deiner Website hinzufügen möchtest. **Dies ist der Hauptordner, in dem du arbeiten wirst**.

- `index.html` ist die Hauptseite deiner Website, an der du arbeiten wirst.
- Füge gerne direkt im `src`-Ordner neue `html`-Seiten hinzu, die du erstellst.

### `main.scss`

- Die Datei `main.scss` wird jeglichen `scss`-Code enthalten, den du schreibst.

### `dist`(Distribution) wird automatisch generiert

- Der `dist`-Ordner wird automatisch generiert, wann immer du das Start- oder Build-Skript ausführst:

```bash
npm start
npm run build
```

- `npm start` wird ein nicht optimiertes Bundle erstellen und `npm run build` wird ein optimiertes Produktions-Bundle erstellen, bereit zum Deployment.
- Es wird von der `git`-Verfolgung ausgeschlossen, da es nicht üblich ist, kompilierten Code in einem Entwicklungsprojekt einzuschließen.

## `Deployments`

- Wenn du bereit bist, dein Projekt zu veröffentlichen, kannst du den Befehl `npm publish` verwenden, um dein Projekt auf GitHub Pages zu veröffentlichen.
