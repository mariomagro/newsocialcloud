To check if a URL is a white label, make an unauthenticated GET request.

**URL:**

http://login.newsocialcloud.com/api/utils/site_lookup.json

**HTTP Methods:**

GET

**Authentication:**

None.

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>url: The URL of the current site.</p>

**Success Response:**

{
> "stylesheet\_url": "http://login.newsocialcloud.com/styling?site_name=NSC&type=webapp",
> "api\_endpoint": "http://login.newsocialcloud.com",
> "site\_code": "NewSocialCloud",
> "is\_wl": true,
> "site\_name": "NewSocialCloud",
> "favicon\_url": "![https://snd-store.s3.amazonaws.com/0/newsocialcloud/NSC_16x16.png](https://snd-store.s3.amazonaws.com/0/newsocialcloud/NSC_16x16.png)",
> "logo\_url": "![https://snd-store.s3.amazonaws.com/0/newsocialcloud/NSC_16x16.png](https://snd-store.s3.amazonaws.com/0/newsocialcloud/NSC_16x16.png)"
}

OR

{

"is\_wl": false
}

**Error Response:**

{

"error": {
"type": "NotFound", "message": "This site has not yet been configured. "
}
}