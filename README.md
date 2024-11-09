# Juss

## Project Overview
Juss is a web-based poetry generation platform that leverages a sophisticated NLP model for generating, analyzing, and presenting high-quality Arabic poetry. The project is built using Django for the backend and React for the frontend, ensuring seamless interactions and dynamic user experiences.

## Features
- Generate poetry based on a given title or first line.
- Analyze the generated poems for structure and meter.
- Display the results in an interactive, web-based interface.
- Export generated poems to various formats.

## Installation Guide
To run the project locally, you will need to set up your development environment by installing the required dependencies and running both the backend and frontend servers.

### Prerequisites
Ensure that the following are installed on your system:
- Python (version 3.8 or higher)
- Node.js (version 14 or higher)
- npm or yarn (for frontend dependency management)
- pip (Python package installer)
- Virtual environment tools (e.g., venv or virtualenv)

### Libraries and Dependencies
Install the following libraries to run the project successfully:

#### Backend (Django)
- Django (>=3.2)
- djangorestframework
- pandas
- requests
- json
- datetime

#### Frontend (React)
- React (>=17.0)
- axios
- react-router-dom
- styled-components (optional for custom styling)

### Setting Up the Backend
1. **Clone the repository:**
   ```bash
   git clone https://github.com/username/juss-poetry-model.git
   cd juss-poetry-model
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```

3. **Install the required Python packages:**
   ```bash
   pip install -r requirements.txt
   ```
   Ensure `requirements.txt` contains:
   ```
   Django>=3.2
   djangorestframework
   pandas
   requests
   json
   ```

4. **Run database migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Start the Django development server:**
   ```bash
   python manage.py runserver
   ```

### Setting Up the Frontend
1. **Navigate to the frontend directory:**
   ```bash
   cd frontend
   ```

2. **Install npm dependencies:**
   ```bash
   npm install
   ```
   Or, if using yarn:
   ```bash
   yarn install
   ```

3. **Start the React development server:**
   ```bash
   npm start
   ```
   Or, if using yarn:
   ```bash
   yarn start
   ```

### Running the Project
- Once both servers are running, navigate to `http://localhost:3000` to interact with the web application.

## Project Structure
- **/backend**: Contains Django models, views, and API endpoints.
- **/frontend**: Contains React components, hooks, and services for the UI.
- **/static**: Includes any static files such as CSS and JavaScript.
- **/templates**: Contains HTML templates for Django.

## Additional Notes
- Make sure to set environment variables for sensitive data like API keys and database credentials.
- The frontend and backend should communicate via REST API endpoints provided by Django.

## Future Enhancements
- Integrate support for more advanced NLP models.
- Enhance user authentication and session management.
- Provide more export formats (e.g., PDF and EPUB).

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with detailed information on your changes.

## License
This project is licensed under the MIT License. See `LICENSE` for more information.

---
### Contact
For any questions or feedback, please reach out to the project maintainer at [mmalardawi@stu.kau.edu.sa].

