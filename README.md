IdeaScaly: IdeaScale RESTful API Client
=========
[![Latest Version](https://img.shields.io/pypi/v/ideascaly.svg)](https://pypi.python.org/pypi/ideascaly/)
[![Supported Python versions](https://img.shields.io/pypi/pyversions/ideascaly.svg)](https://pypi.python.org/pypi/ideascaly/)
[![Development Status](https://img.shields.io/pypi/status/ideascaly.svg)](https://pypi.python.org/pypi/ideascaly/)
[![Coverage Status](https://coveralls.io/repos/joausaga/ideascaly/badge.svg)](https://coveralls.io/r/joausaga/ideascaly)
[![License](https://img.shields.io/pypi/l/ideascaly.svg)](https://pypi.python.org/pypi/ideascaly/)

IdeaScale RESTful API client written in Python. So far, IdeaScaly supports about **50%** of [IdeaScale API] 
(http://support.ideascale.com/customer/portal/articles/1001563-ideascale-rest-api) methods. Basically, with IdeaScaly is
 possible to:
 * Add new members;
 * Attach images as members' avatars;  
 * Get information about community members;
 * Create and delete ideas;
 * Vote up/down on ideas;
 * Attach files to ideas;  
 * Post comments on ideas and comments;
 * Get the list of recent, top, and hot ideas;
 * Get the list of ideas under review, in progress, and complete;
 * Get the list of campaigns;
 * Get archived ideas;
 * Get active ideas;  
 and much more. 
 
The complete list of implemented methods is available 
<a href="https://docs.google.com/spreadsheets/d/1gICkmX7EiSukQ0iTsOkxNrkES2blc5joh-AIeFVTcI8/edit?usp=sharing" target="_blank">here</a> 

Installation
------------

The easiest way to install the latest version is through pip/easy_install, which will pull from PyPI

`pip install ideascaly`

Also, it is possible to clone the repository from Github and install it manually:

```
git clone https://github.com/joausaga/ideascaly
cd ideascaly
python setup.py install
```

Documentation
-------------
* IdeaScaly, coming soon! (meanwhile the examples may help)
* <a href="http://support.ideascale.com/customer/portal/articles/1001563-ideascale-rest-api" target="_blank">IdeaScale</a>

License
-------
MIT

Acknowledgement
---------------
The design and architecture of the code is mostly based on the project [Tweepy](https://github.com/tweepy/tweepy) 