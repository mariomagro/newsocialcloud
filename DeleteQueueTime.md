To delete one of the times on a SmartQueue, make a DELETE call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/queue_times.json

**HTTP Methods:**

DELETE

**Parameters:**

application\_id: Your application id from http://newsocialcloud.com/developers.html
queue\_time\_id: The id belonging to the SmartQueue time item.

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{"status": "OK"}