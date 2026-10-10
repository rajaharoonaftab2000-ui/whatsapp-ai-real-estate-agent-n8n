# WhatsApp AI Real Estate Agent

An AI-powered real estate assistant built with n8n, WhatsApp Business Cloud API, Google Gemini, Google Sheets, and Google Calendar.

## Overview

This automation helps real estate businesses handle property inquiries through WhatsApp.

The agent responds in the customer's language, finds matching property listings from Google Sheets, collects lead information, and books property viewings in Google Calendar.

It also sends WhatsApp notifications to the business owner and redirects unrelated questions back to property topics.

## Workflow

WhatsApp Message → AI Agent → Understand Customer Request → Find Matching Listings → Reply on WhatsApp

Depending on the conversation, the agent can also:

- Save lead details to Google Sheets.
- Create a property viewing appointment in Google Calendar.
- Send a WhatsApp alert to the business owner.

## How It Works

1. 📩 **Receive a WhatsApp inquiry**  
   A customer sends a message asking about available properties or requesting a viewing.

2. 🤖 **Understand the request**  
   Google Gemini interprets the customer's message and identifies their property requirements.

3. 🌐 **Respond in the customer's language**  
   The agent replies in the language used by the customer.

4. 🏠 **Find matching properties**  
   The agent retrieves relevant property listings from Google Sheets and shares the available details.

5. 📋 **Capture lead information**  
   Customer contact details and property requirements are saved in Google Sheets.

6. 📅 **Book a property viewing**  
   The agent collects the required booking details and creates a viewing appointment in Google Calendar.

7. 🔔 **Notify the business owner**  
   A WhatsApp alert keeps the owner informed about new leads.

8. 🎯 **Keep conversations relevant**  
   Off-topic questions are politely redirected to real estate inquiries.

## Features

- 💬 WhatsApp-based customer interaction
- 🤖 AI-powered inquiry handling
- 🌐 Multilingual replies
- 🏠 Property listings retrieved from Google Sheets
- 📋 Automatic lead capture
- 📅 Google Calendar viewing bookings
- 🔔 Owner notifications through WhatsApp
- 🎯 Property-focused conversation handling
- ⚙️ Customizable business information and response style

## Technologies Used

- **n8n** — Workflow automation
- **WhatsApp Business Cloud API** — Customer messaging and owner alerts
- **Google Gemini** — AI conversation processing
- **Google Sheets** — Property listings and lead storage
- **Google Calendar** — Property viewing appointments

## Use Case

This automation helps real estate agents and agencies reduce repetitive replies, organize incoming leads, and simplify property viewing bookings.

Customers can ask about properties through WhatsApp, receive relevant listing information, and request a viewing within the same conversation.

The workflow can be customized for rental agencies, property dealers, and residential or commercial real estate businesses.

## Setup Requirements

- A running n8n instance
- A configured WhatsApp Business Cloud API connection
- A publicly accessible webhook URL for incoming messages
- Google Gemini API access
- Google Sheets containing property listings and lead fields
- A connected Google Calendar for viewing appointments

Before testing, connect your own credentials and configure the WhatsApp details, spreadsheet IDs, calendar, owner notification number, and timezone.

## Important Notes

- Property responses depend on the information stored in Google Sheets.
- Keep listing prices, availability, and property details up to date.
- Automated replies require the workflow to be active and n8n to remain running.
- WhatsApp messaging is subject to Meta's applicable messaging rules.
- Hosting, API usage, and messaging costs depend on the services used.
- Use sample customer data when demonstrating the workflow publicly.

## Demo Video

[Watch the WhatsApp Real Estate Agent Demo](./WhatsApp_RealEstate_Agent_Demo_No_Voice_No_Song.mp4.mp4)

## Project Status

Completed portfolio demo demonstrating WhatsApp property inquiries, listing retrieval, lead capture, viewing bookings, and owner notifications.
