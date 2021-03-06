Print Patch 
==========

Adds a menu button to print emails with inline images. Compared to the built in Zimbra print feature, this Zimlet reduces the number of pages to print by 50% or so saving the environment.

If you find Print Patch Zimlet useful and want to support its continued development, you can make donations via:
- PayPal: info@barrydegraaff.tk
- Bank transfer: IBAN NL55ABNA0623226413 ; BIC ABNANL2A

Bugs and feedback: https://github.com/Zimbra-Community/printpatch-zimlet/issues

========================================================================

### Installing

    rm -Rf /opt/zimbra/zimlets-deployed/_dev/tk_barrydegraaff_printpatch
    mkdir -p /opt/zimbra/zimlets-deployed/_dev/tk_barrydegraaff_printpatch
    cd /opt/zimbra/zimlets-deployed/_dev/tk_barrydegraaff_printpatch
    wget https://raw.githubusercontent.com/Zimbra-Community/printpatch-zimlet/master/tk_barrydegraaff_printpatch/tk_barrydegraaff_printpatch.xml
    wget https://raw.githubusercontent.com/Zimbra-Community/printpatch-zimlet/master/tk_barrydegraaff_printpatch/tk_barrydegraaff_printpatch.js

### Illustration

![alt tag](https://raw.githubusercontent.com/Zimbra-Community/printpatch-zimlet/master/Zimbra%20Print%20Patch%20by%20Barry.png)

Related bug: https://bugzilla.zimbra.com/show_bug.cgi?id=95856
