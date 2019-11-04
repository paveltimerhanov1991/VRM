
Skip to content

    Why GitHub?
                          


                    
Enterprise
Explore
                      

                    
Marketplace
Pricing
                       


                        

Sign in
Sign up
Code Issues 0 Pull requests 0 Projects 0 Security Pulse
Join GitHub today

GitHub is home to over 40 million developers working together to host and review code, manage projects, and build software together.
booking_app/README.md
@vhniii vhniii Update README.md 6328c04 on Sep 16
60 lines (39 sloc) 1.22 KB
Booking App
Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
Prerequisites

Needed software in your computer to run this software:

    php

sudo apt-get install php7.0-cli
sudo apt-get install php-xml

    composer

    SQLite

sudo apt-get install php-sqlite3

Installing

To install the software you have following options:

Cloning the project to your computer. If you have ssh access.

git glone git@gitlab.com:i-sepp/bcs-koolitus.git

Or download it manually from the gitlab page.

Then you need to have composer installed in your computer. And then you need to install composer packages in your project folder.

composer install

Testing

You can test by starting server and going to the following url:

symfony server:start
URL: localhost:8000/bookings/create

Built With

    Symfony - The web framework used
    Composer - Dependency Management
    Twig - Php template engine

License

This project is licensed under the MIT License.

    © 2019 GitHub, Inc.
    Terms
    Privacy
    Security
    Status
    Help

    Contact GitHub
    Pricing
    API
    Training
    Blog
    About

