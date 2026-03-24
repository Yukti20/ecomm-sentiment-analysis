In this project, I'm fine-tuning a sentiment analysis model (Hugging Face) and using it to classify Amazon product reviews.

**Dataset**: `amazon_polarity`
The dataset is a dictionary-like container storing `train` and `test` splits. Each split contains:
`title`, `content`, and `label`.

Label mapping (binary classification):
`label=0` -> negative, `label=1` -> positive. 

**Pretrained model**: `distilbert-base-uncased`

## Quick start
1. Create a virtual environment.
2. Install dependencies:
   - `pip install -r requirements.txt`
3. Open and run `ecomm_sentiment_analysis.ipynb`.

## Notes
- The notebook is designed to be runnable as a demo by using small subsets of the dataset.
- Fine-tuned model saving is optional. In the notebook, set `SAVE_MODEL = True` to write outputs under `artifacts/`.
