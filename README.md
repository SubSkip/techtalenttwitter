## Getting Started

Welcome to my Tech Talent South Social Media project. This project was completed over three course days and includes usage of: HTML/CSS, JS, Thymeleaf, Bootstrap, Lombok, and Java. Currently, the application only runs from within Visual Studio Code using the applicable extensions.

## Assignment

Create a Social Media/Twitter application:

1. In each of our html pages, we've included several css and js files. Break this out into a fragment and then include the fragment on each page.

2. Add a sign up button to the login page so that it's easier to navigate. This will need to be a mini form that just makes a get request.

3. In our AuthorizationController, we sent back a success message in the model if the registration was successful. We haven't done anything with it yet. On the registration page, if a success message comes back, hide the form, display the success message, and display a button to navigate to the login page. If a user is filling out form still (no success message included in the model), then the page should look the same as it does now.

4. On the main feed page, display a message saying no tweets are available when that is the case, rather than showing an entirely blank page like we are right now.

5. On the main feed page, improve the styling of the tweets. Check out the bootstrap list-group and list-group-item classes and use them to display each tweet inside of a box.

6. Let's think back to day 1. In our AuthorizationController, we sent back a success message in the model if the registration was successful. We haven't done anything with it yet. On the registration page, if a success message comes back, hide the form, display the success message, and display a button to navigate to the login page. If a user is filling out form still (no success message included in the model), then the page should look the same as it does now.

7. Add username links to the main feed, just like we did in the user and hashtag pages.

8. On the main feed, we currently show all tweets in the system. Change it so that it only shows tweets for the accounts the user is following.

9. On the users page, display the text '(Me)' next to the username of the currently logged in user.
