Allows you to create or update a custom field and set its value for a given contact. If the field already exists, it will be updated with the new value, otherwise it will be created.

**URL:**

http://login.newsocialcloud.com/api/v1/contact_field.format

**Formats:**

Replace format with either xml or json

**HTTP Methods:**

POST

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>contact_id: Required. The contact id.</p>
<p>field_name: Required. The name of the field you would like to create or update.</p>
<p>field_value: Required. The value of the field_name that you would like to set.</p>
<p>field_type: Optional. The type of field that will be created. Valid options are: text or password.</p>

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



**Error Responses:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;



OR



&lt;error&gt;




&lt;type&gt;

ContactNotFoundError

&lt;/type&gt;




&lt;message&gt;

Contact could not be found.

&lt;/message&gt;




&lt;/error&gt;

