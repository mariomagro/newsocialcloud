To register a new mobile device for PUSH notifications, make a POST request, authenticating as the user.

**URL:**

http://login.newsocialcloud.com/api/v2/device_registration.json

**HTTP Methods:**

POST

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>device_id: Required. The device registration ID, provided by Google or Apple.</p>
<p>device_type: Required. Either android or ios.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> "status": "OK"
}