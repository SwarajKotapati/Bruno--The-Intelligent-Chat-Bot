# ChatBot-using-NLP
Meet Chat Bot Bruno who is designed to make your life easier by single voice command


This is an application designed using python leverages the capabilities of various APIs to provide following useful funtionalities 


1. Weather details
2. List of Upcoming Holidays
3. Creating a calander event
4. List of upcoming saved calander events
5. Searching for places on Google Maps
6. Seraching queries on Google and Youtube
7. Finding out information on Wikipedia
8. Latest news headlines
9. General Trivia questions
10. Solving basic arithmetic questions
11. Sending messages on WhatsApp
12. Sending a mail on Gmail
13. Making a voice call



## Diagramatic Representation of the application's working :

![image](https://user-images.githubusercontent.com/70504997/219971840-a403c095-8fb7-4569-a87a-f02c6b7bb8ba.png)



> ## How does it work ?

1. Used speech_recognition library to recognize user's voice.
2. From the query provided by the user, finding his intentions using if, elif loops 
ie : if 'headlines' in query, elif 'search for' in query, elif 'play' in query 


![image](https://user-images.githubusercontent.com/70504997/219972364-b2d720a2-febb-47de-b47d-438af402c731.png)




3. After finding the correct intention of the user, using respective APIs to retrive or process the information

Eg : Here's a function to return the location requested by the user


![image](https://user-images.githubusercontent.com/70504997/219972388-29b13437-f75d-415e-b9d8-9bb365dfddba.png)


Eg : Another example of returning headlines to user using Beautiful Soup API ie Infomration parser

![image](https://user-images.githubusercontent.com/70504997/219972594-a40eabad-e60f-45ce-96ef-0fe0bc774335.png)

![image](https://user-images.githubusercontent.com/70504997/219972615-71c77d89-dd86-4d1f-8385-c0c67f84460c.png)


4. Finally your friendly Bruno can shut down when not in need using a simple command

![image](https://user-images.githubusercontent.com/70504997/219972656-e6fbf66a-dc71-4a76-8629-66092a3db716.png)



### Bruno is a highly functional bot, can be extended to numerous supported funtions using API's and your imagination. :)
