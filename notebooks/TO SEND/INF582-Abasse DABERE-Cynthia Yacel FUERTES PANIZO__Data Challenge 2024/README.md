# INF582-DataChallenge2024

# News Articles Title Generation Challenge

### Students Name:
- DABERE Abasse
- FUERTES PANIZO Cynthia Yacel

### Installation

1. Clone this repository to your local machine
2. Navigate to the cloned repository and install the required packages using: pip install -r requirements.txt

### Preparing the Environment

1. Place the `data` folder in the same directory as the Jupyter notebooks.
2. Ensure that all necessary data files are present in the `data` folder.
   The dataset is split into three files:

- `train.csv`: Contains 21,405 news articles and titles.
- `validation.csv`: Contains 1,500 news articles and titles.
- `test_text.csv`: Contains 1,500 news articles for which titles need to be generated.

### Running the Notebooks

1. Begin by running the `02_Grammar_correction.ipynb` notebook to get train_grammar_correction.csv dataset.
2. Run Fine_Tuned Model notebooks


### Notebooks:
- `01_Data_Analysis.ipynb`: Data analysis that we did in order to understand the data.
- `02_Grammar_correction.ipynb`: All the approaches that we made to correct the grammatical errors in the text.
- `03_Fine_Tuning_M1_mbart.ipynb`: Fine-Tuning of mbart-mlsum-automatic-summarization.
- `04_Fine_Tuning_M2_T5.ipynb`: Fine-Tuning of t5-base-fr-sum-cnndm
- `05_Fine_Tuning_M3_mT5_multilingual.ipynb`: Fine-Tuning of mT5_multilingual_XLSum

The best score is obtained with the model `mT5_multilingual` and with the grammatical correction dataset created using `import language_tool_python`.