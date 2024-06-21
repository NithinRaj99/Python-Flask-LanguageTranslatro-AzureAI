# Python-Flask-LanguageTranslatro-AzureAI
A Simple Python and Flask based language Translator using Azure AI Translator


To Start using this the following steps are needed to be done first:

# Install Visual Studio Code (if not already installed)

# Install Python (if not already installed)
  Must have Python 3.6 or above version
  python --version   # code to check python vresion in terminal
  Create a directory for your code
  Create a virtual environment 
  Create a Python virtual environment
  -Windows, macOS or Linux
     Create the environment
      python -m venv venv
  -Windows
     Activate the environment
      ./venv/scripts/activate
  -macOS or Linux
     Activate the environment
       source ./venv/bin/activate

# Install Flask and other libraries
   Run the requirements.txt to install Flask and other libraries
   -code to run requirements.txt
     pip install -r requirements.txt

# Create Translator service
  Go to Azure portal : https://portal.azure.com/
  
  create an account then create a translator resource
  Fill in the tabs and click create
  
  ![create-translator-form](https://github.com/NithinRaj99/Python-Flask-LanguageTranslatro-AzureAI/assets/105411249/bf53484a-162d-43cb-8744-95d82b930140)
  
  Now go to resource and selecte translator and get the API keys
  
  ![translator-keys](https://github.com/NithinRaj99/Python-Flask-LanguageTranslatro-AzureAI/assets/105411249/3c9ccf93-d15d-40d1-a9ac-fdf7cf60c87e)

# In the project folder create .env file to store the key
  in the .env file add these
  #values inside .env file replace the KEY, ENDPOINT and LOCATION with your API keys
  KEY=your_key
  ENDPOINT=your_endpoint
  LOCATION=your_location
  
  


