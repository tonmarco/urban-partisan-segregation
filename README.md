# Replication code for "Within and across partisan divides: mobility behavior and experienced partisan segregation in US cities"

This folder reproduces Figures 2–4 from the plotting tables in `data/`. It does not include Cuebiq or other individual-level data, that can be requested directly from Cuebiq through its Social Impact program, subject to Cuebiq's eligibility requirements and data-use conditions (https://cuebiq.com/social-impact, contact https://cuebiq.com/contact/).

From `code_paper/`, install the requirements and open JupyterLab:

```bash
python -m pip install -r requirements.txt
jupyter lab
```

Open `fig_2.ipynb`, `fig_3.ipynb`, or `fig_4.ipynb` and run the cells in order. The commented calculation cells explain how the plotting tables were made; they do not need the original data. The notebooks use the bundled Barlow fonts in `font/`. Figure 4 also uses `data/fig4c_basemap.png` for its map background.
