To create a new event subscription for the authenticated user, make a POST request. Once configured, NewSocialCloud will issue a POST with the following parameters to your callback url: verification\_code, object\_name, event\_name, data.

**URL:**

http://login.newsocialcloud.com/api/v2/event_subscription.json

**HTTP Methods:**

POST

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>subscription_id: Required. The specific developer_subscription event that the authenticated user will be subscribing to.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user that will be subscribing to the event.

**Success Response:**

{"status": "OK" }

**Error Response:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;

