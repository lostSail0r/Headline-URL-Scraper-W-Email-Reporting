Headline and URL Scraper with built-in automatic email reporting - Python/Tkinter and Windows .bat<br><br>

<hr><img src="http://cgfixit.com/img/scrapeNemail.png"><hr>

***DOUBLE CLICK MAIN.PY to start program***<hr>Just update the email address info and file paths in the email.bat to your email and where the unzipped Scrape-n-Email folder is located and it should work<hr><br>

scrapes news headlines/urls,craigslist job posts, and exports RCP news into CSV file - Then sends them all (2 text files and 1 excel spreadsheet) as an email attachment<br>

<hr>*Please note even slight changes to website code will break the scrape if it is expecting objects that have been removed/re-named, but they are usually pretty easy to fix.*<hr>
<br>Scrape working for realclearpolitics.com and craigslist.com as of 11/29, although my code is messy and has old comments and modules that aren't really utilized but other active modules rely on so I didn't want to remove; another day I will consolidate and properly label each module and their respective functions but this will work as a template - Compatible on multiple versions but I recently confirmed on Python 3.7, although you will need dependencies like beautifulsoup installed<br><br>

sendEmail.exe credit goes to:<br>
sendEmail - Send email from a console near you!<br>
Written by: Brandon Zehm <caspian@dotconf.net><br>
http://caspian.dotconf.net/<br>
<br>

^^Python and Batch files are my original code, but I downloaded and integrated the sendEmail tool into the batch script - Just wanted to make sure he receives credit for the program that actually sends the email^^
