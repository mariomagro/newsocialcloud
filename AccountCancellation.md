<div>
<p>To cancel a user's account, make a POST request. If this is an administrator, this will result in the cancellation of all other users in the account. </p>
<h4>
<a></a>URL:<a href='#URL:'></a>
</h4>
<p><a href='http://login.newsocialcloud.com/api/v2/account_cancellation.json'><a href='http://login.newsocialcloud.com/api/v2/account_cancellation.json'>http://login.newsocialcloud.com/api/v2/account_cancellation.json</a></a></p>
<h4>
<a></a>HTTP Methods:<a href='#HTTP_Methods:'></a>
</h4>
<p>POST </p>
<h4>
<a></a>Parameters:<a href='#Parameters:'></a>
</h4>
<ul>
<li><tt>application_id</tt>: Your application id from <a href='http://newsocialcloud.com/developers'><a href='http://newsocialcloud.com/developers'>http://newsocialcloud.com/developers</a></a>. </li>
<li><tt>reason</tt>: Required. The user's reason for cancellation. </li>
</ul>
<h4>
<a></a>Authentication:<a href='#Authentication:'></a></h4><p>Basic authentication with username and password or remote API key belonging to the NewSocialCloud user. </p>
<h4>
<a></a>Success Response:<a href='#Success_Response:'></a>
</h4>
<pre>{<br>
"status": "OK";<br>
}</pre>
<h4>
<a></a>Error Response:<a href='#Error_Response:'></a>
</h4>
<pre>
<error><br>
<type>InvalidUsernamePassword<br>
<br>
Unknown end tag for </type><br>
<br>
<br>
<p><br>
<br>
Unknown end tag for </p><br>
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
<pre>
<error><br>
<type>PermissionDenied<br>
<br>
Unknown end tag for </type><br>
<br>
<br>
<message>Only an administrator can delete the account.<br>
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