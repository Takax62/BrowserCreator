# BrowserCreator

BrowserCreator is a Python tool that helps you to create browsers. BrowserCreator 0.1 supports Python 3.6 to 3.9. Newer or older versions aren't supported. To install BrowserCreator, download the zip file and then, open command prompt and when you are in the correct directory, type: py -m pip install "BrowserCreator X.X.zip". Replace X.X with the actual version of BrowserCreator. Example codes for 0.1:

from BrowserCreator import fullgui
fullgui("https://bing.com/", "Browser")

from BrowserCreator import halfguiconsole
halfguiconsole("Enter an URL: ", "Browser")

from BrowserCreator import fullconsole
fullconsole("Enter URL: ")
