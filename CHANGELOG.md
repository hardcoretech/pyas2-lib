# Release History

## 1.1.0 - 2019-04-30

* Handle cases where compression is done before signing.
* Add support for additional encryption algorithms.
* Use binary encoding for encryption and signatures.
* Look for `application/x-pkcs7-signature` when verifying signatures.
* Remove support for Python 2.

## 1.0.3 - 2018-05-01

* Remove unnecessary conversions to bytes.

## 1.0.2 - 2018-05-01

* Fix an issue with message decompression.
* Add optional callback for checking duplicate messages in parse
* Add test cases for decompression and duplicate errors

## 1.0.1 - 2018-04-22

* Check for incorrect passphrase when loading the private key.
* Change field name from `as2_id` to `as2_name` in org and partner
* Change name of class from `MDN` to `Mdn`
* Fix couple of validation issues when loading partner
* Return the traceback along with the exception when parsing messages
* Fix the mechanism for loading and validation partner certs

## 1.0.0 - 2018-02-15

* Initial release.
