# Agriculture Dashboard for Grains and Oilseeds in the EU

This repository contains a Power BI dashboard that tracks key agricultural Key Performance Indicators (KPIs) for the main Grains (wheat, corn, and barley) & Oilseeds (sunflower and rapeseed) in the European Union from 1961 to 2021.

## Business Questions

The dashboard aims to answer the following questions:

- How have the yield, harvested area, and production of different crops changed over time in the EU?
- Can historical data be used to make predictions or forecasts about future yield, harvested areas, or production quantities?
- Which countries are the leading five producers on an annual basis or during distinct time periods?
- How has the EU's/member states' productivity in terms of efficient land cultivation changed over the past six decades?

## Dataset Description

The dashboard utilizes the FAOSTAT database, the official database of the Food and Agriculture Organization of the United Nations. The dataset focuses on primary crops (Corn, Wheat, Barley, Sunflowerseed, Rapeseed) in EU countries, covering elements such as Area Harvested, Yield, and Production Quantity.

For detailed dataset information and filtering, refer to the [FAOSTAT database](https://www.fao.org/faostat/en/#data/QCL).

## Dashboard Layout

The dashboard comprises three main areas:

1. Header area (Title & subtitle)
2. KPI and filter area
3. Main charts area

### Main Charts

1. **Crop Yields (mt/ha) vs. Harvested Area (ha):** A line chart showing aggregated values of yield and harvested areas over time.
2. **Total Production (mt):** A bar chart displaying the top 5 countries in the category of total produced quantity.
3. **Total Harvested Area (ha):** A column chart displaying the top 5 countries in the category of total harvested area.

### KPI Cards

Three KPI cards provide key metrics for the selected filtering:

1. Total Harvested Area (ha)
2. Total Production (mt)
3. Average Yield (mt/ha)

### Slicers

Three slicers enable user interaction:

1. **Crop:** Dropdown slicer with multi-select for the Item field.
2. **Country:** Dropdown slicer with multi-select for the Area field.
3. **Year:** "Between" slicer for the Year column.

### Non-visible Filters

The Total Production and Total Harvested Area charts feature a Top N filtering for the top 5 countries by the sum of Production and Harvested Area, respectively.

For detailed usage instructions and additional insights, refer to the [detailed documentation](link-to-detailed-documentation.md) provided.


### Result

![image](https://github.com/szilvasipeter2000/Data_Visualization/assets/144559314/5cbd8b7e-6525-4b02-b645-257fc6dc38dc)

