# Sony Bravia TV Reviews - NLP Project

This project focuses on building a model to analyze and classify product reviews using Natural Language Processing (NLP) and Neural Networks. The classification task is a 3-class sentiment classification: Negative, Neutral, and Positive.

## Dataset Info
* **File:** `SonyBravia_TV_Reviews.csv`
* **Update:** **1400 new reviews have been added to the dataset**, making it a more robust source for training and evaluating our sentiment classification models.

## Libraries & Dependencies Used

The following libraries and dependencies are used throughout the notebook:

- **Data Processing & Analysis:** `pandas`, `numpy`
- **Deep Learning & Machine Learning:** `tensorflow` (Keras), `scikit-learn`, `imblearn` (SMOTE for class imbalance)
- **Natural Language Processing (NLP):** `nltk`, `gensim` (Word2Vec)
- **Data Visualization:** `matplotlib`, `seaborn`
- **Model Interpretability:** `lime`

## How to Run the Notebook

1. **Prerequisites:** 
   Ensure you have Python installed (preferably version 3.9 or higher). 

2. **Install Dependencies:**
   You can install all required libraries by running the following command in your terminal:
   ```bash
   pip install pandas numpy lime matplotlib seaborn nltk tensorflow gensim scikit-learn imbalanced-learn
   ```
   *(Note: The first cell of the notebook also contains a pip install command to automatically install the core packages).*

3. **Download NLTK Data:**
   The notebook will automatically download the required NLTK datasets (`stopwords`, `wordnet`, `punkt`, `omw-1.4`) when you run the setup cell in Section 0.

4. **Launch the Notebook:**
   Navigate to the project directory containing the notebook and the dataset in your terminal, and start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

5. **Execute the Code:**
   Open `SonyBravia_TV_reviews_NLP_Project.ipynb` in your browser. Ensure that `SonyBravia_TV_Reviews.csv` is located in the exact same directory as the notebook. Simply run the cells in sequential order from top to bottom (Section 0 to Section 10).
