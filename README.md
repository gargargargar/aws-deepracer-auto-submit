# aws-deepracer-auto-submit
This is an auto submission script written for AWS Deepracer with Selenium IDE

Required softwares:
- Selenium IDE (available on Chrome or Firefox)

## Main file: `deepracer-auto-submit`

## Brief Instructions
1. Download and install [Selenium IDE](https://www.selenium.dev/selenium-ide/). (You need to have Google Chrome or Firefox installed.)
2. Download the file `deepracer-auto-submit` from this repository
3. Make sure you're logged into AWS Deepracer!
4. Open Selenium IDE (through your browser), and open the file `deepracer-auto-submit` which you've downloaded.
5. Depending on your needs, you can
	- Click `auto-submit-once` on the left to submit only once, or
	- Click `auto-submit-with-loop` on the left to submit repeatedly automatically
6. You should see "ENTER MODEL NAME HERE" on the line 1. Click on it, and on the bottom where it says "Target", change it to the name of the model you would like to submit.
7. You should see "ENTER COMPETITION URL HERE" on the line 2. Click on it, and on the bottom where it says "Target", change it to the url to the competition you are participating in.
8. Press "Run Current Test," which is the SECOND Play Button on the top. (You can also use Ctrl+R.) DO NOT PRESS THE FIRST PLAY BUTTON! PRESS THE SECOND PLAY BUTTON!

And that should be it! Contact gargar070402@gmail.com if you have any questions.