# 🎙️ AI Podcast Generator using n8n & LLMs

An AI-powered podcast generation system that transforms a simple user topic into a complete podcast script and realistic voice narration using Large Language Models (LLMs) and Text-to-Speech technology.

Built with n8n automation, Google Gemini, and Murf AI, this workflow automates the entire podcast creation process from idea to audio.

---

## 🚀 Features

* AI-generated podcast scripts
* Realistic voice narration using Text-to-Speech
* Automated workflow with n8n
* Chat-based podcast topic input
* End-to-end podcast creation
* Downloadable audio output
* Fully automated content generation pipeline

---

## 🧠 Architecture

```text
User Input
     │
     ▼
Google Gemini (LLM)
     │
     ▼
Podcast Script Generation
     │
     ▼
Murf AI Text-to-Speech
     │
     ▼
Audio Generation
     │
     ▼
Podcast Output (.mp3)
```

---

## 🛠 Tech Stack

* n8n
* Google Gemini
* Murf AI
* REST APIs
* JavaScript (n8n Expressions)
* JSON Workflows

---

## 📸 Workflow Architecture

### 🔄 n8n Workflow

![Workflow Architecture](https://github.com/Harish-Uta17/AI-Podcast-Generator/blob/main/docs/architecture.png?raw=true)


---

## 🎥 How It Works

1. User provides a podcast topic through chat.
2. Google Gemini generates a structured podcast script.
3. The generated script is sent to Murf AI.
4. Murf AI converts the script into realistic speech.
5. The final podcast audio file is generated automatically.
6. Users can download and share the generated podcast.

---

## 🔄 Workflow Explanation

### Step 1: Topic Input

The user submits a podcast topic through the chat interface.

### Step 2: Script Generation

Google Gemini analyzes the topic and creates a structured podcast script containing:

* Introduction
* Main discussion points
* Key insights
* Conclusion

### Step 3: Text-to-Speech Conversion

The generated script is sent to Murf AI, which converts the text into high-quality speech.

### Step 4: Audio Generation

The final podcast audio file is created automatically and made available for download.

---

## 🎧 Sample Podcast Output

This project generates podcast audio files automatically.

Example output location:

```text
output/sample_podcast.mp3
```

The audio file contains:

* AI-generated content
* Natural voice narration
* Structured podcast format

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Harish-Uta17/AI-Podcast-Generator.git
cd AI-Podcast-Generator
```

### 2. Install n8n

Install and start n8n on your local machine or server.

### 3. Import Workflow

Import the workflow JSON file into n8n.

### 4. Configure API Credentials

Add the required credentials:

* Google Gemini API Key
* Murf AI API Key

### 5. Configure Environment Variables

Store your API credentials securely using environment variables.

### 6. Run the Workflow

Trigger the workflow and provide a podcast topic.

Example:

```text
The Future of Artificial Intelligence
```

The workflow will automatically generate a podcast script and audio file.

---

## 📂 Project Structure

```text
AI-Podcast-Generator/
│
├── workflow/
│   └── AI Podcast Generator.json
│
├── docs/
│   └── architecture.png
│
├── output/
│   └── sample_podcast.mp3
│
├── README.md
│
└── .env.example
```

---

## 🎯 Use Cases

* Automated Podcast Creation
* AI Content Production
* Educational Audio Content
* Marketing & Brand Podcasts
* Voice-Based Knowledge Sharing
* AI Media Automation

---

## 🌟 Key Benefits

* Eliminates manual script writing
* Generates professional podcast content
* Creates realistic AI voice narration
* Reduces content production time
* Easy to customize and scale
* Fully automated workflow

---

## 📈 Future Enhancements

* Multiple speaker support
* Multi-language podcast generation
* Background music integration
* Voice customization
* Cloud deployment
* Podcast publishing automation
* RSS feed generation

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Harish Uta**

B.Tech – Data Science | AI Automation Engineer

GitHub: https://github.com/Harish-Uta17

---

## ⭐ Support

If you found this project useful, please consider giving it a **Star ⭐** on GitHub.
