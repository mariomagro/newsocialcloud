To retrieve a user's list of services used by the Priority Inbox (for filtering purposes), make a GET request.

**URL:**

http://login.newsocialcloud.com/api/v2/inbox_services.json

**HTTP Methods:**

GET

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Parameters:**

application\_id: Your application id from http://newsocialcloud.com/developers.html

**Success Response:**

[
> {
> > "description": "YouTube",
> > "picture\_url": "https://i3.ytimg.com/i/j80sc-d9NXS43a6FGXRTHBVQ/1.jpg?v=4f0c620c",
> > "id": 1112,
> > "account\_name": "newsocialcloud"

> },
> {
> > "description": "Twitter",
> > "picture\_url": "![http://pbs.twimg.com/profile_images/43543595459669096449/rA7jKuts_normal.png](http://pbs.twimg.com/profile_images/43543595459669096449/rA7jKuts_normal.png)",
> > "id": 1223,
> > "account\_name": "newsocialcloud"

> },
> {
> > "description": "Facebook Fan Page",
> > "picture\_url": "http://graph.facebook.com/2127486502454/picture",
> > "id": 1235,
> > "account\_name": "newsocialcloud"

> }
]