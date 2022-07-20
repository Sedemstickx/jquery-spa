jquery-spa
A simply made single page application(SPA) template that works exactly like a modern SPA site.

About
This is a simple and light(less than 70 lines of code as of now) Single Page Application (SPA) written in jquery that I decided to create for myself and developers that just learnt javascript and jquery and want to build a simple SPA site/app, or are interested in understanding the fundermentals of what SPA frameworks like angular,vue and react etc. do to create a SPA environment.

This app works with html, css and depends on jquery for simplicity and apache webserver to be fully functional.

Deploy
Just download the files and save them in your webserver and run.

This project is hosted on GH pages so you can see how it works, however due to dependency on apache server edit it has some limitations.

This project has a .htaccess file that works on apache webservers to ensure that on any default browser load action or page access trough the address bar the browser will load the root file of the directory(index.html) before the jquery code loads other pages. If developers run this code on other types of web servers they can delete the .htaccess file and edit their web servers to acheive the same result so that the application doesn't have any limitations.

Limitations
None recorded so far after using all dependencies. Please read code comments to further understand how it works :).

Related Projects
Please check out another SPA project that uses hash(#) in the urls(like the way gmail spa works I think): https://github.com/Sedemstickx/spa-hash

Any commits by other developers to further make this simple and easily used by anyone will be appreciated.
