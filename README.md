# Basic_chatbot

To know more about rasa <a href ='https://itnext.io/building-a-chatbot-with-rasa-9c3f3c6ad64d'> Check </a> the article. Or find rasa <a href ='https://rasa.com/docs/getting-started/'> Documentation </a> here.
<br>
If you want to run rasa for first time, set the directory and then run ``rasa init`` this command in terminal. Then to try it on terminal use ``rasa shell``. If you changed anything from the code, dont forget to train the model again using ``rasa train``. Finally if you want to check the confidence of some intents, run ``rasa shell nlu`` , and that will show all the confidence and details part of your bot.
<br>
Here I made a simple bot that can provide information about some specific timezone. I have not connect it with any database or apis to get the timezone. I just hardcoded some value using city names, so other city that is not present will display an unsuccessful result.
<br>
Here I implimented a chatbot from scratch uusingpython and rasa. Rasa is a chatbot solution. Rasa provides a set of tools to build a complete chatbot at your local desktop and completely free. Their flagship tools are,
<ul>
  <li>Rasa NLU: A natural language understanding solution which takes the user input and tries to infer the intent and extract the available entities.</li>
  <li>Rasa Core: A dialog management solution tries to build a probability model which decides the set of actions to perform based on the previous set of user inputs.</li>
</ul>
Some basic parts of a chatbot
<ul>
  <li>Intent: Consider it as the aim or target of the user input. If a user say, “Which day is today?”, the intent would be finding the day of the week.</li>
  <li>Entity: Consider it as the useful information from the user input that can be extracted. From previous example, by intent we understand the aim is to find the day of week, but of which date? If we extract “Today” as the entity, we can perform the action on today.</li>
  <li>Actions: As the name suggest, its an operation which can be performed by the bot. It could be replying something in return, querying a database or any other thing possible by code.</li>
  <li>Stories: These are a sample interaction between the user and bot, defined in terms of intents captured and actions performed. So developer can mention what to do if you get a use input of some intent with/without some entities. Like saying if user intent is to find the day of week and entity is today, find day of week of today and reply.</li>
</ul>
<br>
