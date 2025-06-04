# chatGpt-openAI-model

A web application that allows users to interact with OpenAI's GPT-3 language model through a simple and user-friendly interface.
This app is for demo purpose to test OpenAI API and may contain issues/bugs.

If you are looking for a simple HTML/vanilla JavaScript version, check [here]chatgpt-web-application)




## Features
- User-friendly interface for making requests to the OpenAI API
- Responses are displayed in a chat-like format
- Select Models (Davinci, Codex, Create Image) based on your needs
- Highlight code syntax

## Technologies Used
- For frontend, I used React.js.
- For backend, I used express.

## Setup Introduction
This guide will help you set up the repository on your local machine. Please follow these steps carefully to ensure a smooth setup process.

### Cloning the repository
dowload zip and extract or gitclone using CLI

```

### Backend Setup
 
- Navigate to backend directory
```sh
cd backend # Navigate to the server directory:
```
- Install dependencies
```sh
npm install #install the backend dependencies
```
- Set the OPENAI_API_KEY in the .env file:
```sh
OPENAI_API_KEY=YOUR_OPENAI_API_KEY
```

- Start the backend server by running the following command:
```sh
node index.js
```

### Frontend Setup

- Navigate to the frontend directory:
```sh
cd frontend
```

- Run the following command to install the frontend dependencies:
```sh
npm install
```

- Set the `REACT_APP_BACKEND_URL` in the `.env` file to the URL of your backend server. For local development, use the following URL:
```sh
REACT_APP_BACKEND_URL=http://localhost:3001/
```

- Start the frontend app by running the following command:
```sh
npm start
```
in the root create .gitignore file(/.idea)

### Hosting Backend and Frontend in Same Port/URL

If you wish to host both the backend and frontend on the same port/URL, follow these steps:

- Build the frontend by running the following command in the `frontend` directory:
```sh
npm run build
```

- Start the backend server using the instructions in the "Backend Setup" section.

- Once the setup process is complete, the frontend will be accessible at the URL of your backend server.

## Usage
- Type in the input field and press enter or click on the send button to make a request to the OpenAI API
- Use control+enter to add line breaks in the input field
- Responses are displayed in the chat-like format on top of the page
- Generate code, including translating natural language to code
- You can also create AI images using DALL·E models 

## Contributing

This project welcomes contributions and suggestions for improvements. If you have any ideas, please feel free to open an issue or create a pull request.

Thank you for your consideration.
Yours trully @cecilgachie


