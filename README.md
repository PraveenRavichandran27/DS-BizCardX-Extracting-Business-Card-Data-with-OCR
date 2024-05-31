# DS-BizCardX-Extracting-Business-Card-Data-with-OCR

## Introduction   

   BizCardX is a Streamlit application that effortlessly streamlines business card data extraction through advanced OCR technology. Users can easily upload card images to retrieve essential details, including company names, cardholder names, contact information, and more. With a strong focus on data security and user authentication, BizCardX ensures secure data storage and offers streamlined management via the user-friendly Streamlit UI. Experience an efficient, secure, and user-friendly solution for managing business card information effortlessly with BizCardX.

## Libraries/Modules Used
  
   a).pandas: Used to create DataFrames for data manipulation and storage.
  
   b).sqlite3: Used to store and retrieve data from a MySQL database.
  
   c).streamlit: Used to create a graphical user interface for users.
  
   d).easyocr: Used for text extraction from business card images.

## Workflow

   * Install the required libraries using the command pip install. Install streamlit, mysql.connector, pandas, and easyocr.
      
   *   Execute the bizcardx.py script using the command streamlit run bizcardx.py.
      
   *  The web application opens in a browser, presenting the user with three menu options: HOME, UPLOAD & MODIFY, DELETE.
      
   *  Users can upload a business card image in the UPLOAD & MODIFY menu.
      
   *  The EasyOCR library extracts text from the uploaded image.
      
   *   Extracted text is classified using regular expressions to identify key information such as company name, Designation, etc.
      
   * The classified data is displayed on the screen and can be edited by the user if needed.
      
   *   The MODIFY menu allows users to read, update, and delete data in the MySQL database.

  
