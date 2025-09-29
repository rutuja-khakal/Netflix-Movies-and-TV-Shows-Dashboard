# Netflix-Movies-and-TV-Shows-Dashboard
Power BI Dashboard showing Netflix content analysis by genre, country, year, and type.
# Netflix Dashboard Task 2

## Objective
Create a Power BI dashboard that visualizes Netflix content trends by genre, release year, country, and content type.

## Dataset
Netflix Movies & TV Shows (cleaned)

## Steps Taken
1. Data Cleaning & Preprocessing
   - Removed duplicates, null values, and inconsistent formats.
   - Split `Listed_In` column into multiple genre columns.
   - Converted `date_added` to DateTime type.

2. Data Visualization
   - **Cards**: Total Content, Total Movies, Total TV Shows
   - **Donut Chart**: Movies vs TV Shows distribution
   - **Line Chart**: Year-wise content addition
   - **Treemap**: Top genres
   - **Map**: Content by country
   - **Bar Chart**: Top directors / actors
   - **Bar**: Ratings distribution
   - **Slicers**: Year, Type, Genre, Country for interactivity

## Key Insights
- Most content is from [Country/Genre insight]  
- Netflix has been growing steadily since [Year]  
- Top actors and directors contribute significantly to content diversity  

## Files
- `Netflix_Dashboard.pbix` → Power BI file  
- `Netflix_Cleaned.csv` → Cleaned dataset  
- `Netflix_Dashboard_Screenshot.png` → Dashboard screenshot
