# OpenAI Image Generator

This is a simple image generator built with Node.js and Express that uses [OpenAI's Dall-E models](https://beta.openai.com/docs/guides/images) to generate images.

## Usage

Create a new file inside the project and name it `.env` and the add the following into it
```bash
PORT = 5000
OPENAI_API_KEY = 'ADD_YOUR_KEY_HERE'
```

Generate an API KEY at [OpenAI](https://beta.openai.com/) and replace it with `ADD_YOUR_KEY_HERE` in the `.env` file.

Install the dependencies

```bash
npm install
```

Run server

```bash
npm start
```

Visit `http://localhost:5000` in your browser.

The endpoint is at `POST http://localhost:5000/openai/generateimage`.