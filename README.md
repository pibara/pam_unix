This version of pam_unix is tollerant of the Caps-Lock key being pressed at password entry time.
Its basically a fork of the ubuntu sources for this PAM module with the following changes:

1)  Added the function 'verify_pwd_hash_caps_ignore' to passverify.c and passverify.h

2) Changed invocations of 'verify_pwd_hash' to use 'verify_pwd_hash_caps_ignore' in the files support.c and passverify.c


