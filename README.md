# Healthcare Assistant Chatbot

A smart healthcare chatbot built with Streamlit and Hugging Face Transformers that provides medical information and guidance to users. The chatbot uses natural language processing to understand user queries and provides relevant healthcare-related responses.

## Features

- Real-time text-based interaction
- Preprocessing of user inputs using NLTK
- Predefined responses for common medical symptoms and conditions
- Fallback to BERT-based question-answering for undefined queries
- Simple and intuitive web interface

## Technologies Used

- **Streamlit**: For the web application interface
- **Hugging Face Transformers**: For advanced question-answering capabilities
- **NLTK**: For natural language processing and text preprocessing
- **Python 3.x**: As the primary programming language

## Installation

1. Clone the repository:
```bash
git clone [your-repository-url]
cd healthcare-chatbot
```

2. Install the required dependencies:
```bash
pip install streamlit transformers nltk
```

3. Download required NLTK resources:
```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

## Usage

1. Run the Streamlit application:
```bash
streamlit run app.py
```

2. Open your web browser and navigate to `http://localhost:8501`

3. Type your health-related query in the text input field and click "Submit"

## Supported Health Topics

The chatbot can provide information about:
- Common symptoms (fever, cough, headache, etc.)
- Allergies and allergic reactions
- General health conditions
- Basic medical advice
- Appointment scheduling
- Medication guidance

## Response Types

1. **Predefined Responses**: For common symptoms and conditions including:
   - Sneezing and allergies
   - Fever and infections
   - Headaches
   - Stomach pain
   - Cold symptoms
   - Throat pain
   - Back pain
   - Chest pain
   - Dizziness
   - Skin rashes
   - Weight loss
   - Fatigue
   - Diabetes

2. **AI-Generated Responses**: For queries not covered by predefined responses, using BERT-based question-answering

## Important Notes

- This chatbot is for informational purposes only and should not be used as a substitute for professional medical advice
- Always consult with a healthcare provider for medical concerns
- In case of emergency, contact emergency services immediately

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details

## Acknowledgments

- Hugging Face for their Transformers library
- Streamlit team for the excellent web app framework
- NLTK team for natural language processing tools
