---
sort: 300
---

# Configuration details

Example:

    @ 1.1
    ;
    ; Tech2Win Configuration
    ;
    -B0 128
    -P0 %Tech2WinUserData%\General Motors\Tech2Win\pcmcia\quickstart.bin
    -PC
    ;-C 9
    -WR 253558
    -ATA
    -W pfrc
    -Pp
    ;-L en_GB
    -CB 0000FF
    -CT FFFFFF
    -S
    -KP R
    -KPBKC FFFFFF

The configuration file for the Tech2Win is stored by default in the `C:\Users\Public\General Motors\Tech2Win\config` folder.

The content of a Tech2Win configuration shows `%Tech2WinUserData%`, an application-specific variable, pointing as default to `C:\User\Public`.
