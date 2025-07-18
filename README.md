# RecipeSnap – AI-Based Image to Recipe Converter

## Description
RecipeSnap is a beginner-friendly Flask web application that allows users to upload food images and receive generated recipes based on image recognition. It leverages pre-trained models from torchvision or TensorFlow Hub for food identification and provides recipe downloads as PDF files. Ideal for AI and computer vision enthusiasts looking to explore image classification and recipe generation.

## Tech Stack
- Python 3.x
- Flask
- PyTorch / torchvision or TensorFlow Hub (for image recognition)
- ReportLab (for PDF generation)
- HTML/CSS (for frontend forms and pages)

## Installation
1. Clone the repository:
```bash
git clone https://github.com/bitasmbl/bitasmbl-recipe-snap-ai-based-image-to-recipe-converter.git
```
2. Navigate into the project directory:
```bash
cd bitasmbl-recipe-snap-ai-based-image-to-recipe-converter
```
3. Create and activate a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
4. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage and Examples
1. Run the Flask app:
```bash
flask run
```
2. Open your browser and go to [http://127.0.0.1:5000](http://127.0.0.1:5000).
3. Upload a food image, and upon submission, the app will identify the food, generate a recipe, and display the result.
4. Click on the 'Download Recipe' button to save the recipe as a PDF.

## Implementation Steps
- Set up Flask backend to handle image uploads and display results.
- Integrate a pre-trained image recognition model to identify food items.
- Map identified food to corresponding recipes stored in a static dictionary.
- Generate recipe text and display it on the results page.
- Implement PDF download functionality for the generated recipes.

## When you are done, submit the project from your profile: [https://bitasmbl.com/home/profile](https://bitasmbl.com/home/profile)