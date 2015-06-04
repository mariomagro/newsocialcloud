To retrieve a list of all active event subscriptions for your application, make a GET request.

**URL:**

http://login.newsocialcloud.com/api/v2/developer_subscriptions.json

**HTTP Methods:**

GET

**Parameters:**

application\_id: Your application id from http://newsocialcloud.com/developers.html

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

[
> {
> > <p>"object_name": "Contact",</p>
> > <p>"callback_url": "<a href='http://myurl.com'>http://myurl.com</a>",</p>
> > <p>"subscribers": [</p>
> > > {
> > > > <p>"user": {</p>
> > > > > <p>"fullname": "Mario Magro",</p>
> > > > > <p>"api_key": "XXXXXXXX",</p>
> > > > > <p>"login": "newsocialcloud",</p>
> > > > > <p>"email": "mario...@newsocialcloud.com"</p>

> > > > },
> > > > "id": 1

> > > }

> > ],
> > <p>"id": 1,</p>
> > <p>"event_name": "Create",</p>
> > <p>"verification_code": "test123"</p>

> }
]

**Error Response:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;

