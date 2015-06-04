<div>
<div>
<p>To retrieve a list of the user's Pending/Sent/Draft NewSocialCloud messages, make a GET call using basic authentication. </p>
<h4>
<a></a>URL:<a href='#URL:'></a>
</h4>
<p><a href='http://login.newsocialcloud.com/api/v1/messages.format'><a href='http://login.newsocialcloud.com/api/v1/messages.format'>http://login.newsocialcloud.com/api/v1/messages.format</a></a> </p>
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
<li><tt>status</tt>: Optional. The message status. Default is <tt>Pending</tt>. Possible values are <tt>Pending</tt>, <tt>Draft</tt> or <tt>Sent</tt>. </li>
<li><tt>filter</tt>: Optional. Filter messages by keyword.  </li>
<li><tt>per_page</tt>: Optional. The number of messages to return per page. </li>
<li><tt>page</tt>: Optional. The page number to return.  </li>
<li><tt>start</tt>: Optional. The date range to return. E.g. <tt>2015-12-19</tt> </li>
<li><tt>end</tt>: Optional. The date range to return. E.g. <tt>2015-12-19</tt> </li>
<li><tt>recipient_ids</tt>: Optional. A comma separated list of recipient ids to filter results by. E.g. {{8211,9892,4432}}} </li>
</ul>
<h4>
<a></a>Authentication:<a href='#Authentication:'></a>
</h4>
<p>Basic authentication with username and password or remote API key belonging to the NewSocialCloud user. </p>
<h4>
<a></a>Success Response:<a href='#Success_Response:'></a>
</h4>
<pre><?xml version="1.0" encoding="UTF-8"?><br>
<msgs type="array"><br>
<msg><br>
<status>Pending<br>
<br>
Unknown end tag for </status><br>
<br>
<br>
<subject>Test subject<br>
<br>
Unknown end tag for </subject><br>
<br>
<br>
<tags><br>
<br>
Unknown end tag for </tags><br>
<br>
<br>
<user-id type="integer">1<br>
<br>
Unknown end tag for </user-id><br>
<br>
<br>
<recurs>Once<br>
<br>
Unknown end tag for </recurs><br>
<br>
<br>
<recurs-until-gmt type="datetime">2010-07-30T15:51:42Z<br>
<br>
Unknown end tag for </recurs-until-gmt><br>
<br>
<br>
<recurs-until-client type="datetime">2010-07-30T16:51:42Z<br>
<br>
Unknown end tag for </recurs-until-client><br>
<br>
<br>
<message-id type="integer">895<br>
<br>
Unknown end tag for </message-id><br>
<br>
<br>
<message-text>Hello world.<br>
<br>
Unknown end tag for </message-text><br>
<br>
<br>
<message-rich-text>Hello world.<br>
<br>
Unknown end tag for </message-rich-text><br>
<br>
<br>
<notify-me type="integer">0<br>
<br>
Unknown end tag for </notify-me><br>
<br>
<br>
<send-date-gmt type="datetime">2010-07-30T15:51:42Z<br>
<br>
Unknown end tag for </send-date-gmt><br>
<br>
<br>
<send-date-client type="datetime">2010-07-30T16:51:42Z<br>
<br>
Unknown end tag for </send-date-client><br>
<br>
<br>
<send-to>user@gmail.com<br>
<br>
Unknown end tag for </send-to><br>
<br>
<br>
<timezone-offset-client type="integer">-60<br>
<br>
Unknown end tag for </timezone-offset-client><br>
<br>
<br>
<photos type="array"><br>
<photo><br>
<id type="integer">484<br>
<br>
Unknown end tag for </id><br>
<br>
<br>
<name>logo1w.png<br>
<br>
Unknown end tag for </name><br>
<br>
<br>
<file-url>http://newsocialcloud.com/imagenes/logo1w.png<br>
<br>
Unknown end tag for </file-url><br>
<br>
<br>
<br>
<br>
Unknown end tag for </photo><br>
<br>
<br>
<photo><br>
<id type="integer">485<br>
<br>
Unknown end tag for </id><br>
<br>
<br>
<name>n1727389556_1512.jpg<br>
<br>
Unknown end tag for </name><br>
<br>
<br>
<file-url>http://newsocialcloud.com/imagenes/n1727389556_1512.jpg<br>
<br>
Unknown end tag for </file-url><br>
<br>
<br>
<br>
<br>
Unknown end tag for </photo><br>
<br>
<br>
<br>
<br>
Unknown end tag for </photos><br>
<br>
<br>
<br>
<br>
Unknown end tag for </msg><br>
<br>
<br>
<msg><br>
<status>Pending<br>
<br>
Unknown end tag for </status><br>
<br>
<br>
<subject>Test subject<br>
<br>
Unknown end tag for </subject><br>
<br>
<br>
<tags><br>
<br>
Unknown end tag for </tags><br>
<br>
<br>
<user-id type="integer">1<br>
<br>
Unknown end tag for </user-id><br>
<br>
<br>
<recurs>Once<br>
<br>
Unknown end tag for </recurs><br>
<br>
<br>
<recurs-until-gmt type="datetime">2010-07-30T15:41:35Z<br>
<br>
Unknown end tag for </recurs-until-gmt><br>
<br>
<br>
<recurs-until-client type="datetime">2010-07-30T16:41:35Z<br>
<br>
Unknown end tag for </recurs-until-client><br>
<br>
<br>
<message-id type="integer">894<br>
<br>
Unknown end tag for </message-id><br>
<br>
<br>
<message-text>Hello world.<br>
<br>
Unknown end tag for </message-text><br>
<br>
<br>
<message-rich-text>Hello world.<br>
<br>
Unknown end tag for </message-rich-text><br>
<br>
<br>
<notify-me type="integer">0<br>
<br>
Unknown end tag for </notify-me><br>
<br>
<br>
<send-date-gmt type="datetime">2010-07-30T15:41:35Z<br>
<br>
Unknown end tag for </send-date-gmt><br>
<br>
<br>
<send-date-client type="datetime">2010-07-30T16:41:35Z<br>
<br>
Unknown end tag for </send-date-client><br>
<br>
<br>
<send-to>user@gmail.com<br>
<br>
Unknown end tag for </send-to><br>
<br>
<br>
<timezone-offset-client type="integer">-60<br>
<br>
Unknown end tag for </timezone-offset-client><br>
<br>
<br>
<photos type="array"><br>
<photo><br>
<id type="integer">480<br>
<br>
Unknown end tag for </id><br>
<br>
<br>
<name>logo1w.png<br>
<br>
Unknown end tag for </name><br>
<br>
<br>
<file-url>http://newsocialcloud.com/imagenes/logo1w.png<br>
<br>
Unknown end tag for </file-url><br>
<br>
<br>
<br>
<br>
Unknown end tag for </photo><br>
<br>
<br>
<photo><br>
<id type="integer">481<br>
<br>
Unknown end tag for </id><br>
<br>
<br>
<name>n1727389556_1512.jpg<br>
<br>
Unknown end tag for </name><br>
<br>
<br>
<file-url>http://newsocialcloud.com/imagenes/n1727389556_1512.jpg<br>
<br>
Unknown end tag for </file-url><br>
<br>
<br>
<br>
<br>
Unknown end tag for </photo><br>
<br>
<br>
<br>
<br>
Unknown end tag for </photos><br>
<br>
<br>
<br>
<br>
Unknown end tag for </msg><br>
<br>
<br>
<br>
<br>
Unknown end tag for </msgs><br>
<br>
</pre>
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
</pre>
</div>
</div>