# Weather MCP

![MCP for Production Automation](assets/MCP%20for%20Production%20Automation.webp)

A simple weather service built with [FastMCP](https://github.com/robertchase/fastmcp), demonstrating tools, resources, and prompt implementations for a modular command platform.

## Features

- **Weather Tool**: Get the current weather for a specified location.
- **Weather Resource**: Access weather data as a resource endpoint.
- **Weather Report Prompt**: Generate a weather report prompt for a given location.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/thaletto/mcp.git
   cd mcp
   ```
2. Install dependencies (Python 3.13+ required):
   ```bash
   uv pip install -r uv.lock
   ```

## Usage


- To start the MCP weather server:
  ```bash
  fastmcp dev server.py
  ```

## Project Structure

- `server.py`: Implements the MCP server with weather tools, resources, and prompts.
- `assets/`: Contains project images and assets.

## Dependencies

- [fastmcp](https://github.com/modelcontextprotocol/python-sdk)

---

© 2024 Weather MCP. All rights reserved.
