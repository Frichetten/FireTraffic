# FireTraffic
A client-based web traffic logging tool.

For information on installation and configuration see <a href="http://frichetten.com/blog/firetraffic">the project website</a>

Are you hosting a personal website through a static delivery service such as GitHub Pages? While static webpages have improved security and simplicity, they lack the power that you would normally get if you ran your own web server. One of the drawbacks is that you can't know when someone has visited your website. FireTraffic is the solution!

Using the FireBase realtime database you can log whenever someone has visited your website, what pages they've been to, and at what time.

Simply add the FireTraffic-DB.js and firebase.js files to the JavaScript running on your website, add some HTML, and you'll have your own web server loggin system in no time. The following lines are the HTML you'll need.

<pre><script src="https://ajax.aspnetcdn.com/ajax/jQuery/jquery-3.2.1.min.js"></script>
<script src="https://www.gstatic.com/firebasejs/4.1.3/firebase.js"></script>
<script src="/js/firebase.js"></script>
<script src="/js/FireTraffic-DB.js"></script></pre>
