<div align="center">
  <img src="media/logo.png" alt="Git AI Committer Logo" width="100">
  
  # Git AI Committer
  
  ### AI-powered automatic commit message generation and committing
</div>

[![Version](https://img.shields.io/badge/version-0.1.6-blue.svg)](https://github.com/DraconDev/git-ai-committer)

Git AI Committer is a VS Code extension that automatically generates meaningful commit messages using Google's Gemini AI. It helps developers maintain a clean and descriptive git history without the hassle of writing commit messages manually.

> Developed by [DraconDev](https://github.com/DraconDev)

## Features

-   Automatically generates commit messages based on your code changes
-   Uses Google's Gemini AI for intelligent message generation
-   Configurable auto-commit intervals
-   Manual commit generation option
-   Inactivity-based commit triggers

## Requirements

-   VS Code 1.96.0 or higher
-   Node.js 20.x or higher
-   A Google Gemini API key (get it from [Google AI Studio](https://aistudio.google.com/apikey))
-   Git repository with initialized git config

## Extension Settings

This extension contributes the following settings:

-   `gitAiCommitter.enabled`: Enable/disable automatic commits (default: true)
-   `gitAiCommitter.geminiApiKey`: Your Google Gemini API key for generating commit messages
-   `gitAiCommitter.commitInterval`: Interval in seconds between automatic commits (0 to disable, default: 60)
-   `gitAiCommitter.inactivityTimeout`: Trigger commit after this many seconds of inactivity (0 to disable, default: 10)

## How to Use

1. Install the extension
2. Get your Gemini API key from [Google AI Studio](https://makersuite.google.com/app/apikey)
3. Set your API key in VS Code settings
4. Enable auto-commit using the command palette or settings
5. Start coding! The extension will automatically generate commit messages and commit your changes

## Commands

Available commands can be accessed through the Command Palette (Ctrl+Shift+P):

-   `AI Auto Committer Enable Auto Commit`: Enables automatic commit generation
-   `AI Auto Committer Disable Auto Commit`: Disables automatic commit generation
-   `AI Auto Committer Commit Now`: Manually triggers commit message generation and commits changes
-   `AI Auto Committer Set Gemini API Key`: Set your Gemini API key
-   `AI Auto Committer Set Commit Interval`: Configure automatic commit interval
-   `AI Auto Committer Set Inactivity Delay`: Configure inactivity delay before commit

## Release Notes

### 0.1.6

-   Added command to set Gemini API key directly
-   Added command to configure commit interval
-   Added command to configure inactivity delay
-   Improved error handling for API requests
-   Added default values for settings

### 0.0.1

Initial release of Git AI Committer:

-   Basic auto-commit functionality
-   Gemini AI integration
-   Configurable commit intervals
-   Manual commit option

---

## Following extension guidelines

Ensure that you've read through the extensions guidelines and follow the best practices for creating your extension.

-   [Extension Guidelines](https://code.visualstudio.com/api/references/extension-guidelines)

## Working with Markdown

You can author your README using Visual Studio Code. Here are some useful editor keyboard shortcuts:

-   Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux).
-   Toggle preview (`Shift+Cmd+V` on macOS or `Shift+Ctrl+V` on Windows and Linux).
-   Press `Ctrl+Space` (Windows, Linux, macOS) to see a list of Markdown snippets.

## For more information

-   [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
-   [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

## Contributing

Contributions are welcome! Please read our [contributing guidelines](https://github.com/DraconDev/git-ai-committer/blob/main/CONTRIBUTING.md) before submitting pull requests.

**Enjoy!!!**
