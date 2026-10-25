# From the Shelf to the Screen: How Australians Use Libraries

FIT3179 Data Visualisation 2. Author: Jordan Lew. Date: 26 October 2026.

**Live site:** https://jordanlew21.github.io/FIT3179---Australians-Library-Usage/

## Domain, who, what, why, how
- **Domain:** Australian public libraries, 2017 to 2025.
- **Who:** The average Australian who is curious how libraries are changing. No statistics knowledge needed.
- **What:** 14 charts, including a choropleth, a proportional symbol map and a dot density map, on library loans, visits, members, programs and who attends.
- **Why:** Libraries are busier and more digital, but fewer people are members and fewer say they attend. The page shows both sides.
- **How:** One scrolling story in Vega-Lite (vega-embed), with each chart in `js/` and its data in `data/`. Chapters: the shift, the catch, where, change, what libraries do now.

## Data sources
- NSLA and ALIA, Australian Public Libraries Statistical Report 2024-25 and 2021-22 (CC BY 4.0). Tables copied from the PDFs into CSV.
- Australian Bureau of Statistics, Cultural and creative activities 2021-22, and Attendance at Selected Cultural Venues and Events 2017-18.
- RMIT University, Australian public lending library locations 2016-2018 (Higgs, C. et al., 2022).
- State boundaries: anthwri/GeoJson-Data on GitHub, converted to TopoJSON.

## Known data limits
- The 2021-22 Australia total leaves out the ACT, so states were summed.
- 2020-21 physical plus digital loans do not add up to the total (9.8m gap).
- Wi-Fi data is patchy and Queensland's reporting scope changed.

## AI use
Claude (Anthropic) helped prepare CSV files, write and debug Vega-Lite specs and edit page text. The author chose the topic, sources and story and checked the figures.
