# Sentiment Analysis

This tutorial on Sentiment Analysis was developed for CDCS by **Dave Elsmore** (Edina) and updated by Xandra Dave Cochran, Somya Iqbal and Aybuke Atalay. 
This workshop uses the programming language **Python** and **R** to perform some common text analysis  tasks. The aim is that by using the pre-supplied code examples, and editing them to examine the different results, you will begin to gain an understand of the techniques used. 
## Workshop Files

#### Text Files
- [The Origin of Species, Charles Darwin](https://raw.githubusercontent.com/DCS-training/SentimentAnalysis/main/darwin-origin.txt)
- [Dream Psychology, Sigmund Freud](https://raw.githubusercontent.com/DCS-training/SentimentAnalysis/main/freud-dreams.txt)
- [Frankenstein, Mary Shelley](https://raw.githubusercontent.com/DCS-training/SentimentAnalysis/main/shelley-frankenstein.txt)
- [War of the Worlds, H.G. Wells](https://raw.githubusercontent.com/DCS-training/SentimentAnalysis/main/wells-war-worlds.txt)
- [Pride & Prejudice, Jane Austen](https://raw.githubusercontent.com/DCS-training/SentimentAnalysis/main/austen-pride-prejudice.txt)

#### CSV Files
- [Trump Tweet Archive, Donald Trump](https://raw.githubusercontent.com/DCS-training/SentimentAnalysis/main/trump-tweet-archive.csv)
- [Trump Tweet 2020 Tweets, Donald Trump](https://raw.githubusercontent.com/DCS-training/SentimentAnalysis/main/trump-tweets-2020.csv)

#### Text files with chapter tags
- [Jane Eyre, Charlotte Bronte](https://raw.githubusercontent.com/DCS-training/SentimentAnalysis/main/bronte-jane-eyre.txt)
- [Frankenstein, Mary Shelley](https://raw.githubusercontent.com/DCS-training/SentimentAnalysis/main/shelley-frankenstein2.txt)
- [Pride and Prejudice, Jane Austen](https://raw.githubusercontent.com/DCS-training/SentimentAnalysis/main/austen-pride.txt)
- [Wuthering Heights, Emily Bronte](https://raw.githubusercontent.com/DCS-training/SentimentAnalysis/main/bronte-wuthering-heights.txt)

### Useful resources and links

If you'd like to continue with text analysis beyond TextBlob used in the notebooks for this session, you may be interested in exploring:
- **NLTK**, python natural language toolkit ([link](https://www.nltk.org/index.html))
- NLTK, freely available book guide ([link](https://www.nltk.org/book/))
- NLTK, guide in python ([link](https://realpython.com/python-nltk-sentiment-analysis/))
- **spaCY** , a python package - includes sentiment analysis ([link](https://spacy.io/usage))
  
---

You may be interested in visualisng outputs from your analyses for example a word cloud, or bar charts for positive/negative valence, counts of top terms in your text and so forth:

> **Note**: data should be pre-processed and ready for visualising your final outputs, this can include removing stop words for instance.
- Matplotlib, a python library for visualising outputs ([link](https://matplotlib.org/stable/users/explain/quick_start.html#quick-start))
- Seaborn, a python library ([link](https://seaborn.pydata.org/))
- Plotly, a python library for interactive visualisations ([link](https://plotly.com/python/))
- ggplot2, an R visualisation library ([link](https://ggplot2.tidyverse.org/))

## Copyright

This repository has a [![License: CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc/4.0/) license

## How to use this repository

Inside this repository you are going to find a Jupyter Notebook (for python users) and RMarkDown file (for R users) that will allow learning how to perform sentiment analysis and a series of datasets (.txt files). The analysis files work exactly the same and are set to suit preferences for either python or R.
If you want more information on how to use RegEx (Regular Expression) via Python you can have a look to this [module](https://www.w3schools.com/python/python_regex.asp).

## How to use the Jupyter Notebooks (python) & R analyses files

### 1. Noteable

If you are part of the University of Edinburgh you can use [Noteable](https://noteable.edina.ac.uk/) the cloud-based computational notebook system which works on your browser from any device.

To get started:

#### Start Noteable (for Python users)
1.  Open the following link in a new tab:  [https://noteable.edina.ac.uk/login](https://noteable.edina.ac.uk/login)
2.  Login with your EASE credentials
3.  Under 'Standard Notebook' click 'Start'

#### Start Noteable (for R users)
1.  Open the following link in a new tab:  [https://noteable.edina.ac.uk/login](https://noteable.edina.ac.uk/login)
2.  Login with your EASE credentials
3.  Under 'RStudio' click 'start'
   
#### Upload the Notebook (and files) to Noteable
1.  From the Noteable home page, click on the 'Git'>'Clone a Repository' button at the top bar of the screen and enter the link of this repo [https://github.com/DCS-training/SentimentAnalysis.git](https://github.com/DCS-training/SentimentAnalysis.git)
2.  Now click on Clone
3.  You now have imported the full repo and you can see all the material within the folder names'SentimentAnalysis'
4.  Double-click on 'intro_sentiment_analysis_2025.ipynb' to open the Notebook for Python and 'intro_sentiment_analysis_2025.Rmd' if following the R version of this analysis.
5.  Follow the instruction on the Notebook

##### Noteable is the reccomended mode for University members since your EASE credentials provide easy access to the analysis and avoid further installation of any software or tools locally.

### 2. Installing Python via Anaconda

[Python][python] is great for general-purpose programming and is a popular language for scientific computing as well. Installing all of the packages required for this lessons individually can be a bit difficult, however, so we recommend the all-in-one installer [Anaconda][anaconda].

Regardless of how you choose to install it, please make sure you install Python version 3.x (e.g., Python 3.6 version). 

#### Windows - [Video tutorial][video-windows]

1. Open [anaconda.com/download][anaconda-dl] with your web browser.

2. Download the Python 3 installer for Windows.

3. Double-click the executable and install Python 3 using _MOST_ of the default settings. The only exception is to check the **Make Anaconda the default Python** option.

#### macOS - [Video tutorial][video-mac]

1. Open [anaconda.com/download][anaconda-dl] with your web browser.

2. Download the Python 3 installer for macOS.

3. Install Python 3 using all of the defaults for installation.

#### Starting Python
To start Jupyter Notebook Open the Anaconda Navigator and Launch Jupyter Notebook
#### Upload the Notebook
1. Download the notebook on your machine
2. Go to Upload
3. Navigate to where you have download your file
4. Select Upload again
5. Double click on the uploaded file 

[anaconda]: https://www.anaconda.com/distribution
[anaconda-dl]: https://www.anaconda.com/download/
[python]: https://python.org
[jupyter]: https://jupyter.org/index.html
[jupyter-install]: https://jupyter.org/install.html
[video-mac]: https://www.youtube.com/watch?v=TcSAln46u9U
[video-windows]: https://www.youtube.com/watch?v=xxQ0mzZ8UvA

### 3. Run the notebooks via GoogleColab

Open Google Colab: [https://colab.research.google.com](https://colab.research.google.com)
If you are not already logged you will be prompted to log-in via gmail
#### Upload the Notebook to Noteable
1. Go on the GitHub header and copy paste the link to the notebook you want to use and press enter

### 4. Using the Notebook
The Notebook contains paragraphs of explanatory text interspersed with grey cells containg code blocks. To run a code block and see the result:

1.  Place your cursor within the cell
2.  Click the 'Run' button on the top menu
4.  The results of running this code will appear below
5.  if the results don't appear immediately, check the icon in the browser tab. AN eggtimer icon indicates it is processing the code.
6.  It is best to follow the Notebook from top to bottom as some code blocks will depend on results from previous cells
7.  You can edit code blocks yourself and run them to see the results of your changes
### 5. Clearing the cells
To clear the results and run the code again you can use the 'Cell' menu on the top menu bar

1.  To clear the results of the current cell:  **Cell > Current Outputs > Clear**
2.  To clear the results of all cells:  **Cell > All Output > Clear**
