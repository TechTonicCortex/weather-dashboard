# Weather Dashboard

**Search a city and see the weather, forecast, UV index and air quality.**
Open `index.html` in a browser. It needs internet and a free API key.

## What it does
Type a city name. It shows current weather, a forecast, the UV index and air pollution.

## Setup (one time)
1. Make a free account at openweathermap.org and copy your API key.
2. Open the file and replace `YOUR_OPENWEATHERMAP_API_KEY` near the top of the script with your key.

## ⚠️ Key safety
**Never upload your real key to a public GitHub repo.** Anyone can copy it. The file in the repo must keep the placeholder text. Keep your real key only on your own computer.
(New keys can take a little while to start working.)

## How it works
- Four OpenWeatherMap endpoints: current weather, forecast, UV, and air pollution.
- It first searches by city name, then uses the returned coordinates for the UV and air-quality requests.
- It shows a friendly message if the key is missing or the city isn't found.

## Limits
Free-tier limits apply, and UV data may not be available for every account or plan.

## What I learned
How APIs work, why keys must stay private, and how one result (coordinates) feeds the next request.

## Next steps
Add °C/°F toggle and link air quality to a health tip, using the same idea as [LifeKnow](https://github.com/TechTonicCortex/lifeknow).

---
Part of [Aadit's projects](https://github.com/TechTonicCortex/techtoniccortex).
