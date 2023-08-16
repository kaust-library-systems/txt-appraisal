# txt-appraisal

 Extract text from scanned documents using [Azure AI Vision](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/) and [Azure AI Document Intelligence](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/?view=doc-intel-3.1.0)

## Requirements

Installing [Read API](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/how-to/call-read-api):

```
PS C:\Users\garcm0b\Work\txt-appraisal> python -m venv venv --prompt txt-appraisal
PS C:\Users\garcm0b\Work\txt-appraisal> . .\venv\Scripts\activate
(txt-appraisal) PS C:\Users\garcm0b\Work\txt-appraisal> python -m pip install azure-ai-vision
(txt-appraisal) PS C:\Users\garcm0b\Work\txt-appraisal> pip install azure-ai-formrecognizer==3.3.0
(txt-appraisal) PS C:\Users\garcm0b\Work\txt-appraisal> python -m pip freeze > requirements.txt
```

## Resources

1. Resource group: Kaust_Library
1. Storage account: kaustlibrary
1. Container: digitpres
1. Azure AI services multi-service account: cs-library-archive

## Environment Variables

Setting the environment variables `VISION_KEY` and `VISION_ENDPOINT` in an external file `.env`.