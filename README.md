# Batch Script to Runserver Your Django App

This batch script will get the IP Adress of your computer then run the server based on the IP Address.
<br>The same result with if you run: `python manage.py runserver your_ip_address:80`

# How to Use
1. put this script file in your django app root (in the same level with your manage.py). 
2. double click the script file to run it.
3. the cmd window will pop up immediately, there will be IP address shown, you can access the app with that IP address.

The IP Address shown in the command prompt is the url of your app. Make sure the device is in the same network with the server.
<br><strong>Important to note:</strong> if you're using virtual environment in your app, you need to adjust your virtual environment folder name or change the `venv\Scripts\activate` in the script with your virtual environment's path.

Have fun~
