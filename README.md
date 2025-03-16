chatbot frontend 
*%%capture --no-stderr
%pip install --quiet -U langchain_google_genai langchain_core langgraph
from langchain_google_genai import ChatGoogleGenerativeAI
llm = ChatGoogleGenerativeAI(model="gemini-1.5-flash")
