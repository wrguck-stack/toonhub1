# TOONHUB Original Hero

Originalgetreue Umsetzung des bereitgestellten TOONHUB-Prompts als React-, TypeScript-, Vite- und Tailwind-Projekt.

## Lokal starten

```bash
npm install
npm run dev
```

## Produktions-Build

```bash
npm run build
```

Vite erzeugt den fertigen Build im Ordner `dist`.

## GitHub-Upload

Die Ordnerstruktur muss erhalten bleiben. Am zuverlässigsten funktioniert das mit GitHub Desktop:

1. Neues Repository in GitHub Desktop anlegen oder klonen.
2. Den gesamten Inhalt dieses Projektordners in den lokalen Repository-Ordner kopieren.
3. `Commit to main` und anschließend `Push origin`.

## Vercel

1. Das GitHub-Repository als neues Vercel-Projekt importieren.
2. Framework Preset: `Vite`.
3. Root Directory: `./`.
4. Keine eigenen Install-, Build- oder Output-Befehle überschreiben.
5. Deploy starten.

Vercel erkennt Vite automatisch. Die Konfiguration in `vercel.json` setzt nur das Framework fest.
