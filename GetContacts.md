Retrieves a list of the authenticated user's contacts.

**URL:**

http://login.newsocialcloud.com/api/v1/contacts.format

**Formats:**

Replace format with either xml or json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>filter: Optional. Filter contacts by keyword.</p>
<p>field_name: Optional. Find contacts that have had this specific field name set using this method.</p>
<p>field_value: Optional. Find contacts that have had this specific field value set using this method.</p>
<p>per_page: Optional. The number of contacts to return per page. Maximum is 1000.</p>
<p>page: Optional. The page number to return.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the newsocialcloud user.

**Success Response:**

<?xml version="1.0" encoding="UTF-8"?>


&lt;contacts type="array"&gt;


> 

&lt;contact&gt;


> > 

&lt;addressline1&gt;



&lt;/addressline1&gt;


> > 

&lt;addressline2&gt;



&lt;/addressline2&gt;


> > 

&lt;birthday type="date" nil="true"&gt;



&lt;/birthday&gt;


> > 

&lt;cellphone&gt;



&lt;/cellphone&gt;


> > 

&lt;city&gt;



&lt;/city&gt;


> > 

&lt;company&gt;



&lt;/company&gt;


> > 

&lt;country&gt;



&lt;/country&gt;


> > 

&lt;email&gt;

tom@smith.com

&lt;/email&gt;


> > 

&lt;fax&gt;



&lt;/fax&gt;


> > 

&lt;firstName&gt;

Tom

&lt;/firstName&gt;


> > 

&lt;id type="integer"&gt;

3566

&lt;/id&gt;


> > 

&lt;lastName&gt;

Smith

&lt;/lastName&gt;


> > 

&lt;occupation&gt;



&lt;/occupation&gt;


> > 

&lt;sex&gt;



&lt;/sex&gt;


> > 

&lt;state&gt;



&lt;/state&gt;


> > 

&lt;tel&gt;



&lt;/tel&gt;


> > 

&lt;unsubscribed type="integer"&gt;

1

&lt;/unsubscribed&gt;


> > 

&lt;zip&gt;



&lt;/zip&gt;


> > 

&lt;contact-accounts type="array"&gt;


> > > 

&lt;contact-account&gt;


> > > > 

&lt;accountTypeName&gt;

Facebook Wall Post

&lt;/accountTypeName&gt;


> > > > 

&lt;account-id&gt;

121212111

&lt;/account-id&gt;


> > > > 

&lt;id type="integer"&gt;

6304

&lt;/id&gt;


> > > > 

&lt;username&gt;

newsocialcloudweb

&lt;/username&gt;



> > > 

&lt;/contact-account&gt;



> > 

&lt;/contact-accounts&gt;


> > 

&lt;contact-fields&gt;


> > > 

&lt;contact-field&gt;


> > > > 

&lt;field-name&gt;

password

&lt;/field-name&gt;


> > > > 

&lt;field-value&gt;

1234

&lt;/field-value&gt;



> > > 

&lt;/contact-field&gt;



> > 

&lt;/contact-fields&gt;



> 

&lt;/contact&gt;




&lt;/contacts&gt;



**Error Response:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;

