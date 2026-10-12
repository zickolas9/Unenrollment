This method terminates MCPS Enterprise from your Chromebook.


Requirements:
A pc of course
Python
A Enrolled Chromebook
======================

Download python here: https://www.python.org/downloads/




Step 1

Open Windows Powershell and enter python -m pip install protobuf requests google

Step 2

Open unenroll.py you will be asked to enter your chromebook SN number
to do that open your chromebook lockscreen and at the top right you will see your sn number
go ahead and type the numbers and click enter

Step 3

You will be asked for your oauth token. to get that go to accounts.google.com/v3/signin/identifier?flow=deviceEnrollment&flowName=GlifSetupChromeOs
login to your Enrolled Account and when its stuck loading Inspect the page by either right clicking and clicking inspect or ctrl+shift+i
go to the application tab and scroll till you see "cookies" expand the cookies and click accounts.google.com and scroll on the right side and find you oauth_code
copy the value and thats your oauth.


step 4
once you click enter it'll close and should be done
Now on your chromebook login and on your keyboard esc+refresh+power button
your screen will go black so don't panic
this next step will depend on what you see

for those who see a white screen recover click ctrl+d then enter, then when it turns on
press space then enter now your Chromebook should be powerwashing itself. when it turns back on
your Chromebook should now be fully unenrolled

for those who see a black screen recovery same process ctrl+d then enter.
when it turns back on select "Return To Secure Mode" then hit enter 2 times




Congratulations you have unenrolled your chromebook!


Note: 
The school cannot block this what so ever
but if this does somehow get patched pm me
and ill update it



Best Regards. 🫶🏽
