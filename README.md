# AI-ChatAssistant
Chatbot Assistant

# CARYS Fashion Chatbot Assistant

This project is a chatbot assistant designed to help customers interact with CARYS, a premium fashion brand. The chatbot provides a seamless way for users to inquire about various business details, store locations, product policies, FAQs, and more. Powered by Google's Generative AI, the chatbot delivers helpful, accurate, and real-time responses.

## Features

- **Business Information**: Provides users with information about CARYS, including business hours, locations, product offerings, and customer support.
- **Store Locations**: Users can inquire about physical store locations in Madurai and Chennai, with details such as addresses, phone numbers, and opening hours.
- **Policies**: The bot explains CARYS' return and refund policies, shipping and delivery details, payment methods, and warranty information.
- **Frequently Asked Questions (FAQs)**: Customers can get answers to common queries about orders, shipping, returns, payments, and store services.
- **Customer Interaction**: Allows users to ask questions and get answers in real-time.

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Google Generative AI API (using the `@google/generative-ai` library)
- **Deployment**: Can be deployed on any web server that supports static files

## How It Works

1. **User Input**: The user enters a message in the chatbot interface.
2. **Message Handling**: The chatbot sends the message to the backend, where it's processed by Google's Generative AI model (Gemini 1.5 flash).
3. **Model Response**: The AI processes the input and generates an appropriate response based on the provided business information and FAQs.
4. **Real-Time Interaction**: The chatbot responds with text-based answers, providing customers with relevant information in a conversational format.
