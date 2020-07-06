# Cognirium_Django-Project

Prerequisites:
1. Ubuntu, Python 2.7, PIP


2. Create a Virtualenv

3. Activate virtual environment


Install dependencies:
pip install -r requirements.txt


START URL:

Registration URL:

http://127.0.0.1:8000/userprofile/register/

provide the details and submit will redirects to login page.



Sign In URL:

http://127.0.0.1:8000/userprofile/signin/

provide the credentials will navigate to public feed.



Blog Feed

http://127.0.0.1:8000/articles/all_posts/9/

On login, with that particular user the page redirects to the above url.


Post Feed:
http://127.0.0.1:8000/articles/all_posts/9/

In this page we can post a blog by providing heading and body and on submit post , will refresh the page and post can be seen.


Edit the Feed:
in the feed page, there is an option to edit the feed by clicking the edit button. on clicking the edit button the data gets populated in next page and edit request can be made by submitting it.
http://127.0.0.1:8000/articles/edit_message/11/


This actually stores into a seperate table, called EditArticles





