# Investigate Business Hotel using Data Visualization

## **Overview**
<div align = 'justify'>

It is very important for a company to always analyze its business performance. On this occasion, we will go deeper into the business in the hospitality sector. Our focus is to find out how our customers behave in making hotel bookings, and their relationship to the cancellation rate of hotel bookings. The results of the insights we find will be presented in the form of visualization data to make it easier to understand and more persuasive.

## **Methods**
This project requires standard pandas, numpy, matplotlib version 3.6.2, seaborn, sklearn packages. If you want to do the same test, you need to install this package first.
#### **EDA:**
Descriptive Statistics

#### **Data Preprocessing:**
- Handle Null Values
- Handle Error Values
- Change Data Type
- Feature Engineering

## **Business Metrics**
- Monthly Hotel Booking Analysis Based on Hotel Type
- Impact Analysis of Stay Duration on Hotel Bookings Cancellation Rates
- Impact Analysis of Lead Time on Hotel Bookings Cancellation Rates

## **Analysis/Insight**
<div align = 'justify'>

- Hotel have more guests during the holiday season while the low season occurs in February-March, this is likely because the holidays have ended and this month is not a busy time for business travel. To optimize hotel resources during low season, this can be done by providing early year holiday promos.
- Both types of hotels (City hotel and Resort) have a positive correlation for cancellation rate and stay duration, but the relationship is more significant for city hotels. To reduce cancellation rates, we could offer non-refundable rates for long stay bookings.
- The longer the lead time, the more canceled bookings. Things that can be done to prevent cancellation:
  * Set the maximum booking lead time.
  * Placing a booking deposit requirement for a lead time >1 month for city hotels and >3 months for resort hotels.
  * Set limitation for the cancellation period.
