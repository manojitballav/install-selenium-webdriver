# install-selenium-webdriver
Contains instructions on how to install selenium on to Linux Enviroment

Install Selenium from pip using the following commands
```sudo pip install selenium```

After installing selenium, copy the geckodriver and chrome driver from the repository and paste in the usr/bin directory


After copying them into the directory run the following python script to check it.
```
from selenium import webdriver


driver = webdriver.Chrome()

driver.maximize_window()
driver.get('http://www.tunester.ml')

#confirming done
print "Done"

#Close the driver successfully
#uncomment the line below to close the browser
#driver.quit()

```

