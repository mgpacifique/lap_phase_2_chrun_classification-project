# Lap Phase 2 Churn Classification Project

This repository contains the Azubi Africa Data Analytics Phase 2 Churn Classification project.

## Project Overview

The goal of this project is to build a model that can predict customer churn for a telecommunications company. The dataset used for this project includes customer information and their churn status.

## Repository Structure

- `.env`: Environment variables for the project.
- `.gitignore`: Specifies files and directories to be ignored by git.
- `best_log_reg_model.pkl`: Serialized logistic regression model.
- `dap_phase2_churn_classification_project.ipynb`: Jupyter notebook containing the project code and analysis.
- `LP2_Telco-churn-second-2000_1.csv`: First part of the dataset.
- `LP2_Telco-churn-second-2000.csv`: Second part of the dataset.
- `README.md`: Project documentation.
- `requirements.txt`: List of required Python packages.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python packages (listed in `requirements.txt`)

### Installation

1. Clone the repository:
    ```sh
    git clone <https://github.com/mgpacifique/lap_phase_2_chrun_classification-project>
    ```
2. Navigate to the project directory:
    ```sh
    cd lap_phase_2_chrun_classification-project
    ```
3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

### Usage

1. Open the Jupyter Notebook:
    ```sh
    jupyter notebook dap_phase2_churn_classification_project.ipynb
    ```
2. Run the cells in the notebook to execute the analysis and model training.

### Results

The best logistic regression model is saved as `best_log_reg_model.pkl`. You can load this model to make predictions on new data.

## Dataset

The dataset used in this project is split into two CSV files:
- `LP2_Telco-churn-second-2000_1.csv`
- `LP2_Telco-churn-second-2000.csv`

## License

This project is licensed under the MIT License.

## Acknowledgements

- Azubi Africa for providing the dataset and project guidelines.
