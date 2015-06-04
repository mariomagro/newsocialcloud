To create a media file for a given user and store it on NewSocialCloud, make a POST call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/media.json

**HTTP Methods:**

POST

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>media: A comma separated list of files or images to attach to the message. Each item in the list must contain the file name with extension and a URL-encoded base64 string representing the data. Format: file_name_1|base64string_1,file_name_2|base64string_2. e.g. logo1w.png|iVBORw0KGgoAAAANSUhEUgAAARMAAABfCAMAAAD8mtMpAAADAFBMVEUAcwsOcRojZitLflOWBR...</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

> {
> > "id": 3748430,
> > "file\_name": "Attachment",
> > "content\_type": "image",
> > "file\_size": "",
> > "link\_title": "",
> > "link\_url": "http://bbc.in/IUnCfJ",
> > "link\_url\_display": "www.bbc.co.uk",
> > "link\_description": "Breaking%20news,%20sport,%20TV,%20radio%20and%20a%20whole%20lot%20more.%20The%20BBC%20informs,%20educates%20and%20entertains%20-%20",
> > "type": "image",
> > "url\_original": "![http://static.bbci.co.uk/frameworks/barlesque/2.51.1/desktop/3.5/img/blq-blocks_grey_alpha.png](http://static.bbci.co.uk/frameworks/barlesque/2.51.1/desktop/3.5/img/blq-blocks_grey_alpha.png)",
> > "url\_med": "![http://static.bbci.co.uk/frameworks/barlesque/2.51.1/desktop/3.5/img/blq-blocks_grey_alpha.png](http://static.bbci.co.uk/frameworks/barlesque/2.51.1/desktop/3.5/img/blq-blocks_grey_alpha.png)",
> > "url\_thumb": "![http://static.bbci.co.uk/frameworks/barlesque/2.51.1/desktop/3.5/img/blq-blocks_grey_alpha.png](http://static.bbci.co.uk/frameworks/barlesque/2.51.1/desktop/3.5/img/blq-blocks_grey_alpha.png)"
> > }

**Error Response:**

{"error": {"type": "MissingParameter", "message": "Media must contain file name and base64 string separated by a pipe."} }

{"error": {"type": "FileSizeExceeded", "message": "File size must be less than 4MB."} }