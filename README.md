# Cloud_Messaging-Hosting-
In this task, you are required to implement any client side app,create a user notifications history page,use firebase cloud hosting to host the notification page online

Task 1

In this task, you are required to implement any client side app (Web, Android or iOS) using any language with the following functions:
- Your app should have a simple form with 2 fields to collect social media groups name, and type and a submit button to save this data in the database.
For example, Group Name "Fitness", Group Type "Sports"
- Every time the submit button is clicked, save the data in the database, clear the fields and start the collect process again.
- The database should carry multiple entries for the social media groups.
- Create another page that fetches the database to get list of stored groups and display them

Task 2
In this task, you are required to implement any client side app using any language with the following functions:
- Configure you client app to receive cloud messages in both foreground and background cases
- If your app receives a data message containing the key "subscribeToTopic" then it should opt in by subscribing to the topic value
 - If your app receives a data message containing the key "unsubscribeToTopic" then it should opt out by unsubscribing from the topic value

Task 3
In this task, you are required to create a user notifications history page as follows:
- Whenever you receive a cloud message on your client (from task 2), store that message in the database that you have created in task 1. Store both parts of the cloud message; data payload and notification payload
- Create a simple webpage called notifications that fetches the list of the notifications history from the database and displays it in a table
- Finally, use firebase cloud hosting to host the notification page online

Note: task 3 must be implemented using web client, however, you can use web or mobile client for task 2

Firebase could messaging documentation
https://firebase.google.com/docs/cloud-messaging/android/client

Firebase hosting documentation
https://firebase.google.com/docs/hosting
