# Read 27

* ## Android Tasks and the Back Stack<br/>
Have you ever wondered Whats happening behind the screnes when you tap an app icon and the app launches..??It creates a stack of Activities.The Activities are Arranged in a stack(The back Stack) in the order in which each activity is opened by the User.For example, an email app might have one activity to show a list of new messages. When the user selects a Watsaap messenger icon, a new activity opens to view that messages. This new activity is added to the back stack. If the user presses the Back button, that new activity is finished and popped off the stack.<br/>
### behaviors of the Task and the Back Stack.<br/>
The application launcher makes another Task with the main Activity made and put in the foundation of the back stack (It has another job that we will Check it out later).<br/>
When the current Activity That we have created starts another Activity, then the new Activity is pushed on top of the stack and takes into focus.<br/>
The past Activity moves bellow the new Activity in the back stack and is Stopped. The system holds the present condition of this present Activity's UIs like content in the structure, scroll position and so on.<br/>
The Activities Keeps on piling the Back stack untill the back button is pressed<br/>
At the point when the Back Button is pressed then the present Activity is flown from the highest point of the back stack Hence it destroys the Activity and the past Activity resumes with its state reestablished.<br/>
The Back Button at that point continues popping the present Activities and reestablishing the past exercises. At the point when the last Activity is expelled from the back stack, at that point the Task ends to the screen that was last running before the making of the Task (for our situation the launcher screen or our main activity) Untill the back stack goes empty untill the task stopps existing And the Activities of different applications invoked by the intent are put into the same Task.<br/>

* ## Android SharedPreferences<br/>
Android provides many ways of storing data of an application. One of this way is called Shared Preferences. Shared Preferences allow you to save and retrieve data in the form of key,value pair.<br/>
In order to use shared preferences, you have to call a method getSharedPreferences() that returns a SharedPreference instance pointing to the file that contains the values of preferences.<br/>

![Image](img/android.jpg)

---
