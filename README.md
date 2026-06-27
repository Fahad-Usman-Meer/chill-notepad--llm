# Chill-Notebook++LLM 📓✨

A modern, standalone, fully-functional AI workspace packed into a single HTML file. Chill-Notebook++LLM features a premium, Framer-inspired "Chill" aesthetic and brings together PDF viewing, AI chat, workflow mind-mapping, and presentation generation in one seamless experience.

## ✨ Features

- **Zero Setup:** No `npm install`, no build steps, no backend. Just double-click the `.html` file and start working!
- **Bring Your Own Key (BYOK):** Connect securely to **Gemini 3.1 Flash-Lite** or **ChatGPT**. Keys are kept locally in your browser session.
- **Multilingual & RTL Support:** Fully hardcoded translations for English, Hindi, and Arabic (with automatic Right-to-Left layout switching).
- **Light/Dark Mode:** Instantly switch between a crisp light theme and a deep, immersive dark theme.
- **Three Core Workspaces:**
  - 📄 **PDF Viewer:** Upload up to 5 PDFs (max 3MB each). Read, zoom, and navigate them right in the browser using `pdf.js`.
  - 🗺️ **Workflow (Mind-maps):** Ask the AI to summarize your PDF into a workflow. Generates a draggable, interactive mind-map that can be exported as a PNG.
  - 📽️ **Presentation:** Automatically generate slide decks from your documents. Edit slide text inline and export the final deck directly to a PDF.
- **AI Chat Assistant:** A dedicated side-panel to chat with the AI about your uploaded documents or general queries.

## 🚀 How to Use

1. **Open the App:** Double click `Chill-Notebook++LLM.html` to open it in any modern web browser (Chrome, Edge, Firefox, Safari).
2. **Enter API Key:** In the top right corner, select your preferred AI provider (Gemini or ChatGPT) and paste your API key. 
3. **Upload a Document:** Drag & drop a PDF into the left sidebar (or click to browse).
4. **Choose a Tab:**
   - Use the **PDF Viewer** to read through your file.
   - Go to the **Workflow** tab, type a prompt (e.g., *"Create a roadmap of chapter 2"*), and click **Generate Mind-map**.
   - Go to the **Presentation** tab, type a prompt (e.g., *"Summarize the main arguments"*), and click **Generate Presentation**.
5. **Chat:** Use the right sidebar to talk directly with the AI about the contents of your PDF.

## 🔒 Privacy & Security

- **Client-Side Only:** This application has no backend server. 
- **API Keys:** Your API keys are strictly used within your local browser memory to make direct requests to Google or OpenAI. They are **never** stored on an external server.
- **Document Data:** PDF text is extracted locally in your browser and only sent directly to the AI provider you select for processing.

## 🛠️ Technical Details

- **Tech Stack:** Vanilla HTML5, CSS3, JavaScript (ES6+).
- **External Dependencies (CDNs only):** 
  - [PDF.js](https://mozilla.github.io/pdf.js/) for client-side PDF rendering and text extraction.
  - Google Fonts (`Inter` and `Cairo`).
