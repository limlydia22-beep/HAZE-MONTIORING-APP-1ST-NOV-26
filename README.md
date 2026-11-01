# Haze Watch

Static single-page app (`index.html`). No build step, no dependencies.

- Haze (PSI, PM2.5, PM10): National Environment Agency via data.gov.sg, Singapore only
- Weather: Open-Meteo

## Deploy to Vercel

1. Go to https://vercel.com/new and choose **Import Git Repository**.
2. Pick `limlydia22-beep/HAZE-MONTIORING-APP-1ST-NOV-26`.
3. Framework Preset: **Other**. Leave Build Command and Output Directory empty. Root Directory: `./`.
4. Click **Deploy**.

Every push to `main` redeploys automatically.

CLI alternative:

    npm i -g vercel
    vercel --prod

## Run locally

Open `index.html` in a browser, or serve the folder (for example `npx serve .`).
