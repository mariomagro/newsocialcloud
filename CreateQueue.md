To create or NewSocialCloud SmartQueue for a given user, make a POST call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/queue.json

**HTTP Methods:**

POST

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>queue_name: The name of the queue.</p>
<p>auto_detect: This is not currently in use. Please use 0.</p>
<p>can_repeat: This is not currently in use. Please use 0.</p>
<p>contributors: Optional. A comma separated lists of user IDs representing users that can contribute to this queue.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> "queue\_times": [.md](.md),
> "can\_repeat": 0,
> "queue\_name": "My Queue",
> "id": 9004,
> "user\_id": 5131,
> "auto\_detect": 0
}