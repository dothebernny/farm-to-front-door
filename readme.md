#Farm to Front Door

Farm to Front Door is a food delivery web app built in Python with Flask, SQLAlchemy & AngularJS. Database scraped from Good Eggs and the Noun Project, using BeautifulSoup and Selenium. Recipe suggestions pulled from Edamam API. Mapping with Google Maps Javascript API. Payment form using Stripe API. Using Twitter Bootstrap.

##Contents
- Tech Stack
- Features
- Installation
- About Me

##Tech Stack

Backend: Python, Flask, PostgreSQL, SQLAlchemy

Frontend: Javascript, AngularJS, jQuery, AJAX, HTML5, CSS3, Bootstrap

APIs: Edamam, Stripe, Google Maps Javascript & Geocoder

##Features

- Users can view the list of all products, filter products by category and search products by name.

- Users can add products to their shopping cart, edit their cart, and choose their delivery or pickup options.

- The app will suggest recipes to the user based on the contents of their shopping cart.

- Users can mark recipes as "favorites."

- Users can checkout and pay for their cart online by credit card.

- Users can view past orders, favorite recipes and account information on their account page.

- Users can view a map of available pickup locations.

Screenshots coming soon.

##Installation

To create and activate a virtual environment:
```
virtualenv env
source env/bin/activate
```

To install the project's dependencies:
```
pip install -r requirements.txt
```

To recreate the database:
```
createdb shop
pg_load database.sql
```

Create a secrets.sh file:
```
export EDAMAM="YOURKEYHERE"
export EDAMAM_KEY="YOURKEYHERE"
export STRIPE_TEST_SECRET="YOURKEYHERE"
export STRIPE_TEST_PUBLISHABLE="YOURKEYHERE"
export STRIPE_LIVE_SECRET="YOURKEYHERE"
export STRIPE_LIVE_PUBLISHABLE="YOURKEYHERE"
export GOOGLE_MAPS_KEY="YOURKEYHERE"
```

And source it:
```
source secrets.sh
```

##About Me

Farm to Front Door was developed by Maria Moy. Find her on [LinkedIn]
(www.linkedin.com/in/maria-k-moy) or [GitHub]
(www.github.com/gerdie). Maria is a software engineering fellow and freelance WordPress developer living in San Francisco.