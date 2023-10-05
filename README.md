# indic-hate-classifier
A Hate classifier for low resource Indian languages

## DataSets
This project uses datasets collected from various research papers and AI workshops. 

### Dataset format 
| Column | Description | Format
--|--|--
UID | Unique identifier to trace the origin of the dataset and act as index for dataset.| <dataset>_<language_code>_<train/test/val>_<index_number>
|text | The text content used for classifier | utf-8 encoded text
|label_yn| A binary label indicating whether text is classified as hate / non-hate in respective datasets.| 1 - hate <br> 0 - non-hate
### Sources
Datasets used for each language are mentioned below. 
#### Hindi : 
1. https://github.com/ShareChatAI/MACD/tree/main/dataset
2. https://competitions.codalab.org/competitions/26654
3. https://github.com/hate-alert/HateCheckHIn/blob/main/monolingual_functionalities.csv
4. https://hasocfire.github.io/hasoc/2019/dataset.html

#### Marathi :
1. https://github.com/Kalit31/HASOC-2021/tree/main/data/marathi
2. https://github.com/TharinduDR/DeepOffense/tree/master/examples/marathi/data
3. https://github.com/l3cube-pune/MarathiNLP/tree/main/L3Cube-MahaHate/2-class

#### Telugu :
1. https://github.com/ShareChatAI/MACD/tree/main/dataset

## Development Setup

1. Please install [Poetry](https://python-poetry.org/docs/#installation)
2. Run `poetry install` in the project root to install required dependencies.
3. Run `poetry shell` to create a new poetry shell.
4. Run `jupyter notebook` to run jupyter notebook server.


