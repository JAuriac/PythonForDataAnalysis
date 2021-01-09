# PythonForDataAnalysis
## Task to perform :

The task we had to perform here was mainly about the three following points :\
-Finding which sklearn model was the most accurate for our problematic, on our dataset\
-Which features were to correlate\
-How could we make a light API for a given request

## Conclusions :

As a result of our analysis, in relation to our three points, the findings that we applied are the following :\
-The Random Forest Classifier model is both very accurate and quick, it is chosen for the API\
-Only a few features were to correlate (as seen on the heatmap below), we decided to drop two features which had too low scores in relation to our classification\
-Flask was chosen in order to make a lightweight API that can easilybe deployed locally.

![Alt text](heatmap.PNG?raw=true "Heatmap")

## API :

To use the API, create a pickle of your chosen model, then run the app.ipynb file, and while keeping it running, run the request.ipynb file with the chosen test.
