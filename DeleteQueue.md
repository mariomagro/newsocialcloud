To delete the user's NewSocialCloud SmartQueue, make a DELETE call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/queue.json

**HTTP Methods:**

DELETE

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>queue_id: The id belonging to the SmartQueue.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{"status": "OK"}