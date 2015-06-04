To retrieve a list of the valid periods for a given social media account detail, make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v1/account-periods.format

**Formats:**

Replace format with either xml or json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>account_detail_id: The account detail id for which to retrieve the valid yearmonth codes. Valid account_detail_ids can be retrieved using the using the GetAccountDetails call.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**



&lt;account-periods&gt;


> 

&lt;yearmonth&gt;

201409

&lt;/yearmonth&gt;


> 

&lt;yearmonth&gt;

201408

&lt;/yearmonth&gt;


> 

&lt;yearmonth&gt;

201407

&lt;/yearmonth&gt;


> 

&lt;yearmonth&gt;

201406

&lt;/yearmonth&gt;


> 

&lt;yearmonth&gt;

201405

&lt;/yearmonth&gt;


> 

&lt;yearmonth&gt;

201404

&lt;/yearmonth&gt;


> 

&lt;yearmonth&gt;

201403

&lt;/yearmonth&gt;


> 

&lt;yearmonth&gt;

201402

&lt;/yearmonth&gt;


> 

&lt;yearmonth&gt;

201401

&lt;/yearmonth&gt;




&lt;/account-periods&gt;



**Error Response:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;

