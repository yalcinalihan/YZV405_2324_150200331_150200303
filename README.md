# Diacritization
Diacritics are some marks (e.g. accents, dots, curves) added to the characters and have a wide usage in many languages. The absence of these marks in the internet is very common and poses a big problem in the automatic processing of these data by NLP tools. Converting an ASCII text to its proper form (with accents and special characters) is called “diacritization”, also referred as “unicodification” [1] or “deasciification” [2]. A Turkish example is the word “dondu” (it is frozen) which may be the ASCII form of both “dondu” (it is frozen) or “döndü” (it returned) where the ambiguity should be resolved according to the context [3].

# How to Use
*Step1 - Downloading the files:*
\
To run this project successfully, you need 'model.ipynb' which contains the main code where training and evaluation are done, and the data folder which contains training and testing data.

*Step2 - Installing libraries:*
\
We programmed and ran this model with libraries within the 'requirement.txt' file with their written versions. Versions may change due time, and this should be taken account.

*Step3 - Running the code:*
\
The first cell of the notebook is about connecting to Google Drive because we trained our model with Google Colab. If you are going to use other environments such as local, please delete or modify that part depending on your choice. And, if you are going to use the Google Colab as we did, please do not forget to set your folder/file path correctly.

# Result
Here is an example about what is our input, what should the output be, and what is the output of our model:

Input &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :  gul  zirve oncesi sunlari soyledi :
\
Correct&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :  gül  zirve öncesi şunları söyledi :
\
Predicted&nbsp; :  gül  zirve öncesi şunları söyledi :
