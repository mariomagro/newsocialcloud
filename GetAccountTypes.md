Retrieve available account types (plans) for a NewSocialCloud White Label partner site. (This is for version 1 white label sites.)

Please note: Before you can retrieve available account types, you need to enable automatic billing on your white label. This can be setup in the Admin section under Billing.

**URL:**

http://login.newsocialcloud.com/api/v1/account_types.format

**Formats:**

Replace format with either xml or json

**HTTP Methods:**

GET

**Authentication:**

Basic authentication with username and password or remote API key belonging to the administrator of the white label site.

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>white_label_code: The unique code that identifies your white label site. You can locate this code in the admin section of your white label under details.</p>

**Success Response:**



&lt;account-types type="array"&gt;


> 

&lt;account-type&gt;


> > 

&lt;description&gt;

Solo

&lt;/description&gt;


> > 

&lt;id type="integer"&gt;

57

&lt;/id&gt;


> > 

&lt;monthlycostUSD type="decimal"&gt;

6.99

&lt;/monthlycostUSD&gt;


> > 

&lt;monthlypriceUSD type="decimal"&gt;

6.99

&lt;/monthlypriceUSD&gt;



> 

&lt;/account-type&gt;


> 

&lt;account-type&gt;


> > 

&lt;description&gt;

Pro

&lt;/description&gt;


> > 

&lt;id type="integer"&gt;

2

&lt;/id&gt;


> > 

&lt;monthlycostUSD type="decimal"&gt;

10.0

&lt;/monthlycostUSD&gt;


> > 

&lt;monthlypriceUSD type="decimal"&gt;

10.0

&lt;/monthlypriceUSD&gt;



> 

&lt;/account-type&gt;




&lt;/account-types&gt;



**Error Responses:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;




&lt;error&gt;




&lt;type&gt;

AccessError

&lt;/type&gt;




&lt;message&gt;

Only an admin user belonging to the white label can retrieve account types.

&lt;/message&gt;




&lt;/error&gt;




&lt;error&gt;




&lt;type&gt;

MissingWhiteLabel

&lt;/type&gt;




&lt;message&gt;

Unable to find white label or automatic billing has not been set up.

&lt;/message&gt;




&lt;/error&gt;

