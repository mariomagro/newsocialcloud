To delete an add-on, make a DELETE call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/add_ons.json

**HTTP Methods:**

DELETE

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>add_on_id: The id of the add-on to be deleted.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{"status": "OK"}