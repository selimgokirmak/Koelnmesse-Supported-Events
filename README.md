# 🤖 [Koelnmesse Exhibitor List Scraper](https://apify.com/skython/koelnmesse-exhibitor-list-scraper)

Extract exhibitor data from trade show exhibitor lists provided by **Koelnmesse**. Easily scrape company profiles including **company details, websites, social media links, product groups, brands, and more**. 

Ideal for **B2B lead generation, market research, event networking, and competitive analysis**. Supports multiple **Koelnmesse** exhibition websites with a consistent HTML structure.

---

## Contents

- [Features](#features)

- [Use Cases](#use-cases)

- [Supported Website Structure](#supported-website-structure)

- [Testing Exhibitor List URLs](#testing-exhibitor-list-urls-for-free)

- [Exhibitor List Scraper - All-In-One Version](#exhibitor-list-scraper---all-in-one-version)

- [Supported Koelnmesse Events (Exhibitor Lists)](#supported-koelnmesse-events-exhibitor-lists)

- [Data Fields](#data-fields)

- [Example Output](#example-output)

- [My Other Exhibitor List Scrapers](#my-other-exhibitor-list-scrapers)

---

## Features

- Scrape all exhibitor profiles from supported Koelnmesse event websites

- Extract detailed data from every exhibitor profile page

- Company primary information (address, email, phone, website)

- Social media links (LinkedIn, Facebook, Instagram, Twitter, YouTube)

- Product groups with full hierarchical structure

- Two output formats (Single-Row & Multi-Row)

- Multi-Row format for Excel-friendly product group filtering

- Export to JSON, CSV, and Excel

---

## Use Cases

- **B2B Lead Generation:** Build targeted contact lists for marketing and sales outreach. 

- **Market Research:** Analyze exhibitors by product categories, brands, and sectors.  

- **Event Networking:** Familiarize yourself with exhibitors before attending trade fairs.  

- **Competitive Analysis:** Track competitor participation and product focus areas.

---

## Supported Website Structure

- This scraper is designed to extract data from exhibitor directories with the same HTML structure as the supported Koelnmesse exhibitor lists below.

- Take a look at some of the event websites from the below list. Your event website URL might be in that list.

- If you are not sure about if this actor is capable of scraping your event URL, test it with [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor.

---

## Testing Exhibitor List URLs for FREE

- Since I have multiple exhibitor list scraper actors for different types of trade event websites, it might be hard to find the correct actor for your exhibitor list URL.

- Use [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor to test your exhibitor list URLs **for FREE** and see which scraper can process them.

---

## Exhibitor List Scraper - All-In-One Version

- I also provide an **All-In-One** version that combines **my 30+ exhibitor list scrapers** into a single actor.

- Instead of searching for the correct scraper for each event URL, simply provide the event URL and the actor automatically selects the appropriate scraper.

- ➡️ [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

---

## Supported Koelnmesse Events (Exhibitor Lists)

> The following partial list includes Koelnmesse exhibitor directory URLs that have been tested so far. Other Koelnmesse events or different events with the same website structure may also be supported.

> Some event URLs may have been updated or canceled entirely; please check them before using.

- [Eisenwarenmesse 2026 Exhibitor List – eisenwarenmesse.com](https://www.eisenwarenmesse.com/eisenwarenmesse-exhibitors/list-of-exhibitors/)

- [Didacta Cologne 2026 Exhibitor List – didacta-cologne.com](https://www.didacta-cologne.com/didacta-exhibitors/list-of-exhibitors/)

- [h+h Cologne 2026 Exhibitor List – hh-cologne.com](https://www.hh-cologne.com/hh-cologne-exhibitors/list-of-exhibitors/)

- [ProSweets Cologne 2026 Exhibitor List – prosweets.com](https://www.prosweets.com/psc-exhibitors/list-of-exhibitors/)

- [Spoga Horse 2026 Exhibitor List – spogahorse.com](https://www.spogahorse.com/spoga-horse-exhibitors/list-of-exhibitors/)

- [ISM Cologne 2026 Exhibitor List – ism-cologne.com](https://www.ism-cologne.com/ism-cologne-exhibitors/list-of-exhibitors/)

- [Anuga 2025 Exhibitor List – anuga.com](https://www.anuga.com/anuga-exhibitors/list-of-exhibitors/)

- [Aquanale 2025 Exhibitor List – aquanale.com](https://www.aquanale.com/aquanale-exhibitors/list-of-exhibitors/)

- [Asia-Pacific Sourcing 2025 Exhibitor List – asia-pacificsourcing.com](https://www.asia-pacificsourcing.com/aps-exhibitors/list-of-exhibitors/)

- [FSB Cologne 2025 Exhibitor List – fsb-cologne.com](https://www.fsb-cologne.com/fsb-exhibitors/list-of-exhibitors/)

- [Intermot Cologne 2025 Exhibitor List – intermot-cologne.com](https://www.intermot-cologne.com/intermot-exhibitors/list-of-exhibitors/)

- [Interzum 2025 Exhibitor List – interzum.com](https://www.interzum.com/en/interzum-exhibitors/list-of-exhibitors/)

- [Kind + Jugend 2025 Exhibitor List – kindundjugend.com](https://www.kindundjugend.com/kindundjugend-exhibitors/list-of-exhibitors/)

- [Spoga+Gafa 2025 Exhibitor List – spogagafa.com](https://www.spogagafa.com/spoga-gafa-exhibitors/list-of-exhibitors/)

- [The Tire Cologne 2025 Exhibitor List – thetire-cologne.com](https://www.thetire-cologne.com/ttc-exhibitors/list-of-exhibitors/)

- [IDS (International Dental Show) 2025 Exhibitor List – english.ids-cologne.de](https://www.english.ids-cologne.de/ids-cologne-exhibitors/list-of-exhibitors/)

- [Gamescom 2025 Exhibitor List – exhibitors.gamescom.global](https://exhibitors.gamescom.global/en/gamescom-exhibitors/list-of-exhibitors/)

- [Orgatec 2024 Exhibitor List – orgatec.com](https://www.orgatec.com/orgatec-exhibitors/list-of-exhibitors/)

- [Anuga FoodTec 2024 Exhibitor List – anugafoodtec.com](https://www.anugafoodtec.com/anuga-foodtec-exhibitors/list-of-exhibitors/)

---

## Data Fields

<table>
  <thead>
    <tr>
    <th><span style="font-size:14px;">Company</span></th>
    <th><span style="font-size:14px;">Social</span></th>
    <th><span style="font-size:14px;">Additional</span></th>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td>Profile URL</td>
            <td>LinkedIn</td>
            <td>Hall Stands</td>
        </tr>
        <tr>
            <td>Company Name</td>
            <td>Facebook</td>
            <td>Product Groups</td>
        </tr>
        <tr>
            <td>Address</td>
            <td>Instagram</td>
            <td>Brands</td>
        </tr>
        <tr>
            <td>Website</td>
            <td>Twitter / X</td>
            <td>Target Markets</td>
        </tr>
        <tr>
            <td>Email</td>
            <td>YouTube</td>
            <td>Product Emphasis</td>
        </tr>
        <tr>
            <td>Phone</td>
            <td></td>
            <td>Product Sectors</td>
        </tr>
    </tbody>
</table>

---

## Example Output

```json
{
  "___exhibitor_profile_url": "https://www.eisenwarenmesse.com/exhibitor/brunox_ag/",
  "__company_name": "Brunox AG",
  "_company_address": "Tunnelstrasse 6, 8732, Neuhaus, Switzerland",
  "_company_country": "Switzerland",
  "_company_website": "http://www.brunox.swiss",
  "_company_email": "office@brunox.com",
  "_company_phone": "+41 552858080",
  "_hall_stands": "Hall 11.1 | G028",
  "_social_url_linkedin": "https://ch.linkedin.com/company/brunox-ag",
  "_social_url_facebook": "https://www.facebook.com/brunoxswiss/?locale=de_DE",
  "_social_url_instagram": "https://www.instagram.com/brunox_ag/",
  "brands": "BRUNOX® Epoxy® | BRUNOX® epoxy® | BRUNOX® Turbo-Spray® | BRUNOX® Turbo-Spray®",
  "target_and_outlet_markets": "Australia | East Africa | Japan | Middle East | New Zealand | Northern Europe | Others Eastern Europe | South Africa | Southern Europe | Western Europe",
  "product_emphasis": "workshop and factory equipment, industrial supplies, protective equipment",
  "product_sector": "Industrial Supply",
  "product_groups": [
    {
      "title": "Hand Tools",
      "subgroups": [
        {
          "title": "Car tools, special",
          "subgroups": null
        },
        {
          "title": "Gardening, agricultural and forestry tools",
          "subgroups": null
        },
        {
          "title": "Joiners' and carpenters' tools",
          "subgroups": null
        }
      ]
    },
    {
      "title": "workshop and factory equipment, industrial supplies, protective equipment",
      "subgroups": [
        {
          "title": "Anti-corrosion products, lubricating-stuff",
          "subgroups": null
        }
      ]
    }
  ]
}
```

---

## My Other Exhibitor List Scrapers

- [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

- [Messe Frankfurt Exhibitor List Scraper](https://apify.com/skython/messe-frankfurt-exhibitor-list-scraper)

- [Map Your Show Exhibitor List Scraper](https://apify.com/skython/map-your-show-exhibitor-list-scraper)

- [Messe Düsseldorf Exhibitor List Scraper](https://apify.com/skython/messe-duesseldorf-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper](https://apify.com/skython/xporience-exhibitor-list-scraper)

- [Reed Expo Exhibitor List Scraper](https://apify.com/skython/reed-expo-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper V2](https://apify.com/skython/xporience-exhibitor-list-scraper-2)

- [Nürnberg Messe Exhibitor List Scraper](https://apify.com/skython/nuernberg-messe-exhibitor-list-scraper)

- [GSMA MWC Exhibitor List Scraper](https://apify.com/skython/gsma-mwc-exhibitor-list-scraper)

- [Messe Berlin Exhibitor List Scraper](https://apify.com/skython/messe-berlin-exhibitor-list-scraper)

- [AFAG Messe Exhibitor List Scraper](https://apify.com/skython/afag-messe-exhibitor-list-scraper)

- [Messe Stuttgart Exhibitor List Scraper](https://apify.com/skython/messe-stuttgart-exhibitor-list-scraper)

- [Messe Essen Exhibitor List Scraper](https://apify.com/skython/messe-essen-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper](https://apify.com/skython/informa-markets-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper V2](https://apify.com/skython/informa-markets-exhibitor-list-scraper-2)

- [Ungerboeck Exhibitor List Scraper](https://apify.com/skython/ungerboeck-exhibitor-list-scraper)

- [A2Z Events Exhibitor List Scraper](https://apify.com/skython/a2z-events-exhibitor-list-scraper)

- [Deutsche Messe Exhibitor List Scraper](https://apify.com/skython/deutsche-messe-exhibitor-list-scraper)

- [Newfront Exhibitor List Scraper](https://apify.com/skython/newfront-exhibitor-list-scraper)

- [Goeshow Exhibitor List Scraper](https://apify.com/skython/goeshow-exhibitor-list-scraper)

- [EasyFairs Exhibitor List Scraper](https://apify.com/skython/easyfairs-exhibitor-list-scraper)

- [IEG Expo Exhibitor List Scraper](https://apify.com/skython/ieg-expo-exhibitor-list-scraper)

- [The Smarter E Exhibitor List Scraper](https://apify.com/skython/the-smarter-e-exhibitor-list-scraper)

- [Schall Messen Exhibitor List Scraper](https://apify.com/skython/schall-messen-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper V2](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper-2)

- [Comexposium Exhibitor List Scraper](https://apify.com/skython/comexposium-exhibitor-list-scraper)

- [IME Events Exhibitor List Scraper](https://apify.com/skython/ime-events-exhibitor-list-scraper)

- [ANDMORE Exhibitor List Scraper](https://apify.com/skython/andmore-exhibitor-list-scraper)

- [Comexposium Exhibitor List Scraper V2](https://apify.com/skython/comexposium-exhibitor-list-scraper-2)