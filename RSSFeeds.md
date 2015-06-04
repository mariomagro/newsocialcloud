Retrieve the authenticated user's RSS Feeds.

**URL:**

http://newsocialcloud.com/api/v2/rssfeeds.json

**HTTP Methods:**

GET

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Parameters:**

application\_id: Your application id from http://newsocialcloud.com/developers.html

**Success Response:**

[
> {
> > "feed\_url": "http://feeds.mashable.com/Mashable",
> > "id": 1,
> > "feed\_name": "Mashable",
> > "user\_id": 5131,
> > "created\_at": "2010/01/21 14:36:11 +0000"

> },
> {
> > "feed\_url": "http://social-media.alltop.com/rss/",
> > "id": 5,
> > "feed\_name": "Social Media Alltop",
> > "user\_id": 5131,
> > "created\_at": "2010/01/21 14:44:12 +0000"

> },
> {
> > "feed\_url": "http://webworkerdaily.com/feed/",
> > "id": 6,
> > "feed\_name": "Web Worker Daily",
> > "user\_id": 5131,
> > "created\_at": "2010/01/22 09:09:23 +0000"

> },
> {
> > "feed\_url": "http://mario.newsocialcloud.com/rss.xml",
> > "id": 20,
> > "feed\_name": "Mario's blog",
> > "user\_id": 5131,
> > "created\_at": "2010/02/12 11:52:40 +0000"

> },
> {
> > "feed\_url": "http://feeds.feedburner.com/readwriteweb",
> > "id": 21,
> > "feed\_name": "RWW",
> > "user\_id": 5131,
> > "created\_at": "2010/02/16 13:42:48 +0000"

> },
> {
> > "feed\_url": "http://www.amazon.co.uk/rss/bestsellers/books/?tag=newsocialcloud-21",
> > "id": 37,
> > "feed\_name": "Amazon Books Bestsellers",
> > "user\_id": 5131,
> > "created\_at": "2010/02/27 13:36:38 +0000"

> },
> {
> > "feed\_url": "http://www.amazon.co.uk/rss/bestsellers/electronics?tag=newsocialcloud-21",
> > "id": 38,
> > "feed\_name": "Amazon Electronics Bestsellers",
> > "user\_id": 5131,
> > "created\_at": "2010/02/27 13:41:17 +0000"

> },
> {
> > "feed\_url": "http://www.amazon.co.uk/rss/bestsellers/videogames?tag=newsocialcloud-21",
> > "id": 39,
> > "feed\_name": "Amazon Videogames Bestsellers",
> > "user\_id": 5131,
> > "created\_at": "2010/02/27 13:43:43 +0000"

> }
]

**Error Response:**

{{
> "error": {
> > "type": "InvalidHTTPMethod",
> > "message": "PUTisinvalidforthisendpoint."

> }
}