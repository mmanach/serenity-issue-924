# serenity-issue-924
Please see the link for the issue details.
https://github.com/serenity-bdd/serenity-core/issues/924 


## Configurations
For now, only tested on Windows 10 and with Chrome and Firefox (both last version).

* Selenium
    * Currently using 3.5.2 selenium libs embedded by Serenity 1.5.9

To run  tests in local, you need to download the browser's drivers :
* chromedriver
    * Tested 2.32 with Chrome 60 (64bits)
    * https://sites.google.com/a/chromium.org/chromedriver/downloads
* geckodriver
    * Tested 0.18 with Firefox 55 (64bits)
    * https://github.com/mozilla/geckodriver/releases
    
And to set up them in your environment path.


## Run tests
For running, different way :

* With gradle
```
> gradle clean test aggregate
```

* From the IDE, right click on the runners class (empty class extending SerenityStory)
   

