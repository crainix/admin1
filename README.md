Get the code
============

Get this project using GitHub or usual git clone.


Modify bash script
==================

Study info.sh. This script shows information for some file types.
Add support for X509 certificates in PEM format:

1. Add hadler for .pem files
2. Use openssl to get subject and MD5 fingerprint of the certificate
3. Print the subject and fingerprint on one line separated by three spaces.
My output for cert.pem:
        `12:34:09:28:AD:05:ED:39:D3:0B:28:88:6B:9A:41:A5:27:0F:4B:F9   /C=EE/ST=Harjumaa/L=Tallinn/O=Edisoft Baltic/CN=HR Test`


Create patch
============

1. After your modifications, create a patch for admin1 directory using git
or usual diff -Nur.

2. Using openssl, encrypt (RSA) the patch with cert.pem.


Entertain yourself
==================

Take a look at the weirdly-named file and find out what to do next.
