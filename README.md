This Power BI dashboard provides an in-depth analysis of retail sales performance and profitability across different countries. Built with DAX, dynamic filtering, and rich visuals, it enables decision-makers to track KPIs, monitor revenue trends, and explore product-level contributions.

---

## 📊 Dashboard Highlights

- 📈 Line chart: Monthly profit trends across regions
- 🗺️ Map: Geographic distribution of revenue
- 📊 Bar chart: Profit comparison by country
- ✅ Slicers for product type and country selection
- 📋 Table summary: Units sold, population, revenue, and profit

---

## 🔍 Key Insights

- **France and the United States lead in overall profit**, followed by Canada and Germany.
- **Seasonal trends** reveal significant spikes in monthly profit, indicating possible promotional cycles or demand surges.
- **Product-level slicer interaction** enables deep dives into the performance of items such as cookies and chocolates.
- **White Chocolate Macadamia Nut**, when selected, shows widespread profitability, making it a standout product across multiple countries.
- **Revenue contributions** align closely with population and sales volume but vary by region due to differing product mixes.

---

## 📁 Repository Structure

global-sales-profit-dashboard/
├── sabiha-powerbi.pbix
├── report/
│ └── Global_Sales_Profit_Summary.docx
├── screenshots/
│ └── dashboard-preview.png
├── data/
│ └── original_dataset_link.txt
├── LICENSE
└── README.md

yaml
Always show details

Copy

---

## 📄 Project Report

A formal executive summary is provided in the [`report/`](report/) folder:  
📄 [Global_Sales_Profit_Summary.docx](report/Global_Sales_Profit_Summary.docx)

---

## 📦 Dataset Source

This dashboard uses a **simulated international sales dataset** with key retail metrics such as:
- Units sold
- Country-level population
- Product category
- Revenue and Profit
It’s designed to mimic real-world retail KPIs in an analytical storytelling format.

---

## 🛠 Tools Used

- Power BI Desktop
- DAX formulas and measures
- GitHub (documentation and version control)

---

## 🪪 License

This project is licensed under the MIT License.
"""

# Save the README to a markdown file
readme_path = "/mnt/data/README.md"
with open(readme_path, "w") as file:
    file.write(readme_content)

readme_path
