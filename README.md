# **Hotel Booking Demand Analysis**

A comprehensive data analysis project using the **Hotel Booking Demand** dataset from Kaggle. The goal is to understand guest behavior patterns, cancellations, revenue generation, and how various booking features (like lead time, country, meal type, and special requests) influence outcomes such as stay duration and cancellation likelihood.

## **Project Summary**

This analysis investigates patterns across five key questions:

1. **Do special requests and room assignment impact guest satisfaction and stay duration?**
2. **How does lead time affect cancellation rates and revenue?**
3. **Are there country-wise differences in guest behavior and booking patterns?**
4. **Does meal type influence booking behavior, cancellations, and volume?**
5. **How do repeated guests and waitlisted bookings differ from others?**

## **Key Findings**

Special Requests: Guests who make more special requests stay longer and cancel less.

Room Assignment: Matched room types lead to longer stays and far fewer cancellations.

Lead Time: Bookings with very long lead times (375+ days) show unusually high cancellation rates and lower revenue.

Country Patterns: Guests from Germany, UK, and Ireland book well in advance and cancel less. Portugal, being local, has higher cancellation rates.

Meal Types: "Breakfast Only" is most popular. Surprisingly, "Full Board" guests cancel more often than expected.

Repeated Guests: They cancel less but make more booking changes.

Waitlisted Bookings: High cancellation rates, fewer booking modifications.

## **Tools & Technologies**
Language: R

Libraries: ggplot2, dplyr, tidyverse, lubridate, scales, readr

Visualization: Custom plots using ggplot2

## **Report & Documentation**
**A full analysis report is provided as Hotel_booking_analysis_Report.pdf**

Note: To view the report in HTML mode, please use the "Download" button (top-right of the file). Once downloaded, open the file in any web browser for the proper formatted view.

The report consists of detailed information like:
- Introduction
- Background
- Methodology
- Questions (each question wise assumption, result, conclusion)
- Overall Results
- Overall Conclusion
- References
- Appendix
  
  -- A. has all variable(column) names and meaning
  
  -- B. has all countries based on their ISO country code.

**A full analysis ppt is also provided as Hotel_booking_analysis_PPT**

Each research question is backed by:
- Clear assumptions
- Visual insights
- Observational results
- Summarized conclusions

## **References**
- Mostipak, Jesse. Hotel Booking Demand. Kaggle, 2018, https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand. (link to download the dataset)
- “ggplot2.” The Tidyverse, https://ggplot2.tidyverse.org/. (documentation)
- “dplyr.” The Tidyverse, https://dplyr.tidyverse.org/. (documentation)
- Grolemund, Garrett, and Hadley Wickham. R for Data Science. O’Reilly Media, 2018.

## **Contact**

Let me know if you'd like to personalize any section or add a GitHub Pages link if you’re publishing your HTML report too!
