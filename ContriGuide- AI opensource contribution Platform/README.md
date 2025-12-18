
# ContriGuide-AI — Open-Source Contribution Recommendation Platform

## About

ContriGuide-AI is an AI-powered platform that helps developers discover relevant **open-source projects** to contribute to based on their skills and interests.

The application uses **OpenAI’s language model** to generate intelligent project recommendations, reducing the time developers spend searching for suitable open-source contributions.

---

## Features

- Skill-based open-source project recommendations  
- AI-powered suggestions using OpenAI API  
- Full-stack application using React and Node.js  
- Responsive user interface for cross-device usage  
- Secure REST API design  

---

## Tech Stack

- Frontend: React.js  
- Backend: Node.js, Express.js  
- AI Integration: OpenAI API  
- Database (optional): MongoDB  

---

## How It Works

1. User enters their technical skills
2. Frontend sends the skills to backend API
3. Backend processes the request and calls OpenAI API
4. OpenAI returns relevant open-source project suggestions
5. Results are displayed on the user interface

---

## Getting Started

### Prerequisites

- Node.js  
- npm or yarn  
- OpenAI API Key (https://platform.openai.com)

---

### Installation

```sh
git clone https://github.com/ParamYadav1978/ContriGuide-AI.git
cd ContriGuide-AI
````

Install backend dependencies:

```sh
cd backend
npm install
```

Install frontend dependencies:

```sh
cd frontend
npm install
```

Create a `.env` file in the backend folder and add:

```env
OPENAI_API_KEY=your_openai_api_key
```

Start backend server:

```sh
npm start
```

Start frontend application:

```sh
npm start
```

---

## Example Usage

Input:

```
React, Node.js, MongoDB
```

Output:

* Open-source React dashboard project
* Node.js authentication boilerplate
* MongoDB data visualization tool

```
