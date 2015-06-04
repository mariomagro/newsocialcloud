To retrieve a list of results from a realtime search on social media. Make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/social_search

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>type: The type of search to perform. Possible values are twitter and facebook.</p>
<p>query: Search query, in text form.</p>
<p>results_per_page: Optional. Results to show on each page (maximum of 100)</p>
<p>max_id: Optional. Show only results up to this ID, used to see older results. Use the max_id that's returned in the results to fetch the next page of results.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> "results": [
> > {
> > > <p>"userimage": "<a href='https://graph.facebook.com/749169125/picture'>https://graph.facebook.com/749169125/picture</a>",</p>
> > > <p>"userlink": "<a href='https://facebook.com/749169125'>https://facebook.com/749169125</a>",</p>
> > > <p>"link": "<a href='https://facebook.com/749169125'>https://facebook.com/749169125</a>",</p>
> > > <p>"created_at_client": "2014-06-07T00:16:36+0000",</p>
> > > <p>"source": "facebook",</p>
> > > <p>"sentiment": 0,</p>
> > > <p>"content": "",</p>
> > > <p>"id": "1495153850697452_1498552240357613",</p>
> > > <p>"term": "newsocialcloud",</p>
> > > <p>"favicon": "<a href='http://www.google.com/s2/favicons?domain=facebook.com'>http://www.google.com/s2/favicons?domain=facebook.com</a>",</p>
> > > <p>"description": "",</p>
> > > <p>"username": "Brandon Drazic",</p>
> > > <p>"type": "facebooksearch",</p>
> > > <p>"domain": "facebook.com",</p>
> > > <p>"title": "and some positive XD\n\n <a href='https://www.youtube.com/watch?v=ybgKvm2KIa8&feature=youtube_gdata&utm_source=rss&utm_medium=newsocialcloud&utm_campaign=RSS'>https://www.youtube.com/watch?v=ybgKvm2KIa8&amp;feature=youtube_gdata&amp;utm_source=rss&amp;utm_medium=newsocialcloud&amp;utm_campaign=RSS</a>",</p>
> > > <p>"nextpage": "1402010570"</p>

> > },
> > {
> > > <p>"userimage": "<a href='https://graph.facebook.com/21274802454/picture'>https://graph.facebook.com/21274802454/picture</a>",</p>
> > > <p>"userlink": "<a href='https://facebook.com/21274802454'>https://facebook.com/21274802454</a>",</p>
> > > <p>"link": "<a href='https://facebook.com/21274802454'>https://facebook.com/21274802454</a>",</p>
> > > <p>"created_at_client": "2014-06-06T21:29:52+0000",</p>
> > > <p>"source": "facebook",</p>
> > > <p>"sentiment": 0,</p>
> > > <p>"content": "",</p>
> > > <p>"id": "21274802454_10152075828387455",</p>
> > > <p>"term": "newsocialcloud",</p>
> > > <p>"favicon": "<a href='http://www.google.com/s2/favicons?domain=facebook.com'>http://www.google.com/s2/favicons?domain=facebook.com</a>",</p>
> > > <p>"description": "",</p>
> > > <p>"username": "newsocialcloud",</p>
> > > <p>"type": "facebooksearch",</p>
> > > <p>"domain": "facebook.com",</p>
> > > <p>"title": "Hi all\n\nWe had a very short downtime earlier but things should be back to normal now. Our server that handles user sessions failed earlier but has now been restored.\n\nWe apologise for the short downtime, but we have now corrected the issues to ensure it doesn't happen again. We generally have a 99.97% uptime, so this is extremely unusual for ewSocialCloud and we have now introduced measures to prevent this from occurring again in the future.\n\nThanks,\n\n NewSocialCloud Team",</p>
> > > <p>"nextpage": "1402010570"<br>
</li></ul><blockquote>},

