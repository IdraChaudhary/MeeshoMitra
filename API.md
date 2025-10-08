# API Documentation

## Base URL
https://api.meeshomitra.com/v1

text

Copy

Download

## Authentication
All requests require API key in header:
```http
Authorization: Bearer YOUR_API_KEY
Endpoints
1. Send Message
http

Copy

Download
POST /chat/message
Content-Type: application/json

{
  "message": "Ye suit monsoon ke liye accha hai?",
  "session_id": "user_session_123",
  "message_type": "text"
}
Response:

json

Copy

Download
{
  "response": "Haan ji! This suit is perfect for monsoon...",
  "session_id": "user_session_123",
  "suggested_products": [...]
}
2. Voice Message
http

Copy

Download
POST /chat/voice
Content-Type: audio/wav

[Binary audio data]
3. Image Analysis
http

Copy

Download
POST /chat/image
Content-Type: image/jpeg

[Binary image data]
4. WhatsApp Integration
http

Copy

Download
POST /whatsapp/session
{
  "phone_number": "+91XXXXXXXXXX",
  "session_data": {...}
}
Error Codes
400 - Bad Request

401 - Unauthorized

500 - Internal Server Error
