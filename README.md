# Subject : Understanding how men and women doctors approach medicine through health textbooks, between 1850 and 1940

# Code Repository

This GitHub repository contains all the code and computational tools used in this research project. Below is a description of the repository structure and the libraries used.

## Global Architecture

The repository is organized as follows:

- **Data**: This folder contains all the data required for analysis.
  - **Contexte**: Includes six CSV files summarizing authors, cited individuals, and publication dates for each book.
  - **Occurrences**: Contains four subfolders, one for each type of book (male, female, mixed). Each subfolder contains CSV files with word occurrences for individual books. An additional subfolder (`txt_merged`) consolidates data into three CSV files for each book category.
  - **TXT**: Stores OCR results for each book category.
  - A special file named `liste_francais.txt` provides data used for comparative OCR analysis.

- **Git-LFS**: Configuration folder to manage large files within the repository.

- **Notebooks**: Contains Jupyter notebooks used for visualizations and advanced analyses, including the interactive complex LDA model.

- **Scripts**: Includes all the functions used in the notebooks and the main project execution scripts.

- - Rapport.pdf : Report of the project.

*Note*: The original source files (PDFs and JPG images) totaling approximately 24 GB are not included in this repository due to their size. These files are stored locally.

---

## Libraries Used

The following libraries were employed in this project:

- **[pdf2image](https://pypi.org/project/pdf2image/)**: For converting PDF files into images.
- **[Tesseract](https://github.com/h/pytesseract)**: OCR engine used to extract text from images.
- **[NLTK](https://www.nltk.org/)**: For text processing, including the removal of stopwords.
- **[Scikit-learn](https://scikit-learn.org/)**: Used for topic modeling with the Latent Dirichlet Allocation (LDA) algorithm.
- **[Pandas](https://pandas.pydata.org/)**: For data manipulation and analysis.
- **[Matplotlib](https://matplotlib.org/)** and **[Seaborn](https://seaborn.pydata.org/api.html)**: For data visualization.
- **[Gensim](https://radimrehurek.com/gensim/)**: For advanced text modeling and topic modeling.
- **[OpenCV](https://opencv.org/)**: For preprocessing images before OCR.

---
