
# Claude Computer Use Demo

A Streamlit-based web application that demonstrates Claude's computer control capabilities through a user-friendly interface.

## Overview

This project showcases Claude's ability to interact with a computer environment through:
- Screen interaction and screenshots
- Keyboard and mouse control
- File system operations
- Shell command execution
- Browser automation with Firefox

## Getting Started

1. Fork this project on Replit
2. Add your `ANTHROPIC_API_KEY` to the Secrets pane in Replit
3. Click "Run" to start the application
4. Access the web interface through the Webview pane

## Features

- **Interactive Web Interface**: Built with Streamlit for easy interaction
- **Multiple Tool Support**:
  - Computer Tool: Screen, keyboard, and mouse control
  - Bash Tool: Shell command execution
  - Edit Tool: File system operations
- **Security Features**:
  - Runs in isolated Replit environment
  - Built-in security warnings
  - Environment variable management
- **API Provider Support**:
  - Direct Anthropic API
  - Amazon Bedrock
  - Google Vertex AI

## Usage

1. The interface shows a chat window where you can send commands to Claude
2. Claude will interpret your commands and execute them using the available tools
3. Results, including screenshots and command outputs, are displayed in the chat
4. HTTP exchange logs are available in a separate tab

## Configuration Options

- Model selection
- Screenshot history control
- Custom system prompt configuration
- Option to hide screenshots
- Reset functionality

## Security Considerations

⚠️ **Important Security Notes:**
- Never provide access to sensitive accounts or data
- Be cautious with web content as it may affect Claude's behavior
- Review all actions before execution
- Monitor tool outputs carefully

## Project Structure

```
├── computer_use_demo/
│   ├── tools/         # Tool implementations
│   ├── loop.py        # Main agent loop
│   └── streamlit.py   # Web interface
├── main.py            # Entry point
└── pyproject.toml     # Project configuration
```

## Technical Requirements

- Python 3.10+
- Key dependencies:
  - anthropic
  - streamlit
  - typing-extensions

## Credits

Based on Anthropic's computer-use-demo, adapted for Replit environment.
