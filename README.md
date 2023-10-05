## Getting Started


Flutter Web & Firebase Integration Task
We have a Flutter web application that needs to be integrated with Firebase to fetch and display data. We've taken the initial steps and integrated Firebase into the project.

Your Task:

Clone the GitHub repository to your local machine.
Set up the Firebase SDK in the Flutter web app. (Note: This might already be done. If so, verify the setup.)
Write the necessary code to connect to the Firebase Realtime Database.
Fetch data from the node named "FarmerData" in the Firebase Realtime Database.
Display the fetched data in a list format on the application's main screen.


Expected Structure of "FarmerData":

{
  "firebaseuserid": {
    "mobilenumber": {
      "acres": "String",
      "city": "String",
      "crop": "String",
      "mobile": "String",
      "name": "String",
      "remark": "String",
      "state": "String",
      "village": "String"
    },
