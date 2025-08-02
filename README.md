Travel Planner Agent : SAFAR

Travel Planner Agent

The Travel Planner Agent is an AI-powered assistant that helps users plan trips efficiently and intelligently. It uses real-time data to suggest destinations, build itineraries, and recommend transport and accommodation options. By understanding user preferences, budgets, and constraints, it tailors personalized travel plans.

The agent is integrated with maps, weather updates, and local guides to ensure a smooth travel experience. It can also manage bookings, alert users to changes, and optimize schedules on the go—transforming complex travel planning into a seamless, enjoyable process.

Objective

To build a smart travel assistant using IBM Cloud Lite services and IBM Granite models that:
- Understands user inputs such as preferences, budget, and travel dates
- Recommends ideal destinations and builds complete itineraries
- Suggests transport and accommodation options
- Displays weather forecasts and local tips
- Manages alerts and booking reminders

Tech Stack

AI Model: IBM Granite Foundation Model (e.g., granite-13b-chat-v2)  
Platform: IBM Watsonx.ai  
Cloud: IBM Cloud Lite (Watson Studio, Cloud Foundry)  
Programming Language: Python  
Data Sources: Weather APIs, Map APIs, Hotel/Travel APIs  
Interface (Optional): Jupyter Notebook / Streamlit / Flask  

Features

AI-generated travel recommendations  
Real-time weather and local information  
Accommodation and transport suggestions  
Itinerary and day-wise schedule generation  
Smart alerts for updates and changes  

Project Structure

travel-planner-agent/

notebooks/               -> IBM Watson Studio or local notebooks  
    main_notebook.ipynb

src/                     -> Source code (optional if using notebooks)  
    planner.py  
    granite_query.py  
    utils.py  

data/                    -> Sample input/output files  
    preferences.json  

README.md  
requirements.txt         -> Python dependencies  

Setup Instructions

1. Create an IBM Cloud Lite account: https://cloud.ibm.com  
2. Enable Watsonx.ai and Granite foundation model  
3. Generate API key and project/space ID  
4. Configure environment:
   export WATSONX_APIKEY="your_api_key"  
   export PROJECT_ID="your_project_id"

5. Install required libraries:
   pip install -r requirements.txt

How It Works

1. User provides travel preferences (destination type, budget, dates, etc.)  
2. Input is passed to the IBM Granite model via API  
3. AI generates a plan (destination, itinerary, suggestions)  
4. Weather, transport, and hotel data is integrated  
5. Final itinerary is displayed with recommendations  

Future Enhancements

Add voice input support  
Real-time bookings (flights, hotels)  
Smart notifications via email or SMS  
Personalized offers or local events  

Team

This project was built as part of the IBM SkillsBuild for Academia Program by:

Shivam Kumar  


License

This project is for educational purposes only under the IBM SkillsBuild initiative.
