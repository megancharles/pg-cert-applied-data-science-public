# Predicting Food Eco-Grades from Ingredient Lists Using Machine Learning

## Description
This repository contains code and resources for predicting food eco-grades from ingredient lists using machine learning. The main goal is to develop models that assess the environmental impact of food products based on their ingredients, leveraging data science techniques for preprocessing, feature extraction, and classification.

## Table of Contents
- [Description](#description)
- [Installation Instructions](#installation-instructions)
- [Usage Instructions](#usage-instructions)
- [Data](#data)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Future Work](#future-work)

## Installation Instructions
1. Clone the repository:
   ```sh
   git clone https://github.com/megancharles/pg-cert-applied-data-science-public.git
   ```
2. Navigate to the project directory:
   ```sh
   cd pg-cert-applied-data-science-public
   ```
3. Install the required Python packages:
   ```sh
   pip install -r requirements.txt
   ```
4. (Optional) Set up a virtual environment for isolation:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

## Usage Instructions
Jupyter notebooks and Python scripts are provided for each stage of the project:
- Data cleaning and translation: `notebooks/cleaning and translating data v2.ipynb`, `src/data/1_data_cleaning.ipynb`
- Feature extraction and preprocessing: `src/features/3_pre-processing.ipynb`
- Model training and evaluation: `src/models/4_classification_model.ipynb`
- Exploratory data analysis and visualisation: `src/visualisation/2_EDA.ipynb`

To run a notebook:
1. Launch Jupyter:
   ```sh
   jupyter notebook
   ```
2. Open the desired notebook and run the cells in order.

To run a Python script:
```sh
python src/data/1_data_cleaning.ipynb
```

## Data
The data used in this project is sourced from [Open Food Facts](https://world.openfoodfacts.org/). It includes raw product data, cleaned ingredient lists, and processed datasets for modeling. Data files are organized in the `data/` directory:
- `data/raw/`: Original raw data files
- `data/processed/`: Intermediate processed files
- `data/final/`: Final cleaned datasets

## File Structure
```
├── data/
│   ├── raw/                # Raw product data
│   ├── processed/          # Processed and intermediate data
│   └── final/              # Final cleaned datasets
├── notebooks/              # Jupyter notebooks for data cleaning and translation
├── reports/
│   └── figures/            # Generated plots and visualisations
├── src/
│   ├── data/               # Data cleaning scripts/notebooks
│   ├── features/           # Feature extraction and preprocessing
│   ├── models/             # Model training and evaluation
│   └── visualisation/      # Exploratory data analysis and visualisation
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
```

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request. For major changes, open an issue first to discuss your proposed improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- Birkbeck University, PG Cert Applied Data Science 2024/25
- Open Food Facts for providing the data
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, transformers, torch, and others listed in `requirements.txt`

## Future Work
- Improve model accuracy and generalisation
- Add more advanced NLP techniques for ingredient processing
- Integrate additional data sources
