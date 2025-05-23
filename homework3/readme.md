To build the docker image for the .ipynb file titled ANDataEng300HW3.ipynb, run docker build -t homework3-pyspark. Then run <docker run -p 8888:8888 homework3-pyspark> and copy the link to the jupyter notebook. Each cell should be run in order. Note that the addab function is used in both Part 1 and Part 2. 

For Part 1. the expected output is the data frame with the first 5 doc d ids and each of their word (t) tf-idf pairs (so for each word, no duplicates, in a document, the associated tf-idf measure is given) 

For Part 2. the expected output is the SVM Objective loss (given a lambda of 1), the prediction value y-hat for each row (each value is either -1 or 1 with 64 entries as there are 64 rows), and the y-hat accuracy level. 

The Generative AI Disclosure is included at the end. 
