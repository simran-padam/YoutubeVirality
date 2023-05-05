Code done by Simran, Spardha, Avery, Milton, Shriniket

Data Used: USVideos.csv, US_category_id.json, updated_youtube_data.csv

Youtube_EDA.ipynb (Spardha) converts USVideos.csv to updated_youtube_data.csv which is
then used by all of the other Rmd and ipynb files. This script removes
duplicates. This file also integrates US_category_id.json into the cleaned dataset after removing its duplicates. It also contains the EDA plots shown in the report.

Final_GAM.Rmd (Avery and Milton) runs the GAM model as well as extracts features for it as highlighted
in the paper.

Linear_Models_and_Trees.Rmd (Shriniket) runs the linear models and random forest models on the 
updated_youtube_data.csv data. The plots in the report is shown in the report.

nlp-youtube-final.ipynb (Simran) contains all of the NLP work including formatting and
tokenizing the title data, creating the word clouds, susbsetting the response into 
5 categories to determine virality. The file also including the training of SVC (one vs rest)
classifiers as well as Boosting and Random Forest.


