<div>
<div>
<p>Retrieves the details about a specific NewSocialCloud message. </p>
<h4>
<a></a>URL:<a href='#URL:'></a>
</h4>
<p><a href='http://newsocialcloud.com/api/v1/message.format'><a href='http://newsocialcloud.com/api/v1/message.format'>http://newsocialcloud.com/api/v1/message.format</a></a> </p>
<h4>
<a></a>Formats:<a href='#Formats:'></a>
</h4>
<p>Replace <tt>format</tt> with either <tt>xml</tt> or <tt>json</tt> </p>
<h4>
<a></a>HTTP Methods:<a href='#HTTP_Methods:'></a>
</h4>
<p>GET</p>
<h4>
<a></a>Parameters:<a href='#Parameters:'></a>
</h4>
<ul>
<li><tt>application_id</tt>: Your application id from <a href='http://newsocialcloud.com/developers.html'><a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></a></li>
<li><tt>message_id</tt>: The message's id. </li>
</ul>
<h4>
<a></a>Authentication:<a href='#Authentication:'></a>
</h4>
<p>Basic authentication with username and password or remote API key belonging to the NewSocialCloud user. </p>
<h4>
<a></a>Success Response:<a href='#Success_Response:'></a>
</h4>
<br>
<br>
<msg><br>
<br>
<br>
<blockquote>

<status>

Sent<br>
<br>
</status><br>
<br>
<br>
<br>
<br>
<subject><br>
<br>
<br>
<br>
</subject><br>
<br>
<br>
<br>
<br>
<tags nil="true"><br>
<br>
<br>
<br>
</tags><br>
<br>
<br>
<br>
<br>
<user-id type="integer"><br>
<br>
1<br>
<br>
</user-id><br>
<br>
<br>
<br>
<br>
<recurs><br>
<br>
Once<br>
<br>
</recurs><br>
<br>
<br>
<br>
<br>
<recurs-until-gmt type="datetime"><br>
<br>
2009-11-12T10:26:55Z<br>
<br>
</recurs-until-gmt><br>
<br>
<br>
<br>
<br>
<recurs-until-client type="datetime"><br>
<br>
2009-11-12T12:26:55Z<br>
<br>
</recurs-until-client><br>
<br>
<br>
<br>
<br>
<message-id type="integer"><br>
<br>
5<br>
<br>
</message-id><br>
<br>
<br>
<br>
<br>
<message-text><br>
<br>
test to FF.<br>
<br>
</message-text><br>
<br>
<br>
<br>
<br>
<message-rich-text><br>
<br>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "<a href='http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd'>http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd</a>"><br>
<br>
<br>
<html><br>
<br>
<br>
<br>
<br>
<head><br>
<br>
<br>
<br>
<br>
<title><br>
<br>
<br>
<br>
</title><br>
<br>
<br>
<br>
<br>
</head><br>
<br>
<br>
<br>
<br>
<body><br>
<br>
<br>
<p>test to FF.</p>
<br>
<br>
</body><br>
<br>
<br>
<br>
<br>
</html><br>
<br>
<br>
<br>
<br>
</message-rich-text><br>
<br>
<br>
<br>
<br>
<notify-me type="integer"><br>
<br>
0<br>
<br>
</notify-me><br>
<br>
<br>
<br>
<br>
<send-date-gmt type="datetime"><br>
<br>
2009-11-12T10:26:55Z<br>
<br>
</send-date-gmt><br>
<br>
<br>
<br>
<br>
<send-date-client type="datetime"><br>
<br>
2009-11-12T12:26:55Z<br>
<br>
</send-date-client><br>
<br>
<br>
<br>
<br>
<send-to><br>
<br>
"Friendfeed - hamgav"<br>
<br>
</send-to><br>
<br>
<br>
<br>
<br>
<timezone-offset-client type="integer"><br>
<br>
-120<br>
<br>
</timezone-offset-client><br>
<br>
<br>
<br>
<br>
<photos type="array"><br>
<br>
<br>
<blockquote>

<photo>

<br>
<blockquote>

<id type="integer">

484<br>
<br>
</id><br>
<br>
<br>
<br>
<br>
<name><br>
<br>
logo1w.png<br>
<br>
</name><br>
<br>
<br>
<br>
<br>
<file_url><br>
<br>
<a href='http://newsocialcloud.com/imagenes/logo1w.pnng'>http://newsocialcloud.com/imagenes/logo1w.pnng</a>

</file_url>

<br>
</blockquote>

</photo>

<br>
<br>
<br>
<photo><br>
<br>
<br>
<blockquote>

<id type="integer">

485<br>
<br>
</id><br>
<br>
<br>
<br>
<br>
<name><br>
<br>
n1727389556_1512.jpg<br>
<br>
</name><br>
<br>
<br>
<br>
<br>
<file_url><br>
<br>
<a href='http://newsocialcloud.com/imagenes/n1727389556_1512.jppg'>http://newsocialcloud.com/imagenes/n1727389556_1512.jppg</a>

</file_url>

<br>
</blockquote>

</photo>

<br>
</blockquote>

</photos>

<br>
<br>
<br>
</msg><br>
<br>
<br>
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
<p>OR</p>
<pre>
<error><br>
<type>MessageNotFoundError<br>
<br>
Unknown end tag for </type><br>
<br>
<br>
<message>Message could not be found.<br>
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