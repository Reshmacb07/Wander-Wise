# ✈️ WanderWise  

An AI-powered travel agent built using IBM Watsonx and Amadeus API. It understands natural language queries, finds real-time flights, recommends destinations, builds itineraries, and offers weather updates — all through an intelligent conversational interface.


<p align="center">
<br>
<img src="https://github.com/user-attachments/assets/76593293-c34f-49ed-b5dd-a12f4b563541" width="400" height="500" style="border-radius:50px"/>
</br>
</p>

# 📝 Problem Statement

Travel planning can be overwhelming, especially when users must search across multiple platforms for flights, hotels, activities, and real-time updates. Most solutions require technical input like airport codes or lack personalized guidance. There's a need for an intelligent, conversational assistant that simplifies travel planning using natural language.


# 💡 Proposed Solution

 **WanderWise** leverages AI and NLP to transform user-friendly queries into actionable travel plans. It automates flight search, destination discovery, itinerary creation, and weather updates — eliminating the complexity of manual trip planning through a single intelligent assistant.


# 🛠️ Technologies Used

✔️ IBM Watsonx.ai – For building, training, and deploying the conversational AI agent

✔️ Watsonx Custom Tools – To connect AI outputs with external APIs and backend logic

✔️ Amadeus Travel API – For fetching real-time flight offers and travel data

✔️ Python – For backend logic, API integration, and data processing

✔️ IBM Cloud – For deployment and API hosting


# ☁️ IBM Cloud Services Used

🔹Watsonx.ai Studio

🔹IBM Granite Model

🔹Watsonx Vector Index

🔹IBM Cloud Lite Account

🔹IBM Cloud IAM

🔹IBM Cloud Object Storage

# 🌟 WOW Factors – WanderWise AI Travel Agent


🧠 Uses LLM-powered NLP to understand casual travel queries like “Plan a weekend in Goa”

🌐 Built entirely on IBM Cloud using Watsonx.ai Studio, Runtime & Custom Tools

✈️ Integrates Amadeus API to fetch real-time flight options based on city names, date & time

🔄 Handles unrelated or vague queries gracefully with smart redirections

🧳 Creates dynamic travel itineraries, ready to be exported as PDFs

🌦️ Provides real-time weather updates and trip alerts for safe travel

💬 Future-ready with multilingual query support & location-aware suggestions

📍 Maps natural language city names to IATA codes automatically (e.g., “Kochi” → “COK”)

🤖 Fully deployable AI agent that runs live — not a prototype

📚 Educates travelers on local culture, best times to visit, and do’s & don’ts

📥 Ready for WhatsApp or Web chatbot integration with minimal effort

# 🔄 How It Works


1. User Makes a Travel Request
The user types a natural question — like finding flights, weekend plans, or activities — without needing technical inputs.

2. LLM Understands Intent & Context
IBM Granite Large Language Model (LLM), via Watsonx.ai, interprets the user's query and extracts relevant parameters such as destination, date, or travel theme.

3. Searches Uploaded Trip Documents 
If itinerary PDFs or travel guides are uploaded, a vector index retrieves trusted and relevant information to support the response.

4. Custom Tool Invokes Flight Search Logic
Based on extracted info, the backend Python tool (connected via Watsonx) sends a real-time query to Amadeus API to find matching flight options.

5. Fetches Flight and Travel Data
Receives data like airlines, schedules, and pricing from the Amadeus API.

6. Agent Responds with Grounded, Contextual Output
The AI combines real-time flight data, document-sourced content (if any), and user preferences to respond in natural, helpful language.

7.  Enhanced Features
Weather updates, transport suggestions, and local experiences.
PDF itinerary generation.
Multilingual and follow-up support for global travelers.

# Screenshots

🔹 Setting Up

<img width="1915" height="835" alt="Setup" src="https://github.com/user-attachments/assets/3c385570-ee1c-4796-bb5f-46cffb753b7d" />
<br>

</br>

🔹 Agent Instructions

<img width="1759" height="675" alt="agent instructions" src="https://github.com/user-attachments/assets/e0fda5d7-4742-4aef-bfbb-5949476e06df" />
<br>

</br>

🔹 Quick start questions

<img width="1920" height="839" alt="Quick start qstns" src="https://github.com/user-attachments/assets/6c226072-b87f-463c-9731-8511c1358780" />
<br>

</br>

🔹 Tools used

<img width="1915" height="867" alt="Tools" src="https://github.com/user-attachments/assets/22b33f57-32f4-4d4b-a7d4-81e2407dbe1f" />
<br>

</br>

🔹 API reference after Deployment

<img width="1574" height="614" alt="API likns" src="https://github.com/user-attachments/assets/f2b6e07e-5c00-49c6-ad42-5041f756eb06" />
<br>

</br>

🔹 Resources list

<img width="1905" height="742" alt="resource list" src="https://github.com/user-attachments/assets/a7bc946d-929e-41c5-8562-043d3e183a7a" />
<br>

</br>

# 🔮 Future scope


📱 WhatsApp or mobile app integration for on-the-go travel planning

🗓️ Auto-generated trip summaries and travel history reports

🧭 Integration with region-specific tourism boards for local recommendations

🌐 Multilingual support using Watson Language Translator

🧳 Personalized travel recommendations based on user history and preferences

🔔 Real-time travel alerts and dynamic itinerary adjustments based on delays or disruptions





 
