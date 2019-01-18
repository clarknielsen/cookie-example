# Node Cookies

Example of a persistent login with cookies and sessions using the `express-session` module.

Normally, user data would be stored in an actual database, but for the sake of this demo, user info is hard-coded as an array.

It's the session that's more important, because that's how we keep track of who logged in even if the page is refreshed or the user visits another page/route. The cookie just helps us re-log them in if they close the browser and/or come back days later.
