# FoodWiseAI: AI-Powered Food Label Analyzer
### Description:

***FoodWiseAI***  is an AI-powered application that helps users make informed dietary choices by analyzing food labels. Users can simply upload an image of a food product's label, and the app will provide detailed nutritional information, allergen warnings, and personalized recommendations.

### Features:

- **Image-based analysis** : Accurately extracts information from food labels using advanced image processing techniques. Comprehensive nutritional data: Provides detailed breakdowns of calories, fats, sugars, proteins, and other key nutrients. Allergen detection: Identifies common allergens such as gluten, dairy, and nuts.
- **Dietary compatibility**: Assesses alignment with various dietary restrictions like vegan, vegetarian, or low-carb.
- **Personalized recommendations:**  Offers tailored suggestions based on user preferences and dietary goals.
- **Interactive chatbot:** Enables users to ask questions and get real-time responses.

#### Install dependencies:
Bash
pip install -r requirements.txt
Use code with caution.

#### Set up environment variables:
Create a .env file and add the following variables:
MODEL_ID=vikhyatk/moondream2
REVISION=2024-07-23
Usage:

### Run the application:
Bash
streamlit run app.py
Use code with caution.

- **Upload an image** : Click the "Choose an image" button and select a food label image.
- **Get analysis** : The app will process the image and display the nutritional information, allergen warnings, and recommendations.
- **Chat with the chatbot** : Ask questions about the product or request personalized recommendations.
  
## Technologies:

- Python
- OpenCV
- Streamlit
- Hugging Face Hub
- VLM
