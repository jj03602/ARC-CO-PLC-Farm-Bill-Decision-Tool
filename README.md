# ARC/PLC Farm Bill Decision Tool

An interactive web tool to help Idaho, Oregon, Utah, and Washington grain and specialty crop producers compare **Agriculture Risk Coverage (ARC-CO)** and **Price Loss Coverage (PLC)** payments under the **One Big Beautiful Bill Act (OBBBA)** for the 2026–2027 marketing year.

🔗 **Live Tool:** [https://jj03602.github.io/arcplc-tool/](https://jj03602.github.io/arcplc-tool/)
📊 **Shiny App:** [https://jung-keon.shinyapps.io/ARC_PLC/](https://jung-keon.shinyapps.io/ARC_PLC/)

---

## What This Tool Does

- Compares ARC-CO and PLC payments for a producer's specific **county, crop, and irrigation type**
- Covers **16 eligible crops** across **Idaho, Oregon, Utah, and Washington**
- Applies current **OBBBA rules**: 90% guarantee and 12% payment cap for ARC-CO; updated Effective Reference Prices for PLC
- Shows **historical payment records** from 2014 to 2024 under both actual and OBBBA retroactive rules
- Allows users to explore how different **MYA price scenarios** affect the program tradeoff

---

## Data Sources

| Data | Source |
|---|---|
| ARC-CO benchmark yields, prices, and revenues | USDA FSA ARC-CO County Benchmark Files |
| PLC yields | USDA FSA PLC Yield Files |
| Effective Reference Prices and Loan Rates | USDA FSA ARC/PLC 2025 Fact Sheet (OBBBA) |
| Historical MYA prices (2014–2024) | USDA FSA Published MYA Tables (Jan 2022, Jan 2026) |
| Historical county yields (2014–2019) | USDA FSA ARC-CO Historical Benchmark File |
| NASS acres harvested | USDA NASS QuickStats API |
| FSA enrolled base acres (2019–2025) | USDA FSA Program Data |

---

## Repository Contents

```
index.html        # Landing page (host this on GitHub Pages)
```

The Shiny app source code is maintained separately at [jung-keon.shinyapps.io/ARC_PLC/](https://jung-keon.shinyapps.io/ARC_PLC/).

---

## Authors

**Jung-Keon Jo**
Postdoctoral Research Fellow
Department of Agricultural Economics and Rural Sociology, University of Idaho
📧 jungkeonjo@uidaho.edu
🌐 [sites.google.com/view/jungkeonjo](https://sites.google.com/view/jungkeonjo)

**Xiaoli Etienne**
Professor and Idaho Wheat Commission Endowed Chair in Commodity Risk Management
Department of Agricultural Economics and Rural Sociology, University of Idaho
📧 xetienne@uidaho.edu

---

## Citation

Jo, J.K. and X. Etienne. (2026). *ARC/PLC Farm Bill Decision Tool for Pacific Northwest Producers*.
University of Idaho Extension. Available at: https://jj03602.github.io/ARC-CO-PLC-Farm-Bill-Decision-Tool/

---

## Acknowledgments

This tool was developed with support from the Idaho Wheat Commission and the University of Idaho
Department of Agricultural Economics and Rural Sociology. ARC/PLC methodology is based on
USDA FSA published program rules and the One Big Beautiful Bill Act (2025).

---

## License

© 2026 University of Idaho. All rights reserved.
