# japanese-chatting-trainer
Practice Japanese conversational skills through interactive chatting scenarios.

## Features

- **Chat Interface**: Engage in conversations with an AI assistant tailored to your proficiency level.
- **History Management**: Keep track of past chats and revisit them anytime.
- **Customizable Settings**: Modify API endpoint, API key, and model parameters to fit your needs.
- **Scheduling Scenarios**: Get various scenarios to practice and improve your Japanese abilities.
- **Responsive Design**: Optimized for use on both desktop and mobile devices.

## Technology Stack

- **HTML**: Structure of the application.
- **CSS**: Styling for the user interface, ensuring a seamless user experience.
- **JavaScript**: Interactive functionalities including API calls and chat management.

## Usage

1. **Starting a New Chat**: Click the "+" button to initiate a new chat session.
2. **Send Messages**: Type your message in the text area and click send or press Enter to send.
3. **View Chat History**: Click on the history icon to see previous conversations.
4. **Settings**: Update the OpenAI API endpoint, API key, and model in the settings panel.
5. **End a Chat**: At any point, you can return home which will clear the current session's messages.

## API Integration

This application uses the OpenAI API for generating chatbot responses. You will need to provide your own API key and ensure that you have access to the OpenAI services.

### API Settings

Update the following settings in the "Settings" page:
- **OpenAI Endpoint URL**: The base URL for the OpenAI API (Default: `https://api.openai.com/v1/chat/completions`)
- **OpenAI API Key**: Your personal access key from OpenAI.
- **OpenAI Model**: Specify which model to use (e.g., `gpt-4o-mini`).