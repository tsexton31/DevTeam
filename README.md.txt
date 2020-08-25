# DevTeam


I don't know if you will need this information, but

Instructions to host WebApp locally for windows 10.

Step 1. Download Anaconda, its a Python distribution

Step 2. Open Powershell, navigate to the python files and do command, 

pip install pelican
pip install markdown

(if you have an error on step two, you might have to navigate to pip in the anaconda files and use ./pip install pelican)
(if you get an error about SSL use 'pip install ssl' no quotes)

Step 3. in your python path, place the brutalist folder 
D:\Python\Lib\site-packages\pelican\themes

Step 4. Make your present working directory the pelican folder
D:\Pelican
and use command
pelican --listen

Step 5. open web browser and go to URL
http://localhost:8000/


I'm sorry if I forgot anything. I expect you will run into errors. This website helped,
https://docs.getpelican.com/en/3.6.3/quickstart.html
(You don't need to use the quickstart command, as all the information is already generated)

-Trent Sexton
DevTeam
