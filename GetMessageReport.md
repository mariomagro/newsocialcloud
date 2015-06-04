Retrieve the details for a given report\_id by making a GET request using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v1/message-report.format

**Formats:**

Replace format with either xml or json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>report_id: The message report id. Retrieved using the message reports call.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

<?xml version="1.0" encoding="UTF-8"?>


&lt;message-report&gt;


> 

&lt;clientTime type="datetime"&gt;

2010-09-12T15:59:11Z

&lt;/clientTime&gt;


> 

&lt;message-html&gt;


&lt;html&gt;
&lt;head&gt;
&lt;title&gt;&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
&lt;p&gt;Burnout is sneaky&amp;mdash;it doesn't happen overnight&amp;mdash;but t
he stages have classic signs. Clueing in to them can help you sidestep a workout
> slump: http://bit.ly/cXrFix&lt;/p&gt;
&lt;/body&gt;
&lt;/html&gt;

&lt;/message-html&gt;


> > 

&lt;message-text&gt;

Burnout is sneaky&#8212;it doesn't happen overnight&#8212;but th
e stages have classic signs. Clueing in to them can help you sidestep a workout
slump: http://bit.ly/cXrFix

&lt;/message-text&gt;


> > 

&lt;report-id type="integer"&gt;

1069562

&lt;/report-id&gt;


> > 

&lt;subject&gt;



&lt;/subject&gt;


> > 

&lt;score type="decimal"&gt;

1834.0

&lt;/score&gt;


> > 

&lt;messages-photos type="array"&gt;


> > > 

&lt;messages-photo&gt;


> > > > 

&lt;photo-id type="integer"&gt;

47908

&lt;/photo-id&gt;


> > > > 

&lt;file-name&gt;

4 Stages of Exercise Burnout &#8212; And How to Avoid Them</fil
e-name>
> > > > 

&lt;file-url&gt;

![http://www.active.com/Assets/Fitness/WH14287.jpg](http://www.active.com/Assets/Fitness/WH14287.jpg)

&lt;/file-url&gt;


> > > > 

&lt;file-type&gt;

image

&lt;/file-type&gt;



> > > 

Unknown end tag for &lt;/messages-photo&gt;



> > 

Unknown end tag for &lt;/messages-photos&gt;


> > 

&lt;message-recipients type="array"&gt;


> > > 

&lt;message-recipient&gt;


> > > > 

&lt;accountName&gt;

Facebook page - C25K Fan Page

&lt;/accountName&gt;


> > > > 

&lt;recipient-first-name&gt;

Status

&lt;/recipient-first-name&gt;


> > > > 

&lt;recipient-identifier&gt;

311542

&lt;/recipient-identifier&gt;


> > > > 

&lt;recipient-last-name&gt;

Update

&lt;/recipient-last-name&gt;


> > > > 

&lt;icon&gt;

/images/facebook\_page.gif

&lt;/icon&gt;



> > > 

&lt;/message-recipient&gt;



> > 

&lt;/message-recipients&gt;


> > 

&lt;message-statistics type="array"&gt;


> > > 

&lt;message-statistic&gt;


> > > > ```
Click```
> > > > 

&lt;stat-value type="integer"&gt;

1822

&lt;/stat-value&gt;



> > > 

&lt;/message-statistic&gt;


> > > 

&lt;message-statistic&gt;


> > > > ```
Comment```
> > > > 

&lt;stat-value type="integer"&gt;

12

&lt;/stat-value&gt;



> > > 

&lt;/message-statistic&gt;



> > 

&lt;/message-statistics&gt;



> 

&lt;responses type="array"&gt;


> > 

&lt;response&gt;


> > > 

&lt;avatar&gt;

http://profile.ak.fbcdn.net/profile-ak-snc1/v22944/426/25/q1000004
89381805\_5137.jpg

&lt;/avatar&gt;


> > > 

&lt;body&gt;

I'm in Cape Coral have been going to a local gym off and on it is ha
rd to get motivated sometimes but I do try to get there at least two or three ti
mes a week when I do go. It would be easier if there was someone like a gym budd
y that also needed motivating to go to the gym. But I will check out the website
.

&lt;/body&gt;


> > > 

&lt;created-at type="datetime"&gt;

2010-09-13T05:12:01Z

&lt;/created-at&gt;


> > > 

&lt;responder-fullname&gt;

Debbie Fisher Riddling

&lt;/responder-fullname&gt;


> > > 

&lt;responder-identifier&gt;

100000489381805

&lt;/responder-identifier&gt;


> > > 

&lt;response-type&gt;

Comment

&lt;/response-type&gt;


> > > 

&lt;service-name&gt;

Facebook(page)

&lt;/service-name&gt;



> > 

&lt;/response&gt;


> > 

&lt;response&gt;


> > > 

&lt;avatar&gt;

http://profile.ak.fbcdn.net/hprofile-ak-snc4/hs462.snc4/48821_6057
02829\_5037\_q.jpg

&lt;/avatar&gt;


> > > 

&lt;body&gt;

The best way to find races is to visit active.com.  You can put in t
he dates and event type you want and then narrow the search with your zip code.

> It's basically the best thing ever!

&lt;/body&gt;


> > 

&lt;created-at type="datetime"&gt;

2010-09-12T19:59:05Z

&lt;/created-at&gt;


> > 

&lt;responder-fullname&gt;

Audrey Hill

&lt;/responder-fullname&gt;


> > 

&lt;responder-identifier&gt;

605702829

&lt;/responder-identifier&gt;


> > 

&lt;response-type&gt;

Comment

&lt;/response-type&gt;


> > 

&lt;service-description&gt;

Facebook Fan Page

&lt;/service-description&gt;


> > 

&lt;/response&gt;



> 

&lt;/responses&gt;




Unknown end tag for &lt;/message-report&gt;



**Error Response:**



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

ParametersMissing

&lt;/type&gt;




&lt;message&gt;

The required parameters for this method are: report\_id.

&lt;/message&gt;




&lt;/error&gt;



OR



&lt;error&gt;




&lt;type&gt;

ReportNotFoundError

&lt;/type&gt;




&lt;message&gt;

Report could not be found.

&lt;/message&gt;




&lt;/error&gt;

