# Automata(R)

* CLI based software testing application which is basically the composition of two top-rated software testing tools.(Apache JMeter and Selenium)
* Automata mainly aims that, by initializing Selenium at background obtaining some automated tests to input them later on initialized JMeter stress/load testing tool.
* In Automata,users should be expected to write some specific commands both to create test cases and to observe the result of tests in chosen test method of theirs.

# To-do's

* http://stackoverflow.com/questions/37720892/you-dont-have-write-permissions-for-the-var-lib-gems-2-3-0-directory

* https://github.com/mozilla/geckodriver/releases (after download,file should be copied to /usr/bin directory...  -> 
{ sudo cp geckodriver /usr/bin })

* Gems need to be installed is stated below as follows;

# Gemlist

* [ruby-jmeter], [recursive-open-struct], [json], [pry-byebug], [rubygems], [bundler/setup], [selenium-webdriver], [browsermob/proxy]

# Test Cases

* Please create test case files in "selenium_test_files" folder in (.rb) format.

# Step-by-step guide:

* Make sure you have Apache JMeter and Selenium Mozilla Plugin
* After creating a test case in Selenium, go Options -> Format -> Ruby/Test::Unit/WebDriver
* Copy the [def test_untitled] method and paste into the file you created in selenium_test_files file. After copying it, you are ready to start!
* Go to the directory of Automata and type "./automata" in console.
* After executing of the program, it asks which test file you want to use and how many thread(s) you want.
* Enjoy!



