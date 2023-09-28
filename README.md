# ChatDoc

Document Question Answering (QA) system powered by ChatGPT and Llama.

## Overview
This is a fun Python project that allows you to chat with a chatbot about the PDF you uploaded. 

![Screenshot from 2023-09-28 12-33-18.png](..%2F..%2FPictures%2FScreenshots%2FScreenshot%20from%202023-09-28%2012-33-18.png)
## Instructions

- Install the requirements

```bash
pip install -r requirements.txt
```

- Get a GPT API key from [OpenAI](https://platform.openai.com/account/api-keys) if you don't have one already.

- Paste your API key in a file called `.env` in the root directory of the project.

```bash
OPENAI_API_KEY=<your key here>
```

- Select a file from the menu or replace the default file `file.pdf` with the PDF you want to use.

- Run the script.

```bash
python3 chatdoc.py
```

- Ask any questions about the content of the PDF.
- Enjoy!

