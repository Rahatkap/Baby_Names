# Baby_Names
**Baby Names Analysis in Tableau**

**Data Import and Preparation:**
1. Connect Tableau to the MySQL database on AWS using the ODBC connector.
   - Tables: NamesPercentByYearNoIndex, NamesNumberByStateYear
   - Utilize NamesNumberByStateYear to find the top name for each state, year, and sex.
   - Use NamesPercentByYearNoIndex to find unisex names for each year.
2. Import CSV files: baby_names.csv, baby_names_by_state.csv, baby_names_by_state_top1.csv, baby_unisex_names.csv.

**Visual Analysis Questions:**

**1. Baby Name Diversity Over Time:**
   - Utilize NamesPercentByYearNoIndex to analyze how baby name diversity changes over time.

**2. Top 10 Boy/Girl Names and Proportions:**
   - Use baby_names.csv to identify the top 10 most popular boy/girl names and visualize their proportions over time.

**3. Top 10 Names in 2008:**
   - Filter the dataset to the year 2008 and analyze the top 10 boy/girl names for that year.

**4. Most Popular Names by State:**
   - Utilize baby_names_by_state.csv to determine the most popular boy/girl name in each state and observe changes over the years.

**5. Unisex Names Analysis:**
   - Use NamesPercentByYearNoIndex and baby_unisex_names.csv to identify unisex names for each year.
   - Compare the proportion of each unisex name among girls and boys.

**6. Bubble Chart for Top N Names:**
   - Create a bubble chart showing the top "N" baby names. Allow users to choose gender, year, and "N" (in the range [1,50]).

**7. Bubble Chart for Top N Names in a State:**
   - Import table "NamesNumberByStateYear" or csv file "baby_names_by_state.csv."
   - Create a bubble chart showing the top "N" baby names. Allow users to pick year, state, gender, and the parameter "N" (in the range [1,50]).

**8. Line Chart for Top 1 Boy/Girl Name and Percent:**
   - Create a line chart showing the top 1 boy/girl name and its percentage for each year.

**Baby Names Dashboard:**
   - Create a dashboard with three visualizations:
      - A map showing the most popular baby name by state.
      - Top N names in the U.S.
      - Top N names in a selected state.
   - Allow users to:
      - Select year, state, sex.
      - Specify "N" for the bubble charts.

By implementing these visualizations and dashboards in Tableau, users can gain insights into the popularity and diversity of baby names over time, across states, and by gender. The interactive features enable users to customize their analysis and explore different aspects of the dataset.
