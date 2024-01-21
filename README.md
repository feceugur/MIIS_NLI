# MIIS_NLI
NLI-final-project 


In this .zip there are the notebooks and the already processed data in .jsons that we've used to generate the models, if these notebooks need to be executed the root path of the training folder has to be specified in the 2nd cell (first %cd)

The folders for generating the models are the following for each of the tasks:

	For task 1 
	User DA
	
	For task 2 (note that we also use a pre-trained sentence embedding for sequence similarity which does not need training)
	Spans_Training
	
	For task 3 there are 3 folders each with one model
	AM_TBRET		(Info to be retrieved
	AM_DA			(Agent dialog act)	
	AM_TBREQ		(To be requested)

We also provide two notebooks for testing:
	
	Demonstration_notebook: Contains the prediction for the dialog that was shown in the presentation
	
	Evaluation_notebook: Evaluates the notebook for every dialog in the test dataset
