# ProCyclingStats Scraper

![banner](https://i.ibb.co/Hf6xG4wP/procyling.png)

Extract comprehensive cycling statistics and race data from ProCyclingStats.com, the world's leading cycling statistics database. This powerful scraper collects detailed race results, rider statistics, team information, and historical cycling data across all major cycling disciplines. Perfect for cycling analysts, sports journalists, team managers, and cycling enthusiasts who need structured data for research, analysis, and reporting.

<p align="center">
  <img src="https://apify-image-uploads-prod.s3.us-east-1.amazonaws.com/DevbkY3adMTBuoECt-actor-7LkTfUEDuXB3tRSES-pzC2Tfq6XQ-id0gXCV51b_logos.png" alt="Procyclingstats.com Scraper" style="height: 60px; margin-right: 15px;" /><a href="https://apify.com/lexis-solutions/procyclingstats-com-scraper" target="_blank">
    <img src="https://img.shields.io/badge/Try%20it%20on-Apify-0066FF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDA4IiBoZWlnaHQ9IjQwOCIgdmlld0JveD0iMCAwIDQwOCA0MDgiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxnIGNsaXAtcGF0aD0idXJsKCNjbGlwMF8zNDFfNDE1NykiPgo8cGF0aCBkPSJNMjE4LjY5NSAxMDRIMzAwLjk3QzMwMi42NDMgMTA0IDMwNCAxMDUuMzU3IDMwNCAxMDcuMDNWMjMyLjc2NkMzMDQgMjM1Ljc3OCAzMDAuMDgzIDIzNi45NDUgMjk4LjQzNCAyMzQuNDI1TDIxNi4xNTkgMTA4LjY5QzIxNC44NDEgMTA2LjY3NCAyMTYuMjg3IDEwNCAyMTguNjk1IDEwNFoiIGZpbGw9IndoaXRlIi8+CjxwYXRoIGQ9Ik0xODkuMzA1IDEwNEgxMDcuMDNDMTA1LjM1NyAxMDQgMTA0IDEwNS4zNTcgMTA0IDEwNy4wM1YyMzIuNzY2QzEwNCAyMzUuNzc4IDEwNy45MTcgMjM2Ljk0NSAxMDkuNTY2IDIzNC40MjVMMTkxLjg0IDEwOC42OUMxOTMuMTU5IDEwNi42NzQgMTkxLjcxMyAxMDQgMTg5LjMwNSAxMDRaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMjAyLjU5MSAyMDQuNjY4TDEwOS4xMjcgMjk4LjgzNUMxMDcuMjI5IDMwMC43NDcgMTA4LjU4MyAzMDQgMTExLjI3OCAzMDRIMjk2LjhDMjk5LjQ4MyAzMDQgMzAwLjg0MiAzMDAuNzcgMjk4Ljk2NyAyOTguODUyTDIwNi45MDggMjA0LjY4NUMyMDUuNzI2IDIwMy40NzUgMjAzLjc4MiAyMDMuNDY4IDIwMi41OTEgMjA0LjY2OFoiIGZpbGw9IndoaXRlIi8+CjwvZz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDBfMzQxXzQxNTciPgo8cmVjdCB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEwNCAxMDQpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==&logoColor=white" alt="Try it on Apify" style="border-radius: 12px; height: 60px;" />
  </a>
</p>


👋 Welcome to the ProCyclingStats Scraper, an actor designed to help you gather comprehensive cycling data from procyclingstats.com! With this actor, you can easily extract race results, rider statistics, and historical cycling information.

## Introduction

## 📊 Actor Stats

| Stat | Value |
|------|-------|
| **Version** | `0.1.2` |
| **Last Update** | Dec 1, 2025 |

---



The ProCyclingStats Scraper is a web scraping tool designed to extract cycling statistics and race data from procyclingstats.com. It was created to make it easier for cycling professionals, analysts, and enthusiasts to access structured data from the world's most comprehensive cycling statistics database.


## 💻 Integration Examples

This repository includes example code showing how to integrate the `procyclingstats-com-scraper` actor into your projects.

You can find example implementations in the [`examples/`](./examples) folder:
- **TypeScript/JavaScript**: See [`examples/typescript/`](./examples/typescript) for a complete TypeScript example
- **Python**: See [`examples/python/`](./examples/python) for a complete Python example

Each example includes:
- Ready-to-use code templates
- Setup instructions
- Documentation links

---


## Use Cases

Here are some typical scenarios in which the ProCyclingStats Scraper can be useful:

- **Cycling Analysts** can use the scraper to extract race results and performance data for statistical analysis
- **Sports Journalists** can use the scraper to gather historical data for articles and race reports
- **Team Managers** can use the scraper to analyze competitor performance and track rider statistics
- **Cycling Enthusiasts** can use the scraper to research historical race data and rider achievements
- **Data Scientists** can use the scraper to build cycling databases for machine learning and predictive modeling

## Input 📥

To use this actor, you need to provide the following input:

- Field: **startUrls**
  - Type: array
  - Required: Yes
  - Description: URLs to scrape from ProCyclingStats.com

```json
{
  "startUrls": [
    {
      "url": "https://www.procyclingstats.com/race/world-championship/results/most-starts-finishes"
    }
  ]
}
```

## How to get `startUrls`?

1. **Race Results Pages**

   - Navigate to any race results page on ProCyclingStats.com
   - Copy the URL from your browser's address bar
   - Add it to the `startUrls` array

2. **Statistics Pages**

   - Visit any statistics page (e.g., most starts/finishes, rider rankings)
   - Copy the URL and add it to the `startUrls` array

3. **Team or Rider Pages**
   - Go to specific team or rider profile pages
   - Copy the URL for data extraction

### Examples

Race results page:

```
https://www.procyclingstats.com/race/world-championship/results/most-starts-finishes
```

Tour de France results:

```
https://www.procyclingstats.com/race/tour-de-france/2024/gc
```

Rider statistics:

```
https://www.procyclingstats.com/rider/eddy-merckx/statistics
```

## Output 📤

An example output looks like this:

```json
{
  "url": "https://www.procyclingstats.com/race/world-championship/results/most-starts-finishes",
  "title": "Most starts and finishes in World Championships ME - Road Race history",
  "extractedAt": "2025-09-23T21:56:30.993Z",
  "results": [
    {
      "Pos.": "1",
      "Rider": "POULIDOR Raymond",
      "Starts": "18",
      "Finishes": "17",
      "First": "1960",
      "Last": "1977"
    },
    {
      "Pos.": "2",
      "Rider": "ZOETEMELK Joop",
      "Starts": "17",
      "Finishes": "16",
      "First": "1970",
      "Last": "1987"
    }
  ],
  "total": 100
}
```

## What data can the ProCyclingStats Scraper extract?

The ProCyclingStats Scraper can extract various types of cycling data including:

- **Race Results** - Complete race standings and classifications
- **Rider Statistics** - Performance metrics, career statistics, and achievements
- **Team Data** - Team rosters, performance history, and statistics
- **Historical Records** - All-time records, most starts/finishes, and career milestones
- **Race Classifications** - General Classification, Points, Mountains, and other classifications
- **Stage Results** - Individual stage results and time gaps

## Why use the ProCyclingStats Scraper?

- ⚡️ **Comprehensive** - Access to the world's largest cycling statistics database
- 🤙 **Easy to use** - Simply input URLs and let the scraper handle the data extraction
- 📊 **Structured Data** - Get clean, structured JSON data ready for analysis
- 🏆 **Historical Coverage** - Access decades of cycling history and statistics
- ☑️ **Well-Maintained** - The scraper is maintained by the Lexis Solutions team, ensuring reliable performance

## Limitations

- The scraper respects ProCyclingStats.com's rate limiting and terms of service
- Some data may require specific access permissions
- Large datasets may take time to process

## FAQ 💬

- **What is ProCyclingStats.com?**

  ProCyclingStats.com is the world's most comprehensive cycling statistics database, covering professional cycling races, riders, teams, and historical data from around the globe.

- **How can I find specific cycling data on ProCyclingStats.com?**

  You can navigate to specific race pages, rider profiles, or statistics sections on the website. The scraper automates the data extraction process from these pages.

- **Can I use the ProCyclingStats scraper for commercial purposes?**

  Please ensure you comply with ProCyclingStats.com's terms of service and any applicable laws and regulations when using this scraper.

- **What types of cycling data can the scraper find?**

  The scraper can extract data from various sections including:

  - Race results and classifications
  - Rider statistics and career data
  - Team information and rosters
  - Historical records and achievements
  - Stage results and time gaps

- **What if the website changes?**

  Website changes may affect the scraper's functionality. In such cases, our team will update the scraper to maintain compatibility. We regularly monitor and maintain our scrapers to ensure reliable operation.

## Need to scrape other sports data?

Here are some other sports scrapers you might find useful:

- **Betting & Racing** 🏇
  - [Sportsbet Scraper](https://apify.com/lexis-solutions/sportsbet-com-au-scraper) - Extract betting odds and racing schedules from Australia's leading sports betting platform
  - [LeTrot Scraper](https://apify.com/lexis-solutions/letrot-com-scraper) - Extract horse racing data and results from France's premier trotting platform

---

👀 p.s.

Got feedback or need an extension?

Lexis Solutions is a [certified Apify Partner](https://apify.com/partners/find). We can help you with custom solutions or data extraction projects.

Contact us over [Email](mailto:scraping@lexis.solutions) or [LinkedIn](https://www.linkedin.com/company/lexis-solutions)

## Support Our Work 💝

If you're happy with our work and scrapers, you're welcome to leave us a company review [here](https://apify.com/partners/find/lexis-solutions/review) and leave a review for the scrapers you're subscribed to. It will take you less than a minute but it will mean a lot to us!

Image Credit: https://www.procyclingstats.com
