To delete an account (service), make a DELETE request.

**URL:**

http://login.newsocialcloud.com/api/v2/account.json

**HTTP Methods:**

DELETE

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>account_id: The account id.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{"status": "OK" }