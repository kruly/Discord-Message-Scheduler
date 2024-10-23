# Discord-Message-Scheduler
A Discord Message Scheduler/Automatic posting of messages


# 🛠 Multi-Token Discord Scheduler

Multi-Token Discord Scheduler is a web-based tool that allows users to schedule messages to multiple Discord channels at specified intervals using different Discord tokens. The tool supports managing multiple tokens, scheduling messages for different channels with unique messages, and provides real-time status updates for each scheduled message.

## ✨ Features

🗝️ Multi-Token Support: Add and manage multiple Discord tokens (bots or user accounts).

📢 Multi-Channel Messaging: Schedule messages to multiple channels, each with its own unique message.

⏲️ Interval-Based Scheduling: Define how frequently messages should be sent (in seconds).

📊 Real-Time Message Logs: Track the logs for each scheduled message, showing when it was sent, and whether it was successful or failed.

🔁 Stop/Restart Scheduling: Toggle between stopping and restarting a scheduled message for any channel.

❌ Error Tracking: Real-time status updates for each scheduled message, showing success or failure.


## ⚙️ Setup and Installation

Prerequisites

Node.js (v14 or higher)

npm (Node Package Manager)


🚀 1. Clone the Repository

git clone https://github.com/yourusername/multi-token-discord-scheduler.git
cd multi-token-discord-scheduler

📦 2. Install Dependencies

npm install

▶️ 3. Run the Server

node app.js

The application will now be running on http://localhost:4000. You can access the user interface in your browser.

📝 4. Usage

1. Enter your Discord Token(s):

Go to the "Schedule Message" tab and add your Discord token(s).



2. Enter Channel IDs and Messages:

Input the Discord Channel IDs (comma-separated) and corresponding messages (also comma-separated). Each message corresponds to the respective Channel ID.



3. Set Message Interval:

Define the interval (in seconds) at which the messages will be sent.



4. Track Logs:

Go to the "Message Logs" tab to view real-time logs of each scheduled message, with details on whether it was sent successfully or failed.




⏹️ 5. Stopping and Restarting Messages

In the "Message Logs" tab:

You can click the "Stop" button to stop scheduling messages to a specific channel.

You can restart the stopped messages by clicking "Restart."


## 🛠 Example

Here’s an example of how the system works:

1. Add a token.


2. Schedule messages for channels with IDs: 123456789, 987654321


3. Assign messages: Hello World!, Welcome to the channel


4. Set interval to 60 seconds.



After starting, messages will be sent to each channel every 60 seconds, and the logs will update accordingly.

# 🛠️ Bug's to be fixed

• Stop/Restart button not working

# 🛠️ Features to be worked on

• Ability to send different messages to different channel id's
•Nickname's for each channel id

## DM mattmatt10. if you found a Bug!!! 🐛 

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.
