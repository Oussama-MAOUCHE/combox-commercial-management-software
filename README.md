# ComBox — Commercial Management Software

ComBox is a multi-module Windows desktop application for day-to-day commercial management: **stock, sales, purchasing, customers, suppliers, cash, inventory and reporting**.

I co-developed the product as part of a small NTICBOX software team. Initial development began around 2017, and the application continued to evolve and remain in commercial use in later versions.

Over its lifecycle, ComBox was commercially deployed and used by **dozens of customers**.

![ComBox dashboard](assets/dashboard.png)

## At a glance

| Area | Details |
|---|---|
| Product | Commercial management desktop software |
| Organization | NTICBOX |
| My contribution | Co-development as part of a small software team |
| Technologies | WINDEV / WLanguage, HFSQL |
| Main areas | Stock, sales, purchasing, customers, suppliers, cash, inventory, reporting |
| Deployment | Commercially used by dozens of customers |

## What ComBox manages

ComBox connects several everyday business workflows in one application rather than treating stock, sales and purchasing as isolated tasks.

### Stock and products

The stock module provides a searchable product catalogue with:

- product reference and designation;
- category;
- current quantity;
- unit of measure;
- purchase price;
- wholesale price;
- retail price;
- overall stock-value visibility.

![Stock management](assets/stock.png)

### Sales and customer documents

The sales area covers multiple document and customer workflows, including counter sales, delivery notes, invoices, proforma invoices, customer returns and customer payments.

Delivery-note views combine document-level information with the associated product lines, quantities and prices.

![Sales and delivery notes](assets/delivery-notes.png)

### Purchasing and receptions

Purchase/reception workflows track incoming goods by supplier, document, date and value, together with the received line items and unit prices.

![Purchase and reception documents](assets/receptions.png)

### Product movement history

ComBox provides product-level traceability across stock movements.

For a selected product, the application can display:

- current quantity;
- purchase and sales movement history;
- related document/movement numbers;
- counterparties;
- quantities and prices;
- purchase and sales totals;
- average purchase/sales price indicators.

![Product movement history](assets/product-movements.png)

### Journal and reporting

The application also consolidates commercial activity into reporting/journal views that combine documents, dates, counterparties and values.

This gives users a broader operational view of sales, purchasing, stock movements and financial follow-up.

![Commercial journal and reporting](assets/journal.png)

## Other functional areas

The product also includes functionality for:

- customer and supplier records;
- customer and supplier payment follow-up;
- customer situation/balance views;
- cash journal and cash movements;
- inventory sessions and inventory closure;
- reports and statistics;
- user/account management;
- product categories and units of measure;
- company settings.

## Technical profile

| Area | Implementation |
|---|---|
| Application type | Windows desktop business application |
| Development environment | WINDEV / WLanguage |
| Data storage | HFSQL |
| Architecture focus | Multi-module commercial workflows with shared business data |
| Product lifecycle | Initial development around 2017, followed by continued evolution and commercial use |

The original project remains in WINDEV's native project format. This public repository focuses on the verified product scope, workflows and selected evidence rather than republishing proprietary project/database files.

## Commercial product experience

ComBox was not only a development exercise. It was packaged, deployed and used by real customers.

The public case study intentionally uses the conservative statement **“dozens of customers”** and does not publish sales figures, revenue metrics or unsupported adoption counts.

## Team contribution

ComBox was a team-developed NTICBOX product.

My work formed part of the product's development and evolution, but this repository does not assign artificial contribution percentages or present the product as a solo project.

## Evidence

The case study is supported by:

- the surviving WINDEV project package;
- application screens from multiple functional modules;
- HFSQL-based application data structures;
- later-version screens showing continued product evolution and use;
- first-hand project context.

Selected application screenshots are published with permission. Raw source-project files, database files, credentials and license data remain private.

See:

- [Technical Notes](docs/technical-notes.md)
- [Evidence & Confidentiality](evidence/README.md)

## Scope note

ComBox is presented as **commercial management software**.

The portfolio does not label it as a full ERP, accounting suite or CRM platform because those labels imply broader scope than is necessary to demonstrate the product's actual capabilities.
