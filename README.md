**💬 Chat App (React Native Project)**

**Description**

This is a simple Chat Application built using **React Native**.
It is designed as a class project to understand how a basic messaging system works in mobile apps.
The app allows a user to send messages and receive a fake automated reply. It demonstrates how chat interfaces work like real messaging apps such as WhatsApp or ChatGPT (UI only).

**🎯 Project Purpose**

The purpose of this project is to learn:

* How to build a chat UI in React Native
* How to use `useState` for managing messages
* How to handle user input and events
* How to dynamically update the UI
* How simple AI-like responses can be simulated

**✨ Features**
* Simple Chat UI (User & AI messages)
* Message input box
* Send message functionality
* Auto fake reply from system
* Scrollable chat area
* Dark theme UI design
* Responsive message bubbles

**🧠 How It Works**

* Messages are stored in an array using `useState`
* When user types a message and presses send:
* Message is added to chat
* Input field clears automatically
* After 0.8 seconds, a fake AI reply is added using `setTimeout`
* Messages are displayed dynamically using `map()`

 **🛠️ Technologies Used**

* React Native
* JavaScript (ES6)
* React Hooks (`useState`)
* Functional Components

**🚀 How to Run Project**

```bash
npm install
npx react-native run-android
```

If using Expo:

```bash
npx expo start
```

**📱 UI Design**

* Dark themed chat interface
* User messages aligned right
* AI messages aligned left
* Rounded message bubbles
* Simple modern layout

**👨‍💻 Author**
Ajmal Ali
