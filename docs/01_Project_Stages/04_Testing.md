For web-based projects, at a minimum, the application should be tested in a variety of web browsers and on different devices.

###Cross-browser

The application should function in the latest versions of the major browsers. Deciding your approach to supporting older versions of each browser will depend on the audience your project is targeting. If the project has an existing web presence, looking at Analytics reports that show browser usage will give a good indication of what is required.

Often, older web browsers will not display applications in the same way as newer browsers. Ensuring support of these older browsers can be time-consuming, costly...and frustrating.  As a general rule, and depending on the application, I would suggest supporting 2-3 versions back from the current version for each web browser (basically >= Internet Explorer 8). 

Progressive Enhancement can be used as an approach to show a basic version of web pages to all users, with an enhanced version being shown to users with modern browsers.


###Cross-device (mobile strategy dependent)

The project should take account of the range of devices (small and large) that users access web-based projects on. 

[Responsive Design](https://en.wikipedia.org/wiki/Responsive_Web_Design) is an approach to design and development which tailors the display of the web application to devices of different sizes. It should be used by web-based projects, unless there is a good reason not to do so. 


###Automated testing strategy

Depending on the complexity of the project, automated testing can be employed. This can be discussed with the project developers.

The approaches used will depend heavily on the project's technology; some examples include PHPUnit and Behance for PHP-based projects, and Mocha or Karma for JavaScript applications.


### Usability Testing

This is the process of evaluating the application with users to determine how usable it is. This can be done in person, or remotely.

> By putting our best guesses about what works in front of our target audience, we get to see where we were right and where we were wrong, ([Goldstein, 2012](http://alistapart.com/article/beyond-usability-testing)). 

Here are some useful articles on the process:

- [Usability Testing Demystified](http://alistapart.com/article/quick-and-dirty-remote-user-testing), Dana Chisnell, 2009
- [Beyond Usability Testing](http://alistapart.com/article/beyond-usability-testing), Devan Goldstein, 2012
- [Quick and Dirty Remote User Testing](http://alistapart.com/article/quick-and-dirty-remote-user-testing), Nate Bolt, 2010