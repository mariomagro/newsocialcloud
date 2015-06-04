To retrieve daily statistics for a given social media account detail, make a GET call using basic authentication. The days returned represent the date for the given year/month period.

**URL:**

http://login.newsocialcloud.com/api/v1/account-statistics.format

**Formats:**

Replace format with either xml or json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>account_detail_id: The account detail id for which to retrieve the valid yearmonth codes. Valid account_detail_ids can be retrieved using the using the GetAccountDetails call.</p>
<p>yearmonth: Optional. The yearmonth period for which to retrieve statistics. Valid yearmonths can be retrieved using the using the GetAccountPeriods call.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**



&lt;account-statistics type="array"&gt;


> 

&lt;account-statistic&gt;


> > ```
Fans```
> > 

&lt;day-1 type="decimal"&gt;

7575.0

&lt;/day-1&gt;


> > 

&lt;day-10 type="decimal"&gt;

7653.0

&lt;/day-10&gt;


> > 

&lt;day-11 type="decimal"&gt;

7663.0

&lt;/day-11&gt;


> > 

&lt;day-12 type="decimal"&gt;

7674.0

&lt;/day-12&gt;


> > 

&lt;day-13 type="decimal"&gt;

7692.0

&lt;/day-13&gt;


> > 

&lt;day-14 type="decimal"&gt;

7704.0

&lt;/day-14&gt;


> > 

&lt;day-15 type="decimal"&gt;

7719.0

&lt;/day-15&gt;


> > 

&lt;day-16 type="decimal"&gt;

7730.0

&lt;/day-16&gt;


> > 

&lt;day-17 type="decimal"&gt;

7743.0

&lt;/day-17&gt;


> > 

&lt;day-18 type="decimal"&gt;

7751.0

&lt;/day-18&gt;


> > 

&lt;day-19 type="decimal"&gt;

7761.0

&lt;/day-19&gt;


> > 

&lt;day-2 type="decimal"&gt;

7568.0

&lt;/day-2&gt;


> > 

&lt;day-20 type="decimal"&gt;

7773.0

&lt;/day-20&gt;


> > 

&lt;day-21 type="decimal"&gt;

7786.0

&lt;/day-21&gt;


> > 

&lt;day-22 type="decimal"&gt;

7795.0

&lt;/day-22&gt;


> > 

&lt;day-23 type="decimal"&gt;

7804.0

&lt;/day-23&gt;


> > 

&lt;day-24 type="decimal"&gt;

7813.0

&lt;/day-24&gt;


> > 

&lt;day-25 type="decimal"&gt;

7827.0

&lt;/day-25&gt;


> > 

&lt;day-26 type="decimal"&gt;

7843.0

&lt;/day-26&gt;


> > 

&lt;day-27 type="decimal"&gt;

7861.0

&lt;/day-27&gt;


> > 

&lt;day-28 type="decimal"&gt;

7873.0

&lt;/day-28&gt;


> > 

&lt;day-29 type="decimal"&gt;

7889.0

&lt;/day-29&gt;


> > 

&lt;day-3 type="decimal"&gt;

7587.0

&lt;/day-3&gt;


> > 

&lt;day-30 type="decimal"&gt;

7901.0

&lt;/day-30&gt;


> > 

&lt;day-31 type="decimal"&gt;

7913.0

&lt;/day-31&gt;


> > 

&lt;day-4 type="decimal"&gt;

7594.0

&lt;/day-4&gt;


> > 

&lt;day-5 type="decimal"&gt;

7610.0

&lt;/day-5&gt;


> > 

&lt;day-6 type="decimal"&gt;

7619.0

&lt;/day-6&gt;


> > 

&lt;day-7 type="decimal"&gt;

7627.0

&lt;/day-7&gt;


> > 

&lt;day-8 type="decimal"&gt;

7635.0

&lt;/day-8&gt;


> > 

&lt;day-9 type="decimal"&gt;

7645.0

&lt;/day-9&gt;


> > 

&lt;id type="integer"&gt;

3975268

&lt;/id&gt;


> > 

&lt;yearmonth&gt;

201203

&lt;/yearmonth&gt;




&lt;/account-statistic&gt;




&lt;account-statistic&gt;


> > ```
Page Views```
> > 

&lt;day-1 type="decimal"&gt;

207.0

&lt;/day-1&gt;


> > 

&lt;day-10 type="decimal"&gt;

252.0

&lt;/day-10&gt;


> > 

&lt;day-11 type="decimal"&gt;

201.0

&lt;/day-11&gt;


> > 

&lt;day-12 type="decimal"&gt;

288.0

&lt;/day-12&gt;


> > 

&lt;day-13 type="decimal"&gt;

188.0

&lt;/day-13&gt;


> > 

&lt;day-14 type="decimal"&gt;

202.0

&lt;/day-14&gt;


> > 

&lt;day-15 type="decimal"&gt;

186.0

&lt;/day-15&gt;


> > 

&lt;day-16 type="decimal"&gt;

200.0

&lt;/day-16&gt;


> > 

&lt;day-17 type="decimal"&gt;

221.0

&lt;/day-17&gt;


> > 

&lt;day-18 type="decimal"&gt;

213.0

&lt;/day-18&gt;


> > 

&lt;day-19 type="decimal"&gt;

226.0

&lt;/day-19&gt;


> > 

&lt;day-2 type="decimal"&gt;

228.0

&lt;/day-2&gt;


> > 

&lt;day-20 type="decimal"&gt;

173.0

&lt;/day-20&gt;


> > 

&lt;day-21 type="decimal"&gt;

199.0

&lt;/day-21&gt;


> > 

&lt;day-22 type="decimal"&gt;

177.0

&lt;/day-22&gt;


> > 

&lt;day-23 type="decimal"&gt;

177.0

&lt;/day-23&gt;


> > 

&lt;day-24 type="decimal"&gt;

213.0

&lt;/day-24&gt;


> > 

&lt;day-25 type="decimal"&gt;

206.0

&lt;/day-25&gt;


> > 

&lt;day-26 type="decimal"&gt;

232.0

&lt;/day-26&gt;


> > 

&lt;day-27 type="decimal"&gt;

188.0

&lt;/day-27&gt;


> > 

&lt;day-28 type="decimal"&gt;

193.0

&lt;/day-28&gt;


> > 

&lt;day-29 type="decimal"&gt;

260.0

&lt;/day-29&gt;


> > 

&lt;day-3 type="decimal"&gt;

181.0

&lt;/day-3&gt;


> > 

&lt;day-30 type="decimal"&gt;

221.0

&lt;/day-30&gt;


> > 

&lt;day-31 type="decimal"&gt;

248.0

&lt;/day-31&gt;


> > 

&lt;day-4 type="decimal"&gt;

226.0

&lt;/day-4&gt;


> > 

&lt;day-5 type="decimal"&gt;

210.0

&lt;/day-5&gt;


> > 

&lt;day-6 type="decimal"&gt;

210.0

&lt;/day-6&gt;


> > 

&lt;day-7 type="decimal"&gt;

153.0

&lt;/day-7&gt;


> > 

&lt;day-8 type="decimal"&gt;

166.0

&lt;/day-8&gt;


> > 

&lt;day-9 type="decimal"&gt;

249.0

&lt;/day-9&gt;


> > 

&lt;id type="integer"&gt;

4137142

&lt;/id&gt;



> 

&lt;yearmonth&gt;

201203

&lt;/yearmonth&gt;




&lt;/account-statistic&gt;



**Error Response:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;

