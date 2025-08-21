# DineSmart
# Food Ordering Chatbot (Dialogflow + Telegram)
This project is a **Food Ordering Chatbot** built using **Dialogflow** for NLP (intent recognition) and integrated with **Telegram** for customer interaction.  
The chatbot allows customers to place food orders, provide their details, confirm the bill, and receive a polite thank-you message.  

# Features
- Customers can order food items (e.g., pizza, burger, coke).
- Collects customer **name** and **phone number**.
- Confirms the **total bill amount** before order completion.
- Ends with a friendly message: *"Thank you, have a nice day!"*.
- Integrated with **Telegram** for real-time conversations.

# Import into Dialogflow
1. Download this repository or the file `dialogflow_agent.zip`.
2. Go to [Dialogflow Console](https://dialogflow.cloud.google.com/).
3. Create a new agent (or use an existing one).
4. Navigate to **Settings ⚙️ → Export and Import → Restore from ZIP**.
5. Upload the provided `dialogflow_agent.zip`

# Connect Dialogflow with Telegram
1. Open **Telegram** and search for **BotFather**.
2. Run `/newbot` and follow the steps to create your bot.
3. Copy the **API Token** provided by BotFather.
4. Go to **Dialogflow Console → Integrations → Telegram**.
5. Paste the token in the integration settings.
6. Enable Telegram integration and start chatting with your bot .
