# 📊 Corporate Tax Flow Visualization with Plotly Sankey

This project demonstrates how to use **Python + Plotly** in **Google Colab** to create an interactive **Sankey diagram** that shows how corporate profit flows into taxable income, tax liability, and final net tax position (payable or refundable).

The idea:  
Revenue → Gross Profit → Operating Profit → Profit Before Tax → Tax Adjustments → Taxable Income → Tax Liability → Net Tax.

---

## 🚀 Features
- Interactive **Plotly Sankey chart**.
- Built-in **demo dataset** (fictional numbers for illustration).
- Clear step-by-step **Google Colab notebook** with comments.
- Easy to replace with **real company numbers** (Apple, Tesla, Microsoft, etc.).
- Outputs both **interactive HTML chart** and **summary CSV**.

---

## 📂 Project Structure
├── demo_income_tax_summary.csv # Example summary dataset (generated)
├── demo_sankey_tax_flow.html # Interactive Sankey chart (generated)
├── notebook.ipynb # Google Colab / Jupyter notebook
├── README.md # This file

---

## Getting Started

### 1. Open in Google Colab
Click below to open the notebook directly in Colab:

https://colab.research.google.com/drive/1Vptg-iH7KhciregMzWBtTVP9EffrnaEq#scrollTo=GHX5LWjg9OBE

### 2. Run the Notebook
The notebook is self-contained:
- Installs dependencies (`plotly`, `kaleido`).
- Builds a **sample income & tax dataset**.
- Creates an **interactive Sankey diagram**.
- Saves results to **CSV** and **HTML**.

---

## 🎨 Example Visualization

<img width="1075" height="571" alt="image" src="https://github.com/user-attachments/assets/f61a096e-bb57-4668-8bbd-a03189abb49b" />

---

## 🔧 Customize with Real Data
To use real company financials:
1. Get income statement & tax disclosures (e.g., from 10-K, annual reports, or APIs like `yfinance`).
2. Replace the demo variables in the notebook (`revenue`, `cogs`, `op_expenses`, etc.).
3. Run all cells again → the Sankey updates automatically.

