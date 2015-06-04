To create a new content library, make a POST call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/content_library.json

**HTTP Methods:**

POST

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>library_name: The name of the library.</p>
<p>consumers: A comma separated list of user ID's that can consume content in this library. User ALL to add all team members/users this user manages.</p>
<p>contributors: A comma separated list of user ID's that can contribute content to this library. User ALL to add all team members/users this user manages.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> "created\_at": "2014/08/29 11:39:16 +0000",
> "consumers": [
> > {
> > > "user": {
> > > > "fullname": "Mario Magro",
> > > > "id": 5131,
> > > > "color": "#b6617c",
> > > > "login": "newsocialcloud"

> > > },
> > > "id": 46737

> > },
> > {
> > > "user": {
> > > > "fullname": "newsocialcloud.com",
> > > > "id": 1,
> > > > "color": "#d79d54",
> > > > "login": "marmag"

> > > },
> > > "id": 46738

> > }

> ],
> "content\_type": "Message",
> "contributors": [.md](.md),
> "updated\_at": "2013/08/29 11:39:16 +0000",
> "id": 6,
> "user\_id": 5131,
> "library\_name": "Quotes"
}