Sales Agent with Dialogflow Integration
A Python-based sales agent that uses Dialogflow for natural language processing and lead management. The agent handles lead interactions, collects information, and manages follow-ups automatically.

Features
Natural language processing using Dialogflow
Automated lead information collection
Smart follow-up system
Lead data management and storage
Error handling and logging
Asynchronous operation
Setup Instructions
Prerequisites
Python 3.8 or higher
Google Cloud account with Dialogflow API enabled
Dialogflow ES agent created and configured
Installation
Clone the repository:
git clone <repository-url>
cd sales-agent
Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:
pip install -r requirements.txt
Set up environment variables: Create a .env file in the project root with:
PROJECT_ID=your-dialogflow-project-id
GOOGLE_APPLICATION_CREDENTIALS=path/to/your/credentials.json
Configure Dialogflow:
Create a Dialogflow ES agent
Set up the following intents:
initial_greeting
collect_age
collect_country
collect_interest
follow_up_message
second_follow_up
end_conversation
