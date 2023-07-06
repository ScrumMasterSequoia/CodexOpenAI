# CodexOpenAI
Integrates with the OpenAI API, sending queries and receiving AI responses

cd into server and run npm run start cd into client and run npm run dev

if your API Key gets exposed in any way you will receive error alertbox upon form 
submit instead of chatbot response, then you will get the bot's response as 
'something went wrong' To fix this, you must go to https://platform.openai.com/account/api-keys 
and generate a new api key, then restart your client and server to use

currently this version of the project is broken for the above reason, as .gitignore failed to stop 
the .env file, which contains the api key, from being brought into the github. 
