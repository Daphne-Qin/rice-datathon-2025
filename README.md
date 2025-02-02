# Rice Datathon 2025
**Team Members**: Edi Berisha, Daphne Qin, João Vana, Justin Wang \
**Presentation**: [link](https://docs.google.com/presentation/d/1Tugsn-UmvUlyUtAzSEODxMXcXqQc4gXau08ZBWmgwtM/edit?usp=sharing) \
**Video**: TBD

This is our submission for the Neurotech@Rice track for Rice Datathon 2025. Here, we analyze an EEG (electroencephalogram) dataset from people with psychiatric disorders (Park et al., 2021) using the Random Forest classification model to predict diagnoses of patients who have had an EEG.

## Running Our Code
**To run our code, simply run `Datathon.ipynb` in full.** This program assumes you already have Numpy, MatPlotLib, Seaborn, Pandas, and scikit-learn installed in your environment, but will install imblearn for you.

On the same directory level as `Datathon.ipynb`, store the training data in file `Train_and_Validate_EEG.csv` and the testing data in file `Test_Set_EEG.csv`. The code will produce output file `submission.csv`.

## Citations
Park, S. M. (2021, August 16). EEG machine learning. Retrieved from [osf.io/8bsvr](https://osf.io/8bsvr/)
