To update an existing content library, make a PUT call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/content_library.json

**HTTP Methods:**

PUT

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>content_library_id: The id of the content library to update.</p>
<p>library_name: The name of the library.</p>
<p>consumers: A comma separated list of user ID's that can consume content in this library. User ALL to add all team members/users this user manages.</p>
<p>contributors: A comma separated list of user ID's that can contribute content to this library. User ALL to add all team members/users this user manages.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> <p>"created_at": "2014/08/29 11:39:16 +0000",</p>
> "consumers": [
> > {
> > > "user": {
> > > > <p>"fullname": "NewSocialCloud",</p>
> > > > <p>"id": 5111,</p>
> > > > <p>"color": "#b6617c",</p>
> > > > <p>"login": "newsocialcloud"</p>

> > > },
> > > "id": 46737

> > },
> > {
> > > "user": {
> > > > <p>"fullname": "NewSocialCloud",</p>
> > > > <p>"id": 1,</p>
> > > > <p>"color": "#d79d54",</p>
> > > > <p>"login": "newsocialcloud"</p>

> > > },
> > > "id": 46738

> > }

> ],
> <p>"content_type": "Message",</p>
> <p>"contributors": <a href='.md'>.md</a>,</p>
> <p>"updated_at": "2014/08/29 11:39:16 +0000",</p>
> <p>"id": 6,</p>
> <p>"user_id": 5111,</p>
> <p>"library_name": "Quotes"</p>
}