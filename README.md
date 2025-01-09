# Gemini Clone App

The Gemini Clone App is a conversational AI interface powered by Google Generative AI, allowing users to ask questions and receive intelligent responses in an intuitive, interactive environment.

## Features

- **Responsive Design**: Optimized for seamless interaction on any device.
- **Interactive Interface**:
  - Prompt-based querying with dynamic response rendering.
  - Predefined example prompts for inspiration.
- **Real-time Feedback**:
  - Typing animation for responses.
  - Highlights in bold for emphasized content.
- **Modular Architecture**:
  - Reusable components like `Main`, `Context`, and more.
  - Context-based state management for efficient updates.

---

### Key Files

1. **Main Component**:
   - Renders the main user interface, including:
     - Greeting and prompt cards.
     - Response viewer with typing animation.
     - Input box for prompts.

2. **Context**:
   - Centralized state management using React Context API.
   - Handles input, API calls, and dynamic response updates.

3. **Google Generative AI Configuration**:
   - Integrates with Google Gemini API for advanced conversational AI.
   - Contains API key and model settings.

---

## Installation

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/ngocmaruko/gemini.git
   ```

2. Navigate to the project directory:
   ```bash
   cd gemini
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to:
   ```
   http://localhost:5173
   ```

---

## Usage

- Enter a prompt in the input box to start a conversation.
- Select predefined cards for quick queries.
- Responses are displayed dynamically with formatting and animation.

---

## Technology Stack

- **Frontend**: React.js, CSS
- **Backend**: Google Generative AI (API integration)
- **State Management**: React Context API

---

## Future Enhancements

- **User Authentication**: Add login/signup functionality.
- **Enhanced Response Formatting**: Support for markdown or rich text.
- **Backend Integration**: Persist user history and preferences.

---
