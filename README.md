do not dupe!!
# how to make it into an exe
install all the requirements.
you will need to copy this code one by one into your CMD.
also make you have to go to the microsoft store and install python 3.11
after it is installed go to cmd and type:
pip install openai 
then type 
pip install pyinstaller
then you are gunna extract your files and put them on your desktop.
once they are on your desktop copy the path and go into the file with vs code or what ever code editor you use and change openai.api_key = "" in the quotes put your api key you can get the key at https://platform.openai.com/account/api-keys sign up and get a key.
then with the path copyed and you have an api key in go to your cmd again and type:
cd then a space then your path
once you are in the path
type in cmd:
pyinstaller chatbot.py
and then let it work and after it is done if you go back in the folder go to dist and you will have the exe
