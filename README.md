
# NGOConnect ( AI4SocialGood)

NGOConnect is an innovative platform designed to bridge the gap between individuals looking to donate and non-governmental organizations (NGOs) in need of resources. By leveraging advanced AI technologies and a user-friendly interface, NGOConnect facilitates meaningful connections and supports the broader mission of empowering NGOs worldwide.

## Features

- **Donor-NGO Matching:** Utilizes location data and NGO need ratings to recommend the most suitable NGOs to potential donors.
- **Community Engagement:** Links individuals to NGO communities based on shared interests, enhancing collaborative efforts.
- **AI-Powered Suggestions:** Offers innovative fundraising ideas and supports NGOs with AI-driven insights during the registration process.

## Tech Stack

- **MERN (MongoDB, Express.js, React, Node.js):** A robust stack for developing scalable full-stack applications.
- **LLM.py & Chatbot.py:** Custom Python scripts integrating large language models for AI functionalities, specifically using the GPT-3.5 Turbo API.

## Project Structure

```
NGOConnect/
│
├── frontend/       # Frontend codebase (React)
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/        # Backend codebase (Express, Node.js)
│   ├── models/
│   ├── routes/
│   ├── llm.py      # LLM integration for user registration
│   ├── chatbot.py  # Chatbot functionality for NGO registration
│   └── package.json
│
└── README.md
```

## Getting Started

### Prerequisites

- Node.js
- MongoDB
- Python 3.x
- OpenAI Python package (for interacting with GPT-3.5 Turbo API)

### Installation

1. **Clone the repository**

```sh
git clone https://github.com/Shreyaar12/Hackbrew.git
cd NGOConnect
```

2. **Set up the backend**

```sh
cd backend
npm install
# Setup your environment variables in a .env file
```

3. **Install Python dependencies**

- It's important to install the OpenAI Python package, which is not listed in `package.json` but is required for the AI functionalities.

```sh
pip install openai==0.28
# Install other Python dependencies as needed
```

4. **Set up the frontend**

```sh
cd ../frontend
npm install
```

### Running the Application

1. **Start the backend server**

```sh
cd backend
npm start
```

2. **Start the frontend application**

```sh
cd frontend
npm start
```

Navigate to `http://localhost:3000` to view the application.

## Usage

- **For Donors:** Follow the on-screen instructions to find NGOs based on your location and interests.
- **For NGOs:** Register your organization and receive tailored AI-driven insights and fundraising ideas.

## Contributing

We welcome contributions to NGOConnect! Please read our contributing guidelines before submitting pull requests.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgements

- [React](https://reactjs.org/)
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [OpenAI GPT-3.5 Turbo API](https://beta.openai.com/docs/)

