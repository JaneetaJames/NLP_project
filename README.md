# NLP_project
This project aims to find out the misspelled words in Malayalam and Hindi text files.The code can be run in Jupyter Notebook.


Installations

	1.Install indicnlp
		pip install indicnlp
	2.Install indic-nlp-library
		pip install indic-nlp-library
	3.Install inltk library
		pip install inltk
	4.Install textblob
		pip install textblob
		
		
Three code files are in master branch.

	1.malayalam_hindi_spellchecker.ipynb 
		This file is to check both Malayalam and Hindi text data
	2.Malayalam_SpellChecker
		This file is to check Malayalam text data
	3.Hindi_SpellChecker_Pgm
		This file is to check Hindi text data
		
		
Sample input Files are in master branch:

	1.inputdata.txt
		Malayalam text data input file.
		
	2.hndinput.txt
		Hindi text data input file.
		
		
Sample output files are in dataset folder:

	1.hindioutput/out.csv
		Sample Hindi output file out.csv, is in hindioutput folder
		
	2.mloutput/out.csv
		Sample Malayalam output file out.csv, is in mloutput folder
		
		
Other files in dataset folder:

	1.train folder
		Includes malayalam text files,used to get the close matches for an invalid Malayalam word
	2.hinditrain folder
		Includes Hindi dataset,used to get the close matches for an invalid Hindi word
	3.hnstopwords.txt
		Stopwords in Hindi
	4.hnvocabe.csv
		Hindi vocabulary dataset,to check the validity of words Hindi in input text
	5.mlvocabe.csv
		Malayalam vocabulary dataset,to check the validity of Malayalam words in input text
		
		
	
