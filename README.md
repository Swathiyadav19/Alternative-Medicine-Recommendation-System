# Alternative-Medicine-Recommendation-System
**Alternate Medicine Recommendation System:**

1.Table of Contents
2.Introduction
3.Project Overview
4.Technologies Used
5.Features
6.Project Structure
7.Installation
8.Usage
9.Acknowledgements
10.Contact


**Introduction**
The Alternate Medicine Recommendation System is an intelligent web application that suggests alternative medicines based on the user's selection. Designed to improve accessibility and assist users in finding effective alternatives, this system enables users to filter by type, select specific manufacturers, and browse reliable alternatives, with direct links for purchasing.


**Project Overview**
The application leverages various technologies to provide a seamless recommendation experience. Users can search for a specific medicine and receive suggestions for alternatives, including descriptions, manufacturer information, and purchase links. This project is part of a comprehensive approach to facilitate alternate medicine recommendations, offering personalized suggestions based on similarity analysis.


**Technologies Used**
The project utilizes the following technologies:

>Streamlit: For creating an interactive and user-friendly web application interface.
>Pickle: For efficient storage and retrieval of serialized data.
>Pandas: For data handling, reading Excel files, and data preparation.
>Scikit-learn: For algorithms related to personalized recommendations (similarity analysis).
>NumPy: For additional data manipulation and handling.
>PIL (Python Imaging Library): For image handling and display.


**Features**
1.Search and Filter: Users can filter medicines by type and manufacturer to narrow down choices.
2.Alternative Recommendations: Suggests five alternative medicines based on similarity, along with key details.
3.Detailed Information: Includes descriptions, prices, and manufacturer information for recommended medicines.
4.Direct Purchase Links: Provides quick links to popular pharmacies for easy purchasing.
5.Image Display: Shows relevant images for each recommended medicine, if available.


**Project Structure**
graph
├── css/
│   └── style.css               # Custom CSS for additional styling
├── images/
│   ├── medicine-image.jpg      # Main display image for the app
│   └── [medicine_name].jpg     # Images for recommended medicines
├── Medicine_description.xlsx    # Excel file with details on medicines
├── similarity.pkl               # Serialized similarity data
├── README.md                    # Project documentation
└── app.py                       # Main Streamlit application file


**Installation**
To run this application locally, follow these steps:

1.Clone the Repository
git clone https://github.com/your-username/alternate-medicine-recommendation-system.git
cd alternate-medicine-recommendation-system
2.Install the Required Packages Ensure you have Python 3.x installed, then run:
pip install -r requirements.txt
The requirements.txt file should include the following:
streamlit
pandas
pickle-mixin
scikit-learn
numpy
pillow
3.Run the Application Start the Streamlit server to run the application:
streamlit run app.py


**Usage**
1.Upload Data Files:
Ensure Medicine_description.xlsx and similarity.pkl are in the root directory.
2.Search for Medicine:
Use the dropdown to filter by Type and Manufacturer, and select a specific medicine for alternative recommendations.
3.Get Recommendations:
Click the Recommend Medicine button to view alternatives. Each result includes:
Description: Key details about the alternative medicine.
Price: If available.
Manufacturer: Manufacturer information.
Direct Links: Links to purchase on PharmEasy, 1mg, and Apollo.
Image: Medicine image (if available).
4.Interactive Display:
The app displays images and provides links for direct purchasing options, enhancing the user experience.


**Acknowledgements**
Special thanks to the Streamlit team for their robust library, and the developers of Pandas, Scikit-learn, NumPy, and PIL for making data manipulation and image handling straightforward.
**Contact**
Project Maintainer: Teljuri Swathi Yadav
Email: swathiyadav2004@gmail.com
LinkedIn: Swathi Yadav's Profile

This README provides an overview of the Alternate Medicine Recommendation System for easy setup and understanding on GitHub. Contributions are welcome!
