CHANGELOG
=========

Version 1.0.6
-------------

* fix getStatus() to returns TRUE on array data responds, such as from sendSms() or getOutgoing()

Version 1.0.5
-------------

* handle some notice and warning error messages


Version 1.0.4
-------------

* fix getStatus() to reflect correct request status


Version 1.0.3
-------------

* urlencode most variable on _setWebservicesUrl()
* run _setWebservicesUrl() on getWebservicesUrl()


Version 1.0.2
-------------

* code cleanups


Version 1.0.1
-------------

* getResponse() returns Webservices_Response object
* add Webservices_Response class


Version 1.0.0
-------------

* add complete test files
* add getResponse() to return json_decode() of response
* add sendSms() and sendSmsToGroup()
* add getPhonebookContacts() and getPhonebookGroups()
* add getOutgoing(), getIncoming(), getInbox() adn getSandbox()
* add setToken()
* add getToken() and getCredit()
* first commit
