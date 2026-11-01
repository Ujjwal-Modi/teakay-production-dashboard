# Teakay Production Dashboard

A single-page dashboard that reads the Production Google Sheet live in the browser and shows wrapper/laddi/shrink wastage, broken %, sweepage, scrap, RM variance, breakdown, gas, electricity and manpower against standards (red above, green at or below).

- The page is `index.html` (no build step). It loads d3 from cdnjs.
- The sheet must be shared as "Anyone with the link: Viewer".
- Don't insert or move columns in the sheet's tabs: the page reads columns by position.
