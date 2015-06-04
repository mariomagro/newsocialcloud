To transfer an account (service), make a POST request.

**URL:**

http://login.newsocialcloud.com/api/v2/account_transfer.json

**HTTP Methods:**

POST

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>account_id: The account id.</p>
<p>to_user_id: The user id to transfer the account to.</p>

**Authentication:**

Basic authentication with username and password or remote API key/access token belonging to the NewSocialCloud user.

**Success Response:**

{"status": "OK" }