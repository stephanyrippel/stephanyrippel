# Which frozen dessert products should be blocked from launch because of Product Data quality issues?

A Product Data quality audit for a frozen dessert manufacturer, inspired by real Product Information Management (PIM), ERP, and food labeling workflows.

## The question

A frozen dessert manufacturer is preparing **90 products** for commercialization across six product categories. Before publication, every product must contain complete and consistent Product Data.

**Which products should be blocked from launch because mandatory labeling information is missing or inconsistent?**

## The answer

**24 products should be blocked before launch.**

The audit found that the highest-risk issues were missing allergen declarations, incomplete Nutrition Facts, ingredient-to-allergen inconsistencies, missing GTINs, and incomplete storage instructions.

Blocking these products before publication reduces compliance risk and prevents incorrect product information from reaching customers and retailers.

## How I got there

I reviewed **90 frozen dessert products** using Product Data validation rules inspired by real FoodChecker (PIM) and 3LM (ERP) workflows.

The products were distributed across six categories:

* Ice Cream Tubs (28)
* Frozen Dessert Bars & Popsicles (22)
* Frozen Cakes & Cheesecakes (14)
* Frozen Dessert Cups (12)
* Frozen Cookies & Brownies (8)
* Seasonal & Limited Editions (6)

Each product was validated for mandatory attributes, including:

* Ingredient list completeness.
* Allergen declaration consistency.
* Nutrition Facts completeness.
* Serving size and net weight.
* Storage temperature instructions.
* Shelf life.
* GTIN (barcode).
* Packaging information.
* Supplier documentation status.

Products were classified as **Approved**, **Warning**, or **Blocked**.

## Dashboard

The compliance dashboard answers three operational questions:

* Which products are ready for launch?
* Which categories have the highest compliance risk?
* Which Product Data issues should be fixed first?

The dashboard summarizes approval status, compliance issues by category, and the most common Product Data validation failures.

## What I'd do next

Prioritize remediation for blocked products, validate mandatory labeling fields against approved product specifications, complete missing GTIN and packaging information, and revalidate products before launch approval.

## Caveats

This project uses a **synthetic dataset** created exclusively for portfolio purposes.

The validation workflow is inspired by real Product Data, food labeling, and Product Information Management processes, without using confidential company or client information.

## Tools used

* FoodChecker (PIM)
* 3LM (ERP)
* Microsoft Excel
* Google Looker Studio
* GitHub Markdown
