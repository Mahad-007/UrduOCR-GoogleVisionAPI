## How to Set Up the Project:

### Step 1: Install Dependencies
Ensure you have Python installed. Install required dependencies using the `requirements.txt` file:
pip install -r requirements.txt

markdown
Copy code

### Step 2: Enable Google Vision API
1. Go to [Google Cloud Console](https://console.cloud.google.com/).
2. Enable the **Vision API** for your project.
3. Obtain an API Key (as provided) or set up a Service Account.

### Step 3: Prepare the Image
Place the `.jpg` image file from which you want to extract Urdu text in the project directory.

### Step 4: Edit the Script
In the `ocr_urdu_text_extraction.py` script:
- Replace `'path_to_your_image.jpg'` with the actual path to your image file.
- Replace `'AIzaSyAVgQOhEV9j2m-Hta1ZGo-v3HrZwTW5Fq8'` with your **Google API key**.

### Step 5: Run the Script
Once the image is in place, run the script: