# Wikipedia Award Winners Clustering
## Description
This project dives into the rich world of Wikipedia to explore and categorize pages dedicated to award-winning individuals across various fields. Utilizing sophisticated machine learning and natural language processing (NLP) techniques, our objective is to cluster Wikipedia pages in a way that reveals underlying patterns, similarities, and thematic groupings among these distinguished figures. By analyzing the textual content of pages related to award recipients, we aim to uncover insights into commonalities in their achievements, careers, and contributions. This clustering endeavor not only aids in the systematic organization of information but also enhances our understanding of the characteristics that link these winners, potentially shedding light on the pathways to excellence and recognition.

## Features
* Automated Text Analysis: Leverages TF-IDF vectorization for feature extraction from textual data.
* Advanced Clustering: Utilizes K-Means and Hierarchical Clustering for document categorization.
* Dynamic Feature Selection: Implements Variance Threshold and TruncatedSVD for efficient dimensionality reduction.
* Robust Evaluation: Employs Silhouette Score, Davies–Bouldin Index, and Calinski-Harabasz Index for in-depth cluster analysis.

## Installation
Getting started with our text clustering project is straightforward. Here’s how:

1. Ensure Python 3.x is Installed: Our project requires Python version 3.6 or newer. You can download it from python.org.

2. Download the Project:
   git clone https://github.com/ronikronitz/Machine-Learning.git
* This makes a copy of the project on your computer.
  
3. Prepare Your Workspace:
* Move into the project directory:
  cd Machine-Learning

4. Install Required Libraries:
  This project makes use of several Python libraries for web scraping, data manipulation, natural language processing (NLP), text analysis, and       
   visualization.
   Ensure you have Python 3.6 or newer installed on your system.
   The required libraries can be installed using the following command:
   pip install wikipedia pandas nltk scikit-learn matplotlib requests numpy

   Post-Installation Steps:
   import nltk
   nltk.download('stopwords')
   nltk.download('punkt')
   import wikipedia
   wikipedia.set_lang("en")
   import VarianceThreshold
   import numpy as np
   
## Usage

With your environment set up and dependencies installed, you're ready to run the project:

1. **Start Jupyter Notebook**:
    If the project is notebook-based (like `WIKIDATA.ipynb`), launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
    Then, open the `MLWIKI.ipynb` notebook in the browser interface that appears.

2. **Running the Notebook**:
    Execute cells sequentially within the notebook to perform the analysis or visualize the data. You can run a cell by selecting it and pressing `Shift + 
    Enter`.

3. **Experimenting**:
    Feel free to modify the code or experiment with different parameters within the notebook to explore the dataset further.

## Contributing
Contributions are welcome! Please open an issue to discuss proposed changes or submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Credits
NLTK for text processing tools.
scikit-learn for machine learning algorithms.
pandas and NumPy for data manipulation.

## Support
For support, please open an issue in the GitHub repository.






   



