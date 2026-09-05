# GBC Ghana — CSR Communications Audit
> Portfolio analysis repository. Findings are based on publicly available materials and clearly identified assumptions; this is not commissioned client work or an official company report.

**Author:** Caleb Agyemang  
**Portfolio:** [calebagyemang.vercel.app](https://calebagyemang.vercel.app)

## Overview

A stakeholder matrix and CSR communication effectiveness audit of Ghana Broadcasting Corporation (GBC), mapping influence, communication need, and CSR performance across 8 stakeholder groups using public data from the 2024 Stakeholders Conference and institutional reports.

## Data Sources

| Source | Type | Coverage |
|--------|------|----------|
| GBC 2024 Stakeholders Conference | Institutional | Funding, sustainability, CSR partnerships |
| Public Media Alliance | Media Analysis | GBC funding challenges, editorial independence |
| GBC Draft Consultation Doc (Nov 2025) | Government | Sustainability & commercial viability |
| Rabotec Group Partnership | CSR | Environmental cleanup initiatives |
| GBC @ 90 Anniversary | Cultural | Historical context, public service legacy |

## Key Findings

- **8 stakeholder groups** mapped across influence × communication need
- **Overall CSR score:** 58.5/100 against best-practice benchmarks
- **Top performer:** Public Education (82/100)
- **Biggest gap:** Funding Advocacy (25 points below target)
- **Transparency score:** 38/100 — significant room for improvement
- **Environmental CSR:** Limited to partnerships, no internal programme

## Technical Stack

- Python 3.11
- Pandas, NumPy
- Matplotlib (stakeholder matrix, radar chart, gap analysis)

## How to Run

```bash
pip install -r requirements.txt
python scripts/analyze_gbc_csr.py
```

## Outputs

- `output/gbc_stakeholder_matrix.png` — Bubble plot (influence × communication need)
- `output/gbc_csr_radar.png` — Performance radar across 6 dimensions
- `output/gbc_csr_gap_analysis.png` — Current vs. best practice comparison
- `output/gbc_executive_summary.json` — Structured findings

## Methodology

Stakeholder mapping using Freeman's stakeholder theory framework, scored by influence (1–10) and communication need (1–10). CSR performance evaluated across 6 dimensions against best-practice benchmarks for public broadcasters in Sub-Saharan Africa.

## License

MIT
