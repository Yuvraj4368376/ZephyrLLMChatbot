# Sustainable Living Advisor Chatbot

## Overview

The Sustainable Living Advisor Chatbot is designed to provide users with tips and advice on sustainable living practices. This chatbot uses the Hugging Face Inference API to generate responses and is built using the Gradio library for a user-friendly interface.

## Features

- **Customizable Responses:** Users can customize the system message, maximum new tokens, temperature, and top-p settings to tailor the chatbot's responses.
- **Streaming Responses:** The chatbot streams its responses for a more interactive experience.
- **User-Friendly Interface:** Built with Gradio, the chatbot provides an easy-to-use interface for seamless interaction.

## Installation

To run this application, you need to install the required dependencies. Create a virtual environment and install the dependencies from `requirements.txt`.

```bash
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
pip install gradio huggingface_hub
```

## Usage

1. Run the `app.py` script to launch the Gradio interface.

```bash
python app.py
```

2. The Gradio interface will open in your default web browser. You can interact with the chatbot by entering your queries and adjusting the additional input settings as needed.

## Project Structure

- `app.py`: Main application file containing the logic for generating chatbot responses and handling user interactions.
- `requirements.txt`: Lists the required Python libraries.

## Example Queries

- How can I reduce my carbon footprint?
- What are some eco-friendly alternatives to plastic?
- How can I save energy at home?
- What are the benefits of composting?
- How can I support local farmers?

## License

This project is for informational purposes only and is intended to provide tips and advice on sustainable living practices. For official guidance, please refer to authorized resources or experts in sustainable living.

## Disclaimer

‼️Disclaimer: This chatbot is based on general sustainable living practices and is for informational purposes only. For official guidance and comprehensive advice, please refer to authorized resources or experts in sustainable living.‼️

---

Feel free to contribute to this project by submitting issues or pull requests on GitHub.
