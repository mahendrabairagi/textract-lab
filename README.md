## Textract-lab

This lab will walk you though using AWS Textract in Sagemaker Notebook.

Amazon Textract is a service that automatically extracts text and data from scanned documents. Amazon Textract goes beyond simple optical character recognition (OCR) to also identify the contents of fields in forms and information stored in tables.

Output of Textract is a json. This lab shows to parse Textract Jsob

Lab Steps:

1. Prerequesite: Make sure SageMaker IAM role has full access to Textract

2. Open SageMaker Notebook

3. On Sagemaker Notebook, select new Terminal

4. This will open new linux terminal on SageMaker Notebook

5. In terminal change directory to "Sagemaker"
``` 
cd ~/Sagemaker 
```
6. Clone git
```
git clone https://github.com/mahendrabairagi/textract-lab.git
```

7. Go to SageMaker Notebook, you will see notebook "Textract_Sample.ipynb" and supporting python file "trp.py"

8. Open notebook and follow direction on the notebook

