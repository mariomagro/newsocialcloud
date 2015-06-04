Create a user on a NewSocialCloud White Label partner site.

Please note: Before you can create a user, you need to enable automatic billing on your white label. This can be setup in the Admin section under Billing.

**URL:**

http://login.newsocialcloud.com/api/v1/user.format

**Formats:**

Replace format with either xml or json

**HTTP Methods:**

POST

**Authentication:**

Basic authentication with username and password or remote API key belonging to the user of the white label site.

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>white_label_code: The unique code that identifies your white label site. You can locate this code in the admin section of your white label under details.</p>
<p>account_type_id: Optional. The ID of the account type that this user will be updated to. To retrieve available account type ID's, please use this API call.</p>
<p>fullname: The user's name.</p>
<p>email: The user's email address.</p>
<p>password: The user's password.</p>
<p>login: The users username.</p>
<p>timezone: Optional. The user's timezone offset from GMT in minutes. Default: The admin user's timezone will be used. In Javascript, this is the value of getTimezoneOffset.</p>
<p>managed_by_id: Optional. The id of the user managing this user's account (the parent user's id).</p>

**Success Response:**



&lt;user&gt;


> 

&lt;email&gt;

testing@gmail.com

&lt;/email&gt;


> 

&lt;fullname&gt;

Test User

&lt;/fullname&gt;


> 

&lt;id type="integer"&gt;

3

&lt;/id&gt;


> 

&lt;login&gt;

testuser

&lt;/login&gt;


> 

&lt;is-pro type="boolean"&gt;

true

&lt;/is-pro&gt;


> 

&lt;account-type-name&gt;

Marketer

&lt;/account-type-name&gt;


> 

&lt;tokens-remaining type="decimal"&gt;

347.0

&lt;/tokens-remaining&gt;


> 

&lt;message-credits-remaining type="integer"&gt;

11585

&lt;/message-credits-remaining&gt;


> 

&lt;api-key&gt;

xxxx

&lt;/api-key&gt;


> 

&lt;contact-count type="integer"&gt;

8105

&lt;/contact-count&gt;


> 

&lt;group-count type="integer"&gt;

20

&lt;/group-count&gt;


> 

&lt;service-count type="integer"&gt;

88

&lt;/service-count&gt;




&lt;/user&gt;



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

PaymentFailed

&lt;/type&gt;




&lt;message&gt;

The user could not be updated because the payment failed. 

&lt;/message&gt;




&lt;/error&gt;




&lt;error&gt;




&lt;type&gt;

AccessError

&lt;/type&gt;




&lt;message&gt;

Only an admin user belonging to the white label can create a user.

&lt;/message&gt;




&lt;/error&gt;




&lt;error&gt;




&lt;type&gt;

AccountTypeNotFound

&lt;/type&gt;




&lt;message&gt;

Unable to find account type.

&lt;/message&gt;




&lt;/error&gt;




&lt;error&gt;




&lt;type&gt;

InvalidTokenQuantity

&lt;/type&gt;




&lt;message&gt;

No pricing could be found for 10 tokens. Please use a standard bundle quantity.

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

