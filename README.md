# TanzMusicML

TanzMusicML is a machine learning project aimed at predicting musical preferences in Tanzania based on demographic data. This project utilizes machine learning algorithms to analyze age, gender, and genre preferences to predict the most likely music genre a person from Tanzania might enjoy.

## Project Structure

The project directory is structured as follows:

- `data/`: Directory for storing data files.

  - `raw/`: Raw data files before preprocessing.
  - `processed/`: Processed data files after preprocessing.
  - `external/`: External datasets (if any).

- `notebooks/`: Jupyter notebooks for data exploration, model training, etc.

  - `data_exploration.ipynb`: Notebook for exploring the dataset.
  - `data_preprocessing.ipynb`: Notebook for data preprocessing.
  - `model_training.ipynb`: Notebook for model training.
  - `model_evaluation.ipynb`: Notebook for model evaluation.

- `src/`: Source code directory.

  - `preprocessing.py`: Scripts for data preprocessing.
  - `modeling.py`: Scripts for model training and evaluation.
  - `utils.py`: Utility functions.

- `models/`: Directory for saving trained models.

- `reports/`: Project reports and documentation.

  - `project_report.pdf`: Final project report.
  - `figures/`: Directory for storing figures generated during analysis.

- `requirements.txt`: List of Python packages required for the project.

- `LICENSE`: Project license file.

## Getting Started

1. Clone this repository:

```bash
git clone https://github.com/Njoxpy/TanzMusicML.git
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Explore the Jupyter notebooks in the notebooks/ directory to understand the project workflow.

4. Run the notebooks and scripts to preprocess the data, train models, and evaluate their performance.

## Usage

- data_exploration.ipynb: Use this notebook to explore the dataset and gain insights into the distribution of age, gender, and music genres.

- data_preprocessing.ipynb: Preprocess the raw data, handle missing values, encode categorical variables, etc.

- model_training.ipynb: Train machine learning models using the preprocessed data.

- model_evaluation.ipynb: Evaluate the trained models' performance and analyze the results.

## Contributing

- Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.
