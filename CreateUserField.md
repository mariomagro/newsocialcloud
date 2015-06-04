<div>
<div>
<p>Allows you to create or update a custom field and set its value for the authenticated user. If the field already exists, it will be updated with the new value, otherwise it will be created.<br>
</p>
<h4>
<a></a>URL:<a href='#URL:'></a>
</h4>
<p>
<a href='http://login.newsocialcloud.com/api/v1/user_field.format'><a href='http://login.newsocialcloud.com/api/v1/user_field.format'>http://login.newsocialcloud.com/api/v1/user_field.format</a></a> </p>
<h4>
<a></a>Formats:<a href='#Formats:'></a>
</h4>
<p>Replace <tt>format</tt> with either <tt>xml</tt> or <tt>json</tt> </p>
<h4>
<a></a>HTTP Methods:<a href='#HTTP_Methods:'></a>
</h4>
<p>POST, PUT </p>
<h4>
<a></a>Parameters:<a href='#Parameters:'></a>
</h4>
<ul>
<li><tt>application_id</tt>: Your application id from <a href='http://newsocialcloud.com/developers.html'><a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></a>. </li>
<li><tt>field_name</tt>: Required. The name of the field you would like to create or update.   </li>
<li><tt>field_value</tt>: Required. The value of the <tt>field_name</tt> that you would like to set. </li>
</ul>
<h4>
<a></a>Authentication:<a href='#Authentication:'></a>
</h4>
<p>Basic authentication with username and password or remote API key belonging to the NewSocialCloud user. </p>
<h4>
<a></a>Success Response:<a href='#Success_Response:'></a>
</h4>
<blockquote>

<api-key>

<br>
<br>
</api-key><br>
<br>
<br>
<br>
<br>
<email><br>
<br>
<b>@</b>.com<br>
<br>
</email><br>
<br>
<br>
<br>
<br>
<fullname><br>
<br>
newsocialcloud<br>
<br>
</fullname><br>
<br>
<br>
<br>
<br>
<id type="integer"><br>
<br>
5131<br>
<br>
</id><br>
<br>
<br>
<br>
<br>
<login><br>
<br>
newsocialcloud<br>
<br>
</login><br>
<br>
<br>
<br>
<br>
<is-pro type="boolean"><br>
<br>
true<br>
<br>
</is-pro><br>
<br>
<br>
<br>
<br>
<account-type-name><br>
<br>
Premium<br>
<br>
</account-type-name><br>
<br>
<br>
<br>
<br>
<total-credits-available type="decimal"><br>
<br>
12121.0<br>
<br>
</total-credits-available><br>
<br>
<br>
<br>
<br>
<tokens-remaining type="decimal"><br>
<br>
1985.0<br>
<br>
</tokens-remaining><br>
<br>
<br>
<br>
<br>
<message-credits-remaining type="integer"><br>
<br>
126956<br>
<br>
</message-credits-remaining><br>
<br>
<br>
<br>
<br>
<contact-count type="integer"><br>
<br>
10433<br>
<br>
</contact-count><br>
<br>
<br>
<br>
<br>
<group-count type="integer"><br>
<br>
66<br>
<br>
</group-count><br>
<br>
<br>
<br>
<br>
<service-count type="integer"><br>
<br>
208<br>
<br>
</service-count><br>
<br>
<br>
<br>
<br>
<contact-fields type="array"><br>
<br>
<br>
<blockquote>

<contact-field>

<br>
<blockquote>

<field-name>

location<br>
<br>
</field-name><br>
<br>
<br>
<br>
<br>
<field-type><br>
<br>
text<br>
<br>
</field-type><br>
<br>
<br>
<br>
<br>
<field-value><br>
<br>
Madrid<br>
<br>
</field-value><br>
<br>
<br>
</blockquote>

</contact-field>

<br>
</blockquote>

</contact-fields>

<br>
<h4>
<a></a>Error Responses:<a href='#Error_Responses:'></a>
</h4>
<pre>
<error><br>
<type>InvalidUsernamePassword<br>
<br>
Unknown end tag for </type><br>
<br>
<br>
<message>Username/password is invalid.<br>
<br>
Unknown end tag for </message><br>
<br>
<br>
<br>
<br>
Unknown end tag for </error><br>
<br>
<br>
</pre>
</div>
</div>