# AgoraAndroid-Prototype
Prototype build for AgoraAndroid App based on UI Mockups

Here is the explaination for the UI Mockups as explained in [!232](https://gitlab.com/aossie/agora-android/-/merge_requests/232)

### App Theme
* Flat Material Style Design.
* Each color of the palette has its own meaning to describe each function. <br>
![colorstyles](https://gitlab.com/aossie/agora-android/uploads/7cf0914e0169e7ce7170323007176d79/colorstyles.png)

Used standard Roboto Fonts (Bold Medium Regular) <br>
![fonts](https://gitlab.com/aossie/agora-android/uploads/6c419c38384352b6479e0a8bc1ff0777/fonts.png)

### UI States
* I preferred using the Custom Button Layout. <br>
* I also revamped the theme of the EditText view. <br>
* I have used steps indicator wherever necessary to make it more intuitive <br>
![uistates](https://gitlab.com/aossie/agora-android/uploads/3760541dc79d9e9f5f99dff51121cb03/uistates.png)

### Splash and Walkthrough
* I have kept it as simple as possible. <br>
* Thinking to include a small animation in the future(if necessary). <br>
* Walkthrough comes when the user opens the app for the first time. <br>
![splash](https://gitlab.com/aossie/agora-android/uploads/0d60b6ab9645111c5e080c214d06e3ec/splash.jpg)

### LogIn and SignUp
* Simple smooth and clean. <br>
* Also added Two factor Authentication and Security Question Based LogIn (derived from Agora Web) <br>
![login](https://gitlab.com/aossie/agora-android/uploads/a6653479acadd702c828b7f02a8dfedb/login.jpg)

### Home Screens
* With increasing screen size, it became important to add the frequently used controls at the bottom of the Layout. <br>
* So I preferred the bottom nav bar over side navbar. <br>
* To make it simple I confined myself to include only create election, home and all election buttons on the navbar and added remaining into the Bottom sheet. <br>
In the profile-section added an option to edit the profile picture. <br>
![homeProfile](https://gitlab.com/aossie/agora-android/uploads/bd21cb069a4fd92d5e565f1dc7f41c8b/homeProfile.jpg)

### Your Elections
* Here I have added two new options, Sort and Filter. <br>
* Sort: Contains options to sort the elections by date, number of voters <br>
* Filter: Used to filter of only required elections based on a voting algorithm or a candidate name... <br>
![yourElections](https://gitlab.com/aossie/agora-android/uploads/f71a672b7c601492b8cabe56f0294f97/yourElections.jpg)

### Election Details
* Added major points on top as chips. <br>
* For Polls user gets and option to generate Voting URL (derived from Agora Web) <br>
* Slightly revamped the Invite voters Page. <br>
![electionDetails](https://gitlab.com/aossie/agora-android/uploads/c5a593c962eba06e47564a9daf6df69d/electionDetails.jpg)

### Create Election
* Here I have added steps indicator which helps users to track the progress. <br>
* For voting algorithm selection I used an Expandable Dropdown view. <br>
* I also included a column where we can add a description of the voting algorithm (from available sources, in the future). <br>
![addElection](https://gitlab.com/aossie/agora-android/uploads/cccf6a41529d570f876862f42cc01cb6/addElection.jpg)

### Cast Vote
* Followed same layout pattern as of Create Election <br>
* Step1: User get to know Details about Election <br>
* Step2: Select a Candidate to be added into ballot <br>
* step3: Review the Ballot and Cast Vote <br>
* Step2 is different for Poll (public election) where user can post scores to each candidate (derived from Agora Web) <br>
![castVote](https://gitlab.com/aossie/agora-android/uploads/e14e674fc216b06e1a3ef5742f2e4d19/castVote.jpg)

### Empty and No Network States
* According to Material Design Guidelines, Empty States should be designed to prevent confusion of the user. <br>
* Empty State appears whenever there is nothing to display on a page. <br>
* And No Network appears in case of any network connection issues. <br>
![emptyStates](https://gitlab.com/aossie/agora-android/uploads/1961d18c334845af093586264a7be8c4/emptyStates.jpg)

### Secure LogIn (optional)
* I would also like to add a secure logIn feature, where a user can enable if necessary. (just like WhatsApp and other apps) <br>
* Fingerprint or Pin based LogIn  <br>
![secureLogin](https://gitlab.com/aossie/agora-android/uploads/bbda1b6706a148ae418a8809060c3707/secureLogin.jpg)

### Dark Theme (Can-Can, in future)
* Dark themes reduce the luminance emitted by device screens,blah blah... Everyone knows advantages of Dark theme.. <br>
* So, As every part of designs is constructed following Material Design Principles it will be easy to implement a dark theme for the same in the future. <br>
![dark](https://gitlab.com/aossie/agora-android/uploads/19a2195a6bfdabebd47fc145fcac71dc/dark.jpg)

**Note:** I will soon add link or a video to show the prototype.
