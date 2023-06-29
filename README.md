# Sentiment Analysis Model to classify Amazon Alexa Reviews into Positive & Negative
An end-to-end toolkit on building a sentiment prediction model with a Jupyer notebook and deploying model pickle on a local machine using Flask. Our use case here is to review the classification of Amazon Alexa customer feedback into positive and negative. 
The dataset source is [here](https://www.kaggle.com/sid321axn/amazon-alexa-reviews).


## Steps to run 

* Open GIT CMD >> navigate to working directory >> Clone this Github Repo

      git clone https://github.com/skillcate/sentiment_analysis_with_sklearn_pipeline.git  
* Open Windows Powershell >> Navigate to new working directory (cloned repo folder)
* Create a virtual environment
  * install virtual environment
 
        pip install virtualenv
        
  * create virtual environment by the name ENV
        
        virtualenv ENV
        
  * activate ENV

        .\ENV\Scripts\activate
        
* Install project dependencies

      pip install -r .\requirements.txt
      
* Run the project

      python app.py
      
* Look for the local host address on the Powershell screen >> Type it on your Web Browser >> Project shall load
* Try out your Amazon Alexa test reviews and look for results
* To close >> Go back to Powershell & type `ctrl+c` >> Deactivate Virtual Environment ENV

      deactivate

