To find all the lists that a service or contact does NOT belong to, make a GET request.

**URL:**

http://login.newsocialcloud.com/api/v2/lists_not_member_of.json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>item_id: The recipient_id of the service retrieved from the Services call or the contact_id of a contact.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

[
> {
> > <p>"color": "#057b79",</p>
> > <p>"list_name": "001_Academy_Newsletter",</p>
> > <p>"user_id": 5131,</p>
> > <p>"consumers": <a href='.md'>.md</a>,</p>
> > <p>"contributors": <a href='.md'>.md</a>,</p>
> > <p>"item_count": 10286,</p>
> > <p>"id": 35529,</p>
> > <p>"list_type": "Mixed"</p>

> }
]