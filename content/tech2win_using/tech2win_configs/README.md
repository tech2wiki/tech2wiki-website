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

---
## Predefined configs

{{ site.repo }}raw/main/assets/binfiles/tech2win_card_

| Tech2WIN .bin file(s)    | Configuration file    |
| ---                   | ---                   |
| [GM NAO v33.004 English]({{ site.repo }}raw/main/assets/binfiles/tech2win_card_gm_nao_v33.004_en.zip) | [tech2win_config_gm_nao_v33.004_en.conf](tech2win_config_gm_nao_v33.004_en.zip) |
| [Holden 1997-2012 v157.000 English]({{ site.repo }}raw/main/assets/binfiles/tech2win_card__holden_1997-2012_v157.000_en.zip) | [tech2win_config_holden_1997-2012_v157.000_en.conf](tech2win_config_holden_1997-2012_v157.000_en.zip) |
| [Holden Export v149.000 English]({{ site.repo }}raw/main/assets/binfiles/tech2win_card_holden_export_v149.000_en.zip) | [tech2win_config_holden_export_v149.000_en.conf](tech2win_config_holden_export_v149.000_en.zip) |
| [Initial software]({{ site.repo }}raw/main/assets/binfiles/tech2win_card_initial_software_v15.100_en.zip) | [tech2win_config_initial_software_v15.100_en.conf](tech2win_config_initial_software_v15.100_en.zip) |
| [NAO v33.008 English]({{ site.repo }}raw/main/assets/binfiles/tech2win_card_nao_v33.008_en.zip) | [tech2win_config_nao_v33.008_en.conf](tech2win_config_nao_v33.008_en.zip) |
| [Opel GT / Chevrolet / HHR v30.004 English]({{ site.repo }}raw/main/assets/binfiles/tech2win_card_opel_gt_chevrolet_hhr_v30.004_en.zip) | [tech2win_config_opel_gt_chevrolet_hhr_v30.004_en.conf](tech2win_config_opel_gt_chevrolet_hhr_v30.004_en.zip) |
| [Opel / Vauxhall v166.000 English]({{ site.repo }}raw/main/assets/binfiles/tech2win_card_opel_vauxhall_v166.000_en.zip) | [tech2win_config_opel_vauxhall_v166.000_en.conf](tech2win_config_opel_vauxhall_v166.000_en.zip) |
| [SAAB NAO v9.250 English]({{ site.repo }}raw/main/assets/binfiles/tech2win_card_saab_nao_v9.250_en.zip) | [tech2win_config_saab_nao_v9.250_en.conf](tech2win_config_saab_nao_v9.250_en.zip) |
| [SAAB v140.500 Russian]({{ site.repo }}raw/main/assets/binfiles/tech2win_card_saab_v140.500_ru.zip)  | [tech2win_config_saab_v140.500_ru.conf](tech2win_config_saab_v140.500_ru.zip) |
| [SAAB v148.000 English]({{ site.repo }}raw/main/assets/binfiles/tech2win_card_saab_v148.000_en.zip) | [tech2win_config_saab_v148.000_en.conf](tech2win_config_saab_v148.000_en.zip) |
| [Saturn Astra v31.001 English]({{ site.repo }}raw/main/assets/binfiles/tech2win_card_saturn_astra_v31.001.zip) | [tech2win_config_saturn_astra_v31.001.conf](tech2win_config_saturn_astra_v31.001.zip) |

---
## Location of .bin-files

In this case; the location where Tech2WIN expects the .bin-files to reside is `C:\Users\Public\General Motors\Tech2Win\pcmcia\`.

---