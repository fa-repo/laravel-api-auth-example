# Laravel & nextjs OAuth2 user/pass example

This is an example of an OAuth2 user/pass system built with nextJS and laravel.

## Features included are

- [x] (Laravel) request access and refresh tokens with username / password
- [ ] (Laravel) refresh access token with refresh token
- [ ] (Laravel) revoke access token
- [ ] (Laravel) handle CRUD operations with access token
- [x] (Nextjs) login from login page
- [ ] (Nextjs) register from register page
- [x] (Nextjs) logout with logout button
- [x] (Nextjs) restrict auth pages (and redirect to login)
- [x] (Nextjs) restrict pages that require user to be logged out (for example login)
- [x] (Nextjs) reflect auth status in nav bar
- [x] (Nextjs) store access / refresh tokens server side without exposure to client
- [x] (Nextjs) logout by clearing access token from cookies
- [ ] (Nextjs) automatically refresh expired access tokens