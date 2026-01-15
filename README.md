# Inventory-Mismatch-Unlocking-Hidden-Revenue-
Final Project for Visual Analytics, Fall 2025 

This code comes from RICS POS System from January 1, 2020, to October 20, 2025.

Each code file is from Google Colab using Python
  - Time Series aggregates sales by day for each month, and shows the next 12 months prediction. There is a lag on January, reflecting the slowest month for the store, and with a spike on August (big time for cross country, kids going back to store, and people ramping up for Fall races).
  - Heat map data looks at the proportion of money that have come from Zip Codes, joining a GeoJson file for NC Zip Codes. This shows that sales center around the store's closest zip codes, and point to where potential marketing could take place to gain new customers.
  - Review code looks at over 500 Google Reviews during the same period of interest, removes non-text Google Reviews, and performs topic modeling and creates a word cloud to look at sentiment. 
