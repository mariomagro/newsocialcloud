Get Feeds or Previous Searches for Twitter/Facebook Search. Make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/storyFeeds

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>feed_type: Set this to feed to get feeds or set this to search to get previous searches for Twitter/Facebook Search</p>
<p>search: Optional. To filter this search</p>
<p>total: Optional. Results to retrieve</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

[
{
> <p>"feed_url" : "surface pro",</p>
> <p>"user_id" : 99583,</p>
> <p>"id" : 26407,</p>
> <p>"feed_type" : "search",</p>
> <p>"feed_name" : "surface pro",</p>
> <p>"created_at" : "2014/05/23 15:23:57 +0000"</p>
},
{
> <p>"feed_url" : "hello",</p>
> <p>"user_id" : 99583,</p>
> <p>"id" : 26404,</p>
> <p>"feed_type" : "search",</p>
> <p>"feed_name" : "hello",</p>
> <p>"created_at" : "2014/05/23 13:38:37 +0000"</p>
},
{
> <p>"feed_url" : "#1DWelcomeToBrazil",</p>
> <p>"user_id" : 99583,</p>
> <p>"id" : 26109,</p>
> <p>"feed_type" : "search",</p>
> <p>"feed_name" : "#1DWelcomeToBrazil",</p>
> <p>"created_at" : "2014/05/07 14:01:02 +0000"</p>
}
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

