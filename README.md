##Let's Build Snapchat

You're now snapchat developers. It's your job to build out the User class and the Image class. You'll want to make sure to setup a SQL database with ActiveRecord, create migrations for your tables, and populate those tables with data using tux.

### User class
Users should:
+ Inherit from ActiveRecord::Base
+ Have a username attribute
+ has_many Snaps

###Snap class
Snaps should:
+ Inherit from ActiveRecord::Base
+ Should have a image_file, caption, and user_id attribute
+ belongs_to user

### Views
+ Create a view that displays all the snaps and the username that sent them


BONUS:
+ Create a "delete button" for each snap, to delete it from the view and the database

