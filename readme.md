LoveBird: free software to run websites
=====
#### created by [Dan McKeown](http:/danmckeown.info) ####
#### based on [CodeIgniter](http://codeigniter.com) 3 ####
##### released under the [MIT License](LICENSE), copyright 2016 #####

LoveBird can be used to create blogs, online stores, pages, and more.

### Setup ###
In order to install LoveBird, create a mySQL database and use the <code>lovebird4.sql</code> file included in the protect to set up the schema.  Then copy the code to the root of a web server, after changing the data in <code>/application/config/config.php</code> to reflect the details of your site.

When your site is ready, change the constant "DEFAULT_NEW_USER_LEVEL" in your project's <code>/application/config/config.php</code> file to 10 [or desired level], then sign up for your account (and have any other admins sign up) and then once you have done that lower the "DEFAULT_NEW_USER_LEVEL" again, probably to 1.  The levels for access of users can be adjusted in the <code>users_levels</code> table in the database.

After that you can customize the site to your needs.  Edit the views that present the content so it looks the way you want, and modify the controllers for your purposes: visit the [CodeIgniter documentaion](https://www.codeigniter.com/user_guide/) and the [LoveBird homepage](http://lovebird.pacificio.com) to learn more about how to build out your site.

### Links ###
		<ul>
			<li><a href="djmblogGuide.md">djmblogGuide</a></li>
			<li><a href="todo.md">todo</a></li>
			<li><a href="http://lovebird.pacificio.com"><b><i>web site</i></b></a></li>
			<li><a href="https://github.com/pacificpelican/lovebird"><b>GitHub</b></a></li>
		</ul>
