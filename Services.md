<div>
<div>
<p>Retrieve the list of social media services, groups and contacts belonging to the authenticated user. </p>
<h4>
<a></a>URL:<a href='#URL:'></a>
</h4>
<p><a href='http://login.newsocialcloud.com/api/v1/services.format?type=type'><a href='http://login.newsocialcloud.com/api/v1/services.format?type=type'>http://login.newsocialcloud.com/api/v1/services.format?type=type</a></a> </p>
<h4>
<a></a>Formats:<a href='#Formats:'></a>
</h4>
<p>Replace <tt>format</tt> with either <tt>xml</tt> or <tt>json</tt> </p>
<h4>
<a></a>HTTP Methods:<a href='#HTTP_Methods:'></a>
</h4>
<p>GET </p>
<h4>
<a></a>Parameters:<a href='#Parameters:'></a>
</h4>
<ul>
<li><tt>application_id</tt>: Your application id from <a href='http://newsocialcloud.com/developers.html'><a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></a>. </li>
<li><tt>type</tt>: Possible values are <tt>all</tt>, <tt>social</tt>, <tt>email</tt>, <tt>sms</tt>, <tt>group</tt>, <tt>contacts</tt> </li>
<li><tt>filter</tt>: Optional. Filter services and/or recipients by keyword. </li>
<li><tt>per_page</tt>: Optional. Number of results to return per page. Default: <tt>100</tt> </li>
<li><tt>page</tt>: Optional. The page number to return. Default: <tt>1</tt> </li>
</ul>
<h4>
<a></a>Authentication:<a href='#Authentication:'></a>
</h4>
<p>Basic authentication with username and password or remote API key belonging to the newsocialcloud user. </p>
<h4><a></a>Success Response:<a href='#Success_Response:'></a>
</h4>
<br>
<br>
<user-service><br>
<br>
<br>
<blockquote>

<account-name>

Facebook note - NewSocialCloud-Web<br>
<br>
</account-name><br>
<br>
<br>
<br>
<br>
<account-type><br>
<br>
Facebook(note)<br>
<br>
</account-type><br>
<br>
<br>
<br>
<br>
<icon-url><br>
<br>
<a href='http://newsocialcloud.com/images/'>http://newsocialcloud.com/images/</a>...<br>
<br>
</icon-url><br>
<br>
<br>
<br>
<br>
<recipient-id><br>
<br>
6304<br>
<br>
</recipient-id><br>
<br>
<br>
<br>
<br>
<total-pages type="integer"><br>
<br>
4<br>
<br>
</total-pages><br>
<br>
<br>
</blockquote><blockquote>

</user-service>

<br>
<br>
<br>
<user-service><br>
<br>
<br>
<blockquote>

<account-name>

Facebook page - Amazon<br>
<br>
</account-name><br>
<br>
<br>
<br>
<br>
<account-type><br>
<br>
Facebook(page)<br>
<br>
</account-type><br>
<br>
<br>
<br>
<br>
<icon-url><br>
<br>
<a href='http://newsocialcloud.com/images/'>http://newsocialcloud.com/images/</a>...<br>
<br>
</icon-url><br>
<br>
<br>
<br>
<br>
<recipient-id><br>
<br>
6296<br>
<br>
</recipient-id><br>
<br>
<br>
<br>
<br>
<total-pages type="integer"><br>
<br>
4<br>
<br>
</total-pages><br>
<br>
<br>
</blockquote>

</user-service>

<br>
<br>
<br>
<user-service><br>
<br>
<br>
<blockquote>

<account-name>

Facebook page - newsocialcloud<br>
<br>
</account-name><br>
<br>
<br>
<br>
<br>
<account-type><br>
<br>
Facebook(page)<br>
<br>
</account-type><br>
<br>
<br>
<br>
<br>
<icon-url><br>
<br>
<a href='http://newsocialcloud.com/images/'>http://newsocialcloud.com/images/</a>...<br>
<br>
</icon-url><br>
<br>
<br>
<br>
<br>
<recipient-id><br>
<br>
6289<br>
<br>
</recipient-id><br>
<br>
<br>
<br>
<br>
<total-pages type="integer"><br>
<br>
4<br>
<br>
</total-pages><br>
<br>
<br>
</blockquote>

</user-service>

<br>
<h4>
<a></a>Error Response:<a href='#Error_Response:'></a></h4><pre>
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
<p>OR </p>
<pre>
<error><br>
<type>ServicesNotFound<br>
<br>
Unknown end tag for </type><br>
<br>
<br>
<message>No services could be found.<br>
<br>
Unknown end tag for </message><br>
<br>
<br>
<br>
<br>
Unknown end tag for </error><br>
<br>
</pre>
</div>
</div>