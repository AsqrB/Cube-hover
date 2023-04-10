# How to make custom Error page for your website and why?

A:- Scenario/problem: User is attempting to look for a page that does not exist.
    Known context: 404 page not found.
    Solution: A friendly page informing the user of what happened in simple language and tell them what to do next.
  
    Step 1 - Create your custom error page in HTML and upload it on your server.
    Step 2 - Look for ".htaccess" file in root directory of your server.
    Step 3 - Edit .htaccess file:
           Open it and add  -> " ErrorDocument 404 /Not_found_error.html "
           Where "Not_found_error.html" is the full path to custom 404 page you have created
           we can do the same for different errors by changing the error codes
    Step 4 - Make sure The path is correct and the custom error page is working.


NOTE: If you are using website builders like Wix or Squarespace then, it should already have 404 error page settings.
  You can use it directly to upload images and add buttons.
