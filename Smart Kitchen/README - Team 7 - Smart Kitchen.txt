README - Smart Kitchen AI Assistant

Follow the steps below to run the project on your local machine:

1. Download the ZIP file and extract it to your desired location.

2. Open Command Prompt (cmd) and navigate to the extracted project folder:
   (Replace this path with the actual folder location on your system)
	cd _insert the path here_

3. Create a virtual environment:
   python -m venv .venv

4. Activate the virtual environment:
   .venv\Scripts\activate

5. Install the required libraries:
   pip install streamlit numpy requests torch torchvision torchaudio faiss-cpu Pillow tensorflow opencv-python transformers gTTS

6. In line 43, add your Spoonacular API Key between the double quotes.

6. Run the Streamlit app:
   streamlit run app7.py

7. Once the app opens in your browser, upload an image. (sample image is in the folder as well)
   The output will be displayed in about a minute.

Enjoy your Smart Kitchen AI Assistant! It includes an avatar, youtube links and an audio file for each recipe generated!
