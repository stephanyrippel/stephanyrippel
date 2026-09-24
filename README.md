# Which frozen dessert products should be blocked from launch because of Product Data quality issues?

A Product Data quality audit for a frozen dessert manufacturer, inspired by real Product Information Management (PIM), ERP, and food labeling workflows used in the food industry.

---

## The business question

A frozen dessert manufacturer is preparing **90 products** for commercialization, but not every product contains complete and consistent Product Data.

**Which products should be blocked from launch because mandatory labeling information is missing or inconsistent?**

This project simulates the Product Data validation process performed before publishing product information in a Product Information Management (PIM) environment.

---

## The answer

I audited **90 frozen dessert products** across six product categories using mandatory Product Data validation rules.

### Executive summary

* **90 products reviewed**
* **48 products approved**
* **18 products approved with warnings**
* **24 products blocked before launch**
* **36 critical Product Data issues identified**

The most frequent issues were missing allergen declarations, incomplete Nutrition Facts, ingredient-to-allergen inconsistencies, and missing GTIN information.

### Business recommendation

Block publication for products with critical Product Data issues and prioritize remediation of allergen declarations and Nutrition Facts before launch approval.

---

## Why this matters

Product Data quality directly affects product launches, customer safety, and regulatory compliance.

Missing or inconsistent product information may result in:

* Incorrect allergen declarations.
* Incomplete Nutrition Facts panels.
* Delayed product launches.
* Incorrect information across sales and operational systems.
* Increased compliance risk and product rework.

A Product Data review ensures mandatory information is complete before commercialization.

---

## How I got there

This analysis follows a Product Data validation workflow commonly performed using a PIM system, an ERP, and Excel.

### Validation rules applied

Every product was validated for mandatory Product Data attributes, including:

* Ingredient list completeness.
* Allergen declaration consistency.
* Nutrition Facts completeness.
* Serving size.
* Net weight.
* Storage temperature instructions.
* Shelf life.
* GTIN (barcode).
* Country of origin.
* Packaging material.
* Supplier documentation status.

Products were classified as:

* **Approved** — All mandatory Product Data attributes are complete.
* **Warning** — Minor Product Data issues require review before publication.
* **Blocked** — Critical Product Data is missing or inconsistent.

---

## Product categories reviewed

| Category                        | Products Reviewed |
| ------------------------------- | ----------------: |
| Ice Cream Tubs                  |                28 |
| Frozen Dessert Bars & Popsicles |                22 |
| Frozen Cakes & Cheesecakes      |                14 |
| Frozen Dessert Cups             |                12 |
| Frozen Cookies & Brownies       |                 8 |
| Seasonal & Limited Editions     |                 6 |

---

## Top Product Data issues identified

| Compliance issue                        | Products affected |
| --------------------------------------- | ----------------: |
| Missing allergen declaration            |                11 |
| Incomplete Nutrition Facts              |                 8 |
| Ingredient and allergen mismatch        |                 6 |
| Missing storage or thawing instructions |                 5 |
| Missing GTIN                            |                 4 |
| Missing supplier documentation          |                 2 |

### Highest-risk categories

The largest concentration of blocked products was found in:

1. Ice Cream Tubs.
2. Frozen Dessert Bars & Popsicles.
3. Frozen Cakes & Cheesecakes.

These categories contain products with multiple mandatory allergen declarations and more complex labeling requirements.

---

## Dashboard

The dashboard was built to answer three operational questions:

1. Which products are ready for launch?
2. Which Product Data issues occur most frequently?
3. Which product categories should be prioritized for remediation?

The dashboard includes executive KPIs, compliance status by category, issue severity, and a list of products blocked before launch.

---

## What I'd do next

To improve launch readiness, I would:

1. Complete mandatory allergen declarations for blocked products.
2. Validate Nutrition Facts against approved product specifications.
3. Resolve ingredient-to-allergen inconsistencies.
4. Complete missing GTIN and packaging information before publication.
5. Revalidate blocked products before approving them for launch.

---

## Tools used

* **FoodChecker (PIM)** — Product specifications and Product Information Management workflows.
* **3LM (ERP + PDV)** — Product registration, inventory, and operational product information workflows.
* **Microsoft Excel** — Data validation, Pivot Tables, XLOOKUP, COUNTIFS, conditional formatting, and quality checks.
* **Google Looker Studio** — Compliance dashboard.
* **GitHub & Markdown** — Project documentation.

---

## Caveats

This repository uses a **synthetic dataset** created exclusively for portfolio purposes.

The workflow is inspired by real Product Data, PIM, ERP, and food labeling processes used in the food industry, but it does not contain confidential company, supplier, or client information.
