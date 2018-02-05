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
| Field Name                                     | Field Number | Type    | Format Example | Last Updated | 
|------------------------------------------------|--------------|---------|----------------|--------------| 
| Transaction ID                                 | 1            | AN      | XXX97001       | 1.0          | 
| Group ID                                       | 2            | AN      | XXX9701A       | 1.0          | 
| Loan ID                                        | 3            | AN      | 00000000012345 | 1.0          | 
| Prospectus Loan ID                             | 4            | AN      | 123            | 1.0          | 
| Original Note Amount                           | 5            | Numeric | 1000000.00     | 1.0          | 
| Original Term Of Loan                          | 6            | Numeric | 240            | 1.0          | 
| Original Amortization Term                     | 7            | Numeric | 360            | 1.0          | 
| Original Note Rate                             | 8            | Numeric | 0.095          | 1.0          | 
| Original Payment Rate                          | 9            | Numeric | 0.095          | 1.0          | 
| First Loan Payment Due Date                    | 10           | AN      | YYYYMMDD       | 1.0          | 
| Grace Days Allowed                             | 11           | Numeric | 10             | 1.0          | 
| Interest Only (Y/N)                            | 12           | AN      | Y              | 1.0          | 
| Balloon (Y/N)                                  | 13           | AN      | Y              | 1.0          | 
| Interest Rate Type                             | 14           | Numeric | 1              | 1.0          | 
| Interest Accrual Method                        | 15           | Numeric | 1              | 4.0          | 
| Interest in Arrears (Y/N)                      | 16           | AN      | Y              | 1.0          | 
| Payment Type                                   | 17           | Numeric | 1              | 4.0          | 
| Prepayment Lock-out End Date                   | 18           | AN      | YYYYMMDD       | 1.0          | 
| Yield Maintenance End Date                     | 19           | AN      | YYYYMMDD       | 1.0          | 
| Prepayment Premium End Date                    | 20           | AN      | YYYYMMDD       | 1.0          | 
| Prepayment Terms Description                   | 21           | AN      | Text           | 1.0          | 
| ARM Index                                      | 22           | AN      | A              | 4.0          | 
| First Rate Adjustment Date                     | 23           | AN      | YYYYMMDD       | 1.0          | 
| First Payment Adjustment Date                  | 24           | AN      | YYYYMMDD       | 1.0          | 
| ARM Margin                                     | 25           | Numeric | 0.025          | 1.0          | 
| Lifetime Rate Cap                              | 26           | Numeric | 0.15           | 1.0          | 
| Lifetime Rate Floor                            | 27           | Numeric | 0.05           | 1.0          | 
| Periodic Rate Increase Limit                   | 28           | Numeric | 0.02           | 1.0          | 
| Periodic Rate Decrease Limit                   | 29           | Numeric | 0.02           | 1.0          | 
| Periodic Pay Adjustment Max-%                  | 30           | Numeric | 0.03           | 1.0          | 
| Periodic Pay Adjustment Max-$                  | 31           | Numeric | 5000.00        | 1.0          | 
| Payment Frequency                              | 32           | Numeric | 1              | 1.0          | 
| Rate Reset Frequency                           | 33           | Numeric | 1              | 1.0          | 
| Pay Reset Frequency                            | 34           | Numeric | 1              | 1.0          | 
| Rounding Code                                  | 35           | Numeric | 1              | 1.0          | 
| Rounding Increment                             | 36           | Numeric | 0.00125        | 1.0          | 
| Index Look Back In Days                        | 37           | Numeric | 45             | 1.0          | 
| Negative Amortization Allowed (Y/N)            | 38           | AN      | Y              | 1.0          | 
| Max Neg Allowed (% Of Orig Bal)                | 39           | Numeric | 0.075          | 1.0          | 
| Maximum Negate Allowed ($)                     | 40           | Numeric | 25000.00       | 1.0          | 
| Remaining Term At Contribution                 | 41           | Numeric | 240            | 1.0          | 
| Remaining Amort Term At Contribution           | 42           | Numeric | 360            | 1.0          | 
| Maturity Date At Contribution                  | 43           | AN      | YYYYMMDD       | 1.0          | 
| Scheduled Principal Balance At Contribution    | 44           | Numeric | 1000000.00     | 1.0          | 
| Note Rate At Contribution                      | 45           | Numeric | 0.095          | 1.0          | 
| Servicer And Trustee Fee Rate                  | 46           | Numeric | 0.00025        | 1.0          | 
| Fee Rate / Strip Rate 1                        | 47           | Numeric | 0.00001        | 1.0          | 
| Fee Rate / Strip Rate 2                        | 48           | Numeric | 0.00001        | 1.0          | 
| Fee Rate / Strip Rate 3                        | 49           | Numeric | 0.00001        | 1.0          | 
| Fee Rate / Strip Rate 4                        | 50           | Numeric | 0.00001        | 1.0          | 
| Fee Rate / Strip Rate 5                        | 51           | Numeric | 0.00001        | 1.0          | 
| Net Rate at Contribution                       | 52           | Numeric | 0.0947         | 1.0          | 
| Periodic P&I Payment At Contribution           | 53           | Numeric | 3000.00        | 1.0          | 
| Number of Properties at Contribution           | 54           | Numeric | 13             | 1.0          | 
| Property Name                                  | 55           | AN      | Text           | 1.0          | 
| Property Address                               | 56           | AN      | Text           | 1.0          | 
| Property City                                  | 57           | AN      | Text           | 1.0          | 
| Property State                                 | 58           | AN      | Text           | 1.0          | 
| Property Zip Code                              | 59           | AN      | Text           | 1.0          | 
| Property County                                | 60           | AN      | Text           | 1.0          | 
| Property Type                                  | 61           | AN      | MF             | 4.0          | 
| Net Rentable Square Feet At Contribution       | 62           | Numeric | 25000          | 5.0          | 
| Number of Units/Beds/Rooms at Contribution     | 63           | Numeric | 75             | 1.0          | 
| Year Built                                     | 64           | AN      | YYYY           | 1.0          | 
| NOI at Contribution                            | 65           | Numeric | 100000.00      | 7.0          | 
| DSCR (NOI) at Contribution                     | 66           | Numeric | 2.11           | 1.0          | 
| Valuation Amount at Contribution               | 67           | Numeric | 1000000.00     | 4.0          | 
| Valuation Date at Contribution                 | 68           | AN      | YYYYMMDD       | 4.0          | 
| Physical Occupancy at Contribution             | 69           | Numeric | 0.88           | 1.0          | 
| Revenue at Contribution                        | 70           | Numeric | 100000.00      | 1.0          | 
| Operating Expenses at Contribution             | 71           | Numeric | 100000.00      | 7.0          | 
| Contribution Financials As Of Date             | 72           | AN      | YYYYMMDD       | 1.0          | 
| Recourse (Y/N)                                 | 73           | AN      | Y              | 1.0          | 
| EMPTY FIELD   (fka Ground Lease (Y/S/N))       | 74           |         | EMPTY          | 4.0          | 
| Cross-Collateralized Loan Grouping             | 75           | AN      | Text           | 1.0          | 
| Collection of Escrow (Y/N)                     | 76           | AN      | Y              | 4.0          | 
| Collection of Other Reserves (Y/N)             | 77           | AN      | Y              | 4.0          | 
| Lien Position at Contribution                  | 78           | Numeric | 1              | 1.0          | 
| Current Hyper Amortizing Date                  | 79           | AN      | YYYYMMDD       | 4.0          | 
| Defeasance Option Start Date                   | 80           | AN      | YYYYMMDD       | 2.0          | 
| EMPTY FIELD   (fka Defeasance Option End Date) | 81           |         | EMPTY          | 4.0          | 
| Last Setup Change Date                         | 82           | AN      | YYYYMMDD       | 2.0          | 
| NCF at Contribution                            | 83           | Numeric | 100000.00      | 7.0          | 
| DSCR (NCF) at Contribution                     | 84           | Numeric | 2.11           | 7.0          | 
| DSCR Indicator at Contribution                 | 85           | AN      | Text           | 2.0          | 
| Loan Contributor to Securitization             | 86           | AN      | Text           | 2.0          | 
| Credit Tenant Lease (Y/N)                      | 87           | AN      | Y              | 4.0          | 
| Financial Information Submission Penalties     | 88           | AN      | M              | 3.0          | 
| Additional Financing Indicator                 | 89           | Numeric | 0              | 4.0          | 
| Loan Structure                                 | 90           | AN      | WL             | 4.0          | 
| Origination Date                               | 91           | AN      | YYYYMMDD       | 8.0          | 
| Original Interest Only Term                    | 92           | Numeric | 360            | 8.0          | 
| Underwriting Indicator                         | 93           | AN      | Y              | 8.0          | 
| Servicing Advance Methodology                  | 94           | Numeric | 1              | 8.0          | 
| Valuation Source at Contribution               | 95           | Numeric | 1              | 8.0          | 
