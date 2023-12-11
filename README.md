Within the cleaning folder are the original csv files and our code for cleaning the data. The code reads in the data from the github so it should run without setup needed. If this fails, then downloading the files directly and changing the pd.read_csv lines accordingly should work. Additionally, the final line in this code that saved the csv has been commented out but can easily be commented back in if needed.

Within the model folder there is a jupiter notebook that has the code for actually creating and testing our model. Within this folder there is also a refined csv file that has mostly been pre-processed already and is ready to go. The jupter notebook should read in the data directly from the github page and so it should just run without any problems. If problems do arise, then you can manually download the csv from github and change the pd.read_csv line to read in the data directly.
