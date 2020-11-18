heroku_scheduler.py
===================  
Use this script when you want to schedule the script for every 6 hourse. you can use this script when you upload it on cloud so that it runs every 6 hours automatically

without_scheduler.py
===================
Use this script to see instant results, you can use this script for presentation purposes.


step wise execution
1. Execute without_scheduler.py script
2. Python code will run and get all latest corona updates from worldometer webiste
3. All the details will be saved on mongodb atlas online database as a new collection with timestamp
4. You will get message on slack with latest bar graph
5.You will see json,csv,xlsx files created in your folder where you executed the script. 




things installed and used

pip

python 

pymongo

bs4

requests

pymongo[srv]

pandas

openpyxl    

slackclient

matplotlib

