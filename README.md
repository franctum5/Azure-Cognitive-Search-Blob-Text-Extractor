# Azure Cognitive Search Blob Text Extractor

This script read all the json files created as blob projections from Azure Cognitive Search indexer and extract just the text from the merged_content field (or translated_text if you're running translation as part of your skillset).
The resulting .txt are uploaded in another container in the same Storage Account.

You can access the source code or just download the pre-packaged exe for Windows. Just run the script and follow the instructions on screen to provide the necessary input.
