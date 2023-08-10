# CodexOpenAI
Integrates with the OpenAI API, sending queries and receiving AI responses

cd into server and run npm run start cd into client and run npm run dev

if your API Key gets exposed in any way you will receive error alertbox upon form 
submit instead of chatbot response, then you will get the bot's response as 
'something went wrong' To fix this, you must go to https://platform.openai.com/account/api-keys 
and generate a new api key, then restart your client and server to use

currently this version of the project is broken for the above reason, as .gitignore failed to stop 
the .env file, which contains the api key, from being brought into the github. 

to access a functional version of this program, go to the CodexLocal repo and work from there. 

source: https://www.youtube.com/watch?v=2FeymQoKvrk&t=360s
source video name: Build and Deploy Your Own ChatGPT AI App in JavaScript | OpenAI, Machine Learning

Domain through Vercel https://vercel.com/

server through Render https://render.com/