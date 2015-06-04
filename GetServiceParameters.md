To retrieve parameters for a given service, make an authenticated GET request.

**URL:**

http://login.newsocialcloud.com/api/v2/service_parameters.json

**HTTP Methods:**

GET

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>service_id: The id of the service retrieved from this call: GetServiceGroups</p>
<p>Note: You can understand how see how these parameters are rendered by looking at: <a href='http://login.newsocialcloud.com/services/new/service_id'>http://login.newsocialcloud.com/services/new/service_id</a> (replace service_id with the value of the service_id parameter you're using)</p>

**Success Response:**

{
> "parameters": [
> > {
> > > "id": 1380,
> > > "post\_description": "This is for your own reference.",
> > > "parameter\_type": "text",
> > > "parameter\_name": "fullname",
> > > "options": null,
> > > "category": "config",
> > > "parameter\_description": "Description",
> > > "isMandatory": true

> > },
> > {
> > > "id": 3,
> > > "post\_description": null,
> > > "parameter\_type": "text",
> > > "parameter\_name": "username",
> > > "options": null,
> > > "category": "config",
> > > "parameter\_description": "Username or Email",
> > > "isMandatory": true

> > },
> > {
> > > "id": 12,
> > > "post\_description": "This will be automatically populated when you connect your account",
> > > "parameter\_type": "hidden",
> > > "parameter\_name": "session\_id",
> > > "options": null,
> > > "category": "config",
> > > "parameter\_description": "Session Key"

> > },
> > {
> > > "id": 10,
> > > "post\_description": "Select your Facebook page from the list above.",
> > > "parameter\_type": "numeric",
> > > "parameter\_name": "account\_id",
> > > "options": "",
> > > "category": "config",
> > > "parameter\_description": "Facebook Page",
> > > "isMandatory": true

> > },
> > {
> > > "id": 388,
> > > "post\_description": "If you select yes, links will be extracted from your posts and a link preview with caption and image will be posted below your Facebook update.",
> > > "parameter\_type": "list",
> > > "parameter\_name": "linkPreview",
> > > "options": "No,Yes",
> > > "category": "config",
> > > "parameter\_description": "Automatically generate link previews",
> > > "isMandatory": true

> > },
> > {
> > > "id": 1552,
> > > "post\_description": "If you select yes, you can define a link that will appear below each post.",
> > > "parameter\_type": "attribution",
> > > "parameter\_name": "attribution",
> > > "options": null,
> > > "category": "config",
> > > "parameter\_description": "Attach an attribution link",
> > > "isMandatory": true

> > },
> > {
> > > "id": 1554,
> > > "post\_description": null,
> > > "parameter\_type": "preview",
> > > "parameter\_name": "preview",
> > > "options": null,
> > > "category": "config",
> > > "parameter\_description": "What my posts will look like",
> > > "isMandatory": true

> > },
> > {
> > > "id": 1556,
> > > "post\_description": null,
> > > "parameter\_type": "hidden",
> > > "parameter\_name": "link",
> > > "options": null,
> > > "category": "config",
> > > "parameter\_description": "Link",
> > > "isMandatory": true

> > },
> > {
> > > "id": 1558,
> > > "post\_description": null,
> > > "parameter\_type": "hidden",
> > > "parameter\_name": "link\_title",
> > > "options": null,
> > > "category": "config",
> > > "parameter\_description": "Link Title",
> > > "isMandatory": true

> > },
> > {
> > > "id": 1562,
> > > "post\_description": "Use geotargeting to personalize and segment content to different audiences. To target different fans of the same page, you can add the same fan page service as many times as you like and just change the geotargeting settings.",
> > > "parameter\_type": "targetting",
> > > "parameter\_name": "targetting",
> > > "options": null,
> > > "category": "config",
> > > "parameter\_description": "Geotargeting",
> > > "isMandatory": true

> > },
> > {
> > > "id": 21891,
> > > "post\_description": "Set this option to Yes to have full-sized images posts to your page.",
> > > "parameter\_type": "list",
> > > "parameter\_name": "post\_image",
> > > "options": "No,Yes",
> > > "category": "config",
> > > "parameter\_description": "Post as full-sized image"

> > },
> > {
> > > "id": 50,
> > > "post\_description": "This will be automatically populated.",
> > > "parameter\_type": "hidden",
> > > "parameter\_name": "token",
> > > "options": null,
> > > "category": "config",
> > > "parameter\_description": "Oauth Token"

> > },
> > {
> > > "id": 6499,
> > > "post\_description": null,
> > > "parameter\_type": "hidden",
> > > "parameter\_name": "refresh\_token",
> > > "options": null,
> > > "category": "config",
> > > "parameter\_description": "Refresh Token"

> > },
> > {
> > > "id": 16877,
> > > "post\_description": null,
> > > "parameter\_type": "hidden",
> > > "parameter\_name": "api\_key",
> > > "options": "",
> > > "category": "config",
> > > "parameter\_description": "Facebook API Key"

> > },
> > {
> > > "id": 16878,
> > > "post\_description": null,
> > > "parameter\_type": "hidden",
> > > "parameter\_name": "secret",
> > > "options": "",
> > > "category": "config",
> > > "parameter\_description": "Facebook Secret"

> > },
> > {
> > > "id": 12994,
> > > "post\_description": "Receive alerts whenever there is new activity on this account.",
> > > "parameter\_type": "list",
> > > "parameter\_name": "notify",
> > > "options": "Priority Inbox Only,Priority Inbox and Email,Email Only,None",
> > > "category": "config",
> > > "parameter\_description": "Receive alerts for new activity"

> > }

> ],
> "id": 19,
> "category": {
> > "is\_rich\_text": false,
> > "category\_name": "Social Media Publishing Services"

> },
> "compose\_parameters": [.md](.md)
}