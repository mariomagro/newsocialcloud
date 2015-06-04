To retrieve the list of all Content Libraries for a given user, make a GET call using basic authentication.

URL:
http://login.newsocialcloud.com/api/v2/content_libraries.json

HTTP Methods:
GET

Parameters:

application\_id: Your application id from http://newsocialcloud.com/developers

type: Optional. all, owner, contributor or consumer.

Authentication:

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

Success Response:
[
> {
> > "created\_at": "2013/08/29 10:18:04 +0000",
> > "consumers": [.md](.md),
> > "content\_type": "Message",
> > "contributors": [.md](.md),
> > "updated\_at": "2013/08/29 10:18:04 +0000",
> > "id": 2,
> > "user\_id": 5131,
> > "library\_name": "My Content"

> },
> {
> > "created\_at": "2013/08/29 11:21:42 +0000",
> > "consumers": [.md](.md),
> > "content\_type": "Message",
> > "contributors": [.md](.md),
> > "updated\_at": "2013/08/29 11:21:42 +0000",
> > "id": 3,
> > "user\_id": 5131,
> > "library\_name": "Quotes"

> },
> {
> > "created\_at": "2013/08/29 11:22:22 +0000",
> > "consumers": [.md](.md),
> > "content\_type": "Message",
> > "contributors": [.md](.md),
> > "updated\_at": "2013/08/29 11:22:22 +0000",
> > "id": 4,
> > "user\_id": 5131,
> > "library\_name": "Quotes"

> },
> {
> > "created\_at": "2013/08/29 11:36:56 +0000",
> > "consumers": [
> > > {
> > > > "created\_at": "2013/08/29 11:36:56 +0000",
> > > > "user": {
> > > > > "fullname": "Mario Magro",
> > > > > "id": 5131,
> > > > > "color": "#b6617c",
> > > > > "login": "newsocialcloud"

> > > > },
> > > > "id": 46736

> > > }

> > ],
> > "content\_type": "Message",
> > "contributors": [.md](.md),
> > "updated\_at": "2013/08/29 11:36:56 +0000",
> > "id": 5,
> > "user\_id": 5131,
> > "library\_name": "Quotes"

> },
> {
> > "created\_at": "2013/08/29 11:39:16 +0000",
> > "consumers": [
> > > {
> > > > "created\_at": "2013/08/29 11:39:17 +0000",
> > > > "user": {
> > > > > "fullname": "Mario Magro",
> > > > > "id": 5131,
> > > > > "color": "#b6617c",
> > > > > "login": "newsocialcloud"

> > > > },
> > > > "id": 46737

> > > },
> > > {
> > > > "created\_at": "2014/08/29 11:39:17 +0000",
> > > > "user": {
> > > > > "fullname": "newsocialcloud",
> > > > > "id": 1,
> > > > > "color": "#d79d54",
> > > > > "login": "mmag"

> > > > },
> > > > "id": 46738

> > > }

> > ],
> > "content\_type": "Message",
> > "contributors": [.md](.md),
> > "updated\_at": "2013/08/29 11:39:16 +0000",
> > "id": 6,
> > "user\_id": 5131,
> > "library\_name": "Quotes"

> },
> {
> > "consumers": [
> > > {
> > > > "created\_at": "2013/08/29 11:36:56 +0000",
> > > > "user": {
> > > > > "fullname": "Mario Magro",
> > > > > "id": 5131,
> > > > > "color": "#b6617c",
> > > > > "login": "newsocialcloud"

> > > > },
> > > > "id": 46736

> > > }

> > ],
> > "contributors": [.md](.md),
> > "id": 5,
> > "user\_id": 5131,
> > "library\_name": "Quotes (Mario Magro)"

> },
> {
> > "consumers": [
> > > {
> > > > "created\_at": "2013/08/29 11:39:17 +0000",
> > > > "user": {
> > > > > "fullname": "Mario Magro",
> > > > > "id": 5131,
> > > > > "color": "#b6617c",
> > > > > "login": "newsocialcloud"

> > > > },
> > > > "id": 46737

> > > },
> > > {
> > > > "created\_at": "2013/08/29 11:39:17 +0000",
> > > > "user": {
> > > > > "fullname": "newsocialcloud",
> > > > > "id": 1,
> > > > > "color": "#d79d54",
> > > > > "login": "mmag"

> > > > },
> > > > "id": 46738

> > > }

> > ],
> > "contributors": [.md](.md),
> > "id": 6,
> > "user\_id": 5131,
> > "library\_name": "Quotes (Mario Magro)"

> }
]