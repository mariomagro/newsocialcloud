To retrieve all items in a list, make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/list_items.json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>list_id: The id of the list whose items you want to retrieve.</p>
<p>per_page: Optional. The number of results to return per page.</p>
<p>page: Optional. The page number for the results you wish to retrieve. Default: 1.</p>
<p>filter: Optional. The keyword/string to filter results by.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

[
> {
> > "id": 2711061,
> > "account": {
> > > "service": {
> > > > "title": "Twitter",
> > > > "icon": "http://twitter.com/phoenix/favicon.ico"

> > > },
> > > "description": "newsocialcloud"

> > }

> },
> {
> > "id": 2724824,
> > "account": {
> > > "service": {
> > > > "title": "Twitter",
> > > > "icon": "http://twitter.com/phoenix/favicon.ico"

> > > },
> > > "description": "FrancineHuaman"

> > }

> }
]

OR, if the list type is Email or SMS:

[
> {
> > <p>"id": 10180451,</p>
> > <p>"user_id": null,</p>
> > <p>"title": "Achoeng Adhie",</p>
> > <p>"icon": "<img src='http://newsocialcloud-public.s3.amazonaws.com/images/silhouette.gif' />",</p>
> > <p>"item_type": "Email",</p>
> > <p>"description": "xxxxx@xxxxx.com"</p>

> },
> {
> > <p>"id": 10180452,</p>
> > <p>"user_id": null,</p>
> > <p>"title": "Islam Samy",</p>
> > <p>"icon": "<img src='http://newsocialcloud-public.s3.amazonaws.com/images/silhouette.gif' />",</p>
> > <p>"item_type": "Email",</p>
> > <p>"description": "xxxxx@xxxxx.com"</p>

> }
]