## Color Palette Generator

https://github.com/Sooowayydh/ai-color-palette-generator/assets/60032431/aaa79ceb-20b9-49f7-a61d-0a42f3c7a164

This is a Flask web application that generates color palettes based on text prompts. It utilizes the OpenAI GPT-3.5 model to convert verbal descriptions into lists of colors.

### Prerequisites

Make sure you have the following installed:

- Python 3
- Flask
- OpenAI Python library
- `python-dotenv` library

### Setup

1. Clone the repository to your local machine.
2. Create a virtual environment (optional but recommended).
3. Create the `.env` file and provide your OpenAI API key.

### Usage

1. Run the Flask application by executing the following command:
   ```
   python app.py
   ```
2. Access the application by opening a web browser and navigating to `http://localhost:5000`.
3. Enter a text prompt describing the desired color palette.
4. Click the "Generate" button.
5. The application will send the text prompt to the OpenAI model, which will generate a list of colors.
6. The generated color palette will be displayed on the web page.

### Examples

Here are a few examples of text prompts you can try:

1. "Convert the following verbal description of a color palette into a list of colors: The Mediterranean Sea"
2. "Convert the following verbal description of a color palette into a list of colors: sage, nature, earth"
3. "Convert the following verbal description of a color palette into a list of colors: [your text prompt here]"

### Notes

- The color palettes generated will contain between 2 and 8 colors.
- The application uses the `text-davinci-003` model from OpenAI to generate the color palettes. You can change the model if desired.
- The generated color palettes are returned in JSON format as an array of hexadecimal color codes.

Feel free to modify and enhance the application according to your needs!
