# 📊 Tabular Transformer

A lightweight web tool to **reshape spreadsheet-like data** into a more normalized table.  
Upload your **CSV or Excel** file, configure fixed and repeating columns, and export the processed data back to Excel/CSV.

👉 [Live Demo](https://amanat003.github.io/Tabular-Transformer/)  

---

## ✨ Features

- 📂 **Drag & drop** CSV or Excel files  
- 🧾 **Input preview** (with column numbers and row count)  
- 🔄 **Reshape repeating groups** into normalized rows  
- 🔒 **Fixed columns** (e.g. `1:4,6,25:26`) stay unchanged  
- ✍️ **Rename repeated group columns** (`Brand,Category,SKU`)  
- 🏷️ **Optional Category column**  
  - Choose which repeated column (e.g. Group2) should drive classification  
  - Auto-maps items to categories (Flour, Lentil, Mustard Oil, Puffed Rice, Rice, Salt, …)  
- 📉 **Output summary** (row & column counts)  
- 💾 **Export** processed data to Excel or CSV  
- 💻 Runs fully in the browser — **no server, no data upload**

---

## 🚀 Usage

1. Open the [demo page](https://amanat003.github.io/Tabular-Transformer/) in your browser  
2. Drag & drop a CSV/Excel file (or click to select a file)  
3. Configure:
   - **Fixed columns (ranges)**: columns that should always stay (`1:3,6,25:26`)  
   - **Repeat group size**: how many columns form one group (`3`)  
   - **Repeat range**: where repeating groups start and end (`4:n`)  
   - **Rename repeated columns** (optional): `Brand,Category,SKU`  
   - **Category column** (optional): enable and choose source column for classification  
4. Click **Process**  
5. Review the **output preview**  
6. Export as **Excel** or **CSV**

---

## 🛠️ Development

Clone and serve locally:

```bash
git clone https://amanat003.github.io/Tabular-Transformer.git
cd TABULAR-TRANSFORMER
