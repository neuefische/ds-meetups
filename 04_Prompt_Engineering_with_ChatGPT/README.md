# Prompt Engineering

Get an OpenAI API Key from [here](https://platform.openai.com/account/api-keys)
> <span style="color:red"> **NOTE:**</span> Using OpenAI's API Key incur some minor charges. You will have to add your credit card details to get the API Key.

Add the api key to a `.env` file in the root directory of the project.

The `.env` file should look something like this
```
OPENAI_API_KEY="your-api-key-here"
```
OR, in root directory of the project, run the following command in terminal
```
echo "OPENAI_API_KEY=your-api-key-here" >> .env
```



## Prompting using OpenAI and LangChain


---
## Environment
`Python v3.11.3`

> NOTE: If not using `pyenv` then remove the `pyenv local 3.11.3` line from the commands below.

### Setup

```python
pyenv local 3.11.3
python -m venv .venv
pip install -u pip
pip install -r requirements.txt
```
