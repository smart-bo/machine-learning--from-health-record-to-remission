# Machine learning study   from health record to remission
 Impact of Hospital Health Record on the Remission of Diabetes Inpatients
 
README 
 -------------- 
Goal of this project：
According to the data of the hospital, try to identify a specific group of inpatients whose health
improves. Original author found that HbA1c determination may improve patient outcomes and
lower cost of inpatient care. We want to assess the importance of other factors (out of a list of 50
features) and compare the predictive performance of algorithms such as Decision Tree, Neural
Networks and SVM.

Our project relies mainly on scikit-learn, Pandas, matplotlib, NumPy, HyperOpt, SciPy and seaborn. 
The code contains the following files:

* ./data/diabetic_data_initial.csv    <-- rawdata 
* ./data/id_mapping.csv               <-- raw id mapping 
* ./results/*.html                    <-- output results of several runs 
* ./preprocess.ipynb                  <-- notebook to preprocess data 
* ./train_rf.ipynb                    <-- notebook to train random forest 
* ./train_mlp.ipynb                   <-- notebook to train neural network
* ./train_svm.ipynb                   <-- notebook to train SVM 

* The code contained in the jupyter notebook preprocess.ipynb should be run first.

*environment: 
	scipy
	seaborn
	hyperopt
	hpsklearn
* GPU is not required. 
* Training takes 0.5~12 hours. 
* The report notebook saves files to the "data" directory.

The diabetic_data_initial data was downloaded from https://www.hindawi.com/journals/bmri/2014/781670/#supplementary-materials
For preprocessing and training we relied heavily on the official documentation of Pandas and scikit-learn. 
