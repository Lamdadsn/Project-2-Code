# Project-2-Code
The notebook was created in Google Colaboratory. It should be run there.

The original version of this code stored all models in a distinct folder each time the notebook was run.
That file versioning code was removed when this was posted to github to simpliofy the process of accessing the files.

The repository is public however so the model with the highest accuracy is accessible in 'saved_models/3/student_loans_smote.h5'.

Instructions to run the notebook:
1) Download the preferred model mentioned above to your local drive before running the notebook
2) Navigate to the notebook in the github repository and open it
3) Assuming guthub is being run from a browser, change the word 'github' in the URL to 'githubtocolab'
4) THe notebook will open in Google Colab
5) Check that there is a saved_models folder in the file navigator (if there is not then create one)
6) Upload the locally saved model (step 1) to the saved_models folder.
7) Run the notebook and if the best accuracy achieved is not better than 91.295% then edit cell 50 by commenting out the first file path and uncommenting the second one. then re-run all cells from 50 onwards.
