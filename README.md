# Simple ChatBot for chatGPT using spaCy

## Project Description :
 ### It is a simple chatbot implementation that provides information on chatGPT collected from the source of wikipedia link. It is implemented using spaCy library in Python and locally hosted using streamlit application.

## Demo :

![](https://github.com/Kaish04/Simple-ChatBot-for-chatGPT-using-spaCy/blob/master/app_demo_gif.gif)

## Implementation :
### Step 1:
Clone the repository to your system using the following command.
~~~ console 
git clone https://github.com/Kaish04/Simple-ChatBot-for-chatGPT-using-spaCy.git
~~~

### Step 2: 

Create a conda environment and activate the environment.Enter the following command for downloading the dependencies.
~~~ console 
pip install -r requirments.txt
~~~
### Step 3 :
After installation of en_core_web_lg in your system, it will be downloaded in \Lib\site-packages of your virtual environment. Copy the path of the folder 'en_core_web_lg-3.5.0' and paste it at line 51 of main.py
(e.g. nlp = spacy.load(r'C:\Users\AISHWARYA KASABE\anaconda3\envs\chatbot_env\Lib\site-packages\en_core_web_lg\en_core_web_lg-3.5.0')

### Step 4: 
After successful installation, run the main.py file on conda terminal using following command.
~~~ console 
streamlit run main.py
~~~
### Step 5:
 The command in step 3 will direct you to streamlit application via a local host (http://localhost:8501/). On this webpage, you can have a live chat with the ChatBot.
