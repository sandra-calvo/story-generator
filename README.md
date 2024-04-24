# Story generator with GenAI

## Cuentacuentos IA

This Streamlit app uses Google Cloud's Gemini-Pro model to generate interactive children's stories based on user input.

![image](https://raw.githubusercontent.com/sandra-calvo/story-generator/main/screencaptures/image1.png)

![image](https://raw.githubusercontent.com/sandra-calvo/story-generator/main/screencaptures/image2.png)

**How to use:**

- Enter the name of the main character, their pet or sidekick, and their favorite activity.
- Click the "Generar historia!" button.
- The app will generate a short story based on your input and read it aloud using text-to-speech.

**Features:**

- Uses Google Cloud's Gemini-Pro model to generate creative and engaging stories.
- Allows users to customize the story by providing their own input.
- Generates high-quality audio of the story using text-to-speech.
- Provides an interactive and engaging experience for children.

**Requirements:**

- Python 3.8 or higher
- Streamlit
- Google Cloud Platform account with the following APIs enabled:
Text-to-Speech
Speech-to-Text
Vertex AI Generative Models

**Setup:**

- Create a Google Cloud Platform account and enable the required APIs.
- Install the required Python packages.
- Set the GOOGLE_APPLICATION_CREDENTIALS environment variable to the path of your service account key file.
- Run the app using the following command:
```bash
streamlit run cuentos_by_gemini.py
```
**Deployment:**

This app can be deployed to Google Cloud or any other platform that supports Streamlit apps.

**License:**

This app is licensed under the Apache License 2.0.


