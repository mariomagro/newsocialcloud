Update an existing user on a newsocialcloud White Label partner site.

Please note: Before you can update a user, you need to enable automatic billing on your white label. This can be setup in the Admin section under Billing.

**URL:**

http://login.newsocialcloud.com/api/v1/user.format

**Formats:**

Replace format with either xml or json

**HTTP Methods:**

PUT

**Authentication:**

Basic authentication with username and password or remote API key belonging to the user of the white label site.

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>white_label_code: The unique code that identifies your white label site. You can locate this code in the admin section of your white label under details.</p>
<p>account_type_id: Optional. The ID of the account type that this user will be updated to. To retrieve available account type ID's, please use this API call.</p>
<p>tokens: Optional. The number of tokens to add to this user. The value can be 500, 1000, 5000 or 10000.</p>
<p>disable: Optional. Set this to true to disable this user account. When set to false, include the parameter user_api_key to represent the user's api_key that needs to be re-enabled.</p>

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

