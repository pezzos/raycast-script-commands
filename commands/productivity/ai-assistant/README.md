# AI Assistant Scripts Collection

## About the Author
[Alexandre Pezzotta](https://github.com/pezzos) - Software Engineer passionate about AI and automation. Feel free to check out my other projects on GitHub!

## Overview
This collection of Raycast scripts provides powerful AI-powered tools to enhance your productivity and text processing capabilities. Each script is designed to be easily accessible through Raycast and leverages OpenAI's advanced language models.

## Scripts Description

### 1. Text Insight Generator (`text-insight-generator.js`)
A versatile tool for analyzing text in multiple ways:
- **Features:**
  - Detailed explanation
  - Concise summary
  - Simplified explanation (ELI8)
  - Key points extraction
  - To-Do list generation
  - Translation
  - Pattern & insight discovery
  - Question generation
  - Mind map creation
- **Usage:**
  1. Select text in any application
  2. Trigger the command through Raycast
  3. Choose analysis type from dropdown
  4. View formatted results

### 2. Summarize Page (`summarize-page.js`)
Quickly generate summaries of web pages or selected text:
- Supports multiple browser selections (Safari, Chrome, Arc)
- Provides concise, readable summaries
- Maintains key information while reducing length

### 3. Improve Text (`improve-text.js`)
Enhance your writing with AI-powered suggestions:
- Grammar and style improvements
- Tone adjustment
- Clarity enhancement
- Professional formatting

### 4. Dictate (`dictate.js` & `dictate-key.js`)
Voice-to-text tools for efficient text input:
- Real-time speech recognition
- Support for multiple languages
- Keyboard shortcut integration

### 5. Translate (`translate.js`)
Quick and accurate text translation:
- Support for multiple languages
- Maintains formatting
- Context-aware translations

## Setup Instructions

1. Install Dependencies:
   ```bash
   npm install
   ```

2. Configure Environment:
   - Copy `.env.example` to `.env`
   - Add your OpenAI API key:
     ```
     OPENAI_API_KEY=sk-your-api-key
     DEFAULT_LANG=fr    # Optional: Default language for translations
     ```

## Example Usage

### Text Insight Generator
```bash
# Select text and use Raycast command
# Example output:
Original Text:
[Your selected text]

Analysis:
[AI-generated insights]
```

### Translation
```bash
# Select text and use Raycast command
# Example output:
Original (English):
Hello, world!

Translated (French):
Bonjour, monde!
```

## Tips
- Use keyboard shortcuts in Raycast for quick access
- Combine scripts for maximum productivity
- Customize language settings in `.env` file
- Check the logs (*.log files) for troubleshooting

## Contributing
Feel free to submit issues and enhancement requests!
