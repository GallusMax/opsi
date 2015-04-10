Installs a tiny Java program displaying the current OPSI hostname (hn=..) for a barcode reader.
Might be useful with the OPSI Admin found at https://github.com/dirtyharryiv/Android-OPSI-Admin

Prerequisite: Java 1.6

Parameter: domain - configurable domain to be appended to the hostname

Btw: the hostname is generated as hex string (lowercase) from the 6 byte MAC address.
The domain may be set as commandline argument. This is where the "domain" Parameter goes.
