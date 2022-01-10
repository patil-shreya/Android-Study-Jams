# Android-Study-Jams

# Quick Notes Application

# Problem Statement:

Taking notes is something that we as students do on a regular basis. 
Not only students but also almost all of the people take notes everyday on some topic or another.
Sometimes we may not be able to carry a notebook, or paper, or pen with us.
In this case it becomes a dilemma for us to take down notes. There are various important things or keywords that we may want to note down,
and arent able to do so because of not having note taking tools.

# Proposed Solution:

This project proposes a "Quick Notes Application" which helps us take down notes quickly through a mobile application.
We do not have to worry about always carrying a notebook or pen as we have our Quick Notes Application i.e. Note It on our mobiles.
Its features include adding quick notes, updating previously added notes as well as keeping track of the date and time notes were added and updated.
Currently the notes can be added by typing only. The project's scope is to take down voice notes as well as adding security to the notes.

# Screenshots:
<img src="https://github.com/patil-shreya/Android-Study-Jams/blob/main/Screenshots/Screenshot_20220110-113507_Note%20It.jpg" height="400" width="300">    <img src="https://github.com/patil-shreya/Android-Study-Jams/blob/main/Screenshots/Screenshot_20220110-113516_Note%20It.jpg" height="400" width="300">    <img src="https://github.com/patil-shreya/Android-Study-Jams/blob/main/Screenshots/Screenshot_20220110-113537_Note%20It.jpg" height="400" width="300">
<img src="https://github.com/patil-shreya/Android-Study-Jams/blob/main/Screenshots/Screenshot_20220110-113610_Note%20It.jpg" height="400" width="300">    <img src="https://github.com/patil-shreya/Android-Study-Jams/blob/main/Screenshots/Screenshot_20220110-113617_Note%20It.jpg" height="400" width="300">
   



# Functionality & Concepts used :

The App has a very simple and interactive interface which helps everyone take quick notes. 
Following are few android concepts used to achieve the functionalities in app :

Constraint Layout : Most of the activities in the app uses a flexible constraint layout, which is easy to handle for different screen sizes.

Simple & Easy Views Design : Use of familiar audience EditText with hints and interactive buttons made it easier for everyone to take down notes without much hassle. Apps also uses App Navigation to switch between different screens.

LiveData, Viewmodel, Room Database:Live Data is a data holder class that can be observed. It holds as well as caches the latest version of the data and notifies our observer whenever the data is being updated or changed. Live Data automatically manages all of this since it is aware of the relevant lifecycle status changes while observing.
View Modal acts as a communication center between repository and UI. The UI no longer needs to worry about the origin of the data. The ViewModel instances survive Activity/Fragment recreation.
Room Database is an improvised version of SQLite Database. It simplifies the database work and serves as an access point to the underlying SQLite database. The room uses DAO to issue queries to the SQLite database.

# Application Link & Future Scope :

The app is currently being used by a limited no. of users. You can access the app: [link]

Once the app is fully functional we plan to add a security to the application to make the notes moe secure.
We also plan to add the feature to take voice notes.
