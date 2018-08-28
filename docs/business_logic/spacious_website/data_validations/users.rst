*****
Users
*****


authentication_handle
=====================
- Presence Validation

email
=====
- Uniqueness Validation
- Format Validation

  - Regexp: ``/\A[\w\._%\-\+]+@[\w\.-]+\.[a-zA-Z]{2,4}\z/``

password
========
- Length Validation

  - Minimum length: 4
  - Maximum length: 128

contact_email
=============
- Format Validation

  - Regexp: ``/\A[\w\._%\-\+]+@[\w\.-]+\.[a-zA-Z]{2,4}\z/``
