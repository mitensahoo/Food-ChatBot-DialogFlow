# Food-ChatBot-DialogFlow

This project demonstrates the integration of a chatbot powered by Dialogflow with a web-based user interface. Users can interact with the chatbot through a web interface built with HTML and CSS. The backend is powered by FastAPI, which connects to a MySQL database to store and retrieve chatbot conversation data.


## Table of Contents

- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Dialogflow Account:** You need a Dialogflow agent set up. Visit [Dialogflow](https://cloud.google.com/dialogflow) to get started.

- **FastAPI**: Ensure you have FastAPI installed on your development environment.

- **MySQL Database**: Set up a MySQL database to store chatbot conversation data.

- **HTML and CSS Knowledge**: Basic knowledge of HTML and CSS for customizing the web interface.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/mitensahoo/Food-ChatBot-DialogFlow.git
   cd Food-ChatBot-DialogFlow
   ```

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Configure Dialogflow:

   - Create a new Dialogflow agent.
   - Set up the necessary intents, entities, and fulfillment for your chatbot.

4. Configure MySQL Database:

   - Update the database connection details.

5. Start the FastAPI server:

   ```bash
   uvicorn main:app --reload
   ```

6. Access the chatbot interface:

   - Open `index.html` in your web browser or host it on a web server.

## Project Structure

- `backend/main.py`: FastAPI application files.
- `frontend/`: Static files (e.g., CSS, JavaScript) for the web interface.
- `backend/main.py`: FastAPI application setup.
- `backend/main.py`: Integration with Dialogflow.
- `backend/db_helper.py`: MySQL database connection and data handling.
- `requirements.txt`: Python package dependencies.
- `README.md`: This documentation.

## Usage

- Interact with the chatbot through the web interface.
- The chatbot responses are powered by Dialogflow and stored in the MySQL database.

## Deployment

- Deploy the FastAPI application and host the HTML/CSS files on a web server or hosting platform.

## Contributing

Feel free to contribute to this project by opening issues and pull requests. Your contributions are highly appreciated.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Special thanks to the Dialogflow, FastAPI, and MySQL communities for their excellent documentation and resources.

## Contact

If you have any questions or need assistance, feel free to contact the project maintainer:

- Miten Ranjan Sahoo
- mitenofficial04@gmail.com

---
