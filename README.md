### Key Objectives:
---
1. Conduct thorough data exploration to uncover insights, establish relationships, and enhance comprehension of customer characteristics.
2. Propose and articulate a customer segmentation strategy derived from observed customer behaviors.
3. Engineer and validate a predictive model to empower the company in maximizing profits from upcoming marketing campaigns.

### Data Dictionary
---
| **Column Name**         | **Description**                                            |
|--------------------------|------------------------------------------------------------|
| id                       | Customer's unique ID                                       |
| year_birth               | Customer's birth year                                      |
| education                | Customer's education level                                 |
| marital_status           | Customer's marital status                                  |
| income                   | Customer's yearly household income                         |
| kidhome                  | Number of children in customer's household                 |
| teenhome                 | Number of teenagers in customer's household                |
| dt_customer              | Date of customer's enrollment with the company             |
| recency                  | Number of days since customer's last purchase              |
| mntwines                 | Amount spent on wine in the last 2 years                   |
| mntfruits                | Amount spent on fruits in the last 2 years                 |
| mntmeatproducts          | Amount spent on meat in the last 2 years                   |
| mntfishproducts          | Amount spent on fish in the last 2 years                   |
| mntsweetproducts         | Amount spent on sweets in the last 2 years                 |
| mntgoldprods             | Amount spent on gold in the last 2 years                   |
| numdealspurchases        | Number of purchases made with a discount                   |
| numwebpurchases          | Number of purchases made through the company's web site    |
| numcatalogpurchases      | Number of purchases made using a catalogue                |
| numstorepurchases        | Number of purchases made directly in stores                |
| numwebvisitsmonth        | Number of visits to company's web site in the last month   |
| acceptedcmp1             | 1 if customer accepted the offer in the 1st campaign, 0 otherwise  |
| acceptedcmp2             | 1 if customer accepted the offer in the 2nd campaign, 0 otherwise  |
| acceptedcmp3             | 1 if customer accepted the offer in the 3rd campaign, 0 otherwise  |
| acceptedcmp4             | 1 if customer accepted the offer in the 4th campaign, 0 otherwise  |
| acceptedcmp5             | 1 if customer accepted the offer in the 5th campaign, 0 otherwise  |
| response                 | 1 if customer accepted the offer in the last campaign, 0 otherwise (Target variable) |
| complain                 | 1 if customer complained in the last 2 years, 0 otherwise |
| country                  | Customer's location                                       |
