#LinkedInWin: Stop nagging me to login

I don't use LinkedIn, but I sometimes need to look up a person that only has available information online via LinkedIn. I find it annoying that LinkedIn requires me to sign up for their service just to view a single LinkedIn page that a user expects others to see. 

So here's a little bookmarklet that hides the nagging modal login screen and enables scrolling the profile page. 

Drag this to your bookmarks bar:
<a class="bookmarklet" href="javascript:(function()%7Bdocument.querySelector('%23advocate-modal').style.display%20%3D%20'none'%3Bdocument.body.style.overflow%20%3D%20'auto'%7D)()">LinkedInWin</a>

-- or add a bookmark yourself with the address  
``javascript:(function()%7Bdocument.querySelector('%23advocate-modal').style.display%20%3D%20'none'%3Bdocument.body.style.overflow%20%3D%20'auto'%7D)()``

