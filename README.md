# WordPress REST API Dashboard Script/Plugin
dashboard.html includes all the html, css, and javascript to succesfully GET various endpoints from the WordPress REST API such as:
- Users
- Categories
- Posts
- Tags
- Media

As well as succesfully POST, DELETE, and PUT Posts, and POST media via a simple SPA dashboard handled within one URL without using a nonce header.
Includes a basic markdown for rendering certain HTML (embedded images, YouTube URLs, bold text, italic text, and underlined text).
Used for client and client's interns to be able to create media and posts without having to login to WordPress, dashboard implemented on a password-protected page.

Custom modifications were made to `.htaccess` and relevant theme's `functions.php` hooks regarding CORS.

*Does not work if site is maitenane mode*
*Uses custom auth hook not present in dashboard.html*
