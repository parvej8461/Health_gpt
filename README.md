# Health_gpt
# Nutritionist Generative AI Doctor Using Google Gemini Pro Vision

This project is a Streamlit-based web application that uses Google's Gemini Pro Vision AI to analyze food images and provide nutritional information, including calorie counts for each item and the total calorie content.

## Features

- Upload food images for analysis
- Get detailed calorie information for each food item in the image
- Calculate the total calorie content of the meal
- User-friendly interface powered by Streamlit

## Installation

1. Clone this repository:
2.  Install the required dependencies:
3.  3. Set up your Google API key:
- Create a `.env` file in the project root
- Add your Google API key to the `.env` file:
  ```
  GOOGLE_API_KEY=your_api_key_here
  ```

## Usage

1. Run the Streamlit app:
2. Open your web browser and go to the URL provided by Streamlit (usually `http://localhost:8501`)

3. Upload an image of food using the file uploader

4. Click the "Tell me the total calories" button to get the analysis

## Dependencies

- Python 3.7+
- Streamlit
- google-generativeai
- python-dotenv
- Pillow

## Configuration

The app uses the Gemini Pro Vision model from Google's Generative AI. Make sure you have the necessary permissions and API access from Google to use this model.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgments

- Google Gemini Pro Vision AI for providing the image analysis capabilities
- Streamlit for the web application framework
   
