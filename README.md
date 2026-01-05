# AI Code Review
!![AI Code Review Banner](https://github.com/user-attachments/assets/0522cb3b-e118-4307-9d81-7cb5c8b94537)


## 📌 Overview
AI Code Review is a comprehensive web and mobile application designed to assist developers in reviewing code using advanced AI capabilities. It leverages the Gemini API to analyze code, provide intelligent suggestions, and enhance overall code quality through automated reviews.


## 📂 Project Structure
The project consists of three main components:

📌 **[FrontendWeb](./FrontendWeb)** (React) - A web-based interface for AI-powered code reviews.  
📌 **[FrontendApp](./FrontendApp)** (React Native Expo) - A mobile application for on-the-go code reviews.  
📌 **[Backend](./Backend)** (Node.js & Express) - A server handling API requests and integrating with Gemini API.  

## 🎯 Features
✅ AI-powered code analysis and suggestions  
✅ Web and mobile compatibility  
✅ Secure backend with Express.js  
✅ Integration with Gemini API for intelligent code reviews  
✅ Code quality metrics and reporting  
 

## 🛠 Tech Stack

### 🌐 Frontend Web (React)
- ⚛️ [React.js](https://reactjs.org/) - A JavaScript library for building user interfaces
- 🔗 [Axios](https://axios-http.com/) - For API requests
- 🎨 [Tailwind CSS](https://tailwindcss.com/) / [Material UI](https://mui.com/) (optional for styling)
- 📊 [React Charts](https://react-charts.tanstack.com/) - For data visualization

### 📱 Frontend App (React Native Expo)
- 📲 [React Native](https://reactnative.dev/) ([Expo](https://expo.dev/))
- 🔀 [React Navigation](https://reactnavigation.org/)
- 💾 [AsyncStorage](https://react-native-async-storage.github.io/async-storage/) for local storage
- 🎨 [Native Base](https://nativebase.io/) for UI components

### 🔧 Backend (Node.js & Express)
- 🟢 [Node.js](https://nodejs.org/)
- 🚀 [Express.js](https://expressjs.com/)
- 🤖 [Gemini API](https://ai.google.dev/gemini) integration
- 🔐 CORS & JWT authentication

## 📥 Installation

### Prerequisites
Ensure you have the following installed:
- 🖥 [Node.js](https://nodejs.org/) (v14+)
- 📦 [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- 🚀 [Expo CLI](https://docs.expo.dev/get-started/installation/) (for React Native app)

### 🔙 Backend Setup
```bash
cd Backend
npm install
# Configure environment variables
cp .env.example .env
# Edit .env with your Gemini API credentials
npm run dev
```

### 🌍 Web Frontend Setup
```bash
cd FrontendWeb
npm install
npm start
```

### 📱 Mobile Frontend Setup
```bash
cd FrontendApp
npm install
expo start
```

## 🌐 Website  
You can also access the web version of the app here: 

🔗 **[AI Code Review Website](https://ai-code-review-3sh7.vercel.app/)**  


## 📱 Mobile App Download
You can download the latest APK for Android devices from the following links:

- [Download Latest Release APK](https://drive.google.com/file/d/1gBNn-onMUi8X-Wv8kJINDcSJX2vSQJW9/view?usp=sharing)

Scan this QR code to download directly:

![APK QR Code](https://github.com/user-attachments/assets/f53b423f-40cc-499f-a149-921dbee8d1ae)



## 📸 Screenshots

### 🌐 Web Interface

[![Web Dashboard](https://github.com/user-attachments/assets/0547a023-c588-4dfa-930a-d9930e3d4845)](https://github.com/user-attachments/assets/0547a023-c588-4dfa-930a-d9930e3d4845)

### 📱 Mobile Interface

[![Mobile App](https://github.com/user-attachments/assets/39732c5e-34fa-408a-9bc4-8b7eb703403c)](https://github.com/user-attachments/assets/39732c5e-34fa-408a-9bc4-8b7eb703403c)

## 🚀 Usage

1. Start the backend server:
   ```bash
   cd Backend
   npm run start
   ```

2. Run the web or mobile frontend:
   - Web: `cd FrontendWeb && npm start`
   - Mobile: `cd FrontendApp && expo start`

3. Upload or paste your code into the application.

4. Select the review options and run the AI-powered analysis.

5. Review suggestions and implement changes as needed.

## 🛣️ Roadmap

- [ ] Add support for more languages
- [ ] Implement team collaboration features
- [ ] Create CI/CD integration
- [ ] Add code smell detection
- [ ] Develop vulnerability scanning

## 🤝 Contributing

We welcome contributions to AI Code Review! Please follow these steps:

1. [Fork the repository](https://github.com/abhishekgurjarin/ai-code-review/fork)
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add some amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. [Open a Pull Request](https://github.com/abhishekgurjarin/ai-code-review/pulls)

Please read our [Contributing Guidelines](./CONTRIBUTING.md) for more details.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## 📬 Contact

- **GitHub**: [@abhishekboadgurjar](https://github.com/abhishekgurjarin)
- **Project Link**: [https://github.com/abhishekboadgurjar/ai-code-review](https://github.com/abhishekgurjarin/ai-code-review)

## 🙏 Acknowledgements

- [Gemini API](https://ai.google.dev/gemini) for providing the AI capabilities
- [React](https://reactjs.org/) and [React Native](https://reactnative.dev/) communities
- All contributors who have helped shape this project
