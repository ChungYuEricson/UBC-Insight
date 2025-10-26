# UBC-Insight

This project delivers a robust full-stack data management and query system for university data, specifically focusing on Course Sections and Campus Rooms. The core component is the InsightFacade, which manages the loading, storing, and querying of two dataset types: academic Section data (parsed from JSON, including grades, courses, and terms) and Room data (scraped from HTML and enriched with latitude/longitude coordinates via an external geocoding service). 

The system features a EBNF-compliant query engine capable of performing complex filtering, sorting, and transformations (grouping and aggregation) across the datasets.

A RESTful API, implemented using an Express.js server, provides all dataset and query functionality to clients.

Due to course policy, the source code for this project cannot be publicly posted on GitHub. However, here's a [demo video](https://vimeo.com/1130383726) showcasing the application's full functionality and user experience:
