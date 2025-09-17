#Project Evolution: Dyslexiview 2.0 ✨
This project has been fundamentally transformed from a simple learning aid into a feature-rich, interactive web application. It's built from the ground up to help users improve reading and writing skills through a series of engaging, AI-powered games.

#Key Features & Additions 🎮
User Login & Progress Tracking: A new login page has been added to save user sessions and track progress directly in the browser using Local Storage.

#Three Interactive Game Levels:

Level 1 (Word Listen): Uses the Web Speech API for text-to-speech, challenging users to identify spoken words.

Level 2 (Color Challenge): Implements Speech Recognition to test cognitive skills and attention.

Level 3 (Write Letters): Features a Canvas drawing board where a TensorFlow.js model provides real-time feedback on handwritten letters.

Reading Helper Tool: Allows users to upload images or PDFs and uses Tesseract.js (OCR) and pdfjs-dist to extract text, making it easier to read.

#Technical Architecture & Stack 🛠️
The application is built as a modern Single-Page Application (SPA) using a client-side architecture.

#Core Frontend Stack:

Framework: React with TypeScript for a robust, component-based structure.

Build Tool: Vite for a fast and modern development experience.

UI/Styling: Tailwind CSS and shadcn/ui for a responsive, modern, and accessible design.

Browser-Based AI & Machine Learning:

Handwriting Recognition: A pre-trained TensorFlow.js (CNN) model runs in the browser to analyze drawings on the Canvas.

Optical Character Recognition (OCR): Tesseract.js is used to extract text from images on the client side.

#State & Session Management:

Custom React Hooks (useGameState) are used to manage the application's global state.

Local Storage is leveraged for data persistence, saving user sessions and game progress without needing a backend database.