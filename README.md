#Hospital Prices data

### CMS Medicare data (FY 2011)

### Description:
In an effort to increase price transparency, the Centers for Medicare and Medicaid Services (CMS) have publicly released for the first time a data set showing what hospitals charged and what Medicare paid for the 100 most common Medicare inpatient stays (Diagnostic Related Groups or DRGs) in 2011. And on June 3, 2013 CMS also released an outpatient data set, containing charges and Medicare payments for 30 select Ambulatory Payment Classification Codes (APCs), by facility.The differences between hospital charges and Medicare payments are striking, as is the enormous variation in hospital charges across and within communities.

[Originally posted here](http://visualizing.org/contests/visualizing-hospital-price-data)

### Fields

* __DRG:__ Diagnoses related group (reason for any given patient visit)
* __ID:__ Provider ID for Hospital
* __Name:__ Name of Hospital
* __Street, City, State, Zip:__ Location
* __Region__: US Region
* __TotalDischarges (int)__: Number of patients seen for DRG in this Hospital for the year
* __AverageCoveredCharges (int):__
* __AverageTotalPayments (int):__
* __type:__ Outpatient or Inpatient
* __lat, lon:__ Geo coordinates (from Yahoo Maps API)
