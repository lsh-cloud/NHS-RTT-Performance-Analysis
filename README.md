# NHS Referral to Treatment (RTT) Performance Analysis

## Overview

This project explores the NHS Referral to Treatment (RTT) waiting list using **Power BI**. In particular this report allows the user to explore which providers are meeting the NHS Constitutional Standard of seeing 92% of patients within 18 weeks, and which specialities are performing well.

## Tools Used

- Power BI  
- DAX
- Power Query

## Report Pages

### RTT Performance

Provides an executive overview of provider performance measured against the NHS Constitutional Standard.  

![RTT_performance](images/RTT_Performance.png)  

### National RTT Overview

Provides a national view of waiting list growth and service pressures. 

### Speciality Analysis

Allows detailed analysis of the individual specialities. 

## Data Source

- The raw data is publicly available from https://www.england.nhs.uk/statistics/statistical-work-areas/rtt-waiting-times/rtt-data-2025-26/ and was transformed using **Power Query***. 
- The data was modelled using a star schema with 4 dimension tables for details about date, provider, speciality and RTT pathway type.
- The relationships were optimised for time intelligence calculations, as well as for proving benchmarks for both specialities and providers.  
