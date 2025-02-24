## Setting up the Environment for gmail service
-   Go to console.cloud.googe.com
-   Create a new google cloud project 
-   Create a client OAuth2.0 for desktop app
-   Change the data access settings according to the email you want to give access to it.

## Setting up the GEMINI API KEY from 
-   Go to **https://aistudio.google.com/** and create a new API Key.
-   Copy the API Key secret and paste it into .env (replace current example.env with .env and paste there with given variable name in example.env)

## Running the agent
-   Inside the root directory there is **agent.py** file:
```
Run python agent.py
``` 

## Changing configuration
-   Inside the **agent.py** in main there is parameter of ***scan_days*** which is for scanning the emails based on days. (Kind of it is window size for emails to be scanned.)
-   Tweak it according to your need.

## What this agent will do ?
-   It will reply to that email and give confidence ratio with which llm has given response to the email. 
-   After replying to the email, it will automatically mark the message unread.


#### I am thinking of adding more functionalities to it.
#### If you have any suggestion you can comment it, I will integrate it. 