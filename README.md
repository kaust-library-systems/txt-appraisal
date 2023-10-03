# txt-appraisal

Using [Azure Document Intelligence](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/overview?view=doc-intel-3.1.0) to process docuemnst.
 
## Requirements

Installing the [requirements for Python](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/quickstarts/get-started-sdks-rest-api?view=doc-intel-3.1.0&viewFallbackFrom=form-recog-3.0.0&preserve-view=true&pivots=programming-language-python):

```
PS C:\Users\garcm0b\Work\txt-appraisal> python -m venv venv --prompt txt-appraisal
PS C:\Users\garcm0b\Work\txt-appraisal> . .\venv\Scripts\activate
pip install azure-ai-formrecognizer==3.3.0
(txt-appraisal) PS C:\Users\garcm0b\Work\txt-appraisal> python -m pip freeze > requirements.txt
```

To read the `.env` file

```
(txt-appraisal) PS C:\Users\mgarcia\Work\txt-appraisal> pip install python-dotenv
```

## Resources

1. Resource group: Kaust_Library
1. Storage account: kaustlibrary
1. Container: digitpres
1. Azure AI services multi-service account: cs-library-archive

## Environment Variables

Setting the environment variables `KEY` and `ENDPOINT` in an external file `.env`.


## Running the Script

```
(txt-appraisal) PS C:\Users\garcm0b\Work\txt-appraisal> python .\doc_intel_quickstart.py read https://kaustlibrary.blob.core.windows.net/appraisal/01-00-00-002-0001_KAUST_BYLAWS_10-25-06.pdf
```