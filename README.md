# Django-Blog

## Purpose
A blog app created to learn how to create a website using Django.

## Functionality
Allows a user to register an account and login in to the website. The user is able to update their details. The user can then view other posts, and create their own posts. They are able to update or delete their own posts.

## Prerequisites
Requires python3, django, pillow, sqlite3

## Password Reset With Email (GMAIL)
To send emails to users with instructions on how to reset their password, do the following:
  - Locate the file: `django_project/settings.py`
  - Next to `EMAIL_HOST_USER`, enter in your email address.
  - Set up 2-Factor Authentication, if not already done.
  - Set up an App Password for this application. 
  - For these two steps I followed this [tutorial](https://devanswers.co/create-application-specific-password-gmail/).
  - Enter this App Password next to `EMAIL_HOST_PASSWORD`

## Acknowledgements
Website created following this [tutorial](https://www.youtube.com/playlist?list=PL-osiE80TeTtoQCKZ03TU5fNfx2UY6U4p) by Corey Shafer
