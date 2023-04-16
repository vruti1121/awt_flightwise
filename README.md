![icon_logo](https://github.com/AVB100/awt_flightwise/blob/main/flight/static/img/icon_logo_white-outline.png)



A flight booking website written in Python, HTML, CSS & Javascript, using the Django Framework.
This is the final project for the Advanced Web Technology course taught at Pandit Deendayal Energy University.

<!-- #### Project Video: [Watch on Youtube](https://www.youtube.com/watch?v=3tD4OsuGmoo) -->


<!-- <img alt="flight" src="https://user-images.githubusercontent.com/56977388/178156598-69491e88-bd9a-42dc-88f3-afeb02d7161e.png"> -->


### Features
1. Users can create their user account.
2. Users can book both one-way as well as round-trip tickets.
3. Webpages are mobile responsive.
4. Users can cancel their booked tickets.
5. Users can view their previously booked tickets (Both confirmed and cancelled tickets).
6. Tickets are downloadable as pdf document.
7. As-you-type Search

### Files & Directories
  - `project` - project directory.
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
