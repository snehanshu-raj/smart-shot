# Chrome Extension for Screenshot and AI Analysis

## Overview

**Smart-Shot AI** is a Chrome extension that democratizes AI-powered screen analysis. The tool captures any screen content and leverages Google Gemini's multimodal capabilities to provide instant explanations, translations, code analysis, visual descriptions, and more.

Perfect for **students, developers, researchers, and professionals** who need quick AI assistance with visual content.

## ✨ Key Features

### 🔍 **Universal Screen Analysis**

- **Text Content**: Explanations, summaries, and translations
- **Code Analysis**: Debug errors, explain algorithms, review syntax
- **Visual Content**: Describe images, diagrams, charts, and UI elements
- **Academic Support**: Solve math problems, explain formulas, analyze graphs
- **Language Translation**: Instant translation of foreign text
- **Documentation**: Extract and explain technical documentation


### 🚀 **Core Functionality**

- **One-Click Screenshots**: Capture any visible screen content
- **AI-Powered Analysis**: Powered by Google Gemini's advanced vision capabilities
- **Custom Prompts**: Ask specific questions about captured content
- **Instant Results**: Get explanations directly in the popup interface
- **Privacy-Focused**: Screenshots processed securely through Google's API


## 🛠️ Installation

### Prerequisites

- Google Chrome browser
- Google Gemini API key ([Get one here](https://makersuite.google.com/app/apikey))


### Setup Instructions

1. **Clone the repository:**

```bash
git clone https://github.com/snehanshu-raj/smart-shot.git
```

2. **Navigate to the project directory:**

```bash
cd chrome-extensions/smart-shot
```

3. **Configure API credentials:**
    - Create a `config.js` file inside `src/popup/`
    - Add your Google Gemini API key:

```javascript
const CONFIG = {
    API_KEY: "YOUR_GEMINI_API_KEY_HERE"
};
```

4. **Load the extension in Chrome:**
    - Open Chrome and navigate to `chrome://extensions/`
    - Enable **"Developer mode"** toggle (top right)
    - Click **"Load unpacked"** and select the `src` directory
    - The extension icon should appear in your toolbar

## 📱 Usage Guide

### Basic Workflow

1. **Activate Extension**: Click the SmartShot AI icon in your Chrome toolbar
2. **Enter Your Question**: Type your question or request in the input field
    - Examples: "Explain this code", "Translate this text", "What does this diagram show?"
3. **Capture Screen**: Click the **"Snap"** button to take a screenshot
4. **Get AI Response**: View the detailed analysis in the popup interface

### Example Use Cases

| Scenario | Input Prompt | Expected Output |
| :-- | :-- | :-- |
| Code Debugging | "What's wrong with this JavaScript code?" | Error identification and fixes |
| Language Learning | "Translate this text to English" | Accurate translation with context |
| Academic Study | "Explain this mathematical formula" | Step-by-step breakdown |
| Design Review | "Describe the UI elements in this interface" | Detailed interface analysis |


## 🚀 Future Enhancements

- [ ] Support for multiple AI models (Claude, GPT-4V)
- [ ] Batch processing of multiple screenshots
- [ ] History of previous analyses
- [ ] Export responses to various formats
- [ ] Keyboard shortcuts for quick capture
- [ ] Custom prompt templates

