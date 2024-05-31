# BizCardX-Extracting-Business-Card-Data-with-OCR

## Introduction   

   BizCardX is a Streamlit application that effortlessly streamlines business card data extraction through advanced OCR technology. Users can easily upload card images to retrieve essential details, including company names, cardholder names, contact information, and more. With a strong focus on data security and user authentication, BizCardX ensures secure data storage and offers streamlined management via the user-friendly Streamlit UI. Experience an efficient, secure, and user-friendly solution for managing business card information effortlessly with BizCardX.

## Libraries/Modules Used
  
   * pandas: Used to create DataFrames for data manipulation and storage.
  
   * sqlite3: Used to store and retrieve data from a SQL database.
  
   * streamlit: Used to create a graphical user interface for users.
  
   * easyocr: Used for text extraction from business card images.

## Workflow

   * Install the required libraries using the command pip install. Install streamlit, sqlite 3, pandas, and easyocr.
      
   * Execute the bizcardx.py script using the command streamlit run bizcardx.py.
      
   *  The web application opens in a browser, presenting the user with three menu options: HOME, UPLOAD & MODIFY, DELETE.
      
   *  Users can upload a business card image in the UPLOAD & MODIFY menu.
      
   *  The EasyOCR library extracts text from the uploaded image.
      
   *   Extracted text is classified using regular expressions to identify key information such as company name, Designation, etc.
      
   *   The classified data is displayed on the screen and can be edited by the user if needed.
      
   *   The MODIFY menu allows users to read, update, and delete data in the MySQL database.

## E T L Process
  
  a) Extract data
        
   * Extract relevant information from business cards by using the easyOCR library
             
  b) Process and Transform the data
        
   * After the extraction process, process the extracted data based on,Name, Company name,  Designation, Mobile Number, Email, Address, and Pincode is converted into a data frame.
             
  c) Load data
        
   * After the transformation process, the data is stored in the SQLITE3.

## User Guide

Step 1. Data collection zone

  * Click the 'Browse Files' button and select an image
    
Step 2. Data upload

 * Click the 'Upload' button to upload the data to the sql database
  
Step 3. Modification zone

 * In this 'Modification zone' you can able to modify the information also you can delete the previous data

## Conclusion

   It will allow users to upload an image of a business card, extract data using easyOCR and display it. It will also allow saving extracted data and image to a database. The application needs to have a simple UI to guide users through uploading, extracting and saving data to the database.

## Screenshots
   Insert relevant screenshots of your application's interface and data extraction here.

Contacts:

📧 Email: praveen2726r@gmail.com

🌐 LinkedIn: https://www.linkedin.com/in/praveenr27/ 

  
