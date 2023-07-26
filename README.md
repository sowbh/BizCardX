# BizCardX: Extracting Business Card Data with OCR

Technologies used: OCR,streamlit GUI, SQL,Data Extraction

Problem statement:
You have been tasked with developing a Streamlit application that allows users to upload an image of a business card and extract relevant information from it using easyOCR. The extracted information should include the company name, card holder name, designation, mobile number, email address, website URL, area, city, state, and pin code. The extracted information should then be displayed in the application's graphical user interface (GUI).
In addition, the application should allow users to save the extracted information into a database along with the uploaded business card image. The database should be able to store multiple entries, each with its own business card image and extracted information.
To achieve this, you will need to use Python, Streamlit, easyOCR, and a database management system like SQLite or MySQL. The application should have a simple and intuitive user interface that guides users through the process of uploading the business card image and extracting its information. The extracted information should be displayed in a clean and organized manner, and users should be able to easily add it to the database with the click of a button. And Allow the user to Read the data, Update the data and Allow the user to delete the data through the streamlit UI.
This project will require skills in image processing, OCR, GUI development, and database management. It will also require you to carefully design and plan the application architecture to ensure that it is scalable, maintainable, and extensible. Good documentation and code organization will also be important for this project.

Approach:
1. Install the required packages: You will need to install Python, Streamlit, easyOCR, and a database management system like SQLite or MySQL.
2. Design the user interface: Create a simple and intuitive user interface using Streamlit that guides users through the process of uploading the business card image and extracting its information. You can use widgets like file uploader, buttons, and text boxes to make the interface more interactive.
3. Implement the image processing and OCR: Use easyOCR to extract the relevant information from the uploaded business card image. You can use image processing techniques like resizing, cropping, and thresholding to enhance the image quality before passing it to the OCR engine.
4. Display the extracted information: Once the information has been extracted, display it in a clean and organized manner in the Streamlit GUI. You can use widgets like tables, text boxes, and labels to present the information.
5. Implement database integration: Use a database management system like SQLite or MySQL to store the extracted information along with the uploaded business card image. You can use SQL queries to create tables, insert data, and retrieve data from the database, Update the data and Allow the user to delete the data through the streamlit UI.
6. Test the application: Test the application thoroughly to ensure that it works as expected. You can run the application on your local machine by running the command streamlit run app.py in the terminal, where app.py is the name of your Streamlit application file.

Run this code in the environment such as vscode, after installing the necessary libraries required in this project.

To run bizcard.py (your_filename.py) using streamlit, type in the terminal (works only in vscode): Streamlit run bizcard.py (your_filename.py) You can now view your Streamlit app in your browser.

Local URL: http://localhost:8501 Network URL: http://192.168.0.106:8501

Input:
clone the repository in your local machine using the command:
https://github.com/your-github-username/BizCardX.git
                      or
create a new repository and upload the following images which is present in the below link in your respective repository;
https://drive.google.com/drive/folders/1FhLOdeeQ4Bfz48JAfHrU_VXvNTRgajhp

Output:

![Capture4](https://github.com/sowbh/BizCardX/assets/95527211/3a0dc59f-92eb-4409-bed0-149db6cacb31)

![Capture5](https://github.com/sowbh/BizCardX/assets/95527211/75d8fbc5-27b2-4220-8ba9-f98474de1c15)

![Capture6](https://github.com/sowbh/BizCardX/assets/95527211/3ca7fad9-7d26-4f53-987f-f7ef22c09328)

![Capture7](https://github.com/sowbh/BizCardX/assets/95527211/090644cb-5fff-46ac-bf36-7830106de520)
