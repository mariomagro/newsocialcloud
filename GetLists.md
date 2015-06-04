To retrieve lists of services for a given user, make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/lists.json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>type: Optional. all, owner, contributor or consumer.</p>
<p>list_type: Optional. mixed, social, sms or email. To filter by multiple list types, separate with commas. E.g. sms,email.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the newsocialcloud user.

**Success Response:**

[
> {
> > "consumers": [
> > > {
> > > > "user": {
> > > > > "fullname": "Jose Garrido",
> > > > > "id": 59119,
> > > > > "color": "#8694e9",
> > > > > "login": "jgarrido"

> > > > },
> > > > "id": 47629

> > > },
> > > {
> > > > "user": {
> > > > > "fullname": "Mario Magro",
> > > > > "id": 77515,
> > > > > "color": "#af1c22",
> > > > > "login": "mmagro"

> > > > },
> > > > "id": 47630

> > > }

> > ],
> > "contributors": [
> > > {
> > > > "user": {
> > > > > "fullname": "Jose Garrido",
> > > > > "id": 59119,
> > > > > "color": "#8694e9",
> > > > > "login": "jgarrido"

> > > > },
> > > > "id": 47631

> > > },
> > > {
> > > > "user": {
> > > > > "fullname": "Mario Magro",
> > > > > "id": 77515,
> > > > > "color": "#af1c22",
> > > > > "login": "mmagro"

> > > > },
> > > > "id": 47632

> > > }

> > ],
> > "id": 47925,
> > "user\_id": 5131,
> > "item\_count": 0,
> > "list\_type": "Social",
> > "list\_name": "My List"

> },
> {
> > "consumers": [.md](.md),
> > "contributors": [.md](.md),
> > "id": 630,
> > "user\_id": 5131,
> > "item\_count": 2,
> > "list\_type": "Social",
> > "list\_name": "newsocialcloud Twitter"

> },
> {
> > "consumers": [.md](.md),
> > "contributors": [.md](.md),
> > "id": 9631,
> > "user\_id": 5131,
> > "item\_count": 0,
> > "list\_type": "Social",
> > "list\_name": "Twitter and Facebook"

> }
]