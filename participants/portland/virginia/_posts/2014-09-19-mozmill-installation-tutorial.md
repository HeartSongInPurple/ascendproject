---
layout: post
title:  "Mozmill Installation Tutorial"
date:   2014-09-19
categories: virginia
---

#Tutorial: How to Install Mozmill on Mac OS X versions 10.5 and later

Hey Mozilla contributor! Yes, you! You are helpful and awesome, and you want to help the hard-working Quality Assurance team (affectionately dubbed mozQA) maximize the functionality and awesomeness of the Firefox web browser! Mozmill is a test suite you can use to run functional tests on any version of Firefox. I'm going to walk you through how to install Mozmill. Ready?

First, if you haven't already, open up your Terminal application or command line shell of your choice. Navigate to your home folder (that command probably looks like this: cd ~), then run each of these commands, as follows:

* $ curl -O https://bitbucket.org/pypa/setuptools/raw/bootstrap/ez_setup.py

When you run that, it will show something like this:

![screenshot1](http://ascendproject.org/participants/portland/virginia/images/1curl.png)

* $ sudo python ez_setup.py

Note: this one may prompt you for your password, which you should go ahead and enter.

![screenshot2](http://ascendproject.org/participants/portland/virginia/images/2sudo_python_ez.png)

This will generate many lines of code as it runs. You will know it's finished when you see this:

![screenshot3](http://ascendproject.org/participants/portland/virginia/images/3sudo_python_finished.png)

* $ sudo easy_install pip

![screenshot4](http://ascendproject.org/participants/portland/virginia/images/4sudo_easy_install.png)

* $ sudo pip install mozmill
Note: This will also generate many lines of code as it downloads. You'll know it's finished when you see this, and then a new command line prompt

![screenshot5](http://ascendproject.org/participants/portland/virginia/images/5sudo_pip_install.png)

Once each of these has been run, you should now have Mozmill installed. You can check by entering this command, which should tell you what version of Mozmill you're running:

* $ mozmill --v

![screenshot6](http://ascendproject.org/participants/portland/virginia/images/6_mozmill__v.png)

So now you're all set up to start running tests! You deserve a badge. Get it [here](https://badges.mozilla.org/en-US/badges/claim/eacw3f)!

Then clone the mozmill-test repository as directed [here](https://developer.mozilla.org/en-US/docs/Mozilla/QA/Mozmill_tests#The_Mozmill-Test_repository), and dig in!
