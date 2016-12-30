# HiveMind

Requirements File Needed to run project 
1. Django 1.10.2 
2. Django allauth ​https://github.com/pennersr/django-allauth 
3. Django Cleanup - pip install django-cleanup
4. Pillow pip install pillow #not used but it is in our code  


Citations  
https://github.com/un1t/django-cleanup/blob/master/django_cleanup/ https://github.com/pennersr/django-allauth https://pillow.readthedocs.io/en/3.4.x/​ #not used but it is in our code   
We used Django cleanup and Allauth in our project. Pillow was going to be used for profile images, and will possibly be added later on.    
Django Cleanup deletes files once we delete the models associated with them and Allauth handles user authentication.   
Our Frontend used Material design and we obtained code from and based on the documentation


This project was done for CSC 210. It was a group project. The goal was to develop a CRUD website.  

HiveMind features:

Users can create accounts, add information such as a Bio and files to their profile pages. 
Users can create Hives(Groups) and add users to these Hives. They can also search users by username
Users can add files and other users from the Hives
They can also delete files and remove users
There is a comment board in the Hives
Once all users are removed from a Hive the Hive autodeletes. 

TODO:
Add profile pictures
Do more JS stuff
