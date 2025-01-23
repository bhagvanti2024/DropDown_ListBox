# DropDown_ListBox
WebElemnetDropDown.java
This Java program demonstrates how to handle dropdown lists (comboboxes) using Selenium WebDriver on the Facebook signup page.

Features:

Setup ChromeDriver: Specifies the path to the ChromeDriver executable.

Navigate to Facebook: Opens https://www.facebook.com/.

Navigate to Create Account: Clicks on the 'Create new account' button to open the signup form.

Wait for Dropdown Visibility: Uses a WebDriverWait to wait until the "month" dropdown is visible.

Interact with Dropdown: Creates a Select object to interact with the dropdown list, prints all options, and selects a specified month.

Close Browser: Closes the browser.

Usage Steps:

Set ChromeDriver Property: Ensure the path to your local ChromeDriver executable is set correctly.

Start ChromeDriver: Initialize the ChromeDriver.

Open Facebook: Navigate to Facebook’s homepage.

Open Signup Form: Click the button to open the signup form.

Wait and Select Month: Wait for the "month" dropdown to become visible, print all available options, and select a specific month.

Close Browser: Close the browser when done.

Notes:
Make sure the ChromeDriver version matches your Chrome browser version.

Adjust the path to chromedriver.exe according to your local file system.

The WebDriverWait ensures the dropdown is visible before interacting with it.

You can customize the selectByVisibleText method to choose any month needed for your tests.

This description should provide a clear and detailed overview of the program for anyone viewing your GitHub repository. Let me know if there's anything else you need!
