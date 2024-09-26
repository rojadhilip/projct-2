# projct-2                                                                                                                                                                                                                  SpiceJet
TestNG automation project in Java Selenium.
The implemented automation framework is 100% open source and the components are as follows:
Eclipse, Java, Selenium, JUnit, Apache POI, TestNG.
Steps are as follow :

LOGIN -> FLIGHT FINDER -> SELECT FLIGHT -> BOOK FLIGHT -> FLIGHT CONFIRMATION -> LOGOUT
LAUNCHING OF WEBSITE
launch into spicejet website in chrome
https://www.spicejet.com/
create method for wait(), screenshot()
maximise the screen
implicitly wait for 6 sec

LOGIN
Login using login button
Click on email Radiobutton
Enter email and password
click on login button

FLIGHT FINDER
Click on "Flight Option" radio button
Click on "One Way" radio button
Enter "From" to "To" destination
Add Departure date
Check Return date TextBox is Disable
Add 3 Adults and 2 Children
Choose INR currency
Click on Search Flight button

SELECT FLIGHT
Select the first element and first radio button
Click on Continue Button
Wait untill Upgrade element is visible
Click on Skip button

BOOK FLIGHT
Fill all the necessary detail( Title, First Name, Last Name, Mobile number, Location, Next Element to fill next passanger detail)

CONFIRM BOOKING
Choose your seat as 7A
Don't click on Continue Button but show the message "The last Continue Button for payment is not clicked deliberatly"

LOG OUT
Click on Log out drop down option
Click LogOut Button

QUIT THE BROWSER
Close and quit the open website
