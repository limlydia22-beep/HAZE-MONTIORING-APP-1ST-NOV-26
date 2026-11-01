# Haze Watch

Static single-page app. No build step.

- Haze (PSI, PM2.5, PM10): National Environment Agency via data.gov.sg, Singapore only
- Weather: Open-Meteo

## Deploy to Vercel

Option A, drag and drop: unzip, then drag the `haze-watch` folder onto https://vercel.com/new.

Option B, CLI:

    npm i -g vercel
    cd haze-watch
    vercel --prod

When asked about framework or build settings, choose "Other" and leave the build command and output directory empty.
