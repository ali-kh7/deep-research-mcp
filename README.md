# Deep Research MCP 🌐

![Deep Research MCP](https://img.shields.io/badge/Release-v1.0.0-blue.svg)  
[Download Releases](https://github.com/ali-kh7/deep-research-mcp/releases)

<a href="https://glama.ai/mcp/servers/@ali-kh7/deep-research-mcp">
  <img width="380" height="200" src="https://glama.ai/mcp/servers/@ali-kh7/deep-research-mcp/badge" alt="Deep Research MCP server" />
</a>

Welcome to the **Deep Research MCP** repository! This project provides a server compliant with the Model Context Protocol (MCP). It is designed to facilitate comprehensive web research. By utilizing Tavily's Search and Crawl APIs, the server gathers detailed information on various topics and structures this data to support high-quality markdown document creation using large language models (LLMs).

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## Features

- **MCP Compliance**: The server adheres to the Model Context Protocol, ensuring compatibility with various tools and services.
- **Data Aggregation**: Efficiently gathers and structures data from multiple sources.
- **Markdown Generation**: Converts gathered data into well-structured markdown documents.
- **Web Crawling**: Utilizes Tavily's Search and Crawl APIs for in-depth web research.
- **Node.js and TypeScript**: Built using modern technologies for better performance and maintainability.

## Installation

To get started with Deep Research MCP, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/ali-kh7/deep-research-mcp.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd deep-research-mcp
   ```

3. **Install the dependencies**:

   ```bash
   npm install
   ```

4. **Run the server**:

   ```bash
   npm start
   ```

You can also check the [Releases](https://github.com/ali-kh7/deep-research-mcp/releases) section for downloadable files and specific versions.

## Usage

Once the server is running, you can interact with it via the API. Here’s how to use it effectively:

1. **Send a request to gather information**:

   You can send a request to the server with a specific topic to gather data. The server will return structured information ready for markdown generation.

   Example request:

   ```http
   POST /api/research
   Content-Type: application/json

   {
     "topic": "Artificial Intelligence"
   }
   ```

2. **Receive structured data**:

   The server responds with data in a structured format. This data can be used directly or transformed into markdown documents.

3. **Generate markdown documents**:

   The structured data can be converted into markdown using the provided functions in the API.

### Example Markdown Output

```markdown
# Artificial Intelligence

## Overview
Artificial Intelligence (AI) refers to the simulation of human intelligence in machines.

## Applications
- Healthcare
- Finance
- Transportation

## Conclusion
AI is transforming industries and shaping the future.
```

## API Documentation

For detailed API documentation, please refer to the `docs` folder in this repository. It contains information on all available endpoints, request formats, and response structures.

### Endpoints

- **POST /api/research**: Gather information on a specific topic.
- **GET /api/status**: Check the server status.

## Contributing

We welcome contributions to improve Deep Research MCP. If you want to contribute, please follow these steps:

1. **Fork the repository**.
2. **Create a new branch**:

   ```bash
   git checkout -b feature/YourFeatureName
   ```

3. **Make your changes**.
4. **Commit your changes**:

   ```bash
   git commit -m "Add your message here"
   ```

5. **Push to the branch**:

   ```bash
   git push origin feature/YourFeatureName
   ```

6. **Open a Pull Request**.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Support

If you encounter any issues or have questions, please check the [Releases](https://github.com/ali-kh7/deep-research-mcp/releases) section or open an issue in the repository.

---

Thank you for checking out Deep Research MCP! We hope this tool enhances your web research capabilities. Happy coding!