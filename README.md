# 🩺 n8n UI Appointment Bot

A lightweight, embedded web chatbot built using **n8n’s Chat Trigger**. Users can **Book** or **Cancel** appointments, pick **Doctors** and **Time Slots**, and get **email confirmation**—all through a clean UI and minimal typing.

---

## 🚀 Key Features

- **Embedded Web Chat**: Add a chat widget to your site using n8n’s Chat Trigger in Embedded mode.  
- **Quick‑Reply Buttons**: Users choose options (Book/Cancel, Doctor, Slot) with a tap—not typing.  
- **Email Confirmation**: Sends appointment details via email using the “Send Email” node.  
- **Conversation Context**: Utilizes n8n’s AI Agent + Memory nodes to manage chat flow.  
- **Flexible Data Source**: Easily integrates with Google Sheets, Airtable, databases, or APIs.

---

## 🛠️ Setup Guide

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/n8n-ui-appointment-bot.git
   cd n8n-ui-appointment-bot
| Step | User Action       | Bot Action                        |
| ---- | ----------------- | --------------------------------- |
| 1    | Opens chat widget | Shows “Book” / “Cancel” buttons   |
| 2    | Selects Doctor    | Shows available time slot buttons |
| 3    | Picks Slot        | Asks: “Please provide your email” |
| 4    | Provides Email    | Bot confirms and sends email      |
| 5    | Booking Completed | Email confirmation sent to user   |

<img width="1392" height="658" alt="image" src="https://github.com/user-attachments/assets/eba2bfd4-7912-4380-b343-2532e1914a2c" />
https://github.com/user-attachments/assets/fd1024d2-b949-43ab-958e-ad64ace608e4
<img width="911" height="552" alt="image" src="https://github.com/user-attachments/assets/f9281bec-9aeb-4d91-9831-43bcacbdb380" />



