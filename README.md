# Investing.com Economic Indicators

List of all the economic indicators from [Investing.com](https://www.investing.com/).

Available as a [CSV table](economic_table.csv).

The list is read from the [Economic Calendar page](https://www.investing.com/economic-calendar/), 
using the follwing protocol:

- Open `Filters`
- `Select All` Countries
- Select all `Importance` levels
- `Apply` filters
- Select `This Week` or `Next Week` tab
- `Save as...` HTML page (try multiple times as the Downloas is often stopped before completion)
- Rename it by starting weekdate (Sunday) and add it to the `html_calendars` folder

For each indicator other info are parsed from the URL of the indicator page: `Title`, `Source`, `Source_link`, `Currency` and `Description`.

## Most Important Indicators (three stars)
1. [United States ADP Nonfarm Employment Change - ID #1](https://www.investing.com/economic-calendar/adp-nonfarm-employment-change-1)
2. [United States Average Hourly Earnings MoM - ID #8](https://www.investing.com/economic-calendar/average-hourly-earnings-8)
3. [United States Building Permits - ID #25](https://www.investing.com/economic-calendar/building-permits-25)
4. [United States CB Consumer Confidence - ID #48](https://www.investing.com/economic-calendar/cb-consumer-confidence-48)
5. [United States Core Consumer Price Index (CPI) MoM - ID #56](https://www.investing.com/economic-calendar/core-cpi-56)
6. [United States Core Durable Goods Orders MoM - ID #59](https://www.investing.com/economic-calendar/core-durable-goods-orders-59)
7. [United States Core PCE Price Index MoM - ID #61](https://www.investing.com/economic-calendar/core-pce-price-index-61)
8. [United States Core Retail Sales MoM - ID #63](https://www.investing.com/economic-calendar/core-retail-sales-63)
9. [United Kingdom Consumer Price Index (CPI) YoY - ID #67](https://www.investing.com/economic-calendar/cpi-67)
10. [European Consumer Price Index (CPI) YoY - ID #68](https://www.investing.com/economic-calendar/cpi-68)
11. [United States Consumer Price Index (CPI) MoM - ID #69](https://www.investing.com/economic-calendar/cpi-69)
12. [United States Crude Oil Inventories - ID #75](https://www.investing.com/economic-calendar/eia-crude-oil-inventories-75)
13. [United States Existing Home Sales - ID #99](https://www.investing.com/economic-calendar/existing-home-sales-99)
14. [U.S. Federal Reserve (Fed) Meeting Minutes - ID #108](https://www.investing.com/economic-calendar/fomc-meeting-minutes-108)
15. [Japan Gross Domestic Product (GDP) QoQ - ID #119](https://www.investing.com/economic-calendar/gdp-119)
16. [United Kingdom Gross Domestic Product (GDP) QoQ - ID #121](https://www.investing.com/economic-calendar/gdp-121)
17. [New Zealand Gross Domestic Product (GDP) QoQ - ID #125](https://www.investing.com/economic-calendar/gdp-125)
18. [Germany Consumer Price Index (CPI) MoM - ID #128](https://www.investing.com/economic-calendar/german-cpi-128)
19. [Germany Gross Domestic Product (GDP) QoQ - ID #131](https://www.investing.com/economic-calendar/german-gdp-131)
20. [Germany Manufacturing Purchasing Managers Index (PMI) - ID #136](https://www.investing.com/economic-calendar/german-manufacturing-pmi-136)
21. [European Interest Rate Decision - ID #164](https://www.investing.com/economic-calendar/interest-rate-decision-164)
22. [Canada Interest Rate Decision - ID #166](https://www.investing.com/economic-calendar/interest-rate-decision-166)
23. [New Zealand Interest Rate Decision - ID #167](https://www.investing.com/economic-calendar/interest-rate-decision-167)
24. [United States Federal Reserve Interest Rate Decision - ID #168](https://www.investing.com/economic-calendar/interest-rate-decision-168)
25. [Switzerland Interest Rate Decision - ID #169](https://www.investing.com/economic-calendar/interest-rate-decision-169)
26. [United Kingdom Interest Rate Decision - ID #170](https://www.investing.com/economic-calendar/interest-rate-decision-170)
27. [Australia Interest Rate Decision - ID #171](https://www.investing.com/economic-calendar/interest-rate-decision-171)
28. [United States ISM Manufacturing PMI - ID #173](https://www.investing.com/economic-calendar/ism-manufacturing-pmi-173)
29. [United States ISM Non-Manufacturing PMI - ID #176](https://www.investing.com/economic-calendar/ism-non-manufacturing-pmi-176)
30. [United Kingdom Manufacturing Purchasing Managers Index (PMI) - ID #204](https://www.investing.com/economic-calendar/manufacturing-pmi-204)
31. [United States New Home Sales - ID #222](https://www.investing.com/economic-calendar/new-home-sales-222)
32. [United States Nonfarm Payrolls - ID #227](https://www.investing.com/economic-calendar/nonfarm-payrolls-227)
33. [United States Pending Home Sales MoM - ID #232](https://www.investing.com/economic-calendar/pending-home-sales-232)
34. [United States Philadelphia Federal Reserve Manufacturing Index - ID #236](https://www.investing.com/economic-calendar/philadelphia-fed-manufacturing-index-236)
35. [United States Producer Price Index (PPI) MoM - ID #238](https://www.investing.com/economic-calendar/ppi-238)
36. [United States Retail Sales MoM - ID #256](https://www.investing.com/economic-calendar/retail-sales-256)
37. [United States Initial Jobless Claims - ID #294](https://www.investing.com/economic-calendar/initial-jobless-claims-294)
38. [United States Unemployment Rate - ID #300](https://www.investing.com/economic-calendar/unemployment-rate-300)
39. [Bank of Japan (BoJ) Press Conference - ID #370](https://www.investing.com/economic-calendar/boj-press-conference-370)
40. [United States Gross Domestic Product (GDP) QoQ - ID #375](https://www.investing.com/economic-calendar/gdp-375)
41. [European Central Bank (ECB) Press Conference - ID #396](https://www.investing.com/economic-calendar/ecb-press-conference-396)
42. [U.S. Federal Reserve (Fed) Statement - ID #398](https://www.investing.com/economic-calendar/fomc-statement-398)
43. [China Gross Domestic Product (GDP) YoY - ID #461](https://www.investing.com/economic-calendar/chinese-gdp-461)
44. [China Industrial Production YoY - ID #462](https://www.investing.com/economic-calendar/chinese-industrial-production-462)
45. [China Manufacturing Purchasing Managers Index (PMI) - ID #594](https://www.investing.com/economic-calendar/chinese-manufacturing-pmi-594)
46. [United Kingdom Gross Domestic Product (GDP) YoY - ID #728](https://www.investing.com/economic-calendar/gdp-728)
47. [United States Consumer Price Index (CPI) YoY - ID #733](https://www.investing.com/economic-calendar/cpi-733)
48. [United States JOLTs Job Openings - ID #1057](https://www.investing.com/economic-calendar/jolts-job-openings-1057)
49. [U.S. Federal Reserve (Fed) Economic Projections - ID #1061](https://www.investing.com/economic-calendar/fomc-economic-projections-1061)
50. [United States Services Purchasing Managers Index (PMI) - ID #1062](https://www.investing.com/economic-calendar/services-pmi-1062)
51. [Euro Zone Deposit Facility Rate - ID #1655](https://www.investing.com/economic-calendar/deposit-facility-rate-1655)
52. [U.S. Federal Reserve (Fed) Press Conference - ID #1692](https://www.investing.com/economic-calendar/fomc-press-conference-1692)
53. [United States Federal Reserve Chair Powell Speaks - ID #1738](https://www.investing.com/economic-calendar/fed-chair-powell-speaks-1738)
54. [United States Federal Reserve Chair Powell Testifies - ID #1739](https://www.investing.com/economic-calendar/fed-chair-powell-testifies-1739)
55. [United Kingdom Gross Domestic Product (GDP) MoM - ID #1792](https://www.investing.com/economic-calendar/gdp-1792)