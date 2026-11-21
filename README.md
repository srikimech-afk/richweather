# SkyTrip - Weather Travel Companion

A graphical Next.js weather app designed for GitHub + Vercel.

## Features
- Current weather for any searched city
- 5-day forecast
- Temperature, feels-like, humidity, wind and cloud cover
- Rain probability, UV index, sunrise and sunset
- Current browser location (permission required)
- Travel Mode: compare home vs destination
- Rule-based packing guidance
- Responsive visual UI for desktop and mobile
- Open-Meteo API; no API key or environment variables required

## GitHub structure
Upload the contents of this folder to the ROOT of your GitHub repository:

```
app/
  layout.js
  page.js
  style.css
package.json
README.md
```

Do NOT put package.json inside app/.

## Run locally
Requires Node.js 20 or newer.

```bash
npm install
npm run dev
```

Open http://localhost:3000

## Deploy to Vercel
1. Push these files to your GitHub repository.
2. In Vercel choose Add New > Project.
3. Import the GitHub repository.
4. Framework Preset should be Next.js.
5. Root Directory should remain `./`.
6. No environment variables are required.
7. Click Deploy.

## API
Weather and geocoding use Open-Meteo. Review Open-Meteo's terms before commercial production use.
