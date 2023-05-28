# DIET MENTOR

Diet Mentor is an electron web application that offers personalized food suggestions based on the health parameters provided by the user.
It aims to help individuals make informed dietary choices and achieve their health goals.

## Link to product walkthrough
https://drive.google.com/file/d/1sNWYeIy54DBwLF5l4lnz9Oq9Tas2vMto/view?usp=drivesdk
## How it Works ?

In the Diet Mentor web app, the working involves integrating the ChatGPT API to provide personalized food suggestions based on the user's health parameters and preferences.
Here's an overview of how the app works:
1.Health Profile: Users enter their health parameters such as age, weight, sugar level, cholesterol level, cuisine preference, and any specific dietary restrictions or
health conditions.
2.User Input: The entered health parameters and preferences are sent as a prompt to the ChatGPT API. The prompt could be structured as a conversation with the model, 
providing the user's inputs and allowing the model to generate appropriate food suggestions.
3.ChatGPT API Interaction: The app communicates with the ChatGPT API to send the prompt and receive the model's response. The response contains food recommendations
and any additional information or clarifications based on the user's inputs.
4.Food Suggestions: The app processes the model's response and extracts the relevant food recommendations. It takes into account the user's nutritional requirements,
dietary restrictions, and preferences.
5.Displaying Results: The food suggestions and additional information (such as nutritional details) are displayed on the webpage for the user to view.

## Libraries used
electron-squirrel-startup 1.0.0
## How to configure
1. Clone the repository to your local machine.
2. Install the required dependencies by running npm install.
## How to Run
Start the app by running npm start.
