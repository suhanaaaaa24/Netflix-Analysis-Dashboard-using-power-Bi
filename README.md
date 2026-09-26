# Netflix Catalog Analytics Dashboard Using Power BI

## Project Overview

This project presents an interactive Netflix Catalog Analytics Dashboard developed using Microsoft Power BI. The dashboard analyzes a catalog of movies and TV shows to understand content distribution, audience ratings, release trends, duration patterns, countries, directors, and data quality.

The project transforms raw catalog data into an interactive multi-page dashboard using data cleaning, calculated columns, DAX measures, and data visualizations.

---

## Project Objectives

The main objectives of this project are:

- Analyze the overall Netflix content catalog
- Compare Movies and TV Shows
- Understand the distribution of audience rating categories
- Analyze the number of titles released across different years and decades
- Identify countries contributing the most titles
- Study movie duration and TV show season patterns
- Analyze director information
- Identify missing or incomplete data in the catalog
- Present the findings through interactive Power BI visualizations

---

## Dataset Overview

The dataset used for this project is:

**File:** `netflix_catalog_data (1).xlsx`

The dataset contains **3,000 titles and 8 columns**.

### Main Columns

| Column | Description |
|---|---|
| Show ID | Unique identifier for each title |
| Title | Name of the movie or TV show |
| Type | Movie or TV Show |
| Director | Director associated with the title |
| Country | Country associated with the title |
| Release Year | Year the title was released |
| Rating | Audience/content rating |
| Duration | Movie duration or number of TV seasons |

---

## Tools & Technologies Used

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel
- Data Visualization

---

## Data Preparation

The dataset was prepared before creating the dashboard.

The project includes:

- Data type checking
- Data cleaning
- Creation of calculated columns
- Duration extraction
- Decade grouping
- Rating categorization
- Director availability checks
- Creation of DAX measures

---

## Calculated Columns

Eight calculated columns were created in Power BI:

1. Is Movie
2. Duration Minutes
3. Duration Seasons
4. Content Age
5. Decade
6. Rating Category
7. Has Director
8. Title Length

These columns were created to make the raw catalog data easier to analyze and visualize.

---

## DAX Measures

DAX measures were created for:

- Total Titles
- Total Movies
- Total TV Shows
- % Movies
- % TV Shows
- Distinct Countries
- Distinct Directors
- Average Movie Duration
- Longest Movie
- Shortest Movie
- Average TV Seasons
- Titles in Latest Year
- Titles YoY Change
- Top Country
- Mature Content %
- Missing Director %

These measures support the dashboard KPIs, charts, and analysis.

---

# Dashboard Pages

## Page 1 — Executive Overview

The Executive Overview provides a high-level summary of the Netflix catalog.

It includes:

- Total Titles
- Total Movies
- Total TV Shows
- Average Release Year
- Movie vs TV Show distribution
- Titles by Release Year/Decade
- Titles by Rating Category

The dashboard contains **3,000 total titles**, including **1,535 Movies and 1,465 TV Shows**.

---

## Page 2 — Ratings & Audience Insights

This page focuses on audience and geographic information.

It includes:

- Mature Content %
- Distinct Countries
- Average Release Year
- Audience Rating Mix
- Top Countries by Title Count

The dashboard shows **20 distinct countries** and an **18.5% mature-content percentage**.

---

## Page 3 — Duration Analysis

This page analyzes the duration patterns of Movies and TV Shows.

It includes:

- Average Movie Duration by Decade
- Average TV Seasons by Decade
- Longest Movie
- Shortest Movie
- Average Movie Duration
- Average TV Seasons

The dashboard reports an average movie duration of **125.1 minutes** and an average of **5.1 TV seasons**.

---

## Page 4 — Directors & Data Quality

This page focuses on director information and catalog data quality.

It includes:

- Distinct Directors
- Missing Director %
- Top Directors by Title Count
- Country and Type filters

The dashboard shows **5.3% of titles missing director information**.

---

## Interactive Features

The dashboard uses slicers and filters to allow users to interact with the data.

Filters include:

- Type
- Country
- Release Year
- Rating
- Decade

Users can use these filters to explore different sections of the Netflix catalog.

---

## Key Insights

Some of the key observations from the dashboard include:

- Movies and TV Shows form two major parts of the catalog, with Movies representing 51.17% and TV Shows 48.83%.
- The catalog contains 3,000 titles.
- The dataset represents 20 distinct countries.
- The average release year is 2012.
- The mature-content percentage is 18.5%.
- The average movie duration is 125.1 minutes.
- The average number of TV seasons is 5.1.
- 5.3% of titles do not have director information recorded.

---

## Project Files

This repository contains the following project files:

- `netflix catlog dashboard FINALLLLL pdf.pdf` — Final Power BI dashboard exported as PDF
- `netflix_catalog_data (1).xlsx` — Source dataset
- `netflix_powerbi_dashboard_design(1).pptx` — Dashboard design and project presentation
- `README.md` — Project documentation
- `.pbix` — Power BI project file, if included

---

## Dashboard Structure

The dashboard follows this navigation:

**Executive Overview → Ratings & Audience Insights → Duration Analysis → Directors & Data Quality**

This structure allows the user to move from an overall catalog summary to detailed audience, duration, and data-quality analysis.

---

## Conclusion

The Netflix Catalog Analytics Dashboard converts raw catalog data into an interactive Power BI report. It provides a structured view of content type, ratings, release trends, geographic distribution, duration patterns, director information, and data quality.

The project demonstrates the use of Power Query, calculated columns, DAX measures, slicers, KPIs, and data visualization to create an interactive business intelligence dashboard.

Suhana Jaganath

**Netflix Catalog Analytics — Power BI Project**
