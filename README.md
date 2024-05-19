
#sharmavarun840@gmail.co/varungenomics.com

pip install pdf2docx
pip install pytesseract
pip install pdf2image
pip install pillow


#Open the provided script file in a text editor.

#Update the paths to Poppler and Tesseract in the script:

# Specify the path to the Poppler bin directory
poppler_path = r'C:\\Path\\To\\Poppler\\bin'

# Specify the path to the Tesseract executable
pytesseract.pytesseract.tesseract_cmd = r'C:\\Path\\To\\Tesseract-OCR\\tesseract.exe'


#Update the directory variable to the path where your PDF files are located:

directory = r'C:\\Path\\To\\Your\\PDFs'


#Open a command prompt or terminal.

#Navigate to the directory where your script is saved.

#Run the script using Python:

test2.py
