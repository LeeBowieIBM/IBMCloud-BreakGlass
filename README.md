IBM Cloud Shutdown Script
=========================

This is a Python script that will shutdown all VSIs and BareMetal servers in an IBM Cloud account. An API Key with the appropriate permissions on the account is required.

Currently supports:
* Classic VSIs 
* Classic BareMetal

Installation
------------

Install requirements via pip:

	$ pip install -r requirements.txt


Usage
-----

	$ python3 breakGlass.py

System Requirements
-------------------
* Python 3.5, 3.6, 3.7, 3.8, or 3.9.
* A valid SoftLayer API username and key.
