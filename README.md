# Agentic Project for YouTube and Gmail

## Overview
This repository contains the source code for an agentic application designed to seamlessly integrate YouTube media controls and Gmail automation. By utilizing LLM-driven architectures, the project automates email content generation and drafting while providing a unified web interface that includes a custom YouTube player.

## Core Modules & Features
### Gmail Agent (app/gmail/):
gmail_gen.py: Leverages conversational AI and LLMs to generate intelligent email responses and automated drafts based on user prompts.

gmail_write.py: Handles the backend communication with the Gmail API to securely write, save, or send the generated emails.

### YouTube Integration (app/youtube/):
player.py: Manages YouTube video playback, providing custom programmatic controls or API interactions for media within the application.

### Web Interface (app/templates/):
index.html: The central UI that connects the backend agents, allowing users to interact with both the email generator and the video player in one place.

## Project Structure

```text
app/
├── __init__.py
├── gmail/
│   ├── __init__.py
│   ├── gmail_gen.py      # Module for generating context-aware email content 
│   └── gmail_write.py    # Interfaces with Gmail API for drafting and sending
├── templates/
│   └── index.html        # Main front-end web interface
└── youtube/
    ├── __init__.py
    └── player.py         # YouTube playback management and controls
```
