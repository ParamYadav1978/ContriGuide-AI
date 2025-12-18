# ContriGuide-AI  
AI-Powered Open-Source Contribution Recommendation Platform

---

## About

ContriGuide-AI is a full-stack application that helps developers discover relevant **open-source projects** to contribute to based on their skills and interests.

The platform uses **OpenAI’s language model** to analyze user-provided skills and generate intelligent recommendations, reducing the time spent searching for suitable open-source contributions.

---

## Features

- Skill-based open-source project recommendations  
- AI-powered suggestions using OpenAI API  
- RESTful backend APIs built with Node.js and Express  
- Responsive user interface  
- Secure and modular application structure  

---

## Tech Stack

- **Frontend:** React.js  
- **Backend:** Node.js, Express.js  
- **AI Integration:** OpenAI API  
- **Database (optional):** MongoDB  

---

## How It Works

1. User enters their technical skills
2. Frontend sends the skills to the backend API
3. Backend constructs a prompt and calls the OpenAI API
4. OpenAI returns relevant open-source project suggestions
5. Recommendations are displayed to the user

---

## Getting Started

### Prerequisites

- Node.js  
- npm or yarn  
- OpenAI API Key (https://platform.openai.com)

---

### Installation

Clone the repository:
```sh
git clone https://github.com/ParamYadav1978/ContriGuide-AI.git
cd ContriGuide-AI
