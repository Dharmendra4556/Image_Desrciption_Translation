# AI Image Description & Translation

This project is a Streamlit-based web application that allows users to upload an image and enter a prompt. The application generates a description of the image based on the user's prompt using a generative AI model. Additionally, users can translate the generated description into various languages and convert the description into audio using text-to-speech.

## Features

- **Image Upload**: Upload an image file in JPG format.
- **Prompt Input**: Enter a custom prompt to generate a description for the uploaded image.
- **AI Image Description**: Uses a generative AI model to create a description of the image based on the user's prompt.
- **Text-to-Speech**: Convert the generated description into audio with options for male and female voices.
- **Translation**: Translate the description into multiple languages including English, Hindi, Odia, Telugu, Tamil, Punjabi, Malayalam, and Marathi.

## Usage

1. **Upload an Image**: Click on "Choose an image..." to upload a JPG file.
2. **Enter a Prompt**: Provide a prompt that the AI will use to generate a description of the image.
3. **Generate Description**: The app will display the uploaded image and the generated description.
4. **Convert Description to Audio**:
   - Select "Male" or "Female" from the "Choose a voice:" dropdown to generate and play the audio.
5. **Translate Description**:
   - Select a language from the "Choose a Language to Translate:" dropdown to translate the description.

## Dependencies

- [Streamlit](https://streamlit.io/)
- [Pillow](https://python-pillow.org/)
- [Google Generative AI](https://developers.google.com/generative-ai)
- [pyttsx3](https://pyttsx3.readthedocs.io/)
- [googletrans](https://pypi.org/project/googletrans/)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## Acknowledgements

- [Streamlit](https://streamlit.io/) for the web app framework.
- [Google Generative AI](https://developers.google.com/generative-ai) for the AI model.
- [pyttsx3](https://pyttsx3.readthedocs.io/) for text-to-speech conversion.
- [googletrans](https://pypi.org/project/googletrans/) for translation.
