<h1 align="center"> Mental Health Awareness </h1>


Mental health issues are often not discussed due to the stigma behind them and this results in many people hesitating to seek help for their mental illnesses. Although the Canadian Government has funded several mental health resources for the general public, very few people utilize these platforms. The main reason for this is the lack of awareness regarding mental health concerns and the resources available in Canada. For my research on mental health awareness, I have developed a descriptive mental health Chatbot application called 'Mental Health Awareness.' This Chatbot incorporates Natural Language Processing and Deep Learning Techniques to provide users with a more interactive and friendly conversation when discussing mental health issues
---

## Repository Details

'Mental Health Awareness' is available in .ipynb for Jupyter Notebook and .py Pycharm IDE (Works on both Community and Professional Pycharm IDE)

For Jupter Notebook consider the following files

```
- trainingmodel.ipynb      
- mentalhealthbot.ipynb
- mentalhealth.json                
- vocabulary.pkl   
- categories.pkl             
- mentalhealthbot_model.h5
```

For Pycharm IDE consider the following files

```
- trainingmodel.py
- mentalhealthbot.py
- mentalhealth.json
- vocabulary.pkl
- categories.pkl
- mentalhealthbot_model.h5
```

---

## Breakdown of the Repository Files:


- trainingmodel.ipynb / trainingmodel.py - Consists of the code required for training the model.
- mentalhealthbot.ipynb / mentalhealthbot.py - Consists of the code required for designing and running the model's GUI.
- mentalhealth.json - Dataset consisting of mental health data and resources needed for training the model.
- vocabulary.pkl and categories.pkl - Stores the list of vocabulary and categories for the model.
- mentalhealthbot_model.h5 - The 'Mental Health Awareness' model created by trainingmodel and used in mentalhealthbot.


---

## Installation

The following packages are required for running the Chatbot:

1. [nltk](https://pypi.org/project/nltk/)
   - nltk.download('punkt')
   - nltk.download('wordnet')
2.  [numpy](https://pypi.org/project/numpy/)
3.  [tensorflow](https://pypi.org/project/tensorflow/)

---

## Usage

First execute trainingmodel.ipynb / trainingmodel.py code to train the model and then execute mentalhealthbot.ipynb / mentalhealthbot.py code to run the application.

Note: While running the model you may encounter this error:

```
ImportError: Could not find the DLL(s) 'msvcp140_1.dll'. TensorFlow requires that these DLLs be installed in a directory that is named in your %PATH% environment variable. You may install these DLLs by downloading "Microsoft C++ Redistributable for Visual Studio 2015, 2017 and 2019" for your platform from this URL: https://support.microsoft.com/help/2977003/the-latest-supported-visual-c-downloads
```

If so please download the required Visual Studio from [Microsoft Support](https://support.microsoft.com/en-us/topic/the-latest-supported-visual-c-downloads-2647da03-1eea-4433-9aff-95f26a218cc0)


