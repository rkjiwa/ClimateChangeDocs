#readme.md

This repo includes the work done for UofT 3666 - Applied Natural Lanaguage Processing Final Project.

For this project, our objective was to take a collection of climate change related pdfs and a csv of possible action items and try to: extract the information from the pdfs, perform LDA topic modelling and, try to parse and classify actions that consumers could do.

File List:
ClimateChangeDocs_pages - pdf pages parsed using pdfminer.
ClimateChangeDocs_pdfminer - pdf documents parsed using pdfminer.
ClimateChangeDocs_pickled - pickled objects of the pdf documents parsed using pdfminer.
Duplicate Of Master - The files that were provided.
Exploratory - Jupyter Notebooks used to explore these topics.
NewDocs - a collection of climate change related pdfs used to expand the dataset.
tikatext - pdf documents parsed using Tika. The documents are from Not_Yet_Examined in DuplicateOfMaster
tikatextcombined - pdf documents parsed using Tika. The documents are from Not_Yet_Examined in DuplicateOfMaster and from NewDocs
Climate Change Docs - Actions.pkl - pickled actions items
Climate Change Docs - Non-Actions.pkl - pickled non action items
Comparison_PDF_Extraction_Tools.ipynb - Jupyter Notebook looking at code and output of all three tested pdf extraction tools (pdfminer, tika, pypdf2)
Identifying_Actions.ipynb - Jupyter Notebook looking at parsing and classifying actions
LDA_using_Gensim_tikatext.ipynb - Jupyter Notebook of LDA using Gensim with text files in tikatext
LDA_using_Gensim_tikatextcombined.ipynb - Jupyter Notebook of LDA using Gensim with text files in tikatextcombined
PDF_to_Text_pdfminer.ipynb - pdf extraction using pdfminer
PDFs_To_Text_PyPDF2.ipynb - pdf extraction using PyPDF2
PDFs_to_Text_Tika.ipynb - pdf extraction using Tika
gensim_climate_change_lda_model.html - pyLDAvis of Gensim LDA model
stopwords.txt - list of stopwords used in LDA
