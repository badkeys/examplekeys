Notes on key conversion
=======================

OpenSSH private key format
--------------------------

Convert PKCS keys in-place to OpenSSH private key format (key needs to be mode 0600):

  ssh-keygen -p -N "" -f [keyfile]

Rejects small RSA keys. Modern versions of OpenSSH do not support DSA.
