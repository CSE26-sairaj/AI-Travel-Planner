✈️ AI Travel Planner: Automated Itinerary Generation
This project implements an end-to-end, AI-powered automation solution that instantly generates personalized, day-by-day travel itineraries based on user preferences. Built as a capstone project for the Mirai Summer Internship, it demonstrates proficiency in Generative AI, workflow automation, and seamless user experience design.

🌟 Project Features

Intelligent Itinerary Generation: Uses a Large Language Model (LLM) to generate a structured, personalized travel plan (destinations, attractions, tips).


Automated Logging: Logs all user inputs and the complete AI-generated itinerary to Google Sheets for data tracking.


Email Automation: Sends the final, cleanly formatted itinerary directly to the user's email address.


Conversational Interface (Optional): Designed for compatibility with optional voice input for enhanced interactivity.


🛠️ Technology Stack
Component	Tool / Technology	Role in Project
Frontend/UI	Lovable.ai	
Used to create the user-friendly data submission form.


Backend/Workflow	n8n	
Orchestrates the entire automation process using webhooks, AI Agents, and email delivery.

Artificial Intelligence	Gemini (LLM)	
Powers the AI Agent to process inputs and generate structured itinerary content.

Data Logging	Google Sheets	
Stores a log of all processed inputs and outputs.

Integration	Webhook	
Connects the Lovable.ai form submission to the n8n workflow trigger.


Export to Sheets
🚀 How It Works (The Automation Flow)
The system is executed through a clean, logical n8n workflow:


User Input: A visitor submits their trip details (Destination, Date, Duration, Budget, etc.) via the Lovable.ai form.



Webhook Trigger: The form data is instantly sent to the n8n workflow via a Webhook.


AI Processing: An AI Agent within n8n uses the LLM to generate the detailed, day-by-day itinerary.


Data Logging: The workflow logs the user's request and the complete generated itinerary to a designated Google Sheet.


Formatted Delivery: An automated email containing the HTML-formatted itinerary is sent to the user.

🔗 Project Links
Live Application Link: https://instant-adventure-ai.lovable.app/

Workflow Diagram/JSON: https://drive.google.com/drive/folders/1GOvoo0uTb50aJ3LeBuAlSb1Z4ckYmtzE?usp=sharing

Submission Video: https://youtu.be/XvBAL6r2RkM

💡 Key Learning Outcomes
Mastered the setup and configuration of 

AI Agents for structured output generation.

Gained expertise in establishing seamless 

Webhook integrations between external platforms (Lovable.ai) and n8n.

Developed skills in data mapping and automated 

logging into Google Sheets.

Successfully implemented automated email delivery with advanced 

HTML formatting for a superior UI/UX.

🧑‍💻 About the Developer
Sairaj Pattnaik
Final Year B.Tech Computer Science Student
Veer Surendra Sai University of Technology

Enthusiastic and passionate about Data Science, Machine Learning, Generative AI, and LLMs.
