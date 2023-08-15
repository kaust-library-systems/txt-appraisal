# txt-appraisal

 Extract text from scanned documents using [Azure AI Vision](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/)

## Requirements

Installing [Read API](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/how-to/call-read-api):

```
PS C:\Users\garcm0b\Work\txt-appraisal> python -m venv venv --prompt txt-appraisal
PS C:\Users\garcm0b\Work\txt-appraisal> . .\venv\Scripts\activate
PS C:\Users\garcm0b\Work\txt-appraisal> python -m pip install azure-ai-vision
PS C:\Users\garcm0b\Work\txt-appraisal> python -m pip freeze
azure-ai-vision==0.13.0b1
(txt-appraisal) PS C:\Users\garcm0b\Work\txt-appraisal> python -m pip freeze > requirements.txt
```

## Resources

1. Resource group: Kaust_Library
1. Storage account: kaustlibrary
1. Container: digitpres

## Environment Variables

Setting the environment variables `VISION_KEY` and `VISION_ENDPOINT` in an external file `.env`.