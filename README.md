# ordermanagement-mod4

to add signals to your project first you need to create a signals.py file in app directory and add some logics you need based on your project to it 
and we should import some libs then remove that logics from views.py file .in this file sender is your model instance is a user that recently beenn created and created 
set to True if the new user has just created.
then you need to change your apps.py and retype ready method and import 'accounts.signals' .then change the app name in settings.py file to accounts.apps.AccountConfig
(this name was wrote in apps.py file)
