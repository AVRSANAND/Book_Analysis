# Book Sentiment Analysis

This repository contains scripts for performing sentiment analysis on a book provided in .txt format. The analysis is performed using Python packages, and the code is provided in Jupyter notebooks.

## Contents

- `Book_Analysis.ipynb`: This notebook contains the preprocessing and analysis of the book's text.
- `Sentiment_Analysis.ipynb`: This notebook focuses on performing sentiment analysis on the processed text from a text file.
- `Pdf_Analysis.ipynb`: Thi notebook focuses on performing sentiment analysis on the processed text from a pdf file.
- `book.txt`: The text file of the book used for analysis.
- `book.pdf`: The pdf file of the book used for analysis.

## Requirements

The following Python packages are required to run the notebooks:

- `nltk` 
- `re`
- `matplotlib`

You can install the required packages using pip:

```bash
pip install nltk
```

## Usage

1. **Book Analysis (`Book_Analysis.ipynb`)**:
    - Load and preprocess the text from `book.txt`.
    - Perform exploratory data analysis (EDA) to understand the structure and content of the text.
    - Clean the text by removing unwanted characters, stop words, and performing tokenization.

2. **Sentiment Analysis (`Sentiment_Analysis.ipynb`)**:
    - Utilize the preprocessed text data from the previous notebook.
    - Apply sentiment analysis using the `nltk` library to determine the sentiment polarity and subjectivity of the text.
    - Visualize the results to interpret the sentiment trends throughout the book.

3. **Pdf Analysis (`Pdf_Analysis.ipynb`)**:
    - Load and preprocess the text from `book.pdf`.
    - Apply sentiment analysis using the `nltk` library to determine the sentiment polarity and subjectivity of the text.
    - Visualize the results to interpret the sentiment trends throughout the book using matplotlib.
   
## How to Run

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/AVRSANAND/Book_Analysis.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Book_Analysis
    ```

3. Ensure you have all required packages installed (see Requirements section).

4. Open the Jupyter notebooks and run the cells sequentially:
    ```bash
    jupyter notebook Book_Analysis.ipynb
    jupyter notebook Sentiment_Analysis.ipynb
    jupyter notebook Pdf_Analysis.ipynb
    ```

## Results

The sentiment analysis results provide insights into the emotional tone of the book across different chapters. By visualizing sentiment scores, we can observe how the author's emotions vary throughout the narrative.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue if you have any suggestions or improvements.
