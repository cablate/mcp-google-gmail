[![MseeP.ai Security Assessment Badge](https://mseep.net/pr/cablate-mcp-google-gmail-badge.png)](https://mseep.ai/app/cablate-mcp-google-gmail)

# Gmail MCP Server

A powerful Model Context Protocol (MCP) server providing comprehensive Gmail integration with LLM processing capabilities.

## Features

### Email Management

- Read and search emails
- Process email content with various formats
- Advanced email filtering
- Attachment handling

## Demo on Dive Desktop

![Gmail Demo](docs/Demo-on-Dive-Desktop.gif)

## Installation

### Manual Installation

```bash
npm install -g @cablate/mcp-gmail
```

## Usage

### CLI

```bash
map-gmail
```

### With [Dive Desktop](https://github.com/OpenAgentPlatform/Dive)

1. Click "+ Add MCP Server" in Dive Desktop
2. Copy and paste this configuration:

```json
{
  "mcpServers": {
    "gmail": {
      "command": "npx",
      "args": ["-y", "@cablate/mcp-gmail"],
      "env": {
        "GMAIL_CLIENT_ID": "your_client_id",
        "GMAIL_CLIENT_SECRET": "your_client_secret",
        "GMAIL_REFRESH_TOKEN": "your_refresh_token"
      },
      "enabled": true
    }
  }
}
```

3. Click "Save" to install the MCP server

## Gmail API Authentication Setup

For detailed instructions on setting up Gmail API authentication and obtaining necessary credentials, please refer to our [Gmail API Setup Guide](guide.md).

## License

MIT

## Contributing

Welcome community participation and contributions! Here are ways to contribute:

- ⭐️ Star the project if you find it helpful
- 🐛 Submit Issues: Report problems or provide suggestions
- 🔧 Create Pull Requests: Submit code improvements

## Contact

If you have any questions or suggestions, feel free to reach out:

- 📧 Email: [reahtuoo310109@gmail.com](mailto:reahtuoo310109@gmail.com)
- 📧 GitHub: [CabLate](https://github.com/cablate/)
- 🤝 Collaboration: Welcome to discuss project cooperation
- 📚 Technical Guidance: Sincere welcome for suggestions and guidance
