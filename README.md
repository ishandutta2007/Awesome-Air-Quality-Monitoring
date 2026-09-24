# Awesome-Air-Quality-Monitoring

# Top Air Quality Monitoring Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Ambient Air Quality Data, AQI APIs, Sensor Networks, Pollution Mapping & Environmental Intelligence*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Air Quality Monitoring**. These systems aggregate station and sensor data, compute AQI, power maps and alerts, and deliver APIs for apps, cities, and researchers tracking PM2.5, NO₂, O₃, and related pollutants.

**Examples** include BreezoMeter, Ambee, Aclima, IQAir AirVisual, Plume Labs, Atmotube, Airly, Clarity Movement, EnviroSuite, and OpenAQ (the category leaders and open data platform).

**Open-source emphasis**: **OpenAQ** is the primary open global air quality data platform. **Sensor.Community** (and related firmware/software), open analysis libraries, and community sensor stacks expand the ecosystem. This section lists every significant relevant project found.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[BreezoMeter](https://www.breezometer.com/)**  
  Air quality and environmental intelligence platform providing high-resolution AQI, pollen, and related data APIs for consumer and enterprise applications (often integrated into larger map/weather products).

- **[IQAir AirVisual](https://www.iqair.com/)**  
  Global air quality monitoring network and app with station data, rankings, and APIs widely used by the public and organizations.

- **[Ambee, Plume Labs, Airly](https://www.getambee.com/)**  
  Air quality data and hyperlocal monitoring platforms offering APIs, maps, and insights for cities, health apps, and businesses.

- **[Aclima, Clarity Movement](https://www.aclima.io/)**  
  Sensor network and measurement platforms focused on street-level and community-scale air quality mapping and analytics.

- **[Atmotube, EnviroSuite](https://atmotube.com/)**  
  Consumer and industrial environmental monitoring solutions spanning personal sensors and broader environmental compliance platforms.

- **[OpenAQ (data platform)](https://openaq.org/)**  
  Nonprofit open platform that aggregates and harmonizes global air quality data for free public access—listed here as the open data leader (see Open-Source section for software).

- **[Other commercial air quality platforms](https://www.iqair.com/)**  
  Additional providers of AQI APIs, hardware networks, and environmental dashboards.

## Open-Source GitHub Projects

- **[OpenAQ](https://github.com/openaq)**  
  Open-source, open-access platform and APIs that aggregate air quality measurements worldwide—SDKs (Python, R), fetch/ingest tools, explorer apps, and standardized data for analysis and advocacy.

- **[Sensor.Community / Luftdaten-style stacks](https://github.com/opendata-stuttgart)**  
  Open citizen-science sensor firmware, backends, and maps for low-cost PM sensors—one of the largest community air quality networks globally.

- **[awesome-air-quality](https://github.com/openaq/awesome-air-quality)**  
  Curated open list of air quality software libraries, datasets, and tools maintained in the OpenAQ ecosystem.

- **[Open analysis libraries (openair, atmospy, etc.)](https://github.com/davidcarslaw/openair)**  
  Open R/Python packages for air quality data analysis, trends, and visualization used by researchers and agencies.

- **[CLI & local AQ tools](https://github.com/fortunto2/airq)**  
  Open command-line tools that combine Sensor.Community and model data (e.g. Open-Meteo) for local air quality checks and reports.

- **[Low-cost sensor open firmware](https://github.com/search?q=air+quality+sensor+ESP32+OR+SDS011)**  
  Community firmware for popular particulate and gas sensors used in DIY and citizen networks.

- **[AQI calculation open implementations](https://github.com/search?q=AQI+calculator+OR+air+quality+index+open+source)**  
  Libraries implementing EPA, EU, and other AQI formulas from concentration data.

- **[Mapping & dashboard open projects](https://github.com/search?q=air+quality+map+OR+AQI+dashboard+open+source)**  
  Open web maps and dashboards built on OpenAQ or Sensor.Community data.

### Additional Strong Open-Source Options

- **Global open data**: OpenAQ as the standard free API and archive for station-based measurements.
- **Citizen sensors**: Sensor.Community hardware + software for hyperlocal networks.
- **Science stack**: openair and related packages for regulatory-style analysis.
- **Composable stacks**: OpenAQ/Sensor.Community data → open AQI libs → custom maps/alerts.
- Commercial platforms still lead in hyperlocal modeling, hardware networks at scale, and polished consumer apps.

**Frameworks for building custom systems**:  
**OpenAQ** provides the open data backbone; **Sensor.Community** adds dense low-cost sensing.  
Analysis libraries and open AQI tools complete research and civic apps.  
Commercial platforms (BreezoMeter, IQAir, Ambee, Airly, Aclima, Clarity, etc.) offer refined models, APIs, and managed networks.  
Many apps and researchers use OpenAQ for baseline data and commercial APIs where higher resolution or SLAs are required. Fully open stacks are excellent for transparency, research, and civic technology.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Air quality data varies in accuracy by sensor type, calibration, and siting. Low-cost sensors and models are not always equivalent to regulatory monitors. Do not use informal data alone for official compliance or medical decisions without appropriate validation.
- Open platforms provide transparency and free access; commercial services may offer higher resolution or support. Always cite data sources and respect API terms of use.

---

**Made for environmental scientists, city innovators, health apps, and clean-air advocates.**  
Let's expand open air quality data and tools while recognizing the coverage and product polish that leading commercial monitoring platforms deliver.
