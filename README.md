# PythonSurfForecast

A Python Script to check the Surf Forecast

## NOTE :
* This code is a bit rough around the edges and may need a bit of work to run, my newer code on other projects is a lot cleaner, use with caution!

<img src="https://github.com/Xioto/PythonSurfForecast/blob/main/docs/assets/img/logo.png" alt=" logo" width="500"/>

[![GitHub Status](https://img.shields.io/github/checks-status/Xioto/PythonSurfForecast/main)](https://github.com/Xioto/PythonSurfForecast/)
[![Github All Releases](https://img.shields.io/github/downloads/Xioto/PythonSurfForecast/total.svg?style=flat-square)](https://github.com/Xioto/PythonSurfForecast/releases/latest)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
![License](https://img.shields.io/github/license/Xioto/PythonSurfForecast)

[See here for detailed documentation!](https://github.com/Xioto/PythonSurfForecast/wiki)


## 💻Requirements
* Python 3.0 & Above ([Download](https://www.python.org/downloads/))
* Pip 21.1.2 (Pre-Installed)
* Git 2.32.0 ([Download](https://git-scm.com/download/))
* StormGlass API Key (<a href="api">See Here</a>)


## 📦Installation

**Note: You may wish to run this script in a virtual environment, as these modules will install system-wide. To find out more, [see here](https://realpython.com/python-virtual-environments-a-primer/#using-virtual-environments)**

1. Clone the repo
   ```sh
   git clone https://github.com/Xioto/PythonSurfForecast
   ```
2. Install Python packages
   ```sh
   # Windows
   cd PythonSurfForecast
   py -3 -m pip install -r requirements.txt
   
   # Unix
   cd PythonSurfForecast
   python3.8 -m pip install -r requirements.txt
   ```
3. Run the `main.py` file using `python main.py` 


## 📝Configuring `main.py`

   ### Latitude & Longitude (Required)
   * Go to [Google Maps](https://www.google.com/maps) and find the Beach that you want to get a Forecast for, then Right-Click and copy the Lat & Long from Google Maps and paste it in `main.py`.


<a id="api"></a>   
### API-Key (Required)
   * Go to [StormGlass](https://stormglass.io/) and click "Try for Free", you will need to Sign Up, it will then redirect you to the [Dashboard](https://dashboard.stormglass.io/). It will then provide you with an API-Key, you can then paste that in `main.py`.
   
   ### Email Support (Optional)
   * To add email support, you will need to allow "[Less Secure Apps](https://myaccount.google.com/lesssecureapps)" on the Google Account you are using to send the email. 
  
   **WARNING** - This will make your account more vunerable to less-secure apps. [Learn More](https://support.google.com/accounts/answer/6010255?p=less-secure-apps&hl=en-GB&visit_id=637672482665758342-55459182&rd=1).
   * To remove email support, either remove the code starting from `mail_content` to `print('Mail Send')`. 
   * `mail_content` - Input the Content of the email you want to send
   * `sender_address` - Input the Email Address of the Google Account above. This will be used to send the email.
   * `sender_pass` - Input the password of the Google Account
   * `receiver_address` - Input the address that you want to send the email to.
   * `message['Subject']` - Input the subject line of the email.

   ### Discord Support (Optional)
   * To add discord support, you will need a Webhook URL. To get one of these, follow [this guide](https://help.dashe.io/en/articles/2521940-how-to-create-a-discord-webhook-url), you will need to then paste the URL where it says `(url='DISCORD-WEBHOOK-URL')`.
   * `content` - Input the content of the Discord Message you want to send.


## 🆕Changelog

   ### V2 - Major Update 🌈
   * Removed checking for updates and version
   * Removed bad error handling
   * Fixed spelling errors
   * Added response.json to .gitignore
   * Tidy of the readme.md
   * Updated wiki
   * Released on 15/03/22

   ### V1.6 - General Tidy 🌈
   * Removed amount of dots when checking version
   * Making comments clearer
   * Released on 15/9/21

   ### V1.5 - Comments 🌈
   * Removed useless comments
   * Released on 20/06/21

   ### V1.4 - Full Release 🌈
   * Leaving Pre-Release!
   * Patched a bug that prevented the sorting of `response.json`.
   * Removed a part of the loading screen
   * Patched another bug that caused multiple emails to be sent at once
   * Released on 20/06/21

   ### V1.3 - Loading Screen & Bugs 🌈
   * Added Loading Screen
   * Patched Small Bug
   * Released on 14/06/21

   ### V1.2 - Discord Support 🌈
   * Added Discord Support and tidying Code.
   * Released on 11/06/21
   
   ### V1.1 - 🌈
   * Added Email Support and fixed Bugs.
   * Released on 10/06/21


## 💸Credits

   ### API
   * [StormGlass](https://stormglass.io/)
   * [StormGlass Docs](https://docs.stormglass.io/#/)
   
   ### Tutorials
   * [Sending Emails with Python and Gmail](https://realpython.com/python-send-email/) 
   * [API Get.Request Code](https://docs.stormglass.io/#/tide)
   * [Discord Webhook Support](https://pypi.org/project/discord-webhook/) 
   
   ### Fixes
   * [Finding Current Day](https://stackoverflow.com/questions/29384696/how-to-find-current-day-is-weekday-or-weekends-in-python)
   * [Finding Content in Cache_File](https://www.reddit.com/r/learnprogramming/comments/ntsu78/creating_string1_with_constantly_changing/)

   ### Other
   * [wsldl for the README.MD style](https://github.com/yuk7/wsldl)


## 📄License
This repository is licensed under the [Apache](https://github.com/Xioto/PythonSurfForecast/blob/main/LICENSE) License.

*I am not responsible for content on any other websites linked to from this site - the inclusion of any such links does not necessarily imply a recommendation or endorse the views expressed within them. I have no control over the nature, content and availability of those sites and you view them strictly at your own risk.*

Copyright©️ 2022 Xioto
