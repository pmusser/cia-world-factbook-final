# CIA World Factbook: final content captures from the Wayback Machine

In the interest of LOCKSS, I'm sharing the content I got from the internet archive on 2/6/2026 and 2/7/2026. It's a bit of a mess and very much raw-data-y, but you can find formatted versions of the data, including images, audio, and recreated PDF's of the fact sheets and travel sheets [here](https://digitalpublicgoodslibrary.org/ark/search?f.search=World+Factbook).

If you like this and want to support more data rescue efforts focusing on educational resources, let me know. Anywho, more elaborate information:

# What's in a CIA World Factbook JSON

Each of the 254 pages is a complete country profile, structured into up to 15 sections. Here's what a reader will find:

## Content Sections (up to 13)

1. **Introduction** — Historical background and current political situation
2. **Geography** — Location, area, terrain, elevation, coastline, borders, natural resources, climate, land use, and an area comparison chart (image)
3. **People and Society** — Population, age structure (with population pyramid graphic), ethnic groups, religions, languages (with audio samples for some countries), literacy, health metrics, birth/death/migration rates, urbanization
4. **Environment** — Environmental issues, international agreements, water resources, waste, emissions, biomes, geoparks
5. **Government** — Country name, capital, government type, constitution, executive/legislative/judicial branches, political parties, flag description, national anthem (with audio), national symbols, diplomatic representation
6. **Economy** — GDP, growth rate, inflation, imports/exports, major industries, agricultural products, unemployment, debt, budget, exchange rates
7. **Energy** — Electricity generation and access, petroleum, natural gas, coal, nuclear energy, consumption per capita
8. **Communications** — Internet users, broadband, mobile/fixed-line subscriptions, broadcast media
9. **Transportation** — Airports, heliports, railways, merchant marine, ports
10. **Military and Security** — Forces, personnel strength, equipment, expenditures, service obligations, deployments
11. **Space** (select countries) — Space agencies, launch sites, program milestones
12. **Terrorism** (select countries) — Active terrorist groups
13. **Transnational Issues** — Refugees/IDPs, trafficking in persons, illicit drugs

The jsons also contain references to: 
## Media Products
- **Country flag** image
- **Country map** image
- **Locator map** (shows the country highlighted on its continent/region)
- **Gallery photos** — varies widely: from 0 (tiny territories) to 40+ (US, France, Spain) — landmark shots, landscapes, cultural sites, aerial views

## Audio Files
- **National anthem MP3** — most sovereign countries have one
- **Language sample MP3s** — spoken samples of official/major languages (many countries have 1–3 of these)

The data from the jsons was used to create the following items:

## Country Documents
- **Country Factsheet PDF** — a one-page summary with flag, maps, population pyramid, and ~20 key statistics (all 254 countries)
- **Travel Facts PDF** — practical travel info: visa requirements, vaccinations, currency, electrical plug types, emergency numbers (72 countries — the ones that had travel data)

## Scale
The smallest profiles (Bouvet Island, Coral Sea Islands) have ~6 sections and 3–4 files. The largest (Germany, United States, France) have all 13 sections, 30–50 files, and 140+ data fields. A typical country falls somewhere in between with 10–12 sections and 8–15 files.
