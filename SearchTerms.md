To retrieve a list of previous social searches the authenticated user has made, make a GET request using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/search_terms

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>per_page: Optional. The maximum number of results to return. Default is 8.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

[
> {
> > "id": 26576,
> > "search\_term": "oracle"

> },
> {
> > "id": 26488,
> > "search\_term": "social media"

> },
> {
> > "id": 26471,
> > "search\_term": "NewSocialCloud"

> },
> {
> > "id": 25614,
> > "search\_term": "NewSocialCloud Main3 Test"

> },
> {
> > "id": 22645,
> > "search\_term": "jsapi"

> },
> {
> > "id": 22571,
> > "search\_term": "humble bundle"

> },
> {
> > "id": 22391,
> > "search\_term": "studio"

> },
> {
> > "id": 22390,
> > "search\_term": "burger king"

> }
]

**Error Response:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;

