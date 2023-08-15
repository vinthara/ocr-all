Small web app built in streamlit where I can add images or pdf files and retrieve the text, the output is a pdf.

## Set up environment

```bash
git clone git@github.com:vinthara/ocr-all.git
```

Create an environment :

```bash
python3 -m venv venv
```

Activate the `venv` : 

```bash
source venv/bin/activate
```

Install the dependencies : 

```bash
pip3 install -r requirements.txt
```

You also need to install [tesseract](https://github.com/tesseract-ocr/tesseract) :

On `ubuntu`

```bash
sudo apt install tesseract-ocr
```

Language data is default to english (`eng`) add french (`fra`) :

```bash
sudo apt install tesseract-ocr-fra
```

You are good to go!