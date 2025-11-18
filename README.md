# azure-nlp-demo

## To run locally 

run the below command 

```code
python -m venv textanalyze
./textanalyze/bin/Activate.ps1
pip install -r requirements.txt azure-ai-textanalytics==5.3.0
```

add the below values in .env file

```code
AI_SERVICE_ENDPOINT=your_azure_language_services_endpoint
AI_SERVICE_KEY=your_azure_language_services_API_Key
```
---

## Summary 

`evaluate sentiment`: Sentiment analysis is a commonly used technique to classify text as positive or negative (or possible neutral or mixed). It's commonly used to analyze social media posts, product reviews, and other items where the sentiment of the text may provide useful insights.

`identify key phrases`: It can be useful to identify key phrases in a body of text to help determine the main topics that it discusses.

`extract entities`: Often, documents or other bodies of text mention people, places, time periods, or other entities. The text Analytics API can detect multiple categories (and subcategories) of entity in your text.

`extract linked entities`: In addition to categorized entities, the Text Analytics API can detect entities for which there are known links to data sources, such as Wikipedia.
