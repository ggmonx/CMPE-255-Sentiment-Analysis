# CMPE-255-Sentiment-Analysis

- Group 7 Members:Gaston Garrido, Derian Lemus, Cong Li, Ealrada Piroyan

# Project Information

- This project's goal is to perform sentiment analysis on a labeled dataset of Amazon reviews

# Download

- Link to download [data](http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Home_and_Kitchen_5.json.gz)
- Disclaimer: This code was run with an RTX 2070 Super GPU
- Might have to make tweaks such as lowering batch size to run code
- The data is omitted from the git repo due to its large size
- `Home_and_Kitchen_5.json` should be downloaded and placed in the root folder of this project

# Running the code

- To recreate the environment in conda run `conda env create -f sentan.yml`
- To activate the environment run `conda activate sentan`
- Run `python -m spacy download en_core_web_sm`
- At this point you can run `jupyter notebook` and then run in order `CMPE255-TeamProject.ipynb`-> `Sentiment_analysis.ipynb` -> `Adding_review_text_column.ipynb` to generate the final results which are looked at in `Data_Analysis.ipynb`.
- To use the `data.json` change the `USE_SMALL_SUBSET` var in `CMPE255-TeamProject.ipynb` to `True`
