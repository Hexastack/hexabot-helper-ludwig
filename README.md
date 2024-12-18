# Hexabot Ludwig NLU Helper Extension

The Ludwig NLU Helper is an extension for Hexabot that acts as a utility class to interact with the Ludwig NLU engine.

Hexabot is an open-source chatbot / agent solution that allows users to create and manage AI-powered, multi-channel, and multilingual chatbots with ease. If you would like to learn more, please visit the [official github repo](https://github.com/Hexastack/Hexabot).

This helper extension simplifies the use of the Ludwig NLU engine by providing methods for preprocessing responses, formatting incoming data, and managing settings. These utilities can be leveraged across various components of Hexabot's architecture to enhance overall functionality and performance.

## Ludwig NLU Engine

The **Hexabot Ludwig NLU** engine is designed to process and analyze text input, extracting key information such as intent, entities, and sentiment to facilitate downstream tasks like chatbot interactions.  For more details, check the [official Github Repository](https://github.com/Hexastack/hexabot-ludwig-nlu)

## Features
- **Payload Formatting:** Easily structure and format retrieved data for human-readable, contextually relevant responses.
- **Settings Management:** Handle configuration and settings across different parts of the Hexabot architecture to maintain consistency.
- **Integrated Utilities:** Provides reusable helper methods for seamless interaction with the Ludwig NLU engine.
- **Customizable Workflows:** Offers flexibility to adapt to various chatbot use cases and workflows within Hexabot.

## Installation

To use the Hexabot Ludwig NLU Helper Extension within Hexabot, follow the steps below: 
```bash
cd ~/projects/my-chatbot
npm install hexabot-helper-ludwig
hexabot dev
```
## Usage
The Hexabot Ludwig NLU Helper provides a range of methods to interact with the Ludwig NLU engine. Here’s how you can use its functionalities.

### Settings
The extension provides configurable settings that can be adjusted to suit your needs. Below are the available settings:
- **API Token:** API token required for authentication with the NLU engine.
- **Endpoint:** URL of the Ludwig NLU API endpoint to interact with
- **Threshold:** Sets the minimum confidence score required for predictions.
