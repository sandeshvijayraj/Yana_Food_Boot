# food_delivery_bot
food delivery bot using alexa voice processing

.enc is the required .py file to run

account on amazon developer is required to test the code. 
Since alexa skill set require HTTPS request , so ngrok is used as a third party to convert our http request to https.
Hence , there should be a account on ngrok to handle request.

A session is created for each user using python in yana.py file. The core working of bot is dealt over here. 

yana.db is a database file which is used to store the values i.e. the value used throughiut the session and the predefined utterances.
