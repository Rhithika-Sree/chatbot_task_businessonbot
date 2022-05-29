Task-Develop a chatbot
Description:
Build a bot to share area details based on pincode

Proposed workflow for the bot.

1. Take an Indian pincode as input and show city/district/state based on user request
2. Show the available categories - using the APIs provided
    
    (Take an input from the user on what he wants to know) You can use a simple menu based approach to take this input Example categories : “City”, State”, ”District”
    
3. Based on these input show results for the users - (use the API provided)
4. After the flow ends - If a user says ”Know More” - prompt him asking if he wants to get more details. For example ( let us say user asked for - State of 560034 )
    
    User : Know my location
    
    Bot :What do you want to know? 1. State 2. City 3. District
    
    User : City
    
    Bot : Please share the pin code
    
    User : 500081
    
    Bot : Your city is Bangalore
    
    User :Thanks
    
    Bot : Welcome
    
5. (Bonus) Handle small talk in English (basic greetings)

Postal PIN Code Data: [Link](http://www.postalpincode.in/Api-Details)

Output snapshot:




![image](https://user-images.githubusercontent.com/94616126/170858012-3ad6fa2e-729c-438a-a550-5c63b9a01e86.png)

Training data:


![training_data](https://user-images.githubusercontent.com/94616126/170858352-f82f0793-8f7f-4430-821f-0dcc08375607.PNG)

Conversation Design:

![convo_design](https://user-images.githubusercontent.com/94616126/170858347-ecb3f33c-650f-4857-9e5f-0b325ceb4f9c.PNG)

Responses:

![responses](https://user-images.githubusercontent.com/94616126/170858359-8cd33afb-a8fd-447a-a436-a2448e46107b.PNG)

Getting data from api:

![getting data](https://user-images.githubusercontent.com/94616126/170858368-93ca2484-a1c7-42f2-8e3c-a9c60737105c.PNG)





