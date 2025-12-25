# Food Ordering Chatbot using Dialogflow & FastAPI

This project is an **AI-powered food ordering chatbot** that enables users to place food orders, manage items, and track order status through natural language conversations. The chatbot is built using **Dialogflow** for intent recognition and conversation flow, with a **FastAPI** backend that handles business logic and communicates with a **MySQL** database for storing and tracking order details.

The chatbot is integrated into a **food website clone** developed using **HTML, CSS, and JavaScript**, providing users with a seamless and interactive ordering experience directly on the website.

---

## Key Features

- AI-based conversational food ordering system  
- Place, update, and complete food orders via chat  
- Track order status using order ID  
- Context-aware conversations using Dialogflow contexts  
- Fast and lightweight backend powered by FastAPI  
- Persistent order storage using MySQL database  
- Fully integrated chatbot within a web-based food website  
- Real-time interaction between frontend, chatbot, and backend  

---

## Technologies Used

### Frontend
- HTML  
- CSS  
- JavaScript  

### Chatbot & NLP
- Dialogflow (Intents, Entities, Contexts, Webhooks)

### Backend
- Python  
- FastAPI  

### Database
- MySQL  

---

## 🧩 How the System Works

Users interact with the chatbot embedded on the food website to place or track orders. Dialogflow processes the user’s input and identifies the correct intent. The request is then sent to the FastAPI backend through a webhook, where business logic is executed. Order details are stored or retrieved from the MySQL database, and the response is sent back to Dialogflow, which replies to the user in natural language.

---

## 💬 Example User Interactions

- “I want to place a new order”  
- “Add two burgers and one pizza”  
- “Remove fries from my order”  
- “Complete my order”  
- “Track my order”  
- “Where is my food?”  

---

## 🎯 Project Use Cases

- Online food ordering platforms  
- Restaurant automation systems  
- AI-powered customer support chatbots  
- Conversational commerce applications  

---

## 🌟 Future Scope

- User authentication and order history  
- Online payment gateway integration  
- Mobile-friendly and responsive UI  
- Admin dashboard for order monitoring  
- Smart food recommendations using AI  
