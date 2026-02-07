## 🔄 Workflow Explanation

The AI Podcast Generator is an event-driven automation workflow built using n8n.  
It transforms user-provided input into a complete podcast audio output by combining
LLM-based script generation with text-to-speech conversion.

---

### Step 1: Chat Trigger – User Input
- The workflow is initiated when a user sends a chat message containing a podcast topic or idea.
- This message serves as the primary input and triggers the automation pipeline.

**Purpose:** Enables real-time interaction and dynamic content generation.

---

### Step 2: Podcast Script Generation (LLM Processing)
- The chat input is passed to the Podcast Script Generator node.
- This node uses a Large Language Model (Google Gemini) to generate a structured podcast script.
- The generated script typically includes:
  - Introduction
  - Main discussion points
  - Conclusion
  - Natural conversational flow

**Purpose:** Demonstrates prompt engineering and AI-driven content creation.

---

### Step 3: LLM Model Integration
- The workflow integrates the Google Gemini Chat Model as the underlying AI engine.
- The model processes the user input and returns a context-aware, coherent podcast script.

**Purpose:** Enables intelligent text generation using modern LLM capabilities.

---

### Step 4: Text-to-Speech Conversion (Murf API)
- The generated podcast script is sent to the Murf Text-to-Speech API.
- The API converts the text into a realistic voice-based audio output.
- Voice attributes such as tone, speed, and language can be customized.

**Purpose:** Converts AI-generated text into production-ready audio content.

---

### Step 5: Final Output
- The workflow produces a podcast-ready audio file as the final output.
- The audio can be streamed, downloaded, or further processed for publishing.

**Purpose:** Completes the end-to-end automation from text input to audio output.

---

## 🔁 Data Flow Summary


User Chat Input → LLM Script Generation → Text-to-Speech API → Podcast Audio Output


## 🧠 Key Concepts Demonstrated
- Event-driven workflow automation
- Prompt engineering for structured content
- Large Language Model (LLM) integration
- REST API consumption
- AI-powered media generation

---

## 📈 Scalability & Future Enhancements
- Support for multiple speakers
- Multi-language podcast generation
- Background music integration
- Cloud deployment
- Automated publishing to podcast platforms
