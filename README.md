# Resume Feedback Generator
This application analyzes resumes or cover letters and provides detailed feedback with bullet points to improve their effectiveness. It also provides a score out of 10 for different aspects such as structure, technical skills, industry professionalism, and the impact of working outcomes. The feedback is tailored to the specific role the candidate is applying for.

## Usage
1. Upload your resume or cover letter using the file uploader in the sidebar.
2. Once uploaded, the application will analyze the document and provide initial feedback with bullet points.
3. You can ask specific questions or provide additional prompts for further feedback.
4. The application will generate responses and provide them in the chat interface.
5. You can interact with the chat interface to refine your document and receive more feedback.

## Getting Started
1. `python -m venv venv`
1. `source venv/bin/activate`
1. `pip install -r requirements.txt`
1. `cp .env.sample .env`
1. Change the `.env` file to match your environment
1. `streamlit run app.py`

## Reflection
This application utilizes GPT-3.5 Turbo model from OpenAI to provide insightful feedback on resumes and cover letters. By leveraging natural language processing, it assists users in improving the quality and effectiveness of their job application documents. Reflection on its usage and potential improvements can provide valuable insights into enhancing its performance and usability. Additionally, integrating user feedback and iterating on the application's features can further enhance its value proposition.