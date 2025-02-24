## GraphRAG Connected to Zotero
This project builds a GraphRAG based on a collection of papers in a Zotero.

### Prerequisites:
#### Zotero
1. Create Zotero account at https://www.zotero.org/user/register
2. Acquire ZOTERO_API_KEY
3. Create a collection in Zotero, and add PDF articles to collection.
4. Sync local Zotero and library on Zotero account.

### OpenAI
1. Crteate an OpenAI account at https://platform.openai.com/
2. Create an OpenAI API Key.
3. 
### OpenRouter
1. Create an OpenRouter account at https://openrouter.ai/
2. Acquire an ThePipe API Key.

### Google Colab Secrets
Use the info acquired above, add key/value pairs in Secrets: ZOTERO_USER_ID, ZOTERO_API_KEY, THEPIPE_API_KEY, LLM_SERVER_API_KEY (OpenRouter API Key), LLM_SERVER_BASE_URL (`https://openrouter.ai/api/v1`).

Then run the cells in the notebook. 
\n
To ask more questions, duplicate cell 15, compose your question and use it to replace the value for "query", then run the cell.


   
