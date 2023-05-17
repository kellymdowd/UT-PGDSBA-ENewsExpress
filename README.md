# UT-PGDSBA-ENewsExpress
_This project was completed as part of Module 2 - Business Statistics in the UT Austin Post Graduate Program in Data Science & Business Analytics._

## Problem Statement and Objective
E-news Express believes that their decline in monthly subscribers is because the webpage is not well-designed and doesn't recommend content to keep customer engaged long enough to subscribe. The E-news Express design team has created a new landing page for their website in the hopes that it will be more effective in engaging customers and getting them to subscribe. Our data science team has conducted an A/B test and we will be perfoming the statistical analysis to answer four key questions along the way:

Do the users spend more time on the new landing page than on the existing landing page?
Is the conversion rate (the proportion of users who visit the landing page and get converted) for the new page greater than the conversion rate for the old page?
Does the converted status depend on the preferred language?
Is the time spent on the new page the same for the different language users?

## Data Dictionary
* user_id - Unique user ID of the person visiting the website
* group - Whether the user belongs to the first group (control) or the second group (treatment)
* landing_page - Whether the landing page is new or old
* time_spent_on_the_page - Time (in minutes) spent by the user on the landing page
* converted - Whether the user gets converted to a subscriber of the news portal or not
* language_preferred - Language chosen by the user to view the landing page
