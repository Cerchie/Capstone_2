# Capstone_2

1. What tech stack will you use for your final project? We recommend that you use
React and Node for this project, however if you are extremely interested in
becoming a Python developer you are welcome to use Python/Flask for this
project.

_React/Node/CLI_

2. Is the front-end UI or the back-end going to be the focus of your project? Or are
you going to make an evenly focused full-stack application?

_Backend-- making the image update in real time will be the toughest part_

3. Will this be a website? A mobile app? Something else?

_It will be code for a github widget image that updates in real=time!_

4. What goal will your project be designed to achieve?

Basically, it will be a pared-down version of 
https://github.com/anuraghazra/github-readme-stats

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
_I won't need one? (Ron: we should discuss)_

b. What kinds of issues might you run into with your API? This is especially
_important if you are creating your own API, web scraping produces
notoriously messy data. 
Probably won't run into many issues with Github's API since it is pretty straightforward, but
making my project an svg that updates to reflect changes to the API call will be the main problem._

c. Is there any sensitive information you need to secure?
_I don't think so._

d. What functionality will your app include?
_I'll design it to include one widget that count the number of commits.
From there, I can stretch my app to include more widget functionality._

e. What will the user flow look like?
_User copy/pastes the code from the readme into their profile readme,
enters their username inside the API call inside the image src markdown,
and saves their readme to see the widget._

f. What features make your site more than a CRUD app? What are your
stretch goals?
_It's more than a CRUD app in that it's not even a CRUD app--
I won't be deleting anything, for one, althought I'll need CRU. 
I'll be working a lot with API calls and the CLI I suppose to get 
a real-time widget. I'll stretch it by adding widget functionality
like a PR count._
