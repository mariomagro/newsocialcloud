To share an account (service) with other users, make a POST request.

**URL:**

http://login.newsocialcloud.com/api/v2/account_shares.json

**HTTP Methods:**

POST

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>account_id: The account id.</p>
<p>contributors: A comma separated list of user ID's to share the service with.</p>

**Authentication:**

Basic authentication with username and password or remote API key/access token belonging to the NewSocialCloud user.

**Success Response:**

{"status": "OK" }