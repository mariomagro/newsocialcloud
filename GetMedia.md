To retrieve the list of all media for a given user, make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/media.json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>user_id: Optional. The specific user id to retrieve messages for. Use ALL to retrieve all media for the team. IF this is not set, then the media for the authenticated user will be returned.</p>
<p>per_page: Optional. The number of messages to return per page.</p>
<p>page: Optional. The page number to return.</p>
<p>filter: Optional. A search string parameter used for filtering results.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> "files": [
> > {
> > > <p>"id": 374843,</p>
> > > <p>"file_name": "Attachment",</p>
> > > <p>"content_type": "image",</p>
> > > <p>"file_size": "",</p>
> > > <p>"link_title": "",</p>
> > > <p>"link_url": "<a href='http://bbc.in/IUnCfJ'>http://bbc.in/IUnCfJ</a>",</p>
> > > <p>"link_url_display": "www.bbc.co.uk",</p>
> > > <p>"link_description": "Breaking%20news,%20sport,%20TV,%20radio%20and%20a%20whole%20lot%20more.%20The%20BBC%20informs,%20educates%20and%20entertains%20-%20",</p>
> > > <p>"type": "image",</p>
> > > <p>"url_original": "<img src='http://static.bbci.co.uk/frameworks/barlesque/2.51.1/desktop/3.5/img/blq-blocks_grey_alpha.png' />",</p>
> > > <p>"url_med": "<img src='http://static.bbci.co.uk/frameworks/barlesque/2.51.1/desktop/3.5/img/blq-blocks_grey_alpha.png' />",</p>
> > > <p>"url_thumb": "<img src='http://static.bbci.co.uk/frameworks/barlesque/2.51.1/desktop/3.5/img/blq-blocks_grey_alpha.png' />"</p>

> > },
}