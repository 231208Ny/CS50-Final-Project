# Voting System using Block-Chain

A user can cast his vote by visiting this web platform. For web server scripting we have used python based web framework *Django*.



## How to run

1. Make sure you are connected to the internet.
2. Install all the (pip) dependency packages (main packages are listed in requirements.txt).
3. Locate EMAIL_ADDRESS and EMAIL_PASSWORD variable in Election/settings.py file and assign your valid credentials. (See [References](#EmailCredentials))
4. Make sure email sending is allowed (while development process sending email every time is not a good idea because API allows us to send email only for limited no. of times.).


​		For this make sure send_otp() method in views.py file looks like this:

python
...
[success, result] = send_email_…
