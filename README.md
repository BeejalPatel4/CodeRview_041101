# CodeRview_041101
A Code Review that show what in code mistakes
.

🧠 Code Review Interface
A sleek, modular React application that allows users to write JavaScript code, submit it for AI-powered review, and receive syntax-highlighted feedback in Markdown format. Built for developers who value clarity, expressiveness, and seamless UX.

🚀 Features
✍️ Live Code Editor powered by react-simple-code-editor

🎨 Syntax Highlighting via PrismJS and highlight.js

🤖 AI Review Integration with a backend endpoint

📄 Markdown Rendering for readable, styled feedback

🧩 Modular Layout with intuitive left/right panel design

📦 Tech Stack
Layer	Library / Tool
Frontend	React, Vite
Editor	react-simple-code-editor
Highlighting	prismjs, highlight.js, rehype-highlight
Markdown	react-markdown
Styling	CSS (App.css)
Backend API	Axios POST to /ai/get-response
🛠️ Setup Instructions
1. Clone the Repository
bash
git clone https://github.com/your-username/code-review-interface.git
cd code-review-interface
2. Install Dependencies
bash
npm install
3. Start the Development Server
bash
npm run dev
4. Backend Endpoint
Ensure your backend is running locally and listening at:

🧪 Usage
Type or paste JavaScript code into the editor.

Click the Review button.

View AI-generated feedback in the right panel, rendered with syntax highlighting.

🎨 Customization
Themes: Swap prism-tomorrow.css or github-dark.css for other styles.

Languages: Extend prism.highlight() to support more languages.

Editor Styling: Modify padding, font, and borders in the inline style prop.

