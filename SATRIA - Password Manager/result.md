# SATRIA v1.0.0

## Permissions
```android.permission.USE_BIOMETRIC```<br>
```android.permission.USE_FINGERPRINT``` <br><br>
Allows an app to use device supported biometric modalities.

## Tech Stack
```flutter``` <br> <br>
This app built with flutter

## Code Analysis
* ```CWE: CWE-649 Reliance on Obfuscation or Encryption of Security-Relevant Inputs without Integrity Checking``` <br> <br>
The App uses the encryption mode CBC with PKCS5/PKCS7 padding. This configuration is vulnerable to padding oracle attacks.

* ```CWE: CWE-276 Incorrect Default Permissions``` <br> <br>
App can read/write to External Storage. Any App can read data written to External Storage.