> > {
> > > <p>"userimage": "<a href='https://graph.facebook.com/588219818/picture'>https://graph.facebook.com/588219818/picture</a>",</p>
> > > <p>"userlink": "<a href='https://facebook.com/588219818'>https://facebook.com/588219818</a>",</p>
> > > <p>"link": "<a href='https://facebook.com/588219818'>https://facebook.com/588219818</a>",</p>
> > > <p>"created_at_client": "2014-06-06T14:29:44+0000",</p>
> > > <p>"source": "facebook",</p>
> > > <p>"sentiment": 0,</p>
> > > <p>"content": "",</p>
> > > <p>"id": "588219818_10152471830099819",</p>
> > > <p>"term": "newsocialcloud",</p>
> > > <p>"favicon": "<a href='http://www.google.com/s2/favicons?domain=facebook.com'>http://www.google.com/s2/favicons?domain=facebook.com</a>",</p>
> > > <p>"description": "",</p>
> > > <p>"username": "Mario Magro",</p>
> > > <p>"type": "facebooksearch",</p>
> > > <p>"domain": "facebook.com",</p>
> > > <p>"title": "They promise they will never do this to U.S.......",</p>
> > > <p>"nextpage": "1402010570"</p>

> > },
> > {
> > > <p>"userimage": "<a href='https://graph.facebook.com/574271150/picture'>https://graph.facebook.com/574271150/picture</a>",</p>
> > > <p>"userlink": "<a href='https://facebook.com/574271150'>https://facebook.com/574271150</a>",</p>
> > > <p>"link": "<a href='https://facebook.com/574271150'>https://facebook.com/574271150</a>",</p>
> > > <p>"created_at_client": "2014-06-06T13:30:59+0000",</p>
> > > <p>"source": "facebook",</p>
> > > <p>"sentiment": 0,</p>
> > > <p>"content": "",</p>
> > > <p>"id": "574271150_10152484849271151",</p>
> > > <p>"term": "newsocialcloud",</p>
> > > <p>"favicon": "<a href='http://www.google.com/s2/favicons?domain=facebook.com'>http://www.google.com/s2/favicons?domain=facebook.com</a>",</p>
> > > <p>"description": "",</p>
> > > <p>"username": "AA and BB Social Marketing",</p>
> > > <p>"type": "facebooksearch",</p>
> > > <p>"domain": "facebook.com",</p>
> > > <p>"title": "AA and BB Social Marketing shared a link.",</p>
> > > <p>"nextpage": "1402010570"</p>

> > },
> > {
> > > <p>"userimage": "<a href='https://graph.facebook.com/454478881363113/picture'>https://graph.facebook.com/454478881363113/picture</a>",</p>
> > > <p>"userlink": "<a href='https://facebook.com/454478881363113'>https://facebook.com/454478881363113</a>",</p>
> > > <p>"link": "<a href='https://facebook.com/454478881363113'>https://facebook.com/454478881363113</a>",</p>
> > > <p>"created_at_client": "2014-06-06T11:53:43+0000",</p>
> > > <p>"source": "facebook",</p>
> > > <p>"sentiment": 0,</p>
> > > <p>"content": "",</p>
> > > <p>"id": "454478881363113_479728652171469",</p>
> > > <p>"term": "newsocialcloud",</p>
> > > <p>"favicon": "<a href='http://www.google.com/s2/favicons?domain=facebook.com'>http://www.google.com/s2/favicons?domain=facebook.com</a>",</p>
> > > <p>"description": "",</p>
> > > <p>"username": "AA and BB Social Marketing",</p>
> > > <p>"type": "facebooksearch",</p>
> > > <p>"domain": "facebook.com",</p>
> > > <p>"title": "AA and BB Social Marketing shared a link.",</p>
> > > <p>"nextpage": "1402010570"</p>

> > },
> > {
> > > <p>"userimage": "<a href='https://graph.facebook.com/100008309898923/picture'>https://graph.facebook.com/100008309898923/picture</a>",</p>
> > > <p>"userlink": "<a href='https://facebook.com/100008309898923'>https://facebook.com/100008309898923</a>",</p>
> > > <p>"link": "<a href='https://facebook.com/100008309898923'>https://facebook.com/100008309898923</a>",</p>
> > > <p>"created_at_client": "2014-06-05T23:22:51+0000",</p>
> > > <p>"source": "facebook",</p>
> > > <p>"sentiment": 0,</p>
> > > <p>"content": "",</p>
> > > <p>"id": "100008309898923_1416218811998435",</p>
> > > <p>"term": "newsocialcloud",</p>
> > > <p>"favicon": "<a href='http://www.google.com/s2/favicons?domain=facebook.com'>http://www.google.com/s2/favicons?domain=facebook.com</a>",</p>
> > > <p>"description": "",</p>
> > > <p>"username": "Mario Magro",</p>
> > > <p>"type": "facebooksearch",</p>
> > > <p>"domain": "facebook.com",</p>
> > > <p>"title": "Mario Magro shared a link.",</p>
> > > <p>"nextpage": "1402010570"</p>

> > }

> ],
> "max\_id": 1402010570
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

