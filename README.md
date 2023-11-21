# ShopBot Pro - Your Intelligent Shopping Assistant
ShopBot Pro is an advanced smart chatbot designed to enhance your online shopping experience. Developed as an LLM-based QA (Question-Answering) system, ShopBot Pro is here to make your shopping journey smoother and more informed.

 ![Alt Text](https://github.com/TAHMID37/ShopBot-Pro/blob/main/ShopBot%20Pro.png)

 ## Built using
 <ul>
        <li><strong>Langchain</li>
        <li><strong>Google PaLM</li>
        <li><strong>InstructorEmbedding</li>
  </ul>

##### Setting Up Google API Key

1. Create a file named `.env` in the root directory of your project

2. Open the `.env` file.
 Replace 'YOUR_GOOGLE_API_KEY' with your actual Google API Key obtained from the Google Developer Console.
 GOOGLE_API_KEY='YOUR_GOOGLE_API_KEY'

3. Save the `.env` file.

##### Setup Development Environment
```bash
pip install pipenv
pipenv install
pipenv shell
```
You might need to use `python3 -m` before `pipenv` in some cases. 

### Run Code
```bash
streamlit run main.py
```

### Installing modules
Before installing modules, use `exit` command to exit the shell, then run the following:
```
pipenv install <module>
```
then use `pipenv shell` to activate the shell back again. This will add the required modules to the Pipfile as well.
