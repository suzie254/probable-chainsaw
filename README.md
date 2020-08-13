# Project Name

INSTA-SITE

## Author's Details

Name: *Susan Akinyi.*

Email: *suzieakinyi08@gmail.com*

Tel:*+254718922958.*

### Project Description

A web application that is a site of instagram with basic functionality. A user can create posts and edit them.

### Project-Setup Instructions

1.Open your github account and search for github username: **wendymunyasi**

1. git clone using the following link.
   link: <https://github.com/suzie254/probable-chainsaw>
2. Open your terminal and run the command `python3 manage.py runserver`.
3. Click the local host link on your terminal to view the app on your browser.

### BDD

| Behaviour | Input | Output |
| --------- | ------| ------ |
|On loading the app you see the landing page with a navbar at the top and a sign up form| Clicking `Home`| You are redirected to the landing page if you had left the page or just loads the landing page again if you are still on the landing page.|
|Clicking the `View Posts` link on the navbar | Mouse click |You are redirected to a page where various posts are displayed.|
|Clicking the `New Image` | Mouse click | You are redirected to a page with a form for adding a new image.|
|Clicking the `Login/Logout` drop down menu | Mouse click | Displays the `Home`, `<your username>` and `logout` links if you are logged in, else displays `login`.|

After filling in the details in the signup form, you receive a httpresponse with a message *'We have sent you an email, please confirm your email address to complete registration.*
On confirming the email address, you are immediately logged in and redirected to the posts page.

## The following include the list of technologies used

**Python3.6**
**Django 3**
**JQuery**

### Known Bugs

The UI isn't as user friendly and the search functionaility is not working.
Deployment to Heroku.

### Collaborate

To collaborate, reach me through my email address suzieakinyi08@gmail.com
