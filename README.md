# ChatGPT for Windows

Desktop ChatGPT application for Windows operating system.

Large Language Model based AI is useful for quick access to artificial intelligence capabilities directly from your desktop. ChatGPT for Windows is a tool to bring AI conversations to your native Windows environment without the need for browser-based interactions.

It works great with various AI providers including OpenAI, and allows seamless switching between different models for optimal results.

### Installation

Use a package manager:

```bash
# Windows (with Winget)
winget install ChatGPT.Desktop

# Windows (with Chocolatey)
choco install chatgpt-desktop

# Scoop
scoop install chatgpt-desktop
```

Or, download it:

- Last release are available in MSI and portable formats
- Binaries are available for Windows x64 and ARM64

System Requirements:

```bash
# Windows 10/11 (64-bit)
# .NET Framework 4.7.2 or higher
# 512 MB free disk space
# Internet connection
```

## What Can It Do?

ChatGPT for Windows works as a native desktop client that provides seamless access to AI conversations. You can send text prompts and receive responses in real-time, with support for conversation history and customizable parameters.

The application offers quick access to ChatGPT, conversation management, model selection, and export capabilities in various formats including Markdown, plain text, and JSON.

## Saved Conversations

Conversations are saved locally by default. Each conversation has a unique identifier and title for easy navigation and reference.

Conversation history allows you to continue previous discussions, review past interactions, and organize your AI conversations efficiently.

## Usage

- `-m`, `--model`: Specify AI model to use
- `-t`, `--temperature`: Set response creativity level  
- `-s`, `--system`: Set system prompt for the conversation
- `-f`, `--format`: Format response output
- `--max-tokens`: Specify maximum response length
- `--save`: Save conversation to history
- `--export`: Export conversation to file
- `--theme`: Set application theme (light, dark, auto)
- `--settings`: Open application settings

#### Conversations

- `--new`: Start new conversation
- `--list`: List saved conversations
- `--continue`: Continue specific conversation
- `--delete`: Delete saved conversations
- `--clear`: Clear conversation history

#### Advanced

- `--api-key`: Set API key for AI provider
- `--endpoint`: Custom API endpoint
- `--proxy`: Use HTTP proxy for connections
- `--timeout`: Set request timeout
- `--retries`: Maximum number of retries

## Custom Prompts

You can create custom system prompts for different use cases:

```yaml
prompts:
  coding:
    - you are a coding assistant
    - provide clean, efficient code solutions
    - include brief explanations when helpful
  writing:
    - you are a writing assistant
    - help improve text clarity and style
    - maintain the original tone and intent
```

Then, use custom prompts in the application through the settings panel or command line interface.

## Setup

### OpenAI

The application uses GPT-4 by default with fallback to GPT-3.5 Turbo.

Set the `OPENAI_API_KEY` environment variable or configure it through the settings panel. You can get your API key from the OpenAI platform.

### Other Providers

The application supports multiple AI providers through compatible API endpoints. Configure your preferred provider through the settings panel with the appropriate API key and endpoint URL.

## Features

- Native Windows application with system tray integration
- Multiple AI provider support
- Conversation history and management
- Export conversations in multiple formats
- Customizable themes and appearance
- Keyboard shortcuts for quick access
- Offline conversation storage
- Auto-save functionality
- Search through conversation history
- Custom system prompts and templates

## Contributing

Contributions are welcome! Please read the contributing guidelines before submitting pull requests.

## License

MIT License - see LICENSE file for details.

---

Made with ❤️ for Windows users.
