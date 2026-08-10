# Taraz Semi-Finished Foods Market Analysis

Scraped and analyzed the local полуфабрикаты (semi-finished foods) market in Taraz, Kazakhstan using 2GIS data - instead of using a pre-made Kaggle dataset.

## Data

Scraped 53 business listings from 2GIS using [parser-2gis](https://github.com/interlark/parser-2gis), searching for "магазин полуфабрикаты" in Taraz. Filtered down to 44 relevant listings (removed a few seafood/unrelated shops pulled in by overlapping category tags).

## What I looked at

- Ratings and review counts across competitors
- Geographic distribution of shops across the city

## Key findings

- Average rating among rated shops is 4.4 — the market is generally well-regarded
- But visibility is low: median review count is just 3, and only a handful of shops (like BariBar АЮ with 25 reviews) have real traction
- Mapping the listings showed clear gaps in coverage - noticeably fewer shops in the northwest and southeast parts of the city than in the center


## Tools

Python, pandas, parser-2gis, folium, matplotlib

