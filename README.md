# WhatsApp-healthcare-booking-automation
Automated WhatsApp chatbot for healthcare appointment booking built with n8n. The system collects patient booking data in Google Sheets which can later be used for healthcare data analysis and reporting.

This project demonstrates an automated healthcare appointment booking system using WhatsApp and n8n.

The chatbot guides patients through a simple booking flow:

• Start conversation  
• Choose a department  
• Select a preferred appointment date  
• Receive appointment confirmation  

All booking data is automatically stored in Google Sheets creating a structured dataset that can later be used for healthcare data analysis and reporting.

---

## Workflow Architecture

![Workflow](images/workflow.png)

---

## Chatbot Interaction

![Chatbot](images/chatbot-demo.png)

---

## Dataset Example

The system automatically logs booking data including:

• phone number  
• selected department  
• appointment date  
• booking status  

This dataset can later be connected to tools such as Power BI for healthcare analytics.

![Dataset](images/dataset.png)

---

## Technologies Used

- n8n
- WhatsApp Business API
- Google Sheets
- Automation Workflows
