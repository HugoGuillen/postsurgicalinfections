# Prediction of Postoperative Infections

This repository contains the supporting code for the article titled "Prediction of Postoperative Infections by Strategic Data Imputation and Explainable Machine Learning". It includes a pre-trained model, executable code, and a notebook designed for Google Colab to facilitate replication and further exploration of the study's findings.

## Repository Structure

- **/data**: Contains the pre-trained machine learning models used in the study.
- **/nb_predictor.ipynb**: Jupyter notebook for performing the classification and SHAP Radar.

## Getting Started

To get started with this project, clone this repository using:
```bash
git clone https://github.com/HugoGuillen/postsurgicalinfections.git
```

##Prerequisites

Ensure you have the following installed:

- Python 3.8 or later
- Jupyter Notebook or access to Google Colab
- Necessary Python libraries which can be installed using: `pip install -r requirements.txt`

## Running the Notebook

- Navigate to the root directory.
- Open the Jupyter Notebook in your local environment or upload it to Google Colab.
- Follow the instructions within the notebook to run the model.

## Using the Model

To use the pre-trained model:

- Import the model from the /model directory.
- Load your data following the structure outlined in the notebook (check the `template.csv`).
- Use the provided code in the notebook to apply the model to your data.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

## Citation

If you use the code or models from this repository in your research, please cite the associated article: `IN REVIEW`

## License
This project is licensed under the Apache 2.0 License.

## Contact
For any queries, please reach out via email at hugo.guillenramirez@unibe.ch.
