# AI-Powered Personal Fitness Tool

## Overview
The AI-Powered Personal Fitness Tool is a comprehensive application designed to help users achieve their fitness goals through personalized workout routines and nutrition plans. By leveraging advanced AI models, a multi-agent system, and robust data storage solutions, this tool offers dynamic, user-specific recommendations while ensuring a seamless user experience.

## Key Features
- **Personalized Fitness Plans**: Tailored workout routines based on user data, goals, and constraints.
- **Nutrition Guidance**: AI-generated calorie, protein, fat, and carb recommendations aligned with fitness objectives.
- **'Ask AI' Module**: Interactive Q&A feature to get real-time suggestions and insights.
- **Secure Data Management**: User data is securely stored and updated using Astra DB.
- **Multi-Agent AI System**: Routes tasks to specialized AI models for optimal performance.

## Technology Stack
- **Python**: Backend logic.
- **Langflow**: Multi-agent system design and task routing.
- **Astra DB**: Secure and scalable data storage.
- **Streamlit**: Interactive and intuitive frontend.
- **OpenAI LLMs**: Advanced natural language processing.

## How to Set Up

### Prerequisites
- Python 3.8+
- Astra DB account
- OpenAI API key
- Streamlit installed locally

### Steps to Run the Application
1. **Clone the Repository**:
   ```bash
   git clone [<repository-url>](https://github.com/syarwinaaa09/workoutapp.git)
   cd workoutapp
   ```
2. **Set Up Astra DB**:
   - Create an account on [Astra DB](https://www.datastax.com/astra).
   - Set up a database instance and note the credentials.
3. **Install Dependencies**:
   ```bash
   pip install langflow dotenv streamlit astrapy
   ```
4. **Configure Environment Variables**:
   Create a `.env` file in the project root and add the following:
   ```env
   OPENAI_API_KEY=""
   ASTRA_DB_APPLICATION_TOKEN=""
   LANGFLOW_TOKEN=""
   ASTRA_ENDPOINT=""
   ```
5. **Run the Application**:
   ```bash
   streamlit run main.py
   ```
6. **Access the App**:
   Open `http://localhost:8501` in your browser to use the tool.

## How It Works
1. **User Inputs**: Users enter their personal details, set goals, and provide notes.
2. **Multi-Agent System**: Langflow routes tasks like workout generation, nutrition calculations, and Q&A to specific AI models.
3. **AI Outputs**: AI generates personalized results based on user input and constraints.
4. **Secure Data Storage**: All user data is stored and updated in Astra DB for consistency and scalability.

## Contributions
Contributions are welcome! Feel free to fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For any questions or feedback, please contact [syarwinaaa09@gmail.com].
