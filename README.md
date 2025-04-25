# 🛍️ E-Commerce Database Project

This project is a relational database design for an e-commerce platform. It includes an ERD, SQL schema, and documentation to explain the structure and data flow.

## 📚 Overview

The database supports products with various attributes, sizes, and colors. It is designed to manage brands, categories, product items, and variations efficiently.

## 🧱 Tables

- **brand**: Stores brand details.
- **product_category**: Categories like clothing, electronics, etc.
- **product**: General product information (name, brand, base price).
- **product_image**: Links products to image URLs.
- **color**: Available color options.
- **size_category**: Groups of sizes (e.g., clothing, shoes).
- **size_option**: Specific sizes (e.g., S, M, 42).
- **product_item**: Final purchasable product variants.
- **product_variation**: Links between products and their variations.
- **attribute_category**: Groups for attributes like material or weight.
- **attribute_type**: Types of attributes (text, number, boolean).
- **product_attribute**: Product-specific custom attributes.

## 🔄 Data Flow

- Brands and categories link to products.
- Each product can have images, items (with color/size), and custom attributes.
- Variations map reusable combinations of color and size.

## 🛠️ How to Use

1. Import `ecommerce.sql` into your MySQL or MariaDB database.
2. View the ERD in `erd.png` or rebuild it using the source `.dbml` file in the `docs` folder.

## 📂 Files

- `ecommerce.sql` — SQL schema for table creation
- `erd.png` — ERD image
- `docs/ERD_Source.dbml` — Optional DBML format (for dbdiagram.io)

## 🤝 Team Members
Valarine Cherono
John Mugendi
James Wanjiku
Noble Uebue
