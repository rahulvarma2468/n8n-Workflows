# n8n-Workflows
🔷 1. Email Adder
Goal: Automatically add or draft emails based on Telegram messages.

Workflow Description:

Trigger: Telegram message received.

AI Agent: Processes the message using OpenAI.

Memory: Retains context (Simple Memory node).

Output:

Sends a text reply to Telegram.

Optionally creates a Gmail draft or sends an email via Gmail.

✅ Useful for quickly turning Telegram messages into emails using AI understanding.
<img width="1450" height="628" alt="Image" src="https://github.com/user-attachments/assets/d76430aa-99ab-453a-9c10-36b1560ad459" />



🔷 2. Conversational Telegram Bot
Goal: Create a smart chatbot on Telegram that can understand text or voice inputs.

Workflow Description:

Trigger: Telegram message (text or voice).

Voice Option:

If voice: downloads it, transcribes to text, sends to AI.

If text: directly goes to AI.

AI Agent: Uses Google Gemini model for contextual understanding.

Memory: Maintains conversation history.

Output: Sends AI-generated reply back to Telegram.

✅ A full conversational bot that supports both text and voice communication.
<img width="1471" height="627" alt="Image" src="https://github.com/user-attachments/assets/530170c6-9ffd-44e1-b6e0-b85cffb3b663" />



🔷 3. Automate Email Filtering & AI Response
Goal: Filter incoming emails and automatically respond or log them based on content.

Workflow Description:

Trigger: New email in Gmail.

Parse Email: Extracts and analyzes content.

Condition: Checks if it's a valid/targeted email.

AI Agent: Uses Google Gemini to draft or analyze.

Output: Logs important data to Google Sheets.

✅ Ideal for use cases like automated customer support, lead filtering, etc.
<img width="1459" height="634" alt="Image" src="https://github.com/user-attachments/assets/f95fa66c-33f5-41b2-a5b8-4a12d7c61f53" />



🔷 4. Generating Image and Uploading to Google Drive
Goal: Generate an image (via API) and store it in Google Drive.

Workflow Description:

Trigger: Button click (“Execute workflow”).

HTTP Request: Sends POST request to an image generation API.

Output: Receives generated image and uploads it to Google Drive.

✅ Great for generating visuals dynamically and saving them automatically.
<img width="1436" height="625" alt="Image" src="https://github.com/user-attachments/assets/7b0f2c3e-4d64-4fe5-806d-fa4748f1026b" />



🔷 5. Generating AI Videos and Adding to Sheets
Goal: Generate AI-powered video content from prompts and track them in Google Sheets.

Workflow Description:

Trigger: Manual “Execute workflow” button.

AI Agent: Accepts a video idea and passes it to OpenAI.

Sheet: Logs idea → fetches it → sends it to Replicate API to create video.

Wait & Polling: Waits for video completion.

If Condition: Checks status.

Output: Adds video link to the Google Sheet.

✅ Perfect for automating content creation pipelines (YouTube Shorts, Instagram Reels ideas, etc.).

<img width="1460" height="630" alt="Image" src="https://github.com/user-attachments/assets/5ba0456b-8441-43d0-88d7-64d89e3174b8" />




