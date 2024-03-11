# Use Case Descriptions 

## Use Case 1: View All Webpages Performance

**Actor:** SEO Specialist

**Description:** Allows the SEO Specialist to view performance metrics of all managed webpages to identify improvement opportunities.

**Pre-conditions:** Actor is logged in Spienzer and has chosen a project.

**Scenario:**
1. SEO Specialist requests to view all webpages' performance metrics.
2. The system displays a dashboard listing all webpages with their performance metrics.
3. SEO Specialist uses sorting/filtering options to prioritize webpages, based on their metrics.
4. System displays the webpages in the sorted order.

**Extensions:**<br />
3a. View webpage perfomance.
   1. SEO Specialist chooses a webpage
   2. System displays the webpage analysis 

**Exceptions:**
4. Sytem message: "No data is available".<br />
4.1 Use case ends here.


## Use Case 2: View Webpage Performance

**Actor:** Content Creator

**Description:** Enables the Content Creator to see detailed performance metrics of a selected webpage to guide content improvement.

**Pre-conditions:** Actor has chosen to view all webpages performance.

**Scenario:**
1. Content Creator selects a webpage from the list.
2. The system **displays search results & SERP ranking data** and **real web traffiic data** for the selected webpage.
3. Content Creator views the data.

**Extensions:**<br />
3a. View predicted web traffic data:
   1. Content Creator chooses to view predicted web ttraffic data.
   2. System displays the prediction(s).

<!-- -->

3b. Identify pages needing optimization:
   1. Content Creator chooses to identify pages needing optimization.
   2. System displays the outcome.

<!-- -->

3c. Export Data:
   1. Content Creator chooses to export the webpage data to a file.
   2. System prompts for file type.
   3. Content Creator selects file type.
   4. System prompts for saving location and file name.
   5. Content Creator inputs the data.
   6. System presents the file.
      
**Exceptions:**
2. Sytem message: "No data is available".<br />
2.1 Use case ends here.

## Use Case 3: View Search Volume and SERP Ranking Data

**Actor:** Content Creator

**Description:** Allows the Content Creator to view search volume and SERP rankings for the primary keyword of their webpages.

**Pre-conditions:** Actor has chosen to view all webpages performance.

**Scenario:**
1. Content Creator accesses the dashboard for specific webpage analytics.
2. The system shows SERP ranking and search volume for the primary keyword.

**Exceptions:**
2. Sytem message: "No data is available".<br />
2.1 Use case ends here.

## Use Case 4: View Real Web Traffic Data

**Actor:** SEA Manager

**Description:** Enables the SEA Manager to access web traffic data from Google Analytics for ad calculations.

**Pre-conditions:** Actor has chosen to view all webpages performance.

**Scenario:**
1. SEA Manager requests to view web traffic data.
2. The system retrieves and displays traffic data for via Google Analytics API integration.

**Exceptions:**
2. Sytem message: "No data is available".<br />
2.1 Use case ends here.

## Use Case 5: Identify Pages Needing Optimization

**Actor:** Website Owner

**Description:** Helps the Website Owner identify webpages that require optimization to improve performance.

**Pre-conditions:** Actor has chosen to view all webpages performance.

**Scenario:**
1. Website Owner views a list of all pages with their performance metrics.
2. The system highlights or flags pages that require optimization.


## Use Case 6: View Predicted Web Traffic Data

**Actor:** Website Owner

**Description:** Allows the Website Owner to view predicted traffic data to estimate future site visits.

**Pre-conditions:** Actor has chosen to view webpage performance.

**Scenario:**
1. Website Owner requests predicted traffic data.
2. The system displays traffic predictions for the next month.

**Exceptions:**
2. Sytem message: "Data is still gathering, try again later".<br />
2.1 Use case ends here.

## Use Case 7: Export Data

**Actor:** Digital Marketing Analyst

**Description:** Enables the Digital Marketing Analyst to export data for external analysis.

**Pre-conditions:** Actor has chosen to view webpage performance.

**Scenario:**
1. Digital Marketing Analyst selects data to export.
2. System provides options for file formats.
3. Digital Marketing Analyst chooses format.
4. System prompts for saving location and file name.
5. Digital Marketing Analyst inputs the data.
6. System provides the file.

**Exceptions:**
6. Sytem message: "Invalid location!".<br />
6.1 Use case ends here.<br />
6. Sytem message: "Invalid file name!".<br />
6.1 Use case ends here.

