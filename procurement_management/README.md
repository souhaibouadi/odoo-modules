# Procurement Management - Odoo 17 CE Module

## Description
Algerian Public Procurement Procedures Management Module for Odoo 17 Community Edition.

Compliant with:
- Law n23-12 (Public Procurement Law)
- Presidential Decree n15-247

## Features
- Multi-phase procurement workflow (24 states)
- Committee management with member roles
- Bidder registration and management
- Document and publication tracking
- Envelope opening sessions
- Bid evaluation system
- Award management (provisional and final)
- PDF report generation (French and Arabic)

## Supported Procedure Types
- Direct Purchase Order / Service Order
- Comparative Offer Table (COT)
- Consultation
- Tender / Call for Competition
- Competition

## Technical Requirements
- Odoo 17.0 Community Edition
- Python 3.10+
- PostgreSQL 14+

## Dependencies
- base
- purchase
- contacts
- mail

## Installation
1. Clone this repository to your Odoo addons folder
2. Update the apps list in Odoo
3. Install the "Procurement Management" module

## Complete Source
For the complete module with all files, visit:
https://github.com/souhaibouadi/procurement_management

## Module Structure
```
procurement_management/
├── __init__.py
├── __manifest__.py
├── models/
├── views/
├── security/
├── data/
├── wizards/
├── controllers/
├── reports/
└── static/
```

## Author
CACOBATH

## License
LGPL-3
