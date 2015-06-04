To retrieve priority inbox items for a given user, make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v1/priority-posts.format

**Formats:**

Replace format with either xml or json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>page: Optional. The page number to return.</p>
<p>per_page: Optional. The number of items to return per page. Default is 20.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the newsocialcloud user.

**Success Response:**

[
> {
> > "account\_detail": {
> > > "account\_id": 43674,
> > > "account": {
> > > > "service": {
> > > > > "stream\_actions": [
> > > > > > {
> > > > > > > "name": "Like",
> > > > > > > "action": "like",
> > > > > > > "can\_message": false,
> > > > > > > "message\_prefix": ""

> > > > > > },
> > > > > > {
> > > > > > > "name": "Comment",
> > > > > > > "action": "comment",
> > > > > > > "can\_message": true,
> > > > > > > "message\_prefix": ""

> > > > > > }

> > > > > ]

> > > > }

> > > },
> > > "account\_name": "newsocialcloud",
> > > "uid": "21274802454"

> > },
> > "message\_type": "Post",
> > "responder\_fullname": "Rosa Maria",
> > "account\_detail\_id": 104714,
> > "relative\_created\_at": "8 hours ago",
> > "post\_link": "",
> > "original\_message": null,
> > "url": null,
> > "sentiment": 2,
> > "isRead": 0,
> > "account\_name": "newsocialcloud",
> > "post\_body": "Hi, this is the post-body.",
> > "uid": "100000103828925",
> > "id": 28428019,
> > "responder\_identifier": "100000103828925",
> > "responder\_avatar": "http://graph.facebook.com/100000103828925/picture",
> > "message\_html": "",
> > "account\_avatar": "http://graph.facebook.com/21274802454/picture",
> > "post\_picture": "",
> > "message\_text": "",
> > "service\_name": "facebook(page)",
> > "service\_image": "![https://d3u44nfepqqjcg.cloudfront.net/images/icons/facebook_page.gif](https://d3u44nfepqqjcg.cloudfront.net/images/icons/facebook_page.gif)",
> > "created\_at": "2012/05/18 00:20:11 +0000"

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

