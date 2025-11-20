# PlantXplore

PlantXplore is a global initiative that helps farmers connect, collaborate, and learn from one another to improve agricultural practices worldwide.

## Table of Contents

- [General Information](#general-information)
- [Scope](#scope)
- [Screenshots](#screenshots)
- [Technologies](#technologies)
- [Setup](#setup)
- [Features](#features)
- [Status](#status)
- [Inspiration](#inspiration)
- [Contact](#contact)

## General Information

According to FAO, more than 60% of the world’s population relies on agriculture for its livelihood. This dependence ultimately rests on farmers, who form the backbone of our global food system. After thorough exploration, there appeared to be no dedicated web platform that connects farmers globally in the way PlantXplore (powered by Goodleaf) aims to do, leaving an important gap in knowledge exchange and community building.  

PlantXplore addresses this by providing a virtual meeting point for farmers around the world to share experiences, challenges, and solutions. Over time, the platform also plans to integrate agricultural experts who can offer free consultations, ensuring farmers receive fast, relevant, and practical advice. In many regions, low crop yield is closely tied to the lack of timely guidance and access to best practices; PlantXplore seeks to reduce this barrier and contribute to stronger, more resilient agriculture worldwide.

## Scope

PlantXplore allows farmers from different countries and climates to understand each other’s local plant species, methods, and conditions. The project is designed to grow beyond crop farming, with future development targeting areas like animal husbandry, dairy, and broader agricultural interactions.  

The long-term goal is to create a shared, community-driven ecosystem where farmers and aspiring agriculturists can access training, mentorship, and real-world experience. By supporting both experienced farmers and newcomers, PlantXplore aims to give back to the community through continuous learning and collaboration.

## Screenshots

![IMG-20231216-WA0000](https://github.com/devarshpatel1506/PlantiX/assets/69602242/fc8fd6bf-3799-455a-a8b0-7ef16a691c50)  
![IMG-20231216-WA0013](https://github.com/devarshpatel1506/PlantiX/assets/69602242/b2a1eb7c-62fc-46d9-aae0-6e4508e1c349)  
![IMG-20231216-WA0001](https://github.com/devarshpatel1506/PlantiX/assets/69602242/d46c4273-cd4f-4f58-914f-16395ac62287)  
![IMG-20231216-WA0002](https://github.com/devarshpatel1506/PlantiX/assets/69602242/0dababa7-ab07-4b6c-9646-a333ac93fc01)  
![IMG-20231216-WA0003](https://github.com/devarshpatel1506/PlantiX/assets/69602242/002fcd03-78e8-41f9-913a-fe4e6e85085e)  
![IMG-20231216-WA0005](https://github.com/devarshpatel1506/PlantiX/assets/69602242/75d89a54-e95d-4e69-9aae-d33eca2854af)  
![IMG-20231216-WA0007](https://github.com/devarshpatel1506/PlantiX/assets/69602242/e4e21be2-8b9d-4c83-9fd4-49e1fb1934ee)  
![IMG-20231216-WA0007](https://github.com/devarshpatel1506/PlantiX/assets/69602242/549f48ff-f159-43e6-951e-5a762eb31eda)  
![IMG-20231216-WA0008](https://github.com/devarshpatel1506/PlantiX/assets/69602242/908bab1d-9568-4734-81ab-3f49820956c8)  
![IMG-20231216-WA0010](https://github.com/devarshpatel1506/PlantiX/assets/69602242/4d46aa3d-472d-449a-91c8-3a9ae221b1a0)  
![IMG-20231216-WA0012](https://github.com/devarshpatel1506/PlantiX/assets/69602242/65e67fd8-6130-4881-8072-b5a995bb8a42)  
![IMG-20231216-WA0004](https://github.com/devarshpatel1506/PlantiX/assets/69602242/4f72a8e9-a34c-4869-8963-44cb9dcf408f)  

## Technologies

At the core of Goodleaf is a deep learning model that uses transfer learning to classify plant leaf images into disease and health categories. It currently supports 38 classes and is designed to expand as new data and diseases are added. The system not only identifies the issue but also proposes suitable remedies within seconds and links users to relevant forum posts in the same category.  

The user interface is intentionally simple and intuitive, allowing farmers and non-technical users to navigate with ease. While the design focuses on clarity and accessibility, ongoing work aims to improve responsiveness so the platform works smoothly across a wide range of devices.  

Goodleaf also hosts a structured discussion forum, which is one of the most valuable parts of the platform. Farmers from diverse geographies, climates, and experience levels can discuss problems, share tips, and learn from one another. Even hobby growers and rooftop gardeners can participate and benefit from this knowledge exchange.

## Setup

1. Clone the repository using Git.
2. Install dependencies:
   ```
   pip3 install -r requirements.txt
   ```
3. Create a `model` directory in:
   ```
   Goodleaf/machinelearning/
   ```
4. Download the models and CSV file from the provided link and unzip them:  
   [Models Link](https://drive.google.com/drive/folders/1qeDUhN-yaSNZ4Ii-N0SDDHfGQE5KrBH5?usp=sharing)  

   Copy all three extracted files into:
   ```
   Goodleaf/machinelearning/model/
   ```
5. Start the server:
   ```
   python3 manage.py runserver
   ```
   Or on Windows:
   ```
   python manage.py runserver
   ```
6. If you encounter errors while detecting images in the web app, open:
   ```
   Goodleaf/machinelearning/predict.py
   ```
   and adjust the first line of the `predict()` function according to your environment.

## Features

- Disease detection for plant leaves.  
- Recommended solutions and remedies for identified issues.  
- An active, helpful online farming community.  
- Exposure to different agricultural practices from around the world.  
- A space where new and less experienced farmers can learn directly from experienced practitioners.

## Status

The project is currently **in progress**, under continuous enhancement, and is regularly updated to better meet the needs of farmers worldwide.

## Inspiration

The developers are from Nepal, a country where agriculture plays a central economic role, with over 63% of national income linked directly or indirectly to farming. Even with such dependence, there was no strong online platform where farmers could openly share their stories, problems, and ideas. PlantXplore was born from the desire to make farming more efficient, informed, and collaborative by giving farmers a dedicated digital home for communication and learning.

