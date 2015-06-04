To update a media file for a given user, make a PUT call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/media.json

**HTTP Methods:**

PUT

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>file_id: The id of the file to be updated.</p>
<p>file_name: The new name of the file.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

> {
> > "id": 3717139,
> > "file\_name": "new logo.png",
> > "content\_type": "image/png",
> > "file\_size": "5929",
> > "link\_title": "",
> > "link\_url": "",
> > "link\_url\_display": "",
> > "link\_description": "",
> > "type": "image",
> > "url\_original": "![https://s3.amazonaws.com/files.newsocialcloud.com/3717139/original.png](https://s3.amazonaws.com/files.newsocialcloud.com/3717139/original.png)",
> > "url\_med": "![https://s3.amazonaws.com/files.newsocialcloud.com/3717139/medium.png](https://s3.amazonaws.com/files.newsocialcloud.com/3717139/medium.png)",
> > "url\_thumb": "![https://s3.amazonaws.com/files.newsocialcloud.com/3717139/thumb.png](https://s3.amazonaws.com/files.newsocialcloud.com/3717139/thumb.png)"
> > }