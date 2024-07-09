# grading-chatbot 📖🤖
Hello world! This is a grading chatbot prototype using streamlit and Anthropic. This is still in the works but you can launch this on your own. This chatbot takes in a case-study and has a few functional buttons that can automate prompts for you to create questions based on the case-study. You can also feed it an answer sheet and answers to score. 



# how to launch
### 1. installing stuff

open command prompt and run these lines of code. may take a few seconds or a minute:

```
  pip install streamlit
```
```
  pip install requests
```
```
  pip install anthropic
```
```
  pip install pdfreader
```

### 2. replace API keys

go to grader_streamlit.py and put in your own API key. Also make sure you have credit on your account to run this bot! Tokens == $$

### 3. run it!

in terminal or your powershell, make sure you are in the right directory. then run this line of code:

```
  streamlit run grader_streamlit.py
```

### done!
