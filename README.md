```markdown
# YouTube Assistant

This is an application designed to assist users by providing them with information about YouTube videos upon request. This could include generating summaries for long-form content, such as 3-hour podcasts, or asking specific questions from the video, making it easier for users to get the required information without watching the entire thing. 

## Features

- **Dynamic Query Handling**: Users can input specific questions related to YouTube videos and receive accurate responses based on the video's transcript.
- **Custom Data Handling**: Incorporates YouTube transcripts into the model, providing contextually relevant responses.

## Installation

To install the YouTube Assistant, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/youtube-assistant.git
   ```
2. Navigate to the project directory:
   ```
   cd youtube-assistant
   ```
3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

To use the YouTube Assistant, perform the following:

1. Set up your environment variables by creating a `.env` file in the root directory and adding your OpenAI API key:
   ```
   OPENAI_API_KEY=your_api_key_here
   ```
2. Run the Streamlit application:
   ```
   streamlit run main.py
   ```
3. Open your web browser and go to `http://localhost:8501`.
4. Enter a YouTube video URL and your query in the respective input fields on the sidebar.
5. Click `Submit` to receive a response based on the video's transcript.