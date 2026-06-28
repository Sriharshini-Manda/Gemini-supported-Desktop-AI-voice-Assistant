# Gemini-Supported Desktop AI Voice Assistant

A lightweight, terminal-based productivity engine that leverages the Gemini API and advanced speech recognition to automate local system tasks, manage documents, and streamline desktop workflows via natural language voice commands.

---

## 🚀 Key Features & Capabilities

* **Intelligent System Automation:** Execute administrative actions, manage applications, and control local system processes directly from a lightweight terminal environment without switching windows.
* **Context-Aware File & Document Operations:** Seamlessly generate, read, and update text documents (`.txt`) and word processing files (`.docx`) dynamically based on voice requests.
* **Semantic Command Processing:** Powered by the Gemini API to handle abstract, multi-turn conversations and complex task execution, moving far beyond rigid regex keyword matching.
* **Fluid Workflow Integration:** Eliminate manual UI friction by offloading repetitive environment setups and system tasks to a non-intrusive background voice loop.

---

## 🛠️ Tech Stack & Frameworks

* **Core Runtime:** Python 3.x
* **LLM Engine:** Google Gemini API (Generative AI SDK)
* **Audio Telemetry:** SpeechRecognition & PyAudio
* **Document Automation:** Python-docx (for handling automated `.docx` configurations)

---

## 📂 Repository Workspace Structure

```text
├── main.py              # Primary application entry point & voice loop
├── requirements.txt     # Global dependency configuration file
├── *.docx               # Automated document templates (hello, age, information)
└── *.txt                # Structured local data text caches
