# chatApp

The first assignment was for the Chat app, an application developed and designed during the cs advanced programming course at Bar Ilan University.
The first level is to develop a chat app, hardcoded, by javascript, HTML, and React.
*Chat application build by HTML, Javascript* 
 
 -----In this exercise i used HTML & Javascript to build a chat application.----
 
Main page: login:
This app begins with a login page in which the app asks the user to type the user name and password. the users are 'hardcoded' and the list of the users(for check validation of the assignment) will be the following :
user name 1 : Bob , password: Ba102030.
user name 1 : Eve , password: E1122551.
user name 1 : Alice, password: AL205214.
user name 1 : Yotam, password: YoTheking1.
user name 1 : Dana, password: D0987654.
The rules of login is combination of numbers and characters only!
the users will be saved in a hardcoded array during all the paged until we'll use sockets.

also for aesthetic i used a toggle icon that we can click and see the password.
if the user didn't sign in to the app there is a link to the registration page.
if the user didn't type anything, a message will popup
Register page:
On this page, the user will type the user name and valid password - a combination of characters and numbers.
if the user didn't type anything, a message will popup
Chat room page:
on this page, we will see the chat room. the user will pick the chat he wants to use.
Chat rooms:
every room will show the messages between users.


----------More features that i have to add and didnt had time----------

 Chat room:
 First i will add an option when we will type in  the search input , and click enter, the relevant user will be the only one on the chat list - for doing it i will add a function for click event, the will iterate the array of users and search the relevant.
 For each chat room and user, i will add 3 more functions - option to send an image, an option to send a voice message, and an option to send a location
 To add these features I will create another block for each feature, paste the specific logo and add the onClick event for each relevant.
 
 another feature that will come after is the option to add another member, using the appendChild function and inner HTML to the chat list.
 
Also, an important feature is to add an option when the user will click Enter on a keyboard, on the register page and login page, the 'click on event' will synchronize.
also for the sending option.
