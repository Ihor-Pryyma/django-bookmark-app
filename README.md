# Django Bookmark App

This is a bookmarking app built using Python's Django framework. The main function of the app is to allow users to save the images of any website and share them for other users.

## Features

- User authentication and authorization
- Bookmark creation and management
- Tagging bookmarks for categorization
- Bookmarking images from other sites
- Saving and rating images
- Following and unfollowing other users
- Social authentication with Facebook, Twitter, and Google


## Installation

1. Clone the repository to your local machine.
2. Install the required packages using `pip install -r requirements.txt`.
3. Run the server using ` python manage.py runserver_plus --cert-file cert.crt`.

## Usage

1. Open your browser and navigate to `http://localhost:8000/account`.
2. You will be redirected to the homepage where you can view all the bookmarks.
3. Click on the `Add Bookmark` button to add a new bookmark.
4. Fill in the details and click on the `Save` button.
5. You will be redirected to the homepage where you can view the newly added bookmark.

## Apps

The following apps have been created for this project:

1. **account**: This app handles user authentication and registration.
2. **images**: This app is the main app that handles bookmark creation, editing, and deletion.
3. **actions**: This app provides search and store different users manipulations.

## Acknowledgments
- [Antonio Mele](https://github.com/AMELANIE/): Author of "Django 4 by Example."