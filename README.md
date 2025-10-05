# 🕷️ Spider-Man DSA Coach

## Overview

Spider-Man DSA Coach is an interactive web application that helps users practice Data Structures and Algorithms (DSA) problems with a fun Spider-Man themed interface. The app features an AI-powered coaching system that provides personalized feedback, encouragement, and hints as you solve coding challenges.

## ✨ Features

### 🎯 Core Functionality
- **Interactive Code Editor**: Write and test code in multiple programming languages
- **Real-time Code Execution**: Run your code against predefined test cases
- **AI-Powered Coaching**: Get personalized feedback and hints from Spider-Man
- **Text-to-Speech**: Audio coaching messages with Spider-Man's voice
- **Problem Browser**: Browse through curated DSA problems
- **Multi-Language Support**: JavaScript, Python, and more

### 🔐 Authentication & Security
- Secure authentication via Auth0
- Protected routes and API endpoints
- User session management

### 🎨 User Interface
- Spider-Man themed design with custom animations
- Draggable Spider-Man character for interactive coaching
- Resizable panels for customizable workspace
- Responsive layout for different screen sizes
- Terminal output for test results and errors

### 📊 Code Analysis
- Complexity analysis and hints
- Data structure recommendations
- Performance metrics and execution time tracking

## 🛠️ Tech Stack

### Frontend
- **React** - UI framework
- **TypeScript** - Type-safe JavaScript
- **Auth0 React SDK** - Authentication
- **Tailwind CSS** - Styling
- **Vite** - Build tool and dev server

### Backend
- **Python** - Backend language
- **Flask/FastAPI** - Web framework
- **OpenAI/AI Services** - Coaching and code analysis
- **Text-to-Speech API** - Audio feedback

## 📁 Project Structure

```
HackUTA7/
├── spiderman-dsa-coach/
│   ├── frontend/
│   │   ├── src/
│   │   │   ├── components/
│   │   │   │   ├── CodeEditor.tsx
│   │   │   │   ├── ProblemPanel.tsx
│   │   │   │   ├── DraggableSpiderMan.tsx
│   │   │   │   ├── LanguageSelector.tsx
│   │   │   │   ├── TerminalOutput.tsx
│   │   │   │   └── QuestionsPage.tsx
│   │   │   ├── services/
│   │   │   │   └── api.ts
│   │   │   ├── data/
│   │   │   │   └── problems.ts
│   │   │   ├── App.tsx
│   │   │   └── main.tsx
│   │   └── package.json
│   └── backend/
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- Python 3.8+
- Auth0 account (for authentication)

### Frontend Setup

1. Navigate to the frontend directory:
```bash
cd spiderman-dsa-coach/frontend
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file with your Auth0 credentials:
```env
VITE_AUTH0_DOMAIN=your-auth0-domain
VITE_AUTH0_CLIENT_ID=your-client-id
VITE_AUTH0_AUDIENCE=your-api-audience
VITE_API_URL=http://localhost:5000
```

4. Start the development server:
```bash
npm run dev
```

### Backend Setup

1. Navigate to the backend directory:
```bash
cd spiderman-dsa-coach/backend
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Create a `.env` file with your API keys:
```env
OPENAI_API_KEY=your-openai-key
AUTH0_DOMAIN=your-auth0-domain
AUTH0_AUDIENCE=your-api-audience
```

5. Start the backend server:
```bash
python app.py
```

## 🎮 Usage

1. **Sign In**: Click the "Log in with Auth0" button to authenticate
2. **Browse Problems**: Click "Browse Problems" to view available DSA challenges
3. **Select a Problem**: Choose a problem from the list
4. **Write Code**: Use the code editor to write your solution
5. **Run Code**: Click the "Run" button to test your code against test cases
6. **Get Feedback**: Spider-Man will provide coaching feedback and hints
7. **Listen**: Audio feedback will play automatically (if enabled)

## 🎯 Features in Detail

### Code Execution
- Runs code against multiple test cases
- Provides detailed output for each test case
- Shows execution time and performance metrics
- Displays clear error messages for debugging

### AI Coaching
- Analyzes code complexity
- Suggests optimal data structures
- Provides encouragement and motivational messages
- Offers hints without giving away the solution

### Audio Feedback
- Text-to-speech conversion for coaching messages
- Audio caching for improved performance
- Queue management for multiple messages
- Automatic playback with user control

## 🤝 Contributing

This project was created for HackUTA7. Contributions, issues, and feature requests are welcome!

## 👥 Team

- [aarohCodes](https://github.com/aarohCodes)
- [ShaheemJ](https://github.com/ShaheemJ)
- Additional contributors from HackUTA7

## 📝 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- Built for HackUTA7 hackathon
- Inspired by Spider-Man and the friendly neighborhood hero spirit
- Thanks to the DSA community for problem inspiration

## 🐛 Known Issues

- Check the [Issues](https://github.com/aarohCodes/HackUTA7/issues) page for current bugs and feature requests

## 📞 Support

For questions or support, please open an issue on GitHub.

---

**Remember**: With great code comes great responsibility! 🕷️
