# Capstone_2

1. What tech stack will you use for your final project? We recommend that you use
React and Node for this project, however if you are extremely interested in
becoming a Python developer you are welcome to use Python/Flask for this
project.

_React/Redux/Express/Ajax/Node_

2. Is the front-end UI or the back-end going to be the focus of your project? Or are
you going to make an evenly focused full-stack application?

_Accessibility will be the focus, and this will likely have ramifications for the front and back end_

3. Will this be a website? A mobile app? Something else?

_It will be a website that collects repos under the a11y topic on github and lets you tweet them_

4. What goal will your project be designed to achieve?

_It will generate more traffic around the a11y topic, driving up awareness_

5. What kind of users will visit your app? In other words, what is the demographic of
your users?

_Github users! Demographic will be developers of all kinds._ 

6. What data do you plan on using? How are you planning on collecting your data?
You may have not picked your actual API yet, which is fine, just outline what kind
of data you would like it to contain. You are welcome to create your own API and
populate it with data. If you are using a Python/Flask stack are required to create
your own API.

_I'll be using the Github API._


7. In brief, outline your approach to creating your project (knowing that you may not
know everything in advance and that these details might change later). Answer
questions like the ones below, but feel free to add more information:

a. What does your database schema look like?
_Small, just for minimal user functionality: TABLE users COLUMNS id, username, password_

b. What kinds of issues might you run into with your API? This is especially
_important if you are creating your own API, web scraping produces
notoriously messy data. 
Probably won't run into many issues with Github's API since it is pretty straightforward. 
I may also add Twitter's API depending on how this goes_

c. Is there any sensitive information you need to secure?
_User passwords, I'll need JWTs and authorization routes._

d. What functionality will your app include?
_You'll be able to tweet from the website. You'll also be able to sign in, save links to tweet on a user page, and signout, logout, or edit your 
user info_

e. What will the user flow look like?
_User visits site, signs up/logs in, views a11y links, hits add/tweet, can view them from his user-links page_

f. What features make your site more than a CRUD app? What are your
stretch goals?
_It's more than a CRUD app in that it allows you to tweet from it_
