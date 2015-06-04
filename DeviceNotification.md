To send a push notification to mobile device, make a POST request, authenticating as the user. This will send a push notification to all devices registered to the authenticating user.

**URL:**

http://login.newsocialcloud.com/api/v2/device_notification.json

**HTTP Methods:**

POST

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>message: Required. The message that will be sent to the device. This needs to be a JSON message.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Response:**

{
> {
> "success": [
> > {
> > > <p>"last_error": "InvalidRegistration",</p>
> > > <p>"device_type": "android",</p>
> > > <p>"device_id": "12345"</p>

> > }
> > ],

> "failed": [
> > {
> > > <p>"last_error": "InvalidRegistration",</p>
> > > <p>"device_type": "android",</p>
> > > <p>"device_id": "999"</p>

> > }

> ]
}
}