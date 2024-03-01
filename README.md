![icon_logo](https://github.com/varun-FSDeveloper/BTreeFlight/assets/153975508/7b010aed-1466-46e3-8636-891bf59dcb25)



A flight booking Django application written in Python, HTML, CSS & Javascript.
This is the BTree project for Python Programming BootCamp with Python and Javascript.

#### Project Video: [Watch on Youtube](https://www.youtube.com/channel/UC3CWkAYRbqUFLq6wQF-VyPw)
#### Live Demo : [Click Here](http://54.175.64.42:8000/)


<img alt="flight" src="https://github.com/varun-FSDeveloper/BTreeFlight/assets/153975508/4a12264a-0f7c-474e-a9af-03e91b05f4e8.png">


### Features
1. Users can create their user account.
2. Users can book both one-way as well as round-trip tickets.
3. Webpages are mobile responsive.
4. Users can cancel their booked tickets.
5. Users can view their previously booked tickets (Both confirmed and cancelled tickets).
6. Tickets are downloadable as pdf document.
7. As-you-type Search

### Files & Directories
  - `capstone` - project directory.
    - `utils.py` - Contains all Django helper functions used in views.py.
    - `urls.py` - This file handles all the URLs of the project.
  - `flight` - main application directory.
    - `static` - contains all static content.
        - `css` - Contains all css files for styling the webpages.
        - `js` - Contains all javascript files used in the application.
        - `img` - Contains all image files used in the application.
    - `templates/flight` Contains all application templates.
        - `book.html` - Template for showing selected flight and reading Travellers data.
        - `bookings.html` - Template for showing bookings done by a user.
        - `index.html` - Home page template.
        - `layout.html` - Base template for all pages except login & register page.
        - `layout2.html` - Base template for login & register page.
        - `login.html` - Login user page.
        - `payment_process.html` - Page after completion of payment.
        - `payment.html` - Payment page.
        - `register.html` - Register user page.
        - `search.html` - Flight search result page.
        - `ticket.html` - Template for printing ticket(pdf).
    - `admin.py` - Contains some models for access to the Django administrator.
    - `models.py` - All models used in the application are created here.
    - `urls.py` - This file handles all the URLs of the web application.
    - `views.py` - This file contains all the application views.
    - `constant.py` - This file contains the fee amount which is charged to the user for booking flight tickets.
  - `requirements.txt` - This file contains all contains all the python packages that needs to be installed to run this web application.
  - `manage.py` - This file is used basically as a command-line utility and for deploying, debugging, or running our web application.

### Justification

1. Mobile responsive webpages.
2. More complex models.
3. More interatactive because webpages use ajax functionality (eg., fetch) written in javascript.
4. Converts html template to downloadable pdf.

### Installation

- Install Python3.9 from [here](https://www.python.org/downloads/) manually.
- Install project dependencies by running `py -m pip install -r requirements.txt`.
- Run the commands `py manage.py makemigrations` and `py manage.py migrate` in the project directory to make and apply migrations.
- Create superuser with `py manage.py createsuperuser`. This step is optional.
- Run the command `py manage.py runserver` to run the web server.
- Open web browser and goto `127.0.0.1:8000` url to start using the web application.

### Our Other Social Platforms

- ![Untitled design (9)](https://github.com/varun-FSDeveloper/BTreeFlight/assets/153975508/33ae95e1-c4d7-47d3-a160-90a6f060896b) Youtube - https://bit.ly/Youtubebtree
- ![icon_logo](https://github.com/varun-FSDeveloper/BTreeFlight/assets/153975508/948141f8-8cdc-4ef1-9615-0fb06cd35574) Instagram - https://bit.ly/Instagrambtree 
- ![Untitled design (10)](https://github.com/varun-FSDeveloper/BTreeFlight/assets/153975508/51189b66-5f75-43fc-a992-dca4805152a0) Facebook - https://bit.ly/btreefacebookpage 
- ![Untitled design (11)](https://github.com/varun-FSDeveloper/BTreeFlight/assets/153975508/0177cf07-7034-41fb-a41c-e292b2eea000) LinkedIn - https://bit.ly/Linkedinbtree 
- ![Untitled design (13)](https://github.com/varun-FSDeveloper/BTreeFlight/assets/153975508/81b02b10-6291-4aeb-8f14-d3f296f2698b) Twitter - https://bit.ly/Twitterbtree 

 Your Dev - Varun👍🏻
