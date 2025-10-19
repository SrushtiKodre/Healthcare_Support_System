# Healthcare_Support_System
Capstone mini project - An AI-powered Multi-agent healthcare support system using Gemini 2.5 flash. It includes agents for symptom checking,medical research and treatment cost estimation.

# “Refer to the Colab notebook for complete setup (API key, ngrok, and Streamlit instructions included).”

# API & ngrok Setup
# For API Key : 
1. Go to Google AI Studio
2. Sign in with your Google account.
3. Create a new API key.
4. Copy the key and paste it in your Colab or code:
GOOGLE_API_KEY = "your gemini api key"

# For ngrok auth token :
1. Create a free account on ngrok.com.
2. Copy your auth token from the dashboard.

run this in separate cell:   !ngrok config add-authtoken "your ngrok auth token"

Set your ngrok auth token here:
conf.get_default().auth_token = "your auth token"

# Run your app:

streamlit run app.py
