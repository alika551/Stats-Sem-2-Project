# Semester 2 Intermediate Statistics Project
## Introduction and Methodology
For our final semester 2 statistics project, we had to choose an overarching topic on which quantitative data can be collected. I chose the topic "WHat are the considerbale differences in consumer behaviour of Gen Z and Gen X when engaging with quick commerce platforms?" 

### The Survey 
A quantitative, cross-sectional survey was designed and digitally administered via Google Forms between April 10–18, 2026. to examine generational differences in quick commerce consumer behaviour across Indian urban markets. 

Quantitative items captured: weekly order frequency, last order spend (in INR), discount dependency (7-point Likert), proportion of eco-friendly items ordered (count out of 7), delivery speed satisfaction (7-point Likert), peak ordering time (four categories), number of apps installed, impulse item count, app frustration rating (7-point Likert), delivery time preference, primary product categories, and main motivation for platform use. Respondents were segmented at the point of collection by self-reported age band (Group 1: 14–30; Group 2: 40–75), subsequently re-labelled Gen Z and Gen X for analytical clarity. City tier (Tier-1, Tier-2, Tier-3) was collected as a proxy for market maturity and infrastructure quality.

### The Responses and Data Cleaning
A deliberate effort was made to balance representation across both generational cohorts; final usable responses comprised 54 Gen Z and 47 Gen X participants. The sample is appropriate for exploratory hypothesis testing and generating directional insights about generational behavioural differences.

Raw data (121 responses) underwent a three-stage cleaning process before analysis:
•	Stage 1 — Extreme outlier removal: Two responses were excluded as implausible data entries. One Gen X respondent reported 67 orders in 7 days with a spend of INR 10,000,000 (almost certainly a test or joke entry). A second Gen X response recorded 1,577 weekly orders with a spend of INR 8, suggesting a column shift or data corruption. Both were flagged and removed, leaving 119 observations.
•	Stage 2 — Zero-order exclusion: An additional 18 responses reported zero orders in the past 7 days. Including non-users would conflate usage behaviour with non-adoption, distorting group means and violating the Poisson distributional assumption (a zero-inflated distribution would require a separate model). These were excluded, yielding a final analytical sample of 101 active quick commerce users.
•	Stage 3 — Variable standardisation: Free-text entries for 'Main Reason' were mapped to five canonical categories (Convenience, 24/7 Availability, Speed, Variety, Discounts). Binary response fields (Yes/No) were recoded to 1/0 for use in regression and proportion tests. Category columns were parsed to produce dummy indicator variables for each product category.

Final analytical sample: n = 101  (Gen Z: 54 | Gen X: 47)

## The Research Questions 
Four research questions were addressed, each with a dedicated probability model, estimation method, and hypothesis test. They have been explored in depth in the attached files, along with descriptive statistics analyses.
