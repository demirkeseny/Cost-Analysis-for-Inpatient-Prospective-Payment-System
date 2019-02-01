# Cost Analysis for Inpatient Prospective Payment System

> Author: [Yalim Demirkesen](github.com/demirkeseny) 
>
> Presentation: [Google Slides](https://docs.google.com/presentation/d/1GTVqyk5zO4JF1aC-jj1xcooovxf6mpkgZUzPTIsVkxA/edit?usp=sharing)

### Problem Statement

In this project, I am analyzing a healthcare data on data.gov. The data is related to the health costs in the US states. It gives charges that are created by more than 3000 hospitals all around US that receive Medicare Inpatient Prospective Payment System (IPPS). 

The costs are related to top 100 most frequently billed discharges, which are paid under Medicare. With the provided data, I will be able to analyze the charges and their correlation with states.

This data set will make it possible for me to analyze the healthcare charges from each state. Since it is also a political issue, the healthcare costs are a popular subject. Throughout this research, the readers will have a chance to examine each hospital that is enrolled to the Inpatient Prospective Payment System. 

The data belongs to each and every contributor to IPPS from each city and each state. So, it gives a nice locational and updated information. Depending on the records, I will be able to provide answer to questions that are related to cost of each hospital and also their discharge numbers and how much they benefit from Medicare funds.

### Data Understanding

The source of the data is Centers for Medicare & Medicaid Services’ (CMS) inpatient database. The dataset that we are interested in is taken from October 1st, 2011 to September 30th, 2012. The database includes IPPS short term care, long term care, critical access hospital, non-medical, rehabilitation and psychiatric discharges.
There are in total 12 columns. Descriptions of each column can be found below:
1. DRG Definition: The definition of the discharge that is stored in the CMS database about inpatient discharges
2. Provider ID: Number that identifies the provider, which is also qualified for Medicare Certification
3. Provider Name: Hospital facility name
4. Provider Street Address: Hospital facility address
5. Provider City: City where the hospital facility is located at
6. Provider State: State where the hospital facility is located at
7. Provider Zip Code: The hospital facility’s zip code
8. Provider HRR: The Hospital Referral Region (HRR) where the provider is located.
9. Total Discharges: The number of discharges billed by the provider for inpatient hospital services
10. Average Covered Charges: The provider's average charge for services covered by Medicare for all discharges. There might be variations in this data because of the different hospital policies
11. Average Total Payments: The average total payments to all providers for all cases. Also included in average total payments are co-payment and deductible amounts that the patient is responsible for and any additional payments by third parties for coordination of benefits.
12. Average Medicare Payments: The average amount that Medicare pays to the provider for Medicare's share. Medicare payments don’t include beneficiary co-payments and deductible amounts nor any additional payments from third parties for coordination of benefits. 