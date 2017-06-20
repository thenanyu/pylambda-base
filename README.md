# pylambda-base

Project boilerplate for AWS Lambda tooling. Uses https://github.com/nficano/python-lambda

### Install Dependencies on OSX
Here's a sane OSX configuration if you are new to Python dev and use a Mac.

1. **Python 2.7** (At the time of writing this, AWS Lambda only supports Python 2.7).
You can use the built-in OSX Python in most cases.
2. **Pip (~8.1.1)** the best way to do this is usually `sudo easy_install pip`
3. **Virtualenv (~15.0.0)** once you have pip, you can `sudo pip install virtualenv`
4. **Virtualenvwrapper (~4.7.1)** `pip install virtualenvwrapper` probably no sudo required, but do so if needed.

### Setup
First go install python-lambda: https://pypi.python.org/pypi/python-lambda/.
Follow the instructions to install python-lambda and set up your AWS Lambda account.
This is all somewhat annoying so read the instructions carefully,
especially the bit around how to configure IAM on AWS.

After you have successfully done that, come back.
