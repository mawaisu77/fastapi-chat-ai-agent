# AI Agent Chatbot with FastAPI

A production-ready AI chatbot application built with FastAPI for the backend and Streamlit for the frontend. This project demonstrates how to create an intelligent chatbot system that can process and respond to user queries effectively.

## Project Structure

```
.
├── AI Chatbot–GenAI Application (Production Ready).pdf  # Detailed documentation
├── ai_agent.py       # AI agent implementation
├── backend.py       # FastAPI backend server
├── frontend.py      # Streamlit frontend interface
├── Pipfile          # Pipenv dependency management
├── Pipfile.lock     # Pipenv lock file
└── requirements.txt # pip requirements file
```

## Prerequisites

- Python 3.11 or higher
- One of the following package managers:
  - pip (Python's default package manager)
  - Pipenv (recommended)
  - Conda

## Installation and Setup

You can set up this project using any of the following methods:

### Using Pipenv (Recommended)

1. **Install Pipenv:**
```bash
pip install pipenv
```

2. **Install Dependencies:**
```bash
pipenv install
```

3. **Activate the Virtual Environment:**
```bash
pipenv shell
```

### Using pip and venv

1. **Create a Virtual Environment:**
```bash
python -m venv venv
```

2. **Activate the Virtual Environment:**
- **macOS/Linux:**
  ```bash
  source venv/bin/activate
  ```
- **Windows:**
  ```bash
  venv\Scripts\activate
  ```

3. **Install Dependencies:**
```bash
pip install -r requirements.txt
```

### Using Conda

1. **Create a Conda Environment:**
```bash
conda create --name myenv python=3.11
```

2. **Activate the Conda Environment:**
```bash
conda activate myenv
```

3. **Install Dependencies:**
```bash
pip install -r requirements.txt
```

## Running the Application

The application consists of three main components that need to be run separately:

1. **Create AI Agent:**
```bash
python ai_agent.py
```

2. **Start the Backend Server:**
```bash
python backend.py
```

3. **Launch the Frontend Interface:**
```bash
python frontend.py
```

### Important Notes

- The backend server (backend.py) must be running before starting the frontend
- Each component should be run in a separate terminal window
- Make sure you have activated your virtual environment in each terminal

## Documentation

For detailed information about the application architecture, features, and implementation details, please refer to the included PDF documentation:
- `AI Chatbot–GenAI Application (Production Ready).pdf`

## PyTorch Integration

This project uses PyTorch for machine learning operations instead of NumPy, providing better performance and GPU acceleration capabilities when available.

## Contributing

Feel free to submit issues, fork the repository, and create pull requests for any improvements.

## License

This project is licensed under the MIT License - see the LICENSE file for details.