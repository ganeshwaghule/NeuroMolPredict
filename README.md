# NeuroMolPredict
NeuroMolPredict is a machine learning tool that predicts the bioactivity of chemical compounds based on their SMILES (Simplified Molecular Input Line Entry System) strings. It uses a pre-trained Random Forest Classifier to assess the potential bioactivity against various targets retrieved from the ChEMBL database.

# Process flowchart for the Tool

![image](https://github.com/ganeshwaghule/NeuroMolPredict/assets/142625938/0526ea62-b615-48e5-9d2c-0abede2c10d5)

## Features

- Fetches target data from the ChEMBL database based on input SMILES strings.
- Uses a Random Forest Classifier to predict bioactivity probabilities for each target.
- Displays results in a table format and allows downloading the data as a PDF.

## Installation

Before running NeuroMolPredict, ensure that you have Python installed along with the following libraries:
- pandas
- requests
- joblib
- IPython
- reportlab

You can install these libraries using pip:

```bash
pip install pandas requests joblib ipython reportlab
```
# Usage
To use NeuroMolPredict, follow these steps:

1. Clone this repository to your local machine.
2. Place your pre-trained model file (chembl_bioactivity_model.pkl) in the root directory.
3. Run the script neuromolpredict.py (or the name of your main script file).
4. Enter a SMILES string when prompted.
5. View the predicted bioactivity probabilities and download the results if desired.

# Contributing
Contributions to NeuroMolPredict are welcome! If you have suggestions for improvements or bug fixes, feel free to open an issue or a pull request.

# License
MIT License

# Contact
For any questions or feedback, please contact Mr. Ganesh Waghule, Email ID- ganeshwaghule12@gmail.com or Call +91 9960867592

