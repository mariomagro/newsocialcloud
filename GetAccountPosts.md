To retrieve daily statistics for a given social media account detail, make a GET call using basic authentication. The days returned represent the date for the given year/month period.

**URL:**

http://login.newsocialcloud.com/api/v1/account-posts.format

**Formats:**

Replace format with either xml or json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>account_detail_id: The account detail id for which to retrieve the valid yearmonth codes. Valid account_detail_ids can be retrieved using the using the GetAccountDetails call.</p>
<p>account_statistic_id: Optional. The account_statistic_id for which to retrieve posts. Valid account_statistic_ids can be retrieved using the using the GetAccountStatistics call.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**



&lt;posts&gt;


> 

&lt;post&gt;


> > 

&lt;account-statistic-id type="integer"&gt;

4006982

&lt;/account-statistic-id&gt;


> > 

&lt;clientTime type="datetime"&gt;

2014-03-29T12:55:06Z

&lt;/clientTime&gt;


> > 

&lt;message-html&gt;

hidng plek, body pgal, kpla pyeng ,.,,allahu akbar

&lt;/message-html&gt;


> > 

&lt;message-text&gt;

hidng plek, body pgal, kpla pyeng ,.,,allahu akbar

&lt;/message-text&gt;


> > 

&lt;metric-1-name&gt;

Comments

&lt;/metric-1-name&gt;


> > 

&lt;metric-1-value type="decimal"&gt;

0.0

&lt;/metric-1-value&gt;


> > 

&lt;metric-2-name&gt;

Likes

&lt;/metric-2-name&gt;


> > 

&lt;metric-2-value type="decimal"&gt;

0.0

&lt;/metric-2-value&gt;


> > 

&lt;post-link/&gt;


> > 

&lt;post-link-name/&gt;


> > 

&lt;post-picture/&gt;


> > 

&lt;poster-avatar&gt;

http://graph.facebook.com/100002382677074/picture

&lt;/poster-avatar&gt;


> > 

&lt;poster-fullname&gt;

BaNnex AZ DeHh

&lt;/poster-fullname&gt;


> > 

&lt;sentiment type="integer"&gt;

0

&lt;/sentiment&gt;


> > 

&lt;post-responses type="array"/&gt;



> 

&lt;/post&gt;


> 

&lt;post&gt;


> > 

&lt;account-statistic-id type="integer"&gt;

4006982

&lt;/account-statistic-id&gt;


> > 

&lt;clientTime type="datetime"&gt;

2012-03-28T13:45:48Z

&lt;/clientTime&gt;


> > 

&lt;message-html&gt;


> > NewSocialCloud I tried to reach your help-desk but I could not. Would you please check why my account ayman@oasisventures.net is suspended? I have a lot of work to do. Thanks
> > 

&lt;/message-html&gt;


> > 

&lt;message-text&gt;


> > NewSocialCloud I tried to reach your help-desk but I could not. Would you please check why my account ayman@oasisventures.net is suspended? I have a lot of work to do. Thanks
> > 

&lt;/message-text&gt;


> > 

&lt;metric-1-name&gt;

Comments

&lt;/metric-1-name&gt;


> > 

&lt;metric-1-value type="decimal"&gt;

1.0

&lt;/metric-1-value&gt;


> > 

&lt;metric-2-name&gt;

Likes

&lt;/metric-2-name&gt;


> > 

&lt;metric-2-value type="decimal"&gt;

0.0

&lt;/metric-2-value&gt;


> > 

&lt;post-link/&gt;


> > 

&lt;post-link-name/&gt;


> > 

&lt;post-picture/&gt;


> > 

&lt;poster-avatar&gt;

http://graph.facebook.com/726184005/picture

&lt;/poster-avatar&gt;


> > 

&lt;poster-fullname&gt;

Ayman Albarbary

&lt;/poster-fullname&gt;


> > 

&lt;sentiment type="integer"&gt;

0

&lt;/sentiment&gt;


> > 

&lt;post-responses type="array"&gt;


> > > 

&lt;post-response&gt;


> > > > 

&lt;avatar&gt;

http://graph.facebook.com/21274802454/picture

&lt;/avatar&gt;


> > > > 

&lt;body&gt;


> > > > Could you try sign in now? You should have access again.
> > > > 

&lt;/body&gt;


> > > > 

&lt;created-at type="datetime"&gt;

2012-03-28T18:02:39Z

&lt;/created-at&gt;


> > > > 

&lt;responder-fullname&gt;

newsocialcloud

&lt;/responder-fullname&gt;


> > > > 

&lt;responder-identifier&gt;

21274802454\_10150611646282455\_21331651

&lt;/responder-identifier&gt;


> > > > 

&lt;sentiment type="integer"&gt;

0

&lt;/sentiment&gt;


> > > > 

&lt;url/&gt;



> > > 

&lt;/post-response&gt;



> > 

&lt;/post-responses&gt;



> 

&lt;/post&gt;




&lt;/posts&gt;



**Error Response:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;

