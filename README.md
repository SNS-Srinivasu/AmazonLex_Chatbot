# Amazon Lex Chatbot


Key Components and Features

Amazon Lex Chatbot

Intent: Includes intents such as BookHotel for hotel reservations.
Slots: Defined slots like Location, CheckinDate, Nights, RoomType, and Cost to gather booking details from users.
Validation: Implemented Lambda function (hotelbookinglambda) for slot validation and fulfillment using AWS Lambda.
WhatsApp Integration

Twilio Integration: Utilizes Twilio to integrate WhatsApp with Amazon Lex chatbot.
Functionality: Allows users to interact with the chatbot via WhatsApp for hotel bookings.
Conversational AI

Purpose: Provides a natural language interface for users to inquire and book hotel reservations.
Explanation: Utilizes intents to understand user goals (BookHotel), slots to collect necessary details, and Lambda functions for validation and fulfillment.
Development and Deployment Steps
Lambda Function: Developed in Python to handle dialog and fulfillments based on user interactions.
Twilio Setup: Configured Twilio account and number for WhatsApp integration.
Amazon Lex Setup: Created bot versions and aliases, configured integration with Twilio for WhatsApp interaction.
Additional Information
Blog Post: Includes a detailed tutorial on how to build and deploy the chatbot using Amazon Lex and AWS Lambda.
Educational Content: Provides insights into intents, slots, slot types, and Lambda integration for effective chatbot development.

This project aims to leverage Amazon Lex and AWS Lambda to create a robust chatbot solution for hotel bookings, integrating seamlessly with WhatsApp for broader user accessibility.
