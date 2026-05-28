# ST10485019_PROG6221 PART2_CYBERSECURITY CHATBOT

A WPF-based Cybersecurity Awareness Chatbot built in C# that educates users 
about online safety through interactive conversation.

## Student Information
- **Name:** Siyahluma Hoyi
- **Student Number:** ST10485019
- **Module:** PROG6221 - Programming 2A
- **Assessment:** Part 2

## Features Implemented

### Core Features
- ✅ WPF GUI with dark red cybersecurity theme and ASCII art header
- ✅ User name capture on startup with personalised welcome message
- ✅ Keyword recognition for cybersecurity topics:
  - Passwords, Phishing, Privacy, Scams, Malware
- ✅ Random responses per keyword (variety in answers)
- ✅ Help menu listing all available topics
- ✅ Voice greeting audio on startup
- ✅ Exit/quit command to close the app

### Advanced Features
- ✅ Sentiment detection (Worried, Curious, Frustrated, Happy, Neutral)
- ✅ Memory store - remembers user name and favourite topic
- ✅ Personalised responses using stored user information
- ✅ "Tell me more" follow-up using last matched topic
- ✅ Special phrase handling: "how are you", "what can you do", "purpose"
- ✅ Random fallback responses when no keyword matched

## Prerequisites

Before running this project, make sure you have:
- ✅ **Visual Studio 2022** (Community or higher)
- ✅ **.NET 8.0 SDK**
- ✅ **Windows OS** (required for WPF and SoundPlayer)

## How to Clone and Run

### Step 1 - Clone the repository
bash
git clone https://github.com/SiyaHoyi19/ST10485019_PROG6221-PART2_CYBERSECURITY-CHATBOT.git

### Step 2 - Open in Visual Studio
1. Open Visual Studio 2022
2. Click **File → Open → Project/Solution**
3. Navigate to the cloned folder
4. Open `CybersecurityChatbot.sln`

### Step 3 - Add the greeting audio file
- Place your `greeting.wav` file in the following folder:
CybersecurityChatbot/bin/Debug/net8.0-windows/greeting.wav
> ⚠️ Without this file the app will still run but no audio will play on startup.

### Step 4 - Run the project
- Press **F5** or click the green **Run** button in Visual Studio

---

## How to Use the Chatbot

1. When the app starts, **type your name** and press Enter or click Send
2. You will receive a personalised welcome message
3. Try typing any of these:
   - `passwords` - get password safety tips
   - `phishing` - learn about phishing attacks
   - `help` - see all available topics
   - `tell me more` - get more info on the last topic
   - `i am interested in malware` - save your favourite topic
   - `how are you` - friendly chat
   - `what can you do` - see bot capabilities
   - `exit` or `quit` - close the app

## Screenshot
<img width="1920" height="1020" alt="Screenshot 2026-05-28 231430" src="https://github.com/user-attachments/assets/50ff4194-1b61-4c75-94a0-a29408678274" />


## Video Demo

🎥 [Watch on YouTube](YOUR_YOUTUBE_LINK_HERE)

---

## GitHub Actions

![CI](../../actions/workflows/dotnet.yml/badge.svg)
