# KamiProject
This is a college Project for an ai recipe generator.

After you clone this repository, you must get into the virtual machine following the steps below.

kamiIsCool is a virtual machine you need to be in the file above in the CMD and activate it with kamiIsCool/Scripts/activate.bat.

If you have an error, you may need to add something to your path variables by going to Advanced settings on your PC and then clicking on environment variables and then new, and then you copy the path that VS code gave you into it then it should work.

Then you go into the Kami folder and write "python manage.py runserver" if you don’t have any of the dependencies downloaded in the VM already follow the steps below.

You may have to run the following commands make sure you are in the VM it will say (kamiIsCool) in front of your location in the CMD (Make sure you are in KamiProject which is the top folder): pip install --force-reinstall -v "openai==0.27.0" pip install mysql-connector-python pip install django and sometimes it cannot dedicate something is downloaded so you have to another pip install but it tells you what is missing.

Make sure you change the database, names, passwords, and whatever else is different in your MySQL. You change these in the main.py and the settings.py there will be some you don’t have to change. After you change those make sure your XAMPP is turned on and go in your CMD put(you must be in the Kami folder): python manage.py makemigrations and maybe: python manage.py migrate

Then you go into the Kami folder and write "python manage.py runserver".

After that copy or press ctrl then click the IP that is in the CMD and paste it(only if your copied it) into a web browser.
