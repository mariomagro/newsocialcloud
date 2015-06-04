To retrieve details about a particular user's profile from a stream, make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v0/profile.json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>account_id: The account ID for this stream.</p>
<p>handle: The user's profile identifier. This is returned by the GetStream call in the uid field.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> "username": "George%20Smith",
> "fullname": "George%20Smith",
> "picture": "http://graph.facebook.com/8154007909/picture?type=normal",
> "location": "Location:%20N/A",
> "joined": "",
> "url": "http://www.facebook.com/profile.php?id=8154607909", "info": null,
> "profile\_streams": [
> > {
> > > name: "Stream",
> > > stream: "profile\_feed"

> > },
> > {
> > > name: "Tagged",
> > > stream: "profile\_tagged"

> > }

> ],
> "profile\_actions": [
> > {
> > > "name": "Follow",
> > > "action": "follow",
> > > "can\_message": false,
> > > "message\_prefix": ""

> > },
> > {
> > > "name": "DM",
> > > "action": "dm",
> > > "can\_message": true,
> > > "message\_prefix": "d "

> > },
> > {
> > > "name": "Reply",
> > > "action": "reply",
> > > "can\_message": true,
> > > "message\_prefix": "@"

> > }

> ]
}
The profile\_streams array returns a list of other possible streams that can be retrieved for the current profile. These can be used with the GetStream call.
For example: http://login.newsocialcloud.com/api/v0/stream-fetch?handle=xxxx&stream=profile_tagged&account_id=xxxx

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>account_id: The account ID for this stream.</p>
<p>handle: The user's profile identifier. This is returned by the GetStream call in the uid field.</p>
<p>stream: The value returned in the stream field within the profile_streams array.</p>

**Error Response:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;

