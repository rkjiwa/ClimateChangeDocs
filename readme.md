# readme.md

This repo includes the work done for UofT 3666 - Applied Natural Lanaguage Processing Final Project.

For this project, our objective was to take a collection of climate change related pdfs and a csv of possible action items and try to: extract the information from the pdfs, perform LDA topic modelling and, try to parse and classify actions that consumers could do.

---
**File List:**
* ClimateChangeDocs_pages: pdf pages parsed using pdfminer.
* ClimateChangeDocs_pdfminer: pdf documents parsed using pdfminer.
* ClimateChangeDocs_pickled: pickled objects of the pdf documents parsed using pdfminer.
* Duplicate Of Master: The files that were provided.
* Exploratory: Jupyter Notebooks used to explore these topics.
* FinalLogisticRegressionModels: folder contains the models for Identifying Actions
* NewDocs: a collection of climate change related pdfs used to expand the dataset.
* tika_alldocs: folder contains all pdf documents parsed into text files using Tika.
* tikatext: pdf documents parsed using Tika. The documents are from Not_Yet_Examined in DuplicateOfMaster
* tikatextcombined: pdf documents parsed using Tika. The documents are from Not_Yet_Examined in DuplicateOfMaster and from NewDocs
* Climate Change Docs - Actions.pkl: pickled parsed actions items
* Climate Change Docs - Non-Actions.pkl: pickled parsed non action items
* Comparison_PDF_Extraction_Tools.ipynb: Jupyter Notebook looking at code and output of all three tested pdf extraction tools (pdfminer, tika, pypdf2)
* Identifying_Actions.ipynb: Jupyter Notebook looking at parsing and classifying actions
* LDA_using_Gensim_tikatext_alldocs_final.ipynb: Jupyter Notebook of LDA using Gensim with text files in tika_alldocs.
* non-actions_raw.txt, non_actions_edited.txt: the files to find examples of non-actions.
* PDF_to_Text_pdfminer.ipynb: pdf extraction using pdfminer
* PDFs_To_Text_PyPDF2.ipynb: pdf extraction using PyPDF2
* PDFs_to_Text_Tika.ipynb: pdf extraction using Tika
* gensim_climate_change_lda_model_alldocs.html: pyLDAvis of Gensim LDA model. An interactive version of this is hosted [here](http://rahimjiwa.com/gensim_climate_change_lda_model_tika_alldocs.html) 
* stopwords.txt: list of stopwords used in LDA
