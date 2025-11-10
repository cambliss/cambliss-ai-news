server/.env
# Razorpay Configuration
# Get your API keys from: https://dashboard.razorpay.com/app/keys

# Test Mode Keys (for development)
RAZORPAY_KEY_ID=rzp_live_RcLrTi5gvveeqy
RAZORPAY_SECRET=FVfBy8BwTTksWkKX56McOZeL
CLERK_SECRET_KEY=sk_test_4au26Cr0GBq4xFXVwlRXHT7c4cph81X3wCAHZ2EtQ4
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_aW50ZW5zZS1tdWxlLTMuY2xlcmsuYWNjb3VudHMuZGV2JA

# Production Mode Keys (for live payments - uncomment when ready)
# RAZORPAY_KEY_ID=rzp_live_xxxxxxxxxx
# RAZORPAY_SECRET=your_live_secret_key_here

# Server Configuration
PORT=5000

# Security Note:
# - NEVER commit your actual .env file to version control
# - Keep your secret keys confidential
# - Use test keys during development
# - Switch to live keys only in production


root/.env
# ElevenLabs API Configuration
# Get your API key from: https://elevenlabs.io/
# Sign up for free tier or subscribe for more usage
VITE_REACT_APP_ELEVENLABS_API_KEY=your_elevenlabs_api_key_here

# Optional: Custom voice settings
VITE_REACT_APP_DEFAULT_VOICE_ID=pNInz6obpgDQGcFmaJgB
VITE_REACT_APP_VOICE_STABILITY=0.5
VITE_REACT_APP_VOICE_SIMILARITY=0.75

VITE_CLERK_PUBLISHABLE_KEY=pk_test_aW50ZW5zZS1tdWxlLTMuY2xlcmsuYWNjb3VudHMuZGV2JA
VITE_API_URL=http://localhost:5000




To Sart The Project

npm install 

npm run dev:full
