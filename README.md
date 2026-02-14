# Odoo Modules Collection

Collection of Odoo 17 Community Edition modules.

## Available Modules

### 1. Procurement Management (`procurement_management/`)

Algerian Public Procurement Procedures Management Module compliant with Law n23-12 and Presidential Decree n15-247.

**Features:**
- Multi-phase procurement workflow (24 states)
- Committee management with member roles
- Bidder registration and management
- Document and publication tracking
- Envelope opening sessions
- Bid evaluation system
- Award management (provisional and final)
- PDF report generation (French and Arabic)

**Supported Procedure Types:**
- Direct Purchase Order / Service Order
- Comparative Offer Table (COT)
- Consultation
- Tender / Call for Competition
- Competition

## Installation

1. Clone this repository into your Odoo addons folder:
   ```bash
   cd /path/to/odoo/addons
   git clone https://github.com/souhaibouadi/odoo-modules.git
   ```

2. Update the Odoo configuration to include the addons path:
   ```
   addons_path = /path/to/odoo/addons,/path/to/odoo/addons/odoo-modules
   ```

3. Restart Odoo and update the apps list

4. Install the desired module from the Apps menu

## Requirements

- Odoo 17.0 Community Edition
- Python 3.10+
- PostgreSQL 14+

## License

LGPL-3

## Author

CACOBATH
