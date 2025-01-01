

LIBRARIES USED:
Here are brief descriptions of each library:

1. **TensorFlow**  
   - An open-source machine learning framework primarily used for training and deploying deep learning models. It supports neural networks, image classification, object detection, and more.

2. **Pillow (PIL)**  
   - A Python Imaging Library used for image processing tasks such as opening, manipulating, and saving image files in various formats.

3. **wikipedia-api**  
   - A Python wrapper for Wikipedia's API, allowing you to fetch and parse Wikipedia content, including page summaries, sections, and metadata.

4. **folium**  
   - A library for creating interactive geographical maps using Python. It's commonly used for data visualization with map markers, layers, and geographic data overlays.

5. **geotext**  
   - A Python library that extracts country and city names from text, making it useful for location-based data processing.

6. **Gradio**  
   - A user-friendly library for creating interactive web interfaces for machine learning models and Python functions. It supports image, text, and audio inputs/outputs.


#Output-1:
Multiple images detecting:
![result](https://github.com/user-attachments/assets/b45575b5-4da8-4641-bf3f-574735138293)


#output-2:using Pill library image preprocessed,bounding box drawn,and detecting the correct image:
![image](https://github.com/user-attachments/assets/79504035-fa2f-4ea7-aa91-d5c982376ed9)


Output-3:Integrated Map Feature:
![image](https://github.com/user-attachments/assets/c5f141f9-ce81-428b-9064-aa012fff8620)



OVERALL EXPLANATION:-
🐞 **Insect Detection and Mapping System - Project Summary** 🌍  

This project is a **Flask-based web application** that utilizes **machine learning, image processing, and geolocation mapping** to detect insects from uploaded images, provide detailed information about them, and dynamically visualize their common locations on an interactive map.  


🚀 **Core Functionalities:**  

1. **Insect Detection using TensorFlow:**  
   - The application uses a **pre-trained ResNet50 deep learning model** to classify insects from uploaded images.  

2. **Information Retrieval from Wikipedia:**  
   - After detection, the application fetches relevant information, such as general details, eradication methods, and pesticide usage, using the **Wikipedia API**.  

3. **Geographical Location Extraction:**  
   - The text from Wikipedia is scanned using **GeoText** to identify mentions of cities and countries where the insect is commonly found.  

4. **Interactive Mapping with Folium:**  
   - Detected locations are plotted dynamically on an **interactive Folium map**, with custom markers based on insect types.  

5. **Image Highlighting:**  
   - Detected insect regions in the uploaded image are highlighted using bounding boxes with **Pillow (PIL)**.  

6. **Dynamic User Interface with Gradio:**  
   - The application supports easy interaction for users through an intuitive web interface built with **Gradio**, allowing users to upload images, view results, and explore detection maps.  



🛠️ **Technology Stack:**  
- **Machine Learning:** TensorFlow (ResNet50)  
- **Image Processing:** Pillow (PIL)  
- **Information Retrieval:** Wikipedia API  
- **Geolocation Mapping:** Folium, GeoText  
- **Web Interface:** Gradio  
- **Backend Framework:** Flask  



🌟 **Key Features:**  
- Accurate insect identification through deep learning.  
- Comprehensive details fetched dynamically from Wikipedia.  
- Real-time visualization of insect locations on a map.  
- Easy-to-use web interface with multi-image upload support.  
- Clear bounding boxes highlighting detected insects.  


This system is a **powerful tool for pest management professionals, researchers, and enthusiasts**, offering a streamlined way to identify insects, understand their behavior, and visualize their global distribution. 🐜📊  







