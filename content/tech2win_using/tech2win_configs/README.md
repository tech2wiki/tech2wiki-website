---
sort: 200
---
# Configuration files

The configuration file for the Tech2WIN is stored by default in the `C:\Users\Public\General Motors\Tech2Win\config` folder.

The content of a tech2win configuration shows `%Tech2WinUserData%`, an application-specific variable, pointing as default to `C:\User\Public`.

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

## Predefined configs

| Tech2WIN .bin file(s)    | Configuration file    |
| ---                   | ---                   |
| [GM NAO](/content/tech2_pcmcia/available_tech2win_.bin-files/tech2win_gm_nao.md) | [tech2win_config_gm_nao_v33.004_en.conf](tech2win_config_gm_nao_v33.004_en.zip) |
| [Holden](/content/tech2_pcmcia/available_tech2win_.bin-files/tech2win_holden.md) | [tech2win_config_holden_1997-2012_v157.000_en.conf](tech2win_config_holden_1997-2012_v157.000_en.zip) |
| [Holden](/content/tech2_pcmcia/available_tech2win_.bin-files/tech2win_holden.md) | [tech2win_config_holden_export_v149.000_en.conf](tech2win_config_holden_export_v149.000_en.zip) |
| [Initial software](/content/tech2_pcmcia/available_tech2win_.bin-files/tech2win_initial_software.md) | [tech2win_config_initial_software_v15.100_en.conf](tech2win_config_initial_software_v15.100_en.zip) |
| [NAO](/content/tech2_pcmcia/available_tech2win_.bin-files/tech2win_nao.md) | [tech2win_config_nao_v33.008_en.conf](tech2win_config_nao_v33.008_en.zip) |
| [Opel GT / Chevrolet / HHR](/content/tech2_pcmcia/available_tech2win_.bin-files/tech2win_opel_gt_chevrolet_hhr.md) | [tech2win_config_opel_gt_chevrolet_hhr_v30.004_en.conf](tech2win_config_opel_gt_chevrolet_hhr_v30.004_en.zip) |
| [Opel / Vauxhall](/content/tech2_pcmcia/available_tech2win_.bin-files/tech2win_opel_vauxhall.md) | [tech2win_config_opel_vauxhall_v166.000_en.conf](tech2win_config_opel_vauxhall_v166.000_en.zip) |
| [SAAB NAO](/content/tech2_pcmcia/available_tech2win_.bin-files/tech2win_saab.md) | [tech2win_config_saab_nao_v9.250_en.conf](tech2win_config_saab_nao_v9.250_en.zip) |
| [SAAB](/content/tech2_pcmcia/available_tech2win_.bin-files/tech2win_saab_nao.md)  | [tech2win_config_saab_v140.500_ru.conf](tech2win_config_saab_v140.500_ru.zip) |
| [SAAB](/content/tech2_pcmcia/available_tech2win_.bin-files/tech2win_saab_nao.md) | [tech2win_config_saab_v148.000_en.conf](tech2win_config_saab_v148.000_en.zip) |
| [Saturn Astra](/content/tech2_pcmcia/available_tech2win_.bin-files/tech2win_saturn_astra.md) | [tech2win_config_saturn_astra_v31.001.conf](tech2win_config_saturn_astra_v31.001.zip) |

## Location of .bin-files

In this case; the location where Tech2WIN expects the .bin-files to reside is `C:\Users\Public\General Motors\Tech2Win\pcmcia\`.

{% include list.liquid all=true %}