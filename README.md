http://nightwatchjs.org/

npm install nightwatch -g

Pre-pend the path "C:\Program Files (x86)\Java\jre1.7.0_40\bin;" to your machine's PATH environment variable

Download selenium standalone from: http://selenium-release.storage.googleapis.com/index.html and put selenium into a "bin" folder in your test source folder

Copy nightwatch.json file from http://nightwatchjs.org/getingstarted

I set the selenium object start_process is set to true; nightwatch will then automatically start the server when you run the tests with grunt. You'll also need to set the server_path to some/directory/selenium-server-standalone-2.40.0.jar

From <http://stackoverflow.com/questions/27225118/connection-refused-is-selenium-server-started> 

Install Chromedriver.exe into your source folder too