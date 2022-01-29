
# Implementation of a Contextual Chatbot in PyTorch.

- This project is one kind of chatbot which serves to new users of Technical Campus of Deggendorf Cham.

- We have built this application on python, deep learning for backend and flask framework for frontend usability.


## Installation

**Create an environment**

Whatever you prefer (e.g. ```conda``` or ```venv```)

```bash
  $ cd chatbot
  $ python3 -m venv venv
```


**Activate It**

Mac/Linux:

```bash
. venv/bin/activate
```

Windows:
```bash
venv\Scripts\activate
```

**Installing the required libraries for the project**

After activating an environment you have to install packages from the **requirements.txt** file. 

```
pip install -r requirements.txt
```

If you facing any error during the first run, you also need to download NLTK package.  

**Then you have to install a NLTK package as shown below**

In the command prompt or terminal you have to activate your python interpreter and type the below commands:

```
$ python
>>> import nltk 
>>> nltk.download()
```

## **Usage**

If you want to chat with chatbot in terminal then you have to run a **chat.py** file.
```
python chat.py
```
In addition also you can deploy this model on webpage using flask library for that you have to run **app.py** file.
```
python app.py
```

## **Customization**
If you want to customize a model.
Have a look at intents.json. You can customize it according to your own use case. Just define a new ```tag```, possible ```patterns```, and possible ```responses``` for the chat bot. You have to re-run the training whenever this file is modified. 
