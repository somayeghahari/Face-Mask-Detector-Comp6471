# comp6471-project-first phase

In this project "AI face mask detector" we implement a CNN to detect and categorize dataset of images into non-human and with-mask and without-mask human.
The following files are submitted:
	- read me file:  README.txt
	- python code:	 AI_project_1.ipynb
			 This Jupyter notebook file contains implementation of our project that includes splitting data, data preprocessing,
			 designing the model, training, testing and evaluation. 
			 --> By executing all the cells of this notebook all the steps will be executed.
	- Exception of originality form: Expectations-of-Originality-Feb14-2012.pdf
	- trained model: SavedModel.pt
			 This file includes our trained data and includes all its features and properties.
			 To load this file, you can apply the following codes:
			
				new_model = myModel(2)
				new_model = new_model.to(device)


				new_model.load_state_dict(torch.load(PATH))
				new_model.eval()


				print("\nTest Phase")
				losses_model_new, accs_model_new, predicted_labels_test_new, accs_plot_model_new, losses_plot_model_new, test_labels_new  = test(dataloaders['Test'], new_model, optimizer)
	- project report: Report.pdf
			 This file has the explanation of the different phases of the project
	- dataset: 	  
			 The main dataset is more than 250MB so we upload it in the repository. This folder contains a sample of images in the main dataset.
			 This folder contains train and test subfolders with all their images. It should be located in the same folder as source code.

Repository address: https://github.com/somayeghahari/comp6471-AI.git





Member Contribution:	1- Somayeh Ghahary: responsible for designing the CNN architecture and collaborating on the report.	2- Mehrnoosh Amjadi: responsible for the evaluation phase, discuss the results, and collaborating on the report.	3- Bikash Jaiswal: responsible for data part and collecting dataset and collaborating on the report.	Note: all of us contribute to all the phases of the project.