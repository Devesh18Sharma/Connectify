# 🌐 Connectify: Secure P2P Communication Platform

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=18S5N7p2FK08Ew_FX--WP9yH8baLKtB0-" alt="Connectify Banner" width="100%">
  
  <div>
     <img src="https://img.shields.io/badge/-Next.js-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="Next.js" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="TypeScript" />
    <img src="https://img.shields.io/badge/-WebRTC-black?style=for-the-badge&logoColor=white&logo=webrtc&color=333333" alt="WebRTC" />
    <img src="https://img.shields.io/badge/-Firebase-black?style=for-the-badge&logoColor=white&logo=firebase&color=FFCA28" alt="Firebase" />
  </div>

  <h3 align="center">Revolutionizing Peer-to-Peer Communication</h3>
</div>

## 📋 Table of Contents

1. [Introduction](#-introduction)
2. [Key Features](#-key-features)
3. [Tech Stack](#-tech-stack)
4. [Project Structure](#-project-structure)
5. [Quick Start](#-quick-start)
6. [Usage](#-usage)
7. [Contributing](#-contributing)
8. [License](#-license)

## 🚀 Introduction

Connectify is a cutting-edge web application that enables secure peer-to-peer communication and file sharing over WebRTC. Built with a focus on privacy and real-time interaction, Connectify offers a seamless platform for video calls, instant messaging, collaborative whiteboarding, and file sharing without intermediary servers.

## 🔑 Key Features

- 🔐 **Secure P2P Connection:** Utilizes WebRTC for direct, encrypted peer-to-peer communication
- 📹 **Video Calling:** High-quality, low-latency video calls between peers
- 💬 **Real-time Messaging:** Instant text communication with Firebase real-time database
- 🖼️ **Screen Sharing:** Share your screen or specific application windows
- 🗂️ **File Sharing:** Securely transfer files of any type directly between peers
- 🎨 **Collaborative Whiteboard:** Real-time drawing and ideation with peers
- 🔒 **Firebase Authentication:** Secure user authentication and management
- 🌓 **Responsive Design:** Seamless experience across devices and screen sizes

## ⚙️ Tech Stack

- **Frontend:** Next.js, TypeScript, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Real-time Communication:** WebRTC, Socket.io
- **Authentication & Database:** Firebase
- **State Management:** React Context API
- **UI Components:** Custom components with Tailwind CSS

## 📁 Project Structure

```bash
├── README.md
├── backend // Server Side Code
│   ├── package.json
│   ├── src
│   ├── tsconfig.json
│   └── yarn.lock
└── client // Client Code - Next.js
    ├── README.md
    ├── api
    ├── components
    ├── context
    ├── firebase
    ├── lottie
    ├── next-env.d.ts
    ├── next.config.js
    ├── package.json
    ├── pages
    ├── postcss.config.js
    ├── prettier.config.js
    ├── public
    ├── services
    ├── styles
    ├── tailwind.config.js
    ├── tsconfig.json
    ├── types
    ├── utils
    └── yarn.lock
```


## 🏁 Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/connectify.git
   cd connectify
2. Set up the client:
```bash
cd client
cp .env.example .env.local
# Add your Firebase config and other API keys to .env.local
yarn install
```

3. Set up the server:
```bash

Copy
cd ../backend
yarn install
```
4. Run the development servers:

   ```bash
   # In the client directory
   yarn dev

   # In the backend directory
   yarn start

5. Open http://localhost:3000 in your browser


- Add API keys to ```.env.local``` file such as Firebase API keys and server URL.
- yarn install in both client and server folder


## 💡 Usage

- **Authentication:** Sign up or log in using Firebase authentication.
- **Create or Join a Room:** Generate a unique room code or enter an existing one.
- **Video Call:** Start a video call with peers in the same room.
- **Messaging:** Use the chat feature for real-time text communication.
- **File Sharing:** Drag and drop files to share them securely with peers.
- **Whiteboard:** Collaborate on the interactive whiteboard for brainstorming.
- **Screen Sharing:** Share your screen or application window during calls.

## 🤝 Contributing

We welcome contributions to Connectify! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name

3. Make your changes and commit them:

   ```bash
   git commit -m 'Add some feature'


4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Submit a pull request.

## 🐞 Reporting Issues

If you encounter any issues, please report them by following these steps:

1. Open an issue on GitHub.
2. Provide a clear and descriptive title for the issue.
3. Describe the issue in detail, including steps to reproduce it, if applicable.
4. Include any relevant logs, screenshots, or other information that might help diagnose the problem.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

<div align="center">
  <h3>Connect with the Developer</h3>
  <a href="[https://twitter.com/yourtwitterhandle](https://x.com/devesh181002)" target="_blank">
    <img src="https://img.shields.io/badge/-Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter" />
  </a>
  <a href="[https://www.linkedin.com/in/yourlinkedinprofile/](https://www.linkedin.com/in/devesh-sharma-87242a14b/)" target="_blank">
    <img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="[https://github.com/yourgithubusername](https://github.com/Devesh18Sharma)" target="_blank">
    <img src="https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</div>
<div align="center">Made with ❤️ by Devesh Sharma</div>
