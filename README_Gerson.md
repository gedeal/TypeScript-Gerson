# New branch

# 01-basics -  TypeScript Basics

```bash
npm init -y
npm install --save-dev typescript
npx tsc -v
npx tsc --init



git clone [http address ]


```

# 02-vite-basics - Vite TypeScript Basics

## Skapa en ny Vite-app med `vanilla-ts` som template

```bash
npm create vite@latest 02-vite-basics -- --template vanilla-ts

npm install -D vite


```

Svara `No` på "Install with npm and start now".
Följ sedan instruktionerna om att gå in i mappen och köra `npm install`. Därefter öppna mappen i
VSCode's inbyggda terminal och kör där `npm run dev`.

Jag har tagit raderat följande filer:

```
public/icons.svg
public/vite.svg
src/assets
src/
  counter.ts
  style.css
```

Samt tömt `main.ts` på innehåll och tagit bort favicon-länken från `index.html`.

# 03 - Todos

## Recreate

Follow the instructions in `02-vite-basics` to create a new app and delete all unnecessary files.

Then install Bootstrap and SASS as dev-dependencies:

```bash
npm i -D -E sass@1.77.6
npm i -D bootstrap
```

## Run

```bash
npm run dev
```
