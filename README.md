# scheduled-posts
<b>Plugin Name:</b>  Scheduled Posts <br>
<b>Price:</b> 30 USD (contact me to buy) <br>
<b>Plugin Description:</b> This is a premium-paid Q2A plugin that offers scheduling the posts to be published at future date.<br>
<br>
<ul class="first">
	<b>Plugin Functionality:</b>
	<li>Plugin creates a table in database to store data.</li>
	<li>Admin sets which user levels can use schedule posts to be published in future date.</li>
	<li>Admin sets which user levels can moderate (view, publish immediately, delete) all scheduled posts.</li>
	<li>Normal users can see/delete/publish only their own scheduled posts. However, moderators can see/delete/publish all scheduled posts.</li>
	<li>Users can load, change, publish or delete their scheduled posts anytime (it is in users' sub navigation page)</li>
	<li>Permitted user will see "Post Later" checkbox at Q2A ask page. If it is checked then scheduling functionality will be active. If not checked then normal ask procedure of q2a will be valid.</li>
	<li>User can set only future dates (on day basis).</li>
	<li>Plugin has page that shows list of posts scheduled for future dates. It is accessible only by moderator users set in (3)</li>
	<li>Site Administrator needs to set cronjob at server side to scheduledposts-mod-page.php file. The cronjob should be running once per day. Alternatively, admin/plugin option includes "Run Cronjob" button. You can click it as well. It will not be problem if you click it many times per day. The script will only run once per day.</li>
	<li>When date comes, plugin will automatically publish the post.</li>
	<li>In order to not cause load to database. Published posts will be removed from scheduled table after one day. Because published posts will already be in posts table.</li>
	<br/>
	<img src="https://ihlassovbetov.github.io/assets/plugin-ss/scheduled-posts/img-2.png" width="500px" height="auto" />
	<img src="https://ihlassovbetov.github.io/assets/plugin-ss/scheduled-posts/img-3.png" width="500px" height="auto" />
	<img src="https://ihlassovbetov.github.io/assets/plugin-ss/scheduled-posts/img-4.png" width="500px" height="auto" />
	<img src="https://ihlassovbetov.github.io/assets/plugin-ss/scheduled-posts/img-5.gif" width="500px" height="auto" />
	<img src="https://ihlassovbetov.github.io/assets/plugin-ss/scheduled-posts/img-6.png" width="500px" height="auto" />
</ul>
<br/>
<ul class="first">	
	<b>Plugin Admin Settings:</b>
	<li>Admin sets which user levels can use schedule posts to be published in future date. (Default: Registered Users)</li>
	<li>Admin sets which user levels can moderate (view, publish immediately, delete) all scheduled posts. (Default: Admin)</li>
	<li>A Cronjob Button for manual running the check file.</li>
	<br/>
	<img src="https://ihlassovbetov.github.io/assets/plugin-ss/scheduled-posts/img-1.png" width="500px" height="auto" />
</ul>
<br/>
<ul class="first">	
	<b>TEST DEMO WEBSITE: <a href="https://www.e-dostluk.com/q2a-demo" target="_blank">LIVE DEMO</a></b>
	<li>Standard registered user (username: deneme_11 / pass: test1234)</li>
	<li>Moderator user (username: demo / pass: demo1234)</li>
</ul>

