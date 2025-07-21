# AI Recipe Generator

A web app that uses AWS Amplify, AWS Bedrock, and React to generate creative recipe ideas based on ingredients you provide.

## Features
- Enter ingredients and get an AI-generated recipe suggestion
- User authentication with AWS Cognito
- Powered by AWS Bedrock (Anthropic Claude model)
- Modern React + TypeScript + Vite frontend

## Prerequisites
- Node.js (v18 or newer)
- AWS account with Amplify and Bedrock access

## Installation
```bash
cd ai-recipe-generator
npm install
```

## Running Locally
```bash
npm run dev
```
Open [http://localhost:5173](http://localhost:5173) in your browser.

## AWS Amplify Setup
- The app uses AWS Amplify for authentication and a GraphQL API.
- Backend configuration is in the `amplify/` folder and `amplify_outputs.json`.
- Make sure your AWS credentials are set up and the backend is deployed using Amplify CLI or Studio.

## Usage
1. Sign up or log in with your email.
2. Enter a comma-separated list of ingredients.
3. Click "Generate" to get a recipe idea.

## Project Structure
- `src/` – React frontend
- `amplify/` – AWS backend (auth, data, Bedrock integration)
- `public/` – Static assets

## Development Scripts
- `npm run dev` – Start development server
- `npm run build` – Build for production
- `npm run lint` – Lint code

## License
This project is for educational/demo purposes only.
