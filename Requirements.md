<u>2.0 Requirements and User Stories<u>

2.1 Required Functionality
-----------------------------------------------------------------------------------------------------------
This app will require docker, kubernetes, tsx, REACT, python, and a bunch of html/mobile programming. Our app will be designed for the user to type in a subject they want to track and the app will send reccomendations on how to quit with products that you can buy. You will get daily motivational quotes as your progress increases, along with this you will also obtain a streak after a certain amount of days. There will be a frontend and backend connected via API's that will have a stable extremely fast connection.

-----------------------------------------------------------------------------------------------------------
1: Streak System <br>
2: Shopping Cart <br>
3: Motivational Quote Notification <br>
4: Integration with Other Apps <br>
5: Social Support System <br>

2.2 User Stories
-----------------------------------------------------------------------------------------------------------
Suggested Word Count: 200-300 words
Translate the required functionality into user stories that capture the end-user’s perspective. These stories should be concise, user-centered descriptions of the functionality, formatted in a way that can be easily validated and tested.

As a registered user, I want to quit an addiction using TheHabitTracker so that I can live an improved and healthier life. When I feel like relapsing on an addiction I am trying to quit, I can click a panic button, which can call a trusted person I know, or receive an AI-generated Motivational text that keeps me from relapsing. As a registered user, I will have access to how long I have kept my good habits, so that I can use it as motivation to not fall back into bad habits. When I add a bad habit I want to quit, like quitting nicotine, TheHabitTracker will give me a questionnaire on what form of nicotine I've been using, how long, and why. Then, it will use AI queries to give me better alternatives to the products, and tips to help me quit depending on how long I have been using them and why I've been using that product. As a registered user, I want to have videos of other people who have maintained similar habits to me, so that I understand that I am not alone in this struggle. As a registered user, I want to have a reward of some kind when I've successfully maintained a good habit for a certain time limit so that there is more of a reward to maintaining good habits.

Create a list of 10-12 user stories using the following guidelines:
Use a template for story structure:
- As a registered user, I want to quit an addiction using TheHabitTracker so that I can live an improved and healthier life.
- As a registered user, I will have access to how long I have kept my good habits, so that I can use it as motivation to not fall back into bad habits.
- When I feel like relapsing on an addiction I am trying to quit, I can click a panic button, which can call a trusted person I know, or receive an AI-generated Motivational text that keeps me from relapsing.
- When I add a bad habit I want to quit, like quitting nicotine, TheHabitTracker will give me a questionnaire on what form of nicotine I've been using, how long, and why. Then, it will use AI queries to give me better alternatives to the products, and tips to help me quit depending on how long I have been using them and why I've been using that product.
- As a registered user, I want to have videos of other people who have maintained similar habits to me, so that I understand that I am not alone in this struggle
- As a registered user, I want to have a reward of some kind when I've successfully maintained a good habit for a certain time limit so that there is more of a reward to maintaining good habits.
- As a registered user, I need an easy-to-use, navigable user interface, so that the app is user-friendly.
- When I need help with a feature on the app, there will be a help feature at the bottom of the app to help me find what I am looking for so that I can use the app to its full potential.
- As a new user, I want to sign up using my email or social login so that I can quickly start using the app.
- As a user, I want to set a frequency (daily, weekly, custom) for each habit so it fits my goals.
- As a user, I want to add reminders or notifications so I don’t forget to complete my habits.
- As a user, I want to group habits into categories (e.g., health, productivity) so I can stay organized.

Attempt to break down user stories related to your "Must Have" required functionality as much as possible. If a functionality is broad, you can break it down into epics, but try to keep the number of epics to a minimum.

Each story should include clear and measurable acceptance criteria that define when the story is complete. While the focus should be on the user’s needs, consider including any critical technical details that might affect implementation.

2.3 User Personas
-----------------------------------------------------------------------------------------------------------
Suggested Word Count: 150-200 words
Provide 2-3 user personas or roles using the following format:


Alex, 36, bachelor’s in chemistry, chemical engineer, born and raised in Massachusetts, spent 4 years at MIT graduated with a 3.8 GPA, 10 years of experience with chemical engineering, multiple certifications like the following PE, ASQ, CCE, EHS. Need an outlet to stop me from using nicotine products to deal with stress during and after work hours. Nicotine has taken time from my personal life through distractions with addiction. 
1.
![people-headshot-nick-maslow-f21ef38676504bc89a091ec9a5c95e4b](https://github.com/user-attachments/assets/8ee0fc81-a06f-4a8f-a900-69cf38f14f16)



Ronald, 55, master’s in business, Finance manager for USAA bank position at Richmond VA, lived in Fredericksburg until 1994, Studied at the University of Richmond. Been working At USAA for the past 12 years. I struggle with overeating, and it has affected my work ethic because I always feel unmotivated due to my weight.
2.
<img width="1024" height="879" alt="image" src="https://github.com/user-attachments/assets/d3a5269d-665b-4f60-8b68-57063b7f49fe" />



Tiffany, 42, bachelor’s in biology, CVS pharmacy Technician, worked at CVS for the past 7 years, I have constant memory and work-related issues due to my lack of sleep, I cant get tired enough during the day and lay awake through most nights.
3.
![people-headshot-lauren-lieberman-830b33fdd4cc4c4bbc6e71ebd84dd633](https://github.com/user-attachments/assets/519bd566-a5cc-41fb-9425-d70d85ad54c6)





2.4.1 Security
-----------------------------------------------------------------------------------------------------------
We plan to inplement a security system with multiple factors like authentification to ensure only the allowed users are allowed to see the what the habits the user has entered the progress made and other users who are on the contact/authorized personel list to edit or view data. Some methods of security we plan to use includes two factor authentification for every login, as well as a password protected section to view very personal information. For GDPR and HIPAA, HIPAA wont apply due to the lack of medical information being used within the application and it all being purely interactable, but GDPR will play into effect for our oversea users as we will only store data provided to us and this data will be stored and only accessible for the users and noone else ensuring limited access to data and an increase to overall privacy.

2.4.2 Performance
-----------------------------------------------------------------------------------------------------------
We want to have the application work almost autonomously where it can be given information do research through our databases and then reply to the user with the information needed to help with any habit the person wants to break or make. We plan to first ensure the response capabilities are met like being able to hold a conversation with the user and to respond with reliable information and sourced data. We want this to be done in a timely manner so the user does not have to backtrack on their habits and possibly do something they do not want to. For the data storing section of our application we want the interface to ask the user to enter their habits, what they plan to improve or get rid of and also what plans they have for them which after this interaction is completed we should instantly return information to the user about what they said they wanted to do. Once this step is completed we will work on the interaction with our AI service agent to help focus in on the goals the user has and what plans to follow to achieve their goals.

2.4.3 Availability
-----------------------------------------------------------------------------------------------------------
The app will be available all hours of the day; The only hours that the app will be down for will be for updates which will go out when their is the least amount of activity.    

2.4.4 Reliability
-----------------------------------------------------------------------------------------------------------
The plan for reliability is the appication should be running perfectly at all times and no real fatal error should occur, This is purely input based information and the only errors would be made by the user inputing the incorrect information or choosing a new plan to change their habits that wasnt provided by the application. The backup protocols will go into effect in a timely matter within a certain period which will ensure 

2.4.5 Ethics and Sustainability
    There will be no bias in any of the algorithms considering this app is strictly to help people. User consent will not be required since it is completely optional for the user to submit their infor for help or not. There should be no data really needing to be kept, this app should be sufficient just via user input.
