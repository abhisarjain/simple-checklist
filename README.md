# Checklist

A simple React checklist with browser-local persistence.

## Run locally

```sh
npm ci
npm run dev
```

## Build

```sh
npm run build
```

## Deploy

Import this repository into Vercel. Framework: Vite. Build command: `npm run build`. Output: `dist`. No environment variables required.

Tasks stay in localStorage in the same browser and site origin. Moving to another URL does not transfer existing tasks. Reset clears the checklist; clearing browser site data also removes it.
