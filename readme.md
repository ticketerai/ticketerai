# 🤖 AI Ticket Assistant – *by ChaiCode*

> 🎥 Built for the **ChaiCode YouTube Series** — an AI-powered ticket management system that *automatically categorizes, prioritizes, and assigns support tickets* to the right moderators using **Google Gemini** and **Inngest**.

---

## ✨ Overview

The **AI Ticket Assistant** brings automation to customer support workflows. It classifies tickets, detects urgency, assigns moderators by skill, and even generates AI-driven notes — all with minimal setup.

---

## 🚀 Key Features

### 🧠 AI Ticket Intelligence
- Automatic categorization & priority detection  
- AI-generated moderator notes  
- Gemini-powered ticket insights  

### 👥 Smart Moderator Assignment
- Skill-based ticket routing  
- Auto-assignment with admin fallback  
- Regex-based skill matching  

### 🔐 User Management
- Role-based access control *(User, Moderator, Admin)*  
- JWT authentication  
- Moderator skill tracking  

### ⚙️ Background Processing
- Event-driven architecture via **Inngest**  
- Async email notifications  
- Scalable job handling  

---

## 🧰 Tech Stack

| Layer | Technology |
|-------|-------------|
| **Backend** | Node.js + Express |
| **Database** | MongoDB |
| **AI** | Google Gemini API |
| **Auth** | JWT |
| **Background Jobs** | Inngest |
| **Email** | Nodemailer + Mailtrap |
| **Dev Tools** | Nodemon |

---

## 📋 Prerequisites
- Node.js **v14+**
- MongoDB
- Google Gemini API key
- Mailtrap account (for testing)

---

## ⚡ Quick Start

```bash
# Clone repository
git clone <repository-url>
cd ai-ticket-assistant

# Install dependencies
npm install
