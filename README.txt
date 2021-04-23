# comp6471-project-first phase

In this project "AI face mask detector" we implement bias detection and resolving steps and K-Fold cross validation step in phase2 of the project.
The following files are submitted:
	- read me file:  README.txt
	- python code:	K-Fold.ipynb
				This Jupyter notebook file contains implementation of K-Fold cross validation in phase 2.
			 	--> By executing all the cells of this notebook all the steps will be executed.
			bias_Train_AI_project_1.ipynb
				This Jupyter notebook file contains implementation of training phase of bias section in phase 2.
			 	--> By executing all the cells of this notebook all the steps will be executed.
			bias_Test_AI_project_1.ipynb
				This Jupyter notebook file contains implementation of testing phase of bias section in phase 2 on male test set and female test set.
			 	--> By executing all the cells of this notebook all the steps will be executed.

	- Exception of originality form: Expectations-of-Originality-Feb14-2012.pdf
	- trained model: bias_before_balancing_sm.pt
			 	This file includes our trained data and includes all its features and properties before balancing the dataset.
			 bias_after_balancing_sm.pt
			 	This file includes our trained data and includes all its features and properties after balancing the dataset.
			
	- project report: Report.pdf
			 	This file has the explanation of the different phases of the project
	- dataset: small-dataset
			small-scale dataset
		   balanced_small_dataset
			balanced small-scale dataset after resolving the bias
		   female_test_set
			test set of female images
		   male_test_set
			test set of male images
		   KFold_Dataset
			similar to small-dataset except that Train and Test folders are merged to make ready for K-Fold cross validation	  
		   KFold_BalancedDataset
			similar to balanced_small_dataset except that Train and Test folders are merged to make ready for K-Fold cross validation	  

Repository address: https://github.com/somayeghahari/comp6471-AI.git







Member Contribution:	1- Somayeh Ghahary: responsible for bias phase, data balancing and collaborating on the report.	2- Mehrnoosh Amjadi: responsible for K-Fold cross validation phase and collaborating on the report.	3- Bikash Jaiswal: responsible for bias phase, data balancing and collaborating on the report.	Note: all of us contribute to all the phases of the project.