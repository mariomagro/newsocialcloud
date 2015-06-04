To retrieve information about the authenticated user's company, make a GET request.

**URL:**

http://login.newsocialcloud.com/api/v2/company.json

**HTTP Methods:**

GET

**Parameters:**

application\_id: Your application id from http://newsocialcloud.com/developers.html

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> "total\_team\_members": 14,
> "company\_favicon": "http://newsocialcloud.com/favicon.ico",
> "company\_name": "NewSocialCloud Test",
> "account\_owner": "James Kane",
> "team\_members": [
> > {
> > > "fullname": "Peter Smith",
> > > "avatar": "![http://www.gravatar.com/avatar=http://newsocialcloud.com/images/silhouette.png](http://www.gravatar.com/avatar=http://newsocialcloud.com/images/silhouette.png)"

> > },
> > {
> > > "fullname": "Jon Smith",
> > > "avatar": "![http://www.gravatar.com/avatar=http://newsocialcloud.com/images/silhouette.png](http://www.gravatar.com/avatar=http://newsocialcloud.com/images/silhouette.png)"

> > }

> ],
> "company\_website": "http://xxxxxxx.com",
> "company\_email": "xxxxxx",
> "company\_logo": "![http://ccc.com/xxxxxx.jpg](http://ccc.com/xxxxxx.jpg)"
}

If this is a white label company, you'll receive the following additional fields:

{
> "theme": "smoothness",
> "language": "es",
> "contact\_us\_url": "http://support.mysite.com",
> "ga\_tracking\_code": "UA-47698035-1",
> "html\_widget\_code": "<div>Hello world</div>",
> "custom\_css": ".body {color: red;} div {color: green;}",
> "menus": [
> > {
> > > "name": "Google Apps",
> > > "submenus": [
> > > > {
> > > > > "name": "Calendar",
> > > > > "url": "http://apps.google.com/calendar",
> > > > > "type": "iframe"

> > > > },
> > > > {
> > > > > "name": "Mail",
> > > > > "url": "http://apps.google.com/mail",
> > > > > "type": "url"

> > > > },
> > > > {
> > > > > "name": "Drive",
> > > > > "url": "http://apps.google.com/drive",
> > > > > "type": "iframe"

> > > > }

> > > ]

> > }

> ]
}