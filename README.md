# PlantXplore
> PlantXplore is a project to help farmers all over the world by bringing them closer to each other. 

## Table of contents
* [General info](#general-info)
* [Scope](#scope)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
According to FAO, more than 60% of the world's population depends on agriculture for survival. When we say it depends on agriculture we mean it depends on farmers, Farmers have been the backbone of our world. However after extensive research no any web portal was found that could link farmers around the world virtually the way we will do now, this was a significant problem as this would create boundaries and distance within farmers. To tackle this problem we came up with the idea of Goodleaf, we believe that it will be a global platform for farmers to come together and help each other. In the coming days: The site will also look forward to coordinating with various agricultural experts around the world, allowing free consultation services to farmers by experts, providing quick, efficient and effective services to the farmers. In many parts of the world, the farmers do not get effective crop production due to a lack of timely consultancy and growing process. This site can help combat this problem and ultimately improve agriculture globally.


## Scope
Farmers globally can interact understanding each other's areas' plant species . 
Along with farming , this can also , in coming times be developed as a portal for Animal Husbandry , Dairy , Interactions  thus giving back to the community a lot of learnings , agriculture related career trainings and ultimately , becoming a shared platform for all the farmers as well as aspirants in the farming sector.

## Screenshots
![IMG-20231216-WA0000](https://github.com/devarshpatel1506/PlantiX/assets/69602242/fc8fd6bf-3799-455a-a8b0-7ef16a691c50)
![IMG-20231216-WA0013](https://github.com/devarshpatel1506/PlantiX/assets/69602242/b2a1eb7c-62fc-46d9-aae0-6e4508e1c349)
![IMG-20231216-WA0001](https://github.com/devarshpatel1506/PlantiX/assets/69602242/d46c4273-cd4f-4f58-914f-16395ac62287)
![IMG-20231216-WA0002](https://github.com/devarshpatel1506/PlantiX/assets/69602242/0dababa7-ab07-4b6c-9646-a333ac93fc01)
![IMG-20231216-WA0003](https://github.com/devarshpatel1506/PlantiX/assets/69602242/002fcd03-78e8-41f9-913a-fe4e6e85085e)
![IMG-20231216-WA0005](https://github.com/devarshpatel1506/PlantiX/assets/69602242/75d89a54-e95d-4e69-9aae-d33eca2854af)
![IMG-20231216-WA000![IMG-20231216-WA0007](https://github.com/devarshpatel1506/PlantiX/assets/69602242/e4e21be2-8b9d-4c83-9fd4-49e1fb1934ee)
![IMG-20231216-WA0007](https://github.com/devarshpatel1506/PlantiX/assets/69602242/549f48ff-f159-43e6-951e-5a762eb31eda)
![IMG-20231216-WA0008](https://github.com/devarshpatel1506/PlantiX/assets/69602242/908bab1d-9568-4734-81ab-3f49820956c8)
![IMG-20231216-WA0010](https://github.com/devarshpatel1506/PlantiX/assets/69602242/4d46aa3d-472d-449a-91c8-3a9ae221b1a0)
![IMG-20231216-WA0012](https://github.com/devarshpatel1506/PlantiX/assets/69602242/65e67fd8-6130-4881-8072-b5a995bb8a42)
![IMG-20231216-WA0004](https://github.com/devarshpatel1506/PlantiX/assets/69602242/4f72a8e9-a34c-4869-8963-44cb9dcf408f)

## Technologies
The cutting edge deep learning model is at the heart of Goodleaf. It takes the advantages of transfer learning to classify diseased and healthy leaves into 38 categories (which will surely increase in near future) with high accuracy. Not just classify but it also provides solutions to the problems within a few seconds. Also, it aggregates other posts in the forum belonging which belong to the category of the classified leaf.

But even an impressive technology like this is nothing without an easy to use and pleasant User Interface. So the UI for Goodleaf is specially built the way it is so that everyone can use it. The UI is very intuitive that everyone can wrap their head around it easily.But still it has got few issues in being a responsive webapp.

Another major feature of the Goodleaf is it’s simple yet very informative forums. I personally think it is the best part about Goodleaf. The best person who could help you in the time of trouble is a fellow person who does the same thing as you do in day to day life. This feature enables farmers from different geographical features, climate, and most importantly knowledge and experience level to connect with each other. Not only farmers even people belonging to other profession doing farming in their roof tops and in other ways can benefit out of this forum.

## Setup
* Git clone the Github repo
* Install files from requirements.txt
`pip3 install -r requirements.txt`
* Make model directory in Goodleaf/machinelearning/
* Keep all models and csv file to Goodleaf/machinelearning/model/. [Link for models](https://drive.google.com/drive/folders/1qeDUhN-yaSNZ4Ii-N0SDDHfGQE5KrBH5?usp=sharing) //Unzip the downloaded folder from drive and go into the directory and copy all three files and paste them to location specified as above
* Start the server by using 
`python3 manage.py runserver`
  or   
`python manage.py runserver`
for windows
* Done!
* 
### Note: You may be required to go to Goodleaf/machinelearning/predict.py file and change first line of function predict() if you face any errors while detecting an image in web app.

## Features
Features of Goodleaf.
* Desease Detection.
* Gives Solutions and Remidies.
* Helpfull and active community.
* Promotion variation in agricultural sector through learnings of different ways of agriculture.
* The inexperienced and new farmers can get  a lot of consultings from the experienced ones.

## Status
Project is: _in progress-constantly updating-meeting the needs of farmers all over the world_

## Inspiration
We are developers from Nepal and our country Nepal is a agriculture based country with over 63% of our economy directly or indirectly depending on Agricilture, Even so we found that there is no proper platform for farmers to discuss their condition, problems and communicate with each other. With the aim to make Farming more efficient we started this project.


