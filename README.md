# Building my Blockchain with Python

Libraries necessary for the creation of a Blockchain with Python.

* **datetime**: The datetime module provides the classes to manipulate dates and times. The implementation allows arithmetic operations with dates and times, but its main objective is to be able to extract fields efficiently for later manipulation or formatting.

* **haslib**: This module implements a common interface to different hash algorithms and secure message digests. Included are the FIPS secure hash algorithms SHA1, SHA224, SHA256, SHA283 and SHA512 in addition to RSA's MD5 algorithm. The terms **secure hash** and **message digest** are interchangeable. The older algorithms were called message digests. The modern term is secure hash.

* **json**: JSON stands for JavaScript Object Notation. JSON is a lightweight data format for data exchange in several different languages. It is easy for humans to read and easy for machines to interpret.

* **Flask**: Flask is a micro web framework written in Python. It is classified as a micro framework because it requires no particular tools or libraries. It has no database abstraction layer, form validation, or any other component where existing third-party libraries provide common functions. However, Flask does support extensions that can add functions to the application as if they were implemented in Flask itself. Extensions exist for object-relational mappers, form validation, load handling, various open authentication technologies and various tools related to the common framework.

* **Flask-ngrok**: A simple way to demonstrate Flask from your machine. Makes your Flask applications running on **localhost** available on the internet through this excellent tool.

## Installations

* !pip install flask==0.12.2
* !pip install flask-ngrok==0.0.25

Creation of a Blockchain class containing all essential methods such as the following:

* Creating a new block
* Obtaining the hash of a block
* Proof of Work (PoW) consensus protocol
* Generating the hash of a block
* Verification of the validity of the Blockchain

Web application accessible via REST API. Through HTTP calls to the REST API we can establish a communication with the use of the Flask module.

REST API calls:

* Block mining: mine_block()
* Get the Blockchain: get_chain()
* Check Blockchain status: is_valid()
