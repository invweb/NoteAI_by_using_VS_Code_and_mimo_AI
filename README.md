# NoteAI

Cross-platform notes application with AI-powered features using Ollama.

## Screenshots

| Notes List | Note Editor |
|------------|-------------|
| ![Notes List](screenshots/notes_list.png) | ![Note Editor](screenshots/note_editor.png) |

| AI Summarize | AI Tag Suggestions |
|--------------|---------------------|
| ![AI Summarize](screenshots/ai_summarize.png) | ![AI Tags](screenshots/ai_tags.png) |

## Features

- Create and edit notes
- AI-powered summarization
- AI-powered tag suggestions
- Persistent storage (notes saved locally)
- Desktop (Windows, macOS, Linux) support
- Android support

## Requirements

- JDK 17+
- Ollama running locally on port 11434

## Setup

1. Install Ollama: https://ollama.com
2. Pull a model: `ollama pull deepseek-r1`
3. Run the application: `gradle :desktopApp:run`

## Tech Stack

- Kotlin Multiplatform
- Compose Multiplatform
- Ollama (local AI)
- Ktor (HTTP client)
