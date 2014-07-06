Discovering pure.css with this playground.

Including
===
Node.js webserver  
Based on express web framework  
Using npm with package.json to install node.js dependencies  
Using bower with bower.json to install front-end dependencies  
Basic project structure with static content, views for html/jade  

What to do to get started
===
Download code as zip file, or clone it, depending on your knowledge.  

Unpack the zip to a place that fits your needs.  

Use the OS X Terminal, Linux Console, or Cygwin and navigate to your folder.  
```cd /Users/yourname/yourdevfolder/purecssplayground```

Enter the commands that follow in the purecss folder parallel to web.js.  

Create a .env file parallel to web.js for secret stuff. You can enter the following command in your console:  
```touch .env```

Add this to your .env:  
>PORT=9999  
>SECRETAUTH=makelotsofrandomnumbersandcharshere  
>SESSIONKEY=dothatheretoo

The port can be anything you like.

I hope you have installed node with brew or in any other way. So you can install the dependencies like this:  
```npm install```

It automatically knows to load the stuff that is written down in package.json.  

So you have bower now and can do this to load the other dependencies:  
```bower install```

It looks into bower.json to load jQuery and Pure.css.  

"Start" the webserver with typing the following into the console:  
```node web.js```

In your browser, you can reach the application via:  
>http://localhost:9999
