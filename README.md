
# 🌿 OrganicBot – Conversational AI for Organic Farming

**OrganicBot** is a Dialogflow-based chatbot designed to assist farmers with organic agriculture practices such as soil fertility, pest control, crop rotation, and composting methods.

---

## 🚀 Features

- Understands and responds to questions about organic farming
- Uses natural language understanding to detect:
  - **Intents**: User goals like improving soil or managing pests
  - **Entities**: Keywords like crop names, seasons, and durations
- Provides context-aware, friendly advice based on best practices

---

## 🧠 Intents and Entities

| Intent              | Description                                      | Entities Used               |
|---------------------|--------------------------------------------------|-----------------------------|
| `soil_fertility`    | Improve soil health organically                  | `crop_name`, `season`       |
| `pest_control`      | Control pests using natural methods              | `crop_name`, `season`       |
| `crop_rotation`     | Suggestions on rotating crops by season          | `season`                    |
| `composting_methods`| Composting techniques and durations              | `crop_name`, `duration`     |
| `greet`             | Greeting intent                                  | None                        |

---

## 🔁 Sample Demo Conversation

**User:** Hi there!  
**Bot:** Hello! How can I help you with your organic farming today?

**User:** How do I improve soil for wheat in summer?  
**Bot:** To improve soil for wheat during summer, use composted manure and nitrogen-fixing cover crops like legumes.

**User:** What's the best pest control for tomatoes in winter?  
**Bot:** To control pests in tomatoes during winter, use neem oil and release beneficial insects like ladybugs.

**User:** What crop should I grow in summer after harvesting maize?  
**Bot:** In summer, rotate heavy feeders like maize with legumes to restore nitrogen to the soil.

**User:** How long does composting take for maize?  
**Bot:** For maize, compost for about 2–3 months to ensure it’s fully decomposed before applying.

**User:** Thanks!  
**Bot:** You're welcome! Let me know if you have more farming questions.

---

## ⚙️ Setup Instructions

### 1. Import into Dialogflow Console

1. Go to [Dialogflow ES Console](https://dialogflow.cloud.google.com)
2. Click on **Create Agent**
3. Choose your language and time zone, name the agent `OrganicBot`
4. Click ⚙️ (gear icon) → **Export and Import** → **Restore from ZIP**
5. Upload the `OrganicBot.zip` file from this repo

### 2. Test the Bot

Use the **Dialogflow simulator** (right panel) to test questions like:
- “How do I improve soil for maize?”
- “What pests affect rice in winter?”
- “Suggest composting methods for wheat.”

---

## 📁 Files in This Repository

- `OrganicBot.zip`: Dialogflow agent with intents, entities, and responses
- `README.md`: Project documentation

---

## ✅ Requirements Met

- [x] Intents and entities created
- [x] Entity-based dynamic responses
- [x] Demo conversation included
- [x] Setup guide provided

---

**Good luck farming organically! 🌱**
