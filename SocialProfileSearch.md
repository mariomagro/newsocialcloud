To search for social profiles on Twitter, Facebook, Instagram or LinkedIn make an authenticated GET request.

**URL:**

http://login.newsocialcloud.com/api/v2/social_profile_search.json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>type: One of the following: twitter, linkedin, facebook, instagram.</p>
<p>q: The name to search for.</p>
<p>account_id: Optional. The service id, if available for the authenticated user returned by the Services API method. Alternatively, just use null.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> "profiles": [
> > {
> > > <p>"profile_id": "606240366",</p>
> > > <p>"profile_name": "NewSocialCloud",</p>
> > > <p>"bio": "",</p>
> > > <p>"last_name": "NewSocialCloud",</p>
> > > <p>"profile_picture": "<a href='https://graph.facebook.com/172622719582956/picture'>https://graph.facebook.com/172622719582956/picture</a>",</p>
> > > <p>"profile_url": "<a href='https://www.facebook.com/pages/NewSocialCloud/172622719582956'>https://www.facebook.com/pages/NewSocialCloud/172622719582956</a>",</p>
> > > <p>"location": "",</p>
> > > <p>"first_name": "NewSocialCloud"</p>

> > },
> > {
> > > <p>"profile_id": "587135622",</p>
> > > <p>"profile_name": "Mario Magro",</p>
> > > <p>"bio": "",</p>
> > > <p>"last_name": "Magro",</p>
> > > <p>"profile_picture": "<a href='https://graph.facebook.com/mmagroman/picture'>https://graph.facebook.com/mmagroman/picture</a>",</p>
> > > <p>"profile_url": "<a href='https://www.facebook.com/mmagroman'>https://www.facebook.com/mmagroman</a>",</p>
> > > <p>"location": "",</p>
> > > <p>"first_name": "Mario"</p>

> > },
> > > ],

> "account\_id": 515290
}