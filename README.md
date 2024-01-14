# Data Engineering Python Group Project
Data Engineering Python Group Dog

### Structure 
```bash
.
├── README.md
├── cleaned
│   ├── bz_grenzen_cleaned.csv
│   ├── districts_cleaned_2023.csv
│   ├── dogs_cleaned_cc.csv
│   ├── fam_total_2021.csv
│   ├── income.csv
│   ├── parks_cleaned.csv
│   └── pop_total_2023.csv
├── data
│   ├── BEZIRKSGRENZEOGD.json
│   ├── PARKINFOOGD.csv
│   ├── hunde-wien.csv
│   ├── vie-bez-biz-ecn-inc-sex-2002f.csv
│   ├── vie-bez-biz-pop-den-2002f.csv
│   └── vie-bez-fam-typ-2012f.csv
├── environments
│   ├── prj01-environment.txt
│   └── prj01-environment.yml
├── prj01.ipynb
└── report_images
    ├── Hyp1_Fig1.png
    ├── Hyp1_Fig2.png
    ├── Hyp1_Fig3.png
    ├── Hyp2_Fig1.png
    ├── Hyp2_Fig2.png
    ├── Hyp4_Fig1.png
    ├── Hyp4_Fig2.png
    └── Hyp5_Fig1.png

```
- Code for Exploratory Data Analysis is in prj01.ipynb
- Original data sources are in `data`, cleaned data is in `cleaned`
- `environment` contains the conda environment.yml as `prj01-environment.yml`and the explicit specification files as `prj01-environment.txt`
- Environments were tested on MacOS and Windows11

### HOW TO RUN: 

- Create environment via `conda env create -f environments/prj01-environment.yml`

- Run prj01.ipynb in jupyter-lab or jupyter-notebook

### Data Links: 

- Main Data Source: hunde-wien.csv (Source: https://www.data.gv.at/katalog/dataset/71edef44-9d6c-4042-ab71-7207dc930ba7)
- Additional Data Sources:
  
  - vie-bez-fam-typ-2012f.csv (Source: https://www.data.gv.at/katalog/dataset/409cb73f-f158-491f-ba23-c9b9cf856964)
  - PARKINFOOGD.csv (Source: https://www.data.gv.at/katalog/dataset/22add642-d849-48ff-9913-8c7ba2d99b46#additional-info)
  - vie-bez-biz-pop-den-2002f.csv (Source: https://www.data.gv.at/katalog/dataset/dc56ea9e-57be-47d5-ab50-d1e74fda7118#additional-info) 
  - BEZIRKSGRENZEOGD.json (Source: https://www.data.gv.at/katalog/dataset/stadt-wien_bezirksgrenzenwien)
  - vie-bez-biz-ecn-inc-sex-2002f.csv https://www.data.gv.at/katalog/de/dataset/vie-bez-biz-ecn-inc-sex-2002f
  
  

