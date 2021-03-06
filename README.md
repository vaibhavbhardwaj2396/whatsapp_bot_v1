# whatsapp_bot_v1

python-whatsapp-bot
This is a Whatsapp Chatbot that responds with quotes or images of cats when either of them is requested.

Usage
Download and install Python. Version 3 and above should come with pip.

Clone or fork this repository (project).

$ git clone https://github.com/Ileriayo/python-whatsapp-bot.git

$ cd python-whatsapp-bot
Create a virtual environment inside this project directoy e.g.,

python -m venv whatsapp-bot-venv
Then activate that environment:

Windows: whatsapp-bot-venv\Scripts\activate

Mac: $ source whatsapp-bot-venv/bin/activate
Install the following dependencies: twilio, flask, requests.

$ pip install twilio flask requests
Run the Flask application
Start by setting (exporting) the FLASK_APP environment variable

Windows: set FLASK_APP=bot.py
Mac: $ export FLASK_APP=bot.py
Run this command afterwards:

python -m flask run
Test the chatbot.

a. Download ngrok. From your CLI (terminal or CMD), navigate to the ngrok directory and run this command:

 $ ngrok http 5000
Copy the URL where you see Forwarding. It will look like this https://066cbc59.ngrok.io.

b. Create an account on Twilio and navigate to the Whatsapp Sandbox. Follow the instructions from Twilio to get a test whatsapp account. At the end of the setup, paste the url you copied earlier into the input field with the label WHEN A MESSAGE COMES IN. At the end of the URL, add '/bot' and hit save.

See the screenshot below:



Bonus: You can create a customized link for your Whatsapp chatbot. Use this template: http://wa.me/<phone-number-from-twilio>?text=<code-to-join-sandbox>.

Send the link to your friends to try out the chatbot.

Technologies Used
Python, Flask framework
Twilio
ngrok
Author
VAIBHAV BHARDWAJ
