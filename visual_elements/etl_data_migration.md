# ETL Data Migration Flow

## Extract
Data is extracted from the legacy banking system, including:
- customer records
- account information
- balances
- transaction history
- employee user accounts

## Transform
Data is cleaned and standardized by:
- removing duplicates
- correcting missing or invalid values
- standardizing account number and date formats
- matching legacy fields to the new system structure

## Load
Validated data is loaded into the new banking system database using controlled migration scripts.

## Flow Summary

Legacy Banking Database  
↓  
Extract  
↓  
Transform  
↓  
Load  
↓  
New Secure Banking Information System
