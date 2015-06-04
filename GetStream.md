To retrieve a list of the user's stream account details, make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v0/stream-fetch.json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>account_id: The stream account id, retrieved using GetStreamAccounts.</p>
<p>next_url_params: Optional. Used for paging after the first page is retrieved.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> "messages": [
> > {
> > > <p>"comments": <a href='.md'>.md</a>,<br>
<blockquote>"comment_count": 0,<br>
"editable": true,<br>
"likes": 4,<br>
"id": "21274802454_1015062080507455",<br>
"profile_id": "",<br>
"uid": "21274802454",<br>
"picture": "<a href='http://platform.ak.fbcdn.net/www/app_full_proxy.php?app=26065877776&v=1&size=z&cksum=a6d8d0c271e3fcc275c4e586841a376d&src=http%3A%2F%2Fpixel.quantserve.com%2Fpixel%2Fp-34dJXVckfZ4eE.gif%3Flabels%3DPresenters'>http://platform.ak.fbcdn.net/www/app_full_proxy.php?app=26065877776&amp;v=1&amp;size=z&amp;cksum=a6d8d0c271e3fcc275c4e586841a376d&amp;src=http%3A%2F%2Fpixel.quantserve.com%2Fpixel%2Fp-34dJXVckfZ4eE.gif%3Flabels%3DPresenters</a>",<br>
"link": "<a href='http://bit.ly/w0h5hA'>http://bit.ly/w0h5hA</a>",<br>
"account_id": 107799,<br>
"info": {<br>
<blockquote>"isRead": 0,<br>
"id": 406942,<br>
"isHighlighted": 0</p>
</blockquote>},<br>
<p>"link_block": "%3Ctable%20style=%22padding-top:5px;%22%3E%3Ctr%3E%3Ctd%20style=%22border:0;%22%20valign=%22top%22%3E%3Ca%20href=%22http://bit.ly/w0h5hA%22%20target=%22_blank%22%3E%3Cimg%20src=%22http://platform.ak.fbcdn.net/www/app_full_proxy.php?app=26065877776&v=1&size=z&cksum=a6d8d0c271e3fcc275c4e586841a376d&src=http%253A%252F%252Fpixel.quantserve.com%252Fpixel%252Fp-34dJXVckfZ4eE.gif%253Flabels%253DPresenters%22%20style=%22max-width:90px;border:0;%22/%3E%3C/a%3E%3C/td%3E%3Ctd%20style=%22border:0;%22%20valign=%22top%22%3E%3Ctable%20%3E%3Ctr%3E%3Ctd%20style=%22border:0;%22%3E%3Ca%20href=%22http://bit.ly/w0h5hA%22%20target=%22_blank%22%3EMeeting%20Registration:%20newsocialcloud%20Product%20Tour%20%7C%20AnyMeeting%20-%20The%20Completely%20Free%20Web%20Conferencing%20and...%3C/a%3E%3C/td%3E%3C/tr%3E%3Ctr%3E%3Ctd%20style=%22border:0;%22%3E%3Cspan%20class=%22faded%22%3Ewww.anymeeting.com%3C/span%3E%3C/td%3E%3C/tr%3E%3Ctr%3E%3Ctd%20style=%22border:0;%22%3EMeeting%20Registration:%20newsocialcloud%20Product%20Tour%20-%20Completely%20Free%20Web%20Conferencing%20and%20Meeting%20Service.%20Produce%20your%20own%20high%20quality%20online%20meetings,%20with%20registration%20service,%20polling,%20surveys%20and%20more.%20It's%20free%20forever!%3C/td%3E%3C/tr%3E%3C/table%20%3E%3C/td%3E%3C/tr%3E%3C/table%3E",<br>
"message": "%3Ca%20href=%22%23%22%20onclick=%22new%20Streams().loadProfile('21274802454',%20107799,%20'facebook');%20%20%20return%20false;%22%3E%3Cb%3Enewsocialcloud%3C/b%3E%3C/a%3E Join%20our%20weekly%20webinar,%20every%20Wednesday%20at%201pm%20EST%20to%20learn%20more%20about%20the%20newsocialcloud%20product.%20Register%20here%20-%20%20",<br>
"message_unformatted": "Join%20our%20weekly%20webinar,%20every%20Wednesday%20at%201pm%20EST%20to%20learn%20more%20about%20the%20newsocialcloud%20product.%20Register%20here%20-%20%20",<br>
"message_formatted": "%3Ca%20href=%22%23%22%20onclick=%22new%20Streams().loadProfile('21274802454',%20107799,%20'facebook');%20%20%20return%20false;%22%3E%3Cb%3Enewsocialcloud%3C/b%3E%3C/a%3E Join%20our%20weekly%20webinar,%20every%20Wednesday%20at%201pm%20EST%20to%20learn%20more%20about%20the%20newsocialcloud%20product.%20Register%20here%20-%20%20",<br>
"screen_name": "newsocialcloud",<br>
"to_name": "John",<br>
"subject": "%3Ca%20href=%22%23%22%20onclick=%22new%20Streams().loadProfile('21274802454',%20107799,%20'facebook');%20%20%20return%20false;%22%3E%3Cb%3Enewsocialcloud%3C/b%3E%3C/a%3E Join%20our%20weekly%20webinar,%20every%20Wednesday%20at%201pm%20EST%20to%20learn%20more%20about%20the%20newsocialcloud%20product.%20Register%20here%20-%20%20",<br>
"subject_formatted": "%3Ca%20href=%22%23%22%20onclick=%22new%20Streams().loadProfile('21274802454',%20107799,%20'facebook');%20%20%20return%20false;%22%3E%3Cb%3Enewsocialcloud%3C/b%3E%3C/a%3E Join%20our%20weekly%20webinar,%20every%20Wednesday%20at%201pm%20EST%20to%20learn%20more%20about%20the%20newsocialcloud%20product.%20Register%20here%20-%20%20",<br>
"subject_unformatted": "Join%20our%20weekly%20webinar,%20every%20Wednesday%20at%201pm%20EST%20to%20learn%20more%20about%20the%20newsocialcloud%20product.%20Register%20here%20-%20%20",<br>
"avatar": "<a href='https://graph.facebook.com/newsocialcloud/picture'>https://graph.facebook.com/newsocialcloud/picture</a>",<br>
"formattedClientTimeLong": "02 Apr 19:10"</p>
</blockquote>
> > }

> ],
> "editable": true,
> "type": "facebook",
> "stream": "facebook",
> "total": 20,
> "total\_after": 200,
> "last\_id": 20,
> "next\_url\_params": "https://graph.facebook.com/21274802454/feed?access_token=********&limit=20&until=1332346207"
}

**Error Response:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;

