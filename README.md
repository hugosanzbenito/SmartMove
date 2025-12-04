**THE .IPYNB PROJECT WON'T WORK BECAUSE THE DATASETS FROM TELEFÓNICA CANNOT BE SHARED BECAUSE SECURITY AND PRIVACY MATTERS, BUT THE FOLLOWING LINK DOES SHOW THE PROJECT'S RESULTS AND EVERYTHING GOTTEN FROM THE CODE. https://smartmovedashboard-w9nyke5lwggyeuwmbwry7m.streamlit.app/ JUST CLICK WAKE UP MY APP.**
\# SmartMove - Barcelona Mobility \& Sustainability Analysis

Team 201F | Universitat Pompeu Fabra



\## 📋 Project Overview

This project analyzes public transport sustainability in Barcelona by contrasting real mobility demand (Residents vs. Tourists) against TMB's infrastructure supply. It uses Machine Learning (K-Means Clustering) to identify saturation points and coverage gaps.



\## 📂 Folder Structure

To ensure the code runs correctly, keep the following structure inside your unzipped folder:



SmartMove\_Project\_201F/

├── SmartMove\_Analysis.ipynb       # Main Google Colab Notebook

└── datasets/                      # Data folder (DO NOT RENAME)

&nbsp;   ├── barris.geojson             # Neighborhood map

&nbsp;   ├── ESTACIONS\_BUS.csv          # TMB Bus Supply

&nbsp;   ├── TRANSPORTS.csv             # Metro/Train Supply

&nbsp;   └── mobility\_data/             # Subfolder with monthly CSVs

&nbsp;       ├── 202301\_movilidad.csv

&nbsp;       ├── ...

&nbsp;       └── 202408\_movilidad.csv



\## 🚀 How to Run the Code (Google Colab)



This notebook is configured to use **Relative Paths**. It does not require mounting a Google Drive. Please follow these steps:



1\.  **Open Google Colab** (https://colab.research.google.com/).

2\.  **Upload the Notebook**: Go to `File > Upload notebook` and select `SmartMove\_Analysis.ipynb`.

3\.  **Upload Data**:

&nbsp;   \* Click on the **Files icon (📁)** on the left sidebar.

&nbsp;   \* Drag and drop the entire **`datasets`** folder from your computer into the Colab file area.

&nbsp;   \* \*Wait for the upload to finish\* (the orange circle must disappear).

4\.  **Execute:**

&nbsp;   \* Go to `Runtime > Run all` (or `Entorno de ejecución > Ejecutar todas`).



\## 🛠️ Requirements

The notebook automatically installs the necessary libraries in the first cell:

\* geopandas

\* hdbscan

\* networkx

\* matplotlib \& seaborn

\* scikit-learn



---

**Note:** If you encounter a "File not found" error, please double-check that the folder uploaded to the left panel is named exactly `datasets`.

