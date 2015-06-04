Returns a downloadable HTML or CSV report for all account data for a given period. Make a GET call using the api key of the authenticated user.

**URL:**

http://login.newsocialcloud.com/reports?type=account-report&ext=format

**Formats:**

Replace format with either html or csv

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>access_key: The api_key belonging to the authenticated user.</p>
<p>account_detail_id: The account detail id for which to retrieve the valid yearmonth codes.</p>
<p>yearmonth: The yearmonth period for which to export.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

A downloadable file in the specified format of HTML or CSV.