# ✈️ Travel Planner Agent  

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






 
