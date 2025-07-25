# Debut 2.0 — Shopify Theme Conversion

This project is a complete conversion of Shopify's legacy **Debut theme** into a **Shopify Online Store 2.0** compatible theme. The goal is to upgrade Debut with modern features such as JSON templates, app blocks, and dynamic sections—while preserving the original aesthetic and structure.

## 🚀 Purpose

- Practice working with legacy Shopify themes
- Learn theme modernization best practices
- Build a production-ready 2.0 base theme from Debut
- Use this conversion in your Shopify developer portfolio

## 🛠 Key Features (Post-Conversion)

- **JSON-based templates** (`.json`)
- **Flexible and dynamic sections** (`{% section %}`)
- **App block support**
- **Modular and reusable components**
- **Dawn-style architecture** where applicable
- **Updated theme settings schema**
- **Improved maintainability and performance**

## 🔧 Setup Instructions

### 1. Clone the Repo

git clone https://github.com/KaeTheDev/debut-conversion/

cd debut-conversion

### 2. Install Shopify CLI

npm install -g @shopify/cli

### 3. Connect to your Development Store

shopify login --store your-store.myshopify.com

### 4. Start the Development Server

shopify theme dev


## 🧱 Directory Structure
```
├── assets/
├── config/
├── layout/
├── locales/
├── sections/
├── snippets/
├── templates/
├── templates/customers/
└── templates/*.json
```

*All .liquid template files are migrated to .json format where applicable.*

## 🔁 Converted Templates

| Legacy Template         | 2.0 Equivalent    | Notes                                    |
|------------------------|-------------------|------------------------------------------|
| `product.liquid`       | `product.json`    | Uses `main-product.liquid` section       |
| `collection.liquid`    | `collection.json` | Fully dynamic                            |
| `index.liquid`         | `index.json`      | Homepage uses flexible sections          |
| `cart.liquid`          | `cart.json`       | Optional—depends on app blocks           |
| `customers/*.liquid`   | still `.liquid`   | Remain in Liquid format                  |

## 📌 Notes

- This is **not a clone of Dawn** — it is a modernization of Debut.
- Some Debut-specific layout decisions have been retained.
- Additional enhancements (accessibility, performance, SEO) may be added.

## 📷 Screenshots (optional)

*Insert screenshots here of homepage, product page, etc.*

## 📄 License

MIT 

## 🙋‍♀️ Author

**KaeTheDev (Shakira Reid-Thomas)**  
[starvingartistddllc.com](https://starvingartistddllc.com)  
[LinkedIn](#) -  [GitHub](#)

---

## 💼 Portfolio Use

This theme conversion is part of my Shopify Developer Portfolio. It demonstrates my ability to work with legacy themes, implement Online Store 2.0 features, and modernize existing codebases for real-world Shopify stores.

For more projects & blogs, visit: [starvingartistddllc.com](https://starvingartistddllc.com)