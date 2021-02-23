# Facebook-Auto-Poster
With this Program you can post automatic messages on Facebook Groups which you can parameterize in an excel sheet.   
  
Get the program and excel-sheet from
<a href="https://github.com/Rapid1898-code/Facebook-Auto-Poster">GitHub </a>
<br>Have a look at my general Online FAQ in
<a href="https://www.rapidtech1898.com/htmlFinanztools/en/faqFinanceToolsEN.html">English</a> or
<a href="https://www.rapidtech1898.com/htmlFinanztools/faqFinanceTools.html">German</a>
for my tools

Not interested in all that programming stuff?  
No problem - get the ready-to-use 
<a href="https://www.rapidtech1898.com/aaadownload/FacebookAutomaticPost.exe">windows program</a>

Want to buy me a 
<a href="https://www.rapidtech1898.com/htmlContent/en/coffeeAndBeer.html">coffee</a>
or even a
<a href="https://www.rapidtech1898.com/htmlContent/en/coffeeAndBeer.html">beer</a>
? That would be awesome! 

## First Steps / Pay Attention
* Please use it with caution and don´t make any spams on Facebook an their groups - Thanks!  
* Please check whether the chromedriver version matches your currently installed Chrome version - the appropriate chromedriver version can be downloaded 
<a href="https://chromedriver.chromium.org/downloads">here</a>
and put it in the same folder of the program
* The firewall access may be activated the first time the program is started (click on "OK" or "Allow") - The program pulls data through online scrapping and
therefore needs online access rights
* It is best not to edit the Excel sheet during the update - otherwise, in rare cases this can lead to conflicts
* Make and save settings in the Excel sheet - then start the program - the Excel will be updated


## Input Fields in FacebookAutomaticPost.xlsx
* All input fields are generally in yellow  
* Cell B1: Your Facebook-User for login
* Cell B2: Your Facebook-Password for login (Caution! Please be aware where to put your excel-sheet with such an information...)
* Cell B3: If yes / y / ja / j => You can see the working on the windows during program run - otherwise it will run in the background
* Column B (starting Cell B5): the link name of the Facebook group  
e.g. for the Python group on Facebook the full link is: https://www.facebook.com/groups/python  
so the relevant link for these entry in column B would be "/python"
* Column D (starting Cell D5): the text-cell which should be posted in the Facebook-group according to the "Text"-worksheet entries


## Program workflow
* Make your inputs in the excel-sheet an save
* Let the program run...  
* If this post worked without problems - the actual date will be placed in the corresponding cell in column E  
* If there are any errors during the work on a post (e.g. some additional approvement window for the 
first post) then there will be written "error" in the corresponding cell in column E  
(if the error is only due the approval of the first post - the second run should be fine - so delete the error message and try again)

## Finally
In case of problems or questions have a look at my Online FAQ in
<a href="https://www.rapidtech1898.com/htmlFinanztools/en/faqFinanceToolsEN.html" >English</a> or
<a href="https://www.rapidtech1898.com/htmlFinanztools/faqFinanceTools.html">German</a>

If this does not help please feel free to get in contact with
<a href="mailto:rapid1898@gmail.com"><span>me</span></a>!

