# Calculate timeline of Journal of Fluid Mechanics manuscript

My advisor wanted to know how long our JFM paper was going to get stuck in the review system. JFM has no data regarding time to first decision or time to acceptance, so I decided to calculate it myself. This Jupyter notebook scrapes the JFM search page for PDF links to Open Access articles, opens each PDF one by one, and searches for the "Received" keyword to get the date info. If too many PDFs are accessed sometimes Cambridge complains and throws an error that tells the script to go away. Which is why, Cambridge, you should really consider just putting the dates on the HTML pages instead.

Anyway, based on past 5 years data from 2018 to 2023, JFM's mean time to first revision was approximately 160.2 days, and mean time to acceptance was approximately 195.7 days. That's approximately 5-7 months! I guess whoever says "JFM is notoriously slow" may indeed be right...

## Legal

Cambridge Core is awesome and, apparently, [they seem totally OK with people scraping their site](https://www.cambridge.org/core/legal-notices/terms). JFM itself also [seems perfectly okay with data mining](https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/information/journal-policies/rights-and-permissions), which makes this script perfectly acceptable, I suppose. Thanks, Cambridge!
