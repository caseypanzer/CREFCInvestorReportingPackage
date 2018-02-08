# Loan Set Up File
The Loan Setup File will contain the majority of the loan level information found in the prospectus. Such information includes cut-off balance, original note rate, maturity date and general prepayment information, as well as “at contribution” financial data.

## Required File Type
.xlsx

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

## Best Practices
[best practices could go here]

## Fields Included
| Field Name                                     | Field Number | Type    | Format Example | 
|------------------------------------------------|--------------|---------|----------------|
| [Transaction ID](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#transaction-id-)                                                           | 1  | AN      | XXX97001       | 
| [Group ID](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#group-id-)                                                                       | 2  | AN      | XXX9701A       | 
| [Loan ID](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#loan-id-)                                                                         | 3  | AN      | 00000000012345 | 
| [Prospectus Loan ID](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#prospectus-loan-id-)                                                   | 4  | AN      | 123            | 
| [Original Note Amount](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#original-note-amount-)                                               | 5  | Numeric | 1000000.00     | 
| [Original Term of Loan](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#original-term-of-loan-)                                             | 6  | Numeric | 240            | 
| [Original Amortization Term](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#original-amortization-term-)                                   | 7  | Numeric | 360            | 
| [Original Note Rate](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#original-note-rate-)                                                   | 8  | Numeric | 0.095          | 
| [Original Payment Rate](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#original-payment-rate-)                                             | 9  | Numeric | 0.095          | 
| [First Loan Payment Due Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#first-loan-payment-due-date-)                                 | 10 | AN      | YYYYMMDD       | 
| [Grace Days Allowed](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#grace-days-allowed-)                                                   | 11 | Numeric | 10             | 
| [Interest Only (Y/N)](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#interest-only-(y/n)-)                                                 | 12 | AN      | Y              | 
| [Balloon (Y/N)](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#balloon-(y/n)-)                                                             | 13 | AN      | Y              | 
| [Interest Rate Type](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#interest-rate-type-)                                                   | 14 | Numeric | 1              | 
| [Interest Accrual Method](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#interest-accrual-method-)                                         | 15 | Numeric | 1              | 
| [Interest In Arrears (Y/N)](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#interest-in-arrears-(y/n)-)                                     | 16 | AN      | Y              | 
| [Payment Type](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#payment-type-)                                                               | 17 | Numeric | 1              | 
| [Prepayment Lock-out End Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#prepayment-lock-out-end-date-)                               | 18 | AN      | YYYYMMDD       | 
| [Yield Maintenance End Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#yield-maintenance-end-date-)                                   | 19 | AN      | YYYYMMDD       | 
| [Prepayment Premium End Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#prepayment-premium-end-date-)                                 | 20 | AN      | YYYYMMDD       | 
| [Prepayment Terms Description](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#prepayment-terms-description-)                               | 21 | AN      | Text           | 
| [ARM Index](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#arm-index-)                                                                     | 22 | AN      | A              | 
| [First Rate Adjustment Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#first-rate-adjustment-date-)                                   | 23 | AN      | YYYYMMDD       | 
| [First Payment Adjustment Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#first-payment-adjustment-date-)                             | 24 | AN      | YYYYMMDD       | 
| [ARM Margin](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#arm-margin-)                                                                   | 25 | Numeric | 0.025          | 
| [Lifetime Rate Cap](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#lifetime-rate-cap-)                                                     | 26 | Numeric | 0.15           | 
| [Lifetime Rate Floor](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#lifetime-rate-floor-)                                                 | 27 | Numeric | 0.05           | 
| [Periodic Rate Increase Limit](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#periodic-rate-increase-limit-)                               | 28 | Numeric | 0.02           | 
| [Periodic Rate Decrease Limit](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#periodic-rate-decrease-limit-)                               | 29 | Numeric | 0.02           | 
| [Periodic Pay Adjustment Max-%](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#periodic-pay-adjustment-max-%-)                             | 30 | Numeric | 0.03           | 
| [Periodic Pay Adjustment Max-$](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#periodic-pay-adjustment-max-$-)                             | 31 | Numeric | 5000.00        | 
| [Payment Frequency](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#payment-frequency-)                                                     | 32 | Numeric | 1              | 
| [Rate Reset Frequency ](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#rate-reset-frequency--)                                             | 33 | Numeric | 1              | 
| [Pay Reset Frequency ](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#pay-reset-frequency--)                                               | 34 | Numeric | 1              | 
| [Rounding Code](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#rounding-code-)                                                             | 35 | Numeric | 1              | 
| [Rounding Increment](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#rounding-increment-)                                                   | 36 | Numeric | 0.00125        | 
| [Index Look Back In Days](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#index-look-back-in-days-)                                         | 37 | Numeric | 45             | 
| [Negative Amortization Allowed (Y/N)](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#negative-amortization-allowed-(y/n)-)                 | 38 | AN      | Y              | 
| [Max Neg Allowed (% Of Orig Bal)](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#max-neg-allowed-(%-of-orig-bal)-)                         | 39 | Numeric | 0.075          | 
| [Maximum Negate Allowed ($)](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#maximum-negate-allowed-($)-)                                   | 40 | Numeric | 25000.00       | 
| [Remaining Term At Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#remaining-term-at-contribution-)                           | 41 | Numeric | 240            | 
| [Remaining Amort Term At Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#remaining-amort-term-at-contribution-)               | 42 | Numeric | 360            | 
| [Maturity Date At Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#maturity-date-at-contribution-)                             | 43 | AN      | YYYYMMDD       | 
| [Scheduled Principal Balance At Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#scheduled-principal-balance-at-contribution-) | 44 | Numeric | 1000000.00     | 
| [Note Rate at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#note-rate-at-contribution-)                                     | 45 | Numeric | 0.095          | 
| [Servicer and Trustee Fee Rate](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#servicer-and-trustee-fee-rate-)                             | 46 | Numeric | 0.00025        | 
| [Fee Rate / Strip Rate 1](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#fee-rate-/-strip-rate-1-)                                         | 47 | Numeric | 0.00001        | 
| [Fee Rate / Strip Rate 2](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#fee-rate-/-strip-rate-2-)                                         | 48 | Numeric | 0.00001        | 
| [Fee Rate / Strip Rate 3](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#fee-rate-/-strip-rate-3-)                                         | 49 | Numeric | 0.00001        | 
| [Fee Rate / Strip Rate 4](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#fee-rate-/-strip-rate-4-)                                         | 50 | Numeric | 0.00001        | 
| [Fee Rate / Strip Rate 5](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#fee-rate-/-strip-rate-5-)                                         | 51 | Numeric | 0.00001        | 
| [Net Rate at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#net-rate-at-contribution-)                                       | 52 | Numeric | 0.0947         | 
| [Periodic P&I Payment At Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#periodic-p&i-payment-at-contribution-)               | 53 | Numeric | 3000.00        | 
| [Number of Properties at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#number-of-properties-at-contribution-)               | 54 | Numeric | 13             | 
| [Property Name](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#property-name-)                                                             | 55 | AN      | Text           | 
| [Property Address](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#property-address-)                                                       | 56 | AN      | Text           | 
| [Property City](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#property-city-)                                                             | 57 | AN      | Text           | 
| [Property State](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#property-state-)                                                           | 58 | AN      | Text           | 
| [Property Zip Code](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#property-zip-code-)                                                     | 59 | AN      | Text           | 
| [Property County](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#property-county-)                                                         | 60 | AN      | Text           | 
| [Property Type](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#property-type-)                                                             | 61 | AN      | MF             | 
| [Net Rentable Square Feet at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#net-rentable-square-feet-at-contribution-)       | 62 | Numeric | 25000          | 
| [Number of Units/Beds/Rooms at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#number-of-units/beds/rooms-at-contribution-)   | 63 | Numeric | 75             | 
| [Year Built](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#year-built-)                                                                   | 64 | AN      | YYYY           | 
| [NOI at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#noi-at-contribution-)                                                 | 65 | Numeric | 100000.00      | 
| [DSCR (NOI) at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#dscr-(noi)-at-contribution-)                                   | 66 | Numeric | 2.11           | 
| [Valuation Amount at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#valuation-amount-at-contribution-)                       | 67 | Numeric | 1000000.00     | 
| [Valuation Date at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#valuation-date-at-contribution-)                           | 68 | AN      | YYYYMMDD       | 
| [Physical Occupancy at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#physical-occupancy-at-contribution-)                   | 69 | Numeric | 0.88           | 
| Revenue at Contribution                                                                                                                                                                 | 70 | Numeric | 100000.00      | 
| [Operating Expenses at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#operating-expenses-at-contribution-)                   | 71 | Numeric | 100000.00      | 
| [Contribution Financials As Of Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#contribution-financials-as-of-date-)                   | 72 | AN      | YYYYMMDD       | 
| [Recourse (Y/N)](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#recourse-(y/n)-)                                                           | 73 | AN      | Y              | 
| EMPTY FIELD   (fka Ground Lease (Y/S/N))                                                                                                                                                | 74 |         | EMPTY          | 
| Cross-Collateralized Loan Grouping                                                                                                                                                      | 75 | AN      | Text           | 
| [Collection of Escrow (Y/N)](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#collection-of-escrow-(y/n)-)                                   | 76 | AN      | Y              | 
| [Collection of Other Reserves (Y/N)](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#collection-of-other-reserves-(y/n)-)                   | 77 | AN      | Y              | 
| [Lien Position at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#lien-position-at-contribution-)                             | 78 | Numeric | 1              | 
| [Current Hyper Amortizing Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#current-hyper-amortizing-date-)                             | 79 | AN      | YYYYMMDD       | 
| [Defeasance Option Start Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#defeasance-option-start-date-)                               | 80 | AN      | YYYYMMDD       | 
| EMPTY FIELD   (fka Defeasance Option End Date)                                                                                                                                          | 81 |         | EMPTY          | 
| [Last Setup Change Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#last-setup-change-date-)                                           | 82 | AN      | YYYYMMDD       | 
| [NCF at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#ncf-at-contribution-)                                                 | 83 | Numeric | 100000.00      | 
| DSCR (NCF) at Contribution                                                                                                                                                              | 84 | Numeric | 2.11           | 
| [DSCR Indicator at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#dscr-indicator-at-contribution-)                           | 85 | AN      | Text           | 
| [Loan Contributor to Securitization](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#loan-contributor-to-securitization-)                   | 86 | AN      | Text           | 
| [Credit Tenant Lease (Y/N)](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#credit-tenant-lease-(y/n)-)                                     | 87 | AN      | Y              | 
| [Financial Information Submission Penalties](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#financial-information-submission-penalties-)   | 88 | AN      | M              | 
| [Additional Financing Indicator](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#additional-financing-indicator-)                           | 89 | Numeric | 0              | 
| [Loan Structure](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#loan-structure-)                                                           | 90 | AN      | WL             | 
| [Origination Date](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#origination-date-)                                                       | 91 | AN      | YYYYMMDD       | 
| [Original Interest Only Term](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#original-interest-only-term-)                                 | 92 | Numeric | 360            | 
| [Underwriting Indicator](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#underwriting-indicator-)                                           | 93 | AN      | Y              | 
| [Servicing Advance Methodology](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#servicing-advance-methodology-)                             | 94 | Numeric | 1              | 
| [Valuation Source at Contribution](https://github.com/caseypanzer/CREFCInvestorReportingPackage/blob/master/DATA_DICTIONARY.md#valuation-source-at-contribution-)                       | 95 | Numeric | 1              | 
