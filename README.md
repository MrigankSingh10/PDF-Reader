# PDF-Reader
This project is made to convert a normal ebook in pdf file format to an audio book.

Step 1 - Download and install the package pyttsx3. (pip install pyttsx)
          
          This package is the speech to text converter.
          You can read it's documentation here-https://pypi.org/project/pyttsx3/
          
Step 2 - Download and install the package PyPDF2
          
          This package will extract text from your pdf files.
          Documentation-https://pythonhosted.org/PyPDF2/

Step 3 - import the packages in your python file .
           
           import pyttsx3
           import PyPDF2

Step 4 - import the book you want the computer to read 
          
          book=open('Computer_networking_Principles.pdf','rb')

Step 5- initialise the speaker object.
          
          speaker= pyttsx3.init()

Step 6- Run the code in a loop from the page you want the reader to read.
        
        for num in range(8,pages):
           page=pdfReader.getPage(8)
           text=page.extractText()
           speaker.say(text)
           speaker.runAndWait()

Step 7 - Run the Code and enjoy my Friend ;) 

You can contact me to know more about the code or any other query.
 
