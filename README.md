# Kimi CLI Zed Extension

A Zed extension that integrates [Kimi CLI](https://github.com/MoonshotAI/kimi-cli) as an ACP (Agent Communication Protocol) agent.

## Features

- Seamless integration of Kimi CLI into Zed editor
- Cross-platform support (macOS, Linux, Windows)
- Automatic binary download and setup
- Interactive terminal-based authentication
- ACP agent capabilities for enhanced development workflow

## Installation

1. Open Zed editor
2. Go to Extensions (Cmd+Shift+X on macOS)
3. Search for "Kimi CLI"
4. Click Install

## Getting Started

1. Open the agent panel with `Cmd+?` (macOS) or `Ctrl+?` (Windows/Linux)
2. Click the `+` button in the top right to start a new Kimi CLI thread
3. On first use, you'll be prompted to authenticate:
   - Click "Setup LLM with /setup slash command"
   - A terminal will open where you can run `/setup`
   - Follow the prompts to select your LLM provider (Kimi, OpenAI, Anthropic, etc.) and enter your API key
4. Once configured, you can start using Kimi CLI directly in Zed!

## Usage

After authentication, you can:
- Use Kimi CLI to complete software development tasks
- @-mention files, symbols, or fetch web content for context
- Execute shell commands and edit code
- Access all Kimi CLI features including MCP tools and skills

## Supported Platforms

- macOS (Apple Silicon & Intel)
- Linux (x86_64)
- Windows (x86_64)

## Development

To develop this extension locally:

1. Clone this repository
2. Install Rust via [rustup](https://rustup.rs/)
3. In Zed, use "Install Dev Extension" and select this directory

## License

Apache-2.0

## Links

- [Kimi CLI Repository](https://github.com/MoonshotAI/kimi-cli)
- [Zed Extension Documentation](https://zed.dev/docs/extensions)