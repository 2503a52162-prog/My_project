# Hospital Patient Analytics Dashboard

This project generates an Excel dashboard from a local healthcare dataset.

## Run the dashboard

1. Install Python 3.11 or later and the `pandas` and `xlsxwriter` packages.
2. Place your authorized `healthcare_dataset.csv` file beside
   `generate_hospital_dashboard.py`.
3. Run:

   ```powershell
   python generate_hospital_dashboard.py
   ```

The script writes `cleaned_healthcare_data.csv` and
`Hospital_Patient_Analytics_Dashboard.xlsx` in the project folder. Dataset and
generated files are excluded from Git to avoid publishing patient information.

The analysis notebook also expects the dataset to be present locally.
