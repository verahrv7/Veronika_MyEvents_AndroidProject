# My Events Android App

For this project, I developed an Android application called My Events. The main purpose of the app is to help users keep track of important events such as birthdays, appointments, meetings, and other plans. I wanted the app to be simple and easy to use. Users can create an account, log in, add events, update them, view their saved events, and delete events they no longer need. I also added an option for SMS reminders.

## User Needs and UI Design

When I designed the app, I tried to think about what a user would actually need and how to make those features easy to find. The app includes a login screen, an event screen where users can view and manage their events, and an SMS permission screen.

I tried to keep the interface simple instead of adding too many buttons or unnecessary features. The event screen allows users to see their saved events and gives them clear options to add, update, or delete an event. I think this design works well because a user can understand what to do without having to spend much time learning how to use the app.

## Coding Approach

I approached the coding process one part at a time. Instead of trying to make the entire application work at once, I worked on individual features and tested them as I went. I connected the Java code to the XML layouts and used SQLite to store user accounts and event information.

One thing I learned during this project is that testing frequently makes development much easier. When something stopped working, it was easier to figure out what caused the problem if I had tested the previous step. I would definitely use this approach again in future projects.

## Testing

I tested the application using the Android Emulator in Android Studio. I tested creating a new account and logging in with saved information. I also tested adding, viewing, updating, and deleting events. I closed and reopened the application to make sure the information stored in the database was still there.

I also tested the SMS permission because the app needs to continue working whether the user allows or denies that permission. Testing was very important because there were several times when the project built successfully but I still needed to check how a feature actually behaved when using the app.

## Challenges and Problem Solving

One of the biggest challenges for me was getting all of the different parts of the application to work together. The UI, Java code, SQLite database, and permissions all had to connect correctly. There were times when fixing one problem led me to discover another one.

I had to slow down, look at the errors, and test different solutions instead of trying to change everything at once. Working through those problems helped me understand Android Studio much better and made me more comfortable troubleshooting problems on my own.

## What I Am Most Proud Of

I am particularly happy with the event management portion of the application. Users can create, view, update, and delete events, and the information is stored in the SQLite database. Seeing the information remain available after closing and reopening the app helped me understand how the database and user interface work together.

Overall, this project gave me much more experience with the complete mobile application development process. Before this project, I mostly thought about creating screens and writing code separately. Now I have a better understanding of how the UI, database, permissions, testing, and user needs all have to work together to create a functional application.
