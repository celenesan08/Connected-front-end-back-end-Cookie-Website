USING FLASK TO CONNECT FRONTEND & BACKEND
1.	Install Python 3 
2.	Create a Project Folder
a.	 make a folder “my-portfolio”
b.	Check it in terminal: ~/Desktop/my-portfolio 
3.	Create a Virtual Environment: a virtual environment keeps your python packages organized and avoids conflicts. (source venu/bin/activate) 
a.	Like a sandbox for python projects
b.	A separate workspace for your project
c.	Open Terminal in your Project Folder 
Create Virtual Environment in your my-portfolio 
1.	How to create and use your virtual environment
a.	Go to your project folder in terminal
cd ~/Desktop/my-portfolio
2.	Create the virtual environment 
a.	Python3 -m venv venv 
This makes a new folder called venv inside my-portfolio
3.	Turn it on (activate it)
a.	Source  venv/bin/activate 
i.	This should follow: (venv)celenesan@Celenes-MacBook-Air my-portfolio %
4.	Install Flask inside this environment 
a.	In terminal: pip install flask 
5.	Run Flask
a.	In terminal: python3 app.py 
NOTE: do not create a folder for app.py in my-portfolio because terminal needs a file, not a folder. Static and Templates can be in folders. (static: Script.js & style.css, templates:Index.html)
