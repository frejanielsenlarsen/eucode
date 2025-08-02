<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=kilocode.Kilo-Code"><img src="https://img.shields.io/visual-studio-marketplace/v/kilocode.Kilo-Code.svg?label=VS%20Code%20Marketplace" alt="VS Code Marketplace"></a>
  <!--<a href="https://marketplace.visualstudio.com/items?itemName=kilocode.Kilo-Code"><img src="https://img.shields.io/badge/Get%20$20%20of%20free%20tokens-green?logo=claude&logoColor=white" alt="Get $20 of tokens for free"></a>-->
  <a href="https://x.com/kilo_code"><img src="https://img.shields.io/twitter/follow/kilo_code?style=flat&logo=x&color=555" alt="X (Twitter)"></a>
  <a href="https://blog.kilocode.ai"><img src="https://img.shields.io/badge/Blog-555?style=flat&logo=substack&logoColor=white" alt="Substack Blog"></a>
  <a href="https://kilocode.ai/discord"><img src="https://img.shields.io/discord/1349288496988160052?style=flat&logo=discord&logoColor=white" alt="Discord"></a>
  <a href="https://www.reddit.com/r/kilocode/"><img src="https://img.shields.io/reddit/subreddit-subscribers/kilocode?style=flat&logo=reddit&logoColor=white" alt="Reddit"></a>
</p>

# 🚀 EU Code

> Lightweight VS Code AI agent. A stripped-down fork of [Kilo Code](https://github.com/Kilo-Org/kilocode) with bloat removed for a clean, focused development experience.

- ✨ Generate code from natural language
- ✅ Checks its own work  
- 🧪 Run terminal commands
- 🌐 Automate the browser
- 🤖 Latest AI models
- 🎯 **Lightweight and focused** - Bloat removed for better performance

<p align="center">
  <img src="https://raw.githubusercontent.com/Kilo-Org/kilocode/refs/heads/main/kilo.gif" width="100%" />
</p>

- [VS Code Marketplace](https://kilocode.ai/vscode-marketplace?utm_source=Readme) (download)
- [Official KiloCode.ai Home page](https://kilocode.ai) (learn more)

## Key Features

- **Code Generation:** Generate code using natural language.
- **Task Automation:** Automate repetitive coding tasks.
- **Automated Refactoring:** Refactor and improve existing code.
- **MCP Server Marketplace**: Easily find, and use MCP servers to extend the agent capabilities.
- **Multi Mode**: Plan with Architect, Code with Coder, and Debug with Debugger, and make your own custom modes.

## What's Been Removed

This lightweight fork removes the following bloat components while maintaining all core functionality:

- **Web applications** (1.4MB+) - Separate web interfaces not needed for VS Code extension
- **Evaluation infrastructure** (312KB) - Testing/benchmarking tools for development
- **Development tooling** (716KB) - E2E testing, Storybook documentation
- **Large demo assets** (13.5MB) - Promotional GIFs and videos
- **Development artifacts** - Test files, changeset configs, deployment files

**Result**: ~16MB+ reduction in source code size while maintaining full VS Code extension functionality.

## How to get started with EU Code

1.  Install the Kilo Code extension from the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=kilocode.Kilo-Code).
2.  Log in with your Google Account to get $20 in free Claude 4 Sonnet & Opus credits.
3.  Start using the extension. Here's a video to help you get started (just click on the image below and you'll be redirected to YouTube):

[![Watch the video](https://img.youtube.com/vi/pqGfYXgrhig/maxresdefault.jpg)](https://youtu.be/pqGfYXgrhig)

## Difference between Roo Code and Cline

We're doing our best to combine the best of both worlds. Kilo Code combines all features of Cline, Roo, and adds a few of our own additions. It has the best features of both, and we're working on making it even better!

No need to fiddle with API keys, Kilo Code ships with the latest AI models plugged in, including Claude 4 Sonnet and Opus and Gemini 2.5 Pro.

Kilo Code is a direct fork from Roo Code, but also includes the following features from Cline (and more):

- MCP Server Marketplace: Easily find, and use MCP servers to extend the agent capabilities.
- System notifications: Get notified when the agent is done with a task.
- Easy model connection: with bigger free tier.

## Extension Development

For details on building and developing the extension, see [DEVELOPMENT.md](/DEVELOPMENT.md)
