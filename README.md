# ManualBotTimer
Finds any product on Supreme's website by keyword. Enter the keyword when prompted and hit enter. 

The script will run at 11AM (you'll have to adjust the code if you're not in the eastern time zone), the time when the webstore opens.

Due to constraints related to the schedules module the error handling is not as robust as the normal ManualBot script.
For example in this script if a product is not initially found (due to site lag, for example) it will not rerun the script for
a set amount of time like the normal ManualBot script.

Once a product is found it will open in your default webbrowser where you will then have to cart and checkout manually.

Used this personally during week 3 of SS'19, it worked great. I had one running for the band aids (keyword band) and one for the tape measurer (keyword penco) and they both opened up on seperate tabs right at 11. From there I was able to cart from each tab and then checkout (using either tab). It was my first multi-item order, so that's cool.

