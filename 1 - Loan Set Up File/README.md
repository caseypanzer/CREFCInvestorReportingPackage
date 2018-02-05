# Loan Set Up File
The Loan Setup File will contain the majority of the loanlevel information found in the prospectus. Such information includes cut-off balance, original note rate, maturity date and general prepayment information, as well as “at contribution” financial data.

## Required File Type
.xls

## File Naming Convention
*Transaction ID*_*YYYYMM*_setup.xls

## Disseminated By
Certificate Administrator

## Prepared by
Master Servicer

## Source of Information
Originators Underwriting

## Frequency of Updates
Once, At Securitization

## Fields Included
| Field Name                                     | Field Number | Type    | Format Example | 
|------------------------------------------------|--------------|---------|----------------|
| [Transaction ID](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#transaction-id-)                                                           | 1  | AN      | XXX97001       | 1.0 | 
| [Group ID](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Group_ID)                                                                       | 2  | AN      | XXX9701A       | 1.0 | 
| [Loan ID](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Loan_ID)                                                                         | 3  | AN      | 00000000012345 | 1.0 | 
| [Prospectus Loan ID](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Prospectus_Loan_ID)                                                   | 4  | AN      | 123            | 1.0 | 
| [Original Note Amount](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Original_Note_Amount)                                               | 5  | Numeric | 1000000.00     | 1.0 | 
| [Original Term of Loan](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Original_Term_Of_Loan)                                             | 6  | Numeric | 240            | 1.0 | 
| [Original Amortization Term](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Original_Amortization_Term)                                   | 7  | Numeric | 360            | 1.0 | 
| [Original Note Rate](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Original_Note_Rate)                                                   | 8  | Numeric | 0.095          | 1.0 | 
| [Original Payment Rate](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Original_Payment_Rate)                                             | 9  | Numeric | 0.095          | 1.0 | 
| [First Loan Payment Due Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#First_Loan_Payment_Due_Date)                                 | 10 | AN      | YYYYMMDD       | 1.0 | 
| [Grace Days Allowed](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Grace_Days_Allowed)                                                   | 11 | Numeric | 10             | 1.0 | 
| [Interest Only (Y/N)](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Interest_Only_(Y/N))                                                 | 12 | AN      | Y              | 1.0 | 
| [Balloon (Y/N)](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Balloon_(Y/N))                                                             | 13 | AN      | Y              | 1.0 | 
| [Interest Rate Type](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Interest_Rate_Type)                                                   | 14 | Numeric | 1              | 1.0 | 
| [Interest Accrual Method](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Interest_Accrual_Method)                                         | 15 | Numeric | 1              | 4.0 | 
| [Interest In Arrears (Y/N)](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Interest_in_Arrears_(Y/N))                                     | 16 | AN      | Y              | 1.0 | 
| [Payment Type](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Payment_Type)                                                               | 17 | Numeric | 1              | 4.0 | 
| [Prepayment Lock-out End Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Prepayment_Lock-out_End_Date)                               | 18 | AN      | YYYYMMDD       | 1.0 | 
| [Yield Maintenance End Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Yield_Maintenance_End_Date)                                   | 19 | AN      | YYYYMMDD       | 1.0 | 
| [Prepayment Premium End Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Prepayment_Premium_End_Date)                                 | 20 | AN      | YYYYMMDD       | 1.0 | 
| [Prepayment Terms Description](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Prepayment_Terms_Description)                               | 21 | AN      | Text           | 1.0 | 
| [ARM Index](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#ARM_Index)                                                                     | 22 | AN      | A              | 4.0 | 
| [First Rate Adjustment Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#First_Rate_Adjustment_Date)                                   | 23 | AN      | YYYYMMDD       | 1.0 | 
| [First Payment Adjustment Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#First_Payment_Adjustment_Date)                             | 24 | AN      | YYYYMMDD       | 1.0 | 
| [ARM Margin](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#ARM_Margin)                                                                   | 25 | Numeric | 0.025          | 1.0 | 
| [Lifetime Rate Cap](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Lifetime_Rate_Cap)                                                     | 26 | Numeric | 0.15           | 1.0 | 
| [Lifetime Rate Floor](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Lifetime_Rate_Floor)                                                 | 27 | Numeric | 0.05           | 1.0 | 
| [Periodic Rate Increase Limit](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Periodic_Rate_Increase_Limit)                               | 28 | Numeric | 0.02           | 1.0 | 
| [Periodic Rate Decrease Limit](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Periodic_Rate_Decrease_Limit)                               | 29 | Numeric | 0.02           | 1.0 | 
| [Periodic Pay Adjustment Max-%](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Periodic_Pay_Adjustment_Max-%)                             | 30 | Numeric | 0.03           | 1.0 | 
| [Periodic Pay Adjustment Max-$](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Periodic_Pay_Adjustment_Max-$)                             | 31 | Numeric | 5000.00        | 1.0 | 
| [Payment Frequency](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Payment_Frequency)                                                     | 32 | Numeric | 1              | 1.0 | 
| [Rate Reset Frequency ](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Rate_Reset_Frequency_)                                             | 33 | Numeric | 1              | 1.0 | 
| [Pay Reset Frequency ](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Pay_Reset_Frequency_)                                               | 34 | Numeric | 1              | 1.0 | 
| [Rounding Code](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Rounding_Code)                                                             | 35 | Numeric | 1              | 1.0 | 
| [Rounding Increment](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Rounding_Increment)                                                   | 36 | Numeric | 0.00125        | 1.0 | 
| [Index Look Back In Days](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Index_Look_Back_In_Days)                                         | 37 | Numeric | 45             | 1.0 | 
| [Negative Amortization Allowed (Y/N)](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Negative_Amortization_Allowed_(Y/N))                 | 38 | AN      | Y              | 1.0 | 
| [Max Neg Allowed (% Of Orig Bal)](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Max_Neg_Allowed_(%_Of_Orig_Bal))                         | 39 | Numeric | 0.075          | 1.0 | 
| [Maximum Negate Allowed ($)](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Maximum_Negate_Allowed_($))                                   | 40 | Numeric | 25000.00       | 1.0 | 
| [Remaining Term At Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Remaining_Term_At_Contribution)                           | 41 | Numeric | 240            | 1.0 | 
| [Remaining Amort Term At Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Remaining_Amort_Term_At_Contribution)               | 42 | Numeric | 360            | 1.0 | 
| [Maturity Date At Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Maturity_Date_At_Contribution)                             | 43 | AN      | YYYYMMDD       | 1.0 | 
| [Scheduled Principal Balance At Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Scheduled_Principal_Balance_At_Contribution) | 44 | Numeric | 1000000.00     | 1.0 | 
| [Note Rate at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Note_Rate_At_Contribution)                                     | 45 | Numeric | 0.095          | 1.0 | 
| [Servicer and Trustee Fee Rate](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Servicer_And_Trustee_Fee_Rate)                             | 46 | Numeric | 0.00025        | 1.0 | 
| [Fee Rate / Strip Rate 1](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Fee_Rate_/_Strip_Rate_1)                                         | 47 | Numeric | 0.00001        | 1.0 | 
| [Fee Rate / Strip Rate 2](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Fee_Rate_/_Strip_Rate_2)                                         | 48 | Numeric | 0.00001        | 1.0 | 
| [Fee Rate / Strip Rate 3](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Fee_Rate_/_Strip_Rate_3)                                         | 49 | Numeric | 0.00001        | 1.0 | 
| [Fee Rate / Strip Rate 4](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Fee_Rate_/_Strip_Rate_4)                                         | 50 | Numeric | 0.00001        | 1.0 | 
| [Fee Rate / Strip Rate 5](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Fee_Rate_/_Strip_Rate_5)                                         | 51 | Numeric | 0.00001        | 1.0 | 
| [Net Rate at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Net_Rate_at_Contribution)                                       | 52 | Numeric | 0.0947         | 1.0 | 
| [Periodic P&I Payment At Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Periodic_P&I_Payment_At_Contribution)               | 53 | Numeric | 3000.00        | 1.0 | 
| [Number of Properties at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Number_of_Properties_at_Contribution)               | 54 | Numeric | 13             | 1.0 | 
| [Property Name](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Property_Name)                                                             | 55 | AN      | Text           | 1.0 | 
| [Property Address](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Property_Address)                                                       | 56 | AN      | Text           | 1.0 | 
| [Property City](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Property_City)                                                             | 57 | AN      | Text           | 1.0 | 
| [Property State](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Property_State)                                                           | 58 | AN      | Text           | 1.0 | 
| [Property Zip Code](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Property_Zip_Code)                                                     | 59 | AN      | Text           | 1.0 | 
| [Property County](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Property_County)                                                         | 60 | AN      | Text           | 1.0 | 
| [Property Type](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Property_Type)                                                             | 61 | AN      | MF             | 4.0 | 
| [Net Rentable Square Feet at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Net_Rentable_Square_Feet_At_Contribution)       | 62 | Numeric | 25000          | 5.0 | 
| [Number of Units/Beds/Rooms at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Number_of_Units/Beds/Rooms_at_Contribution)   | 63 | Numeric | 75             | 1.0 | 
| [Year Built](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Year_Built)                                                                   | 64 | AN      | YYYY           | 1.0 | 
| [NOI at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#NOI_at_Contribution)                                                 | 65 | Numeric | 100000.00      | 7.0 | 
| [DSCR (NOI) at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#DSCR_(NOI)_at_Contribution)                                   | 66 | Numeric | 2.11           | 1.0 | 
| [Valuation Amount at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Valuation_Amount_at_Contribution)                       | 67 | Numeric | 1000000.00     | 4.0 | 
| [Valuation Date at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Valuation_Date_at_Contribution)                           | 68 | AN      | YYYYMMDD       | 4.0 | 
| [Physical Occupancy at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Physical_Occupancy_at_Contribution)                   | 69 | Numeric | 0.88           | 1.0 | 
| Revenue at Contribution                                                                                                                                                                | 70 | Numeric | 100000.00      | 1.0 | 
| [Operating Expenses at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Operating_Expenses_at_Contribution)                   | 71 | Numeric | 100000.00      | 7.0 | 
| [Contribution Financials As Of Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Contribution_Financials_As_Of_Date)                   | 72 | AN      | YYYYMMDD       | 1.0 | 
| [Recourse (Y/N)](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Recourse_(Y/N))                                                           | 73 | AN      | Y              | 1.0 | 
| EMPTY FIELD   (fka Ground Lease (Y/S/N))                                                                                                                                               | 74 |         | EMPTY          | 4.0 | 
| Cross-Collateralized Loan Grouping                                                                                                                                                     | 75 | AN      | Text           | 1.0 | 
| [Collection of Escrow (Y/N)](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Collection_of_Escrow_(Y/N))                                   | 76 | AN      | Y              | 4.0 | 
| [Collection of Other Reserves (Y/N)](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Collection_of_Other_Reserves_(Y/N))                   | 77 | AN      | Y              | 4.0 | 
| [Lien Position at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Lien_Position_at_Contribution)                             | 78 | Numeric | 1              | 1.0 | 
| [Current Hyper Amortizing Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Current_Hyper_Amortizing_Date)                             | 79 | AN      | YYYYMMDD       | 4.0 | 
| [Defeasance Option Start Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Defeasance_Option_Start_Date)                               | 80 | AN      | YYYYMMDD       | 2.0 | 
| EMPTY FIELD   (fka Defeasance Option End Date)                                                                                                                                         | 81 |         | EMPTY          | 4.0 | 
| [Last Setup Change Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Last_Setup_Change_Date)                                           | 82 | AN      | YYYYMMDD       | 2.0 | 
| [NCF at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#NCF_at_Contribution)                                                 | 83 | Numeric | 100000.00      | 7.0 | 
| DSCR (NCF) at Contribution                                                                                                                                                             | 84 | Numeric | 2.11           | 7.0 | 
| [DSCR Indicator at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#DSCR_Indicator_at_Contribution)                           | 85 | AN      | Text           | 2.0 | 
| [Loan Contributor to Securitization](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Loan_Contributor_to_Securitization)                   | 86 | AN      | Text           | 2.0 | 
| [Credit Tenant Lease (Y/N)](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Credit_Tenant_Lease_(Y/N))                                     | 87 | AN      | Y              | 4.0 | 
| [Financial Information Submission Penalties](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Financial_Information_Submission_Penalties)   | 88 | AN      | M              | 3.0 | 
| [Additional Financing Indicator](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Additional_Financing_Indicator)                           | 89 | Numeric | 0              | 4.0 | 
| [Loan Structure](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Loan_Structure)                                                           | 90 | AN      | WL             | 4.0 | 
| [Origination Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Origination_Date)                                                       | 91 | AN      | YYYYMMDD       | 8.0 | 
| [Original Interest Only Term](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Original_Interest_Only_Term)                                 | 92 | Numeric | 360            | 8.0 | 
| [Underwriting Indicator](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Underwriting_Indicator)                                           | 93 | AN      | Y              | 8.0 | 
| [Servicing Advance Methodology](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Servicing_Advance_Methodology)                             | 94 | Numeric | 1              | 8.0 | 
| [Valuation Source at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#Valuation_Source_at_Contribution)                       | 95 | Numeric | 1              | 8.0 | 
