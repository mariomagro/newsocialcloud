To update information about the authenticated user's company, make a PUT request.

URL:
http://login.newsocialcloud.com/api/v2/company.json

HTTP Methods:
PUT

Parameters:
application\_id: Your application id from http://newsocialcloud.com/developers
All parameters are optional:

company\_name: Optional. This is the company name.
company\_email: Optional. This is the company's main email address.
company\_website: Optional.This is the URL to the company's website.
company\_favicon: Optional. This is the URL to the company's website favicon.
company\_logo: Optional. This is the URL to the company logo.
global\_url\_shortener: Optional.Set this to the company's default URL shortener. Values include: bit.ly, is.gd, goo.gl, awe.sm, don't shorten
global\_url\_shortener\_login: Optional. If supported, you can provide the user's bit.ly username.
global\_url\_shortener\_key: Optional. If supported, you can provide the user's bit.ly api key.
Optional for white labels:

language: Optional. The default language code for this white label. E.g. en or es.
contact\_us\_url: Optional. The help URL for this white label site.
ga\_tracking\_code: Optional. The Google Analytics tracking code.
html\_widget\_code: Optional. The HTML widget code that is appended to the site.
theme: Optional. The name of the theme to be applied. E.g. {{smoothness}}
custom\_css: Optional. The custom CSS code to be applied to the white label site along with the theme.
menus: Optional. A JSON object array containing the menu structure. For example:
[
> {
> > "name": "Google Apps",
> > "submenus": [
> > > {
> > > > "name": "Calendar",
> > > > "url": "http://apps.google.com/calendar",
> > > > "type": "iframe"

> > > },
> > > {
> > > > "name": "Mail",
> > > > "url": "http://apps.google.com/mail",
> > > > "type": "url"

> > > },
> > > {
> > > > "name": "Drive",
> > > > "url": "http://apps.google.com/drive",
> > > > "type": "iframe"

> > > }

> > ]

> }
]
Authentication:
Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

Success Response:
{
"status": "OK"
}
Error Responses:

{"error": {"type": "NotFound", "message": "Company could not be found."} }
{"error": {"type": "PermissionDenied", "message": "Only administrators can update the company information."} }