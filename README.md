# TextRazor Proxy for AI Summarizer Chrome Extension

## Overview

This repository hosts a lightweight web proxy for the [TextRazor API](https://www.textrazor.com/) to facilitate the summarization of selected text in a Chrome extension. The proxy addresses CORS issues by allowing your Chrome extension to communicate securely with the TextRazor API without being blocked by the browser’s CORS policy.

## Features

- Acts as a proxy for the TextRazor API to bypass CORS restrictions.
- Allows Chrome extensions to summarize text from any webpage.
- Hosted on Netlify for easy deployment and management.

## Technologies Used

- **Node.js**: For creating the server-side proxy.
- **Express.js**: For handling HTTP requests.
- **Netlify Functions**: For deploying the proxy as serverless functions.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine.
- A [TextRazor account](https://www.textrazor.com/) to obtain your API key.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/your-repo-name.git
   cd your-repo-name
