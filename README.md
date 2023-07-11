# Chatbot-for-network-Optimization
Project : Chatbot for network Optimization assistance


Install Python 3.9.13 and Anaconda 22.11.1.

Copy project under (Chatbot directory) under C:\Users\User>
Replace defaul path User C:\Users\User>

1. Lunch CMD command
cmd1
C:\Users\User>cd chatbot
C:\Users\User\Chatbottest>conda activate rasaenv
rasa data validate
rasa train
(rasaenv) C:\Users\User\Chatbot>rasa shell
Or 
interface html :  rasa run --m models --enable-api --cors "*"
N.B. Internet connexion must be available

2. Lunch CMD command
cmd2
C:\Users\User>cd chatbot
C:\Users\User>conda activate rasaenv
C:\Users\User>rasa run actions
(rasaenv) C:\Users\User>pip install pandas
(rasaenv) C:\Users\User>pip install flask

3. Lunch Index html web page under C:\Users\User\Chatbot>
