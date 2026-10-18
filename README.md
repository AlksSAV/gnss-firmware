# GNSS Firmware Repository

Централизованное хранилище прошивок и документации для GNSS-приёмников различных производителей.

## 📁 Структура

```
├── Firmware/          — прошивки по производителям
│   ├── ComNav/
│   │   └── K8/
│   ├── NovAtel/
│   │   └── OEM719/
│   ├── Septentrio/
│   │   ├── AsteRx/
│   │   └── mosaic x5/
│   ├── Ublox/
│   │   ├── F9P/
│   │   └── x20p/
│   └── Unicore/
│       ├── um980/
│       ├── um981/
│       └── UM982/
├── Manuals/           — документация и reference manuals
├── Software/          — ПО для прошивки и конфигурации
└── README.md
```

## 📦 Производители и модели

### [Septentrio](Firmware/Septentrio/)
| Модель | Прошивка | Документация |
|--------|----------|--------------|
| AsteRx-m3 Pro+ | [v4.15.1](Firmware/Septentrio/AsteRx/AsteRx-m3 Pro+-4.15.1.suf) | [Release Notes](Firmware/Septentrio/AsteRx/AsteRx-m3 Pro+ Firmware v4.15.1 Release Notes.pdf) \| [Reference Guide](Manuals/Septentrio_AsteRx-m3 Pro Firmware v4.15.1 Reference Guide.pdf) |
| AsteRx-m3 Pro+ (AntInfo) | [v26.1.0](Firmware/Septentrio/AsteRx/antinfo-26.1.0-AsteRx-m3 Pro+.suf) | [Release Notes](Firmware/Septentrio/AsteRx/AsteRx-m3 Pro+ AntInfo 26.1.0 Release Notes.pdf) |
| mosaic X5 | — | [Reference Guide](Manuals/Septentrio_mosaic-X5_Firmware_v4.15.0_Reference_Guide.pdf) |

### [u-blox](Firmware/Ublox/)
| Модель | Прошивка | Документация |
|--------|----------|--------------|
| ZED-F9P | [FW 1.00 HPG 1.51](Firmware/Ublox/F9P/UBX_F9_100_HPG151_ZED_F9P.bin) | [Release Notes](Firmware/Ublox/F9P/ZED-F9P-FW100HPG151_RN_UBXDOC-963802114-13110.pdf) |
| ZED-X20P | [HPG 2.10](Firmware/Ublox/x20p/UBX_20_HPG_210_ZED_X20P-01B.512369040097ce18fd3475e71e7c627f.bin) | — |

### [Unicore](Firmware/Unicore/)
| Модель | Прошивка | Документация |
|--------|----------|--------------|
| UM980 | [R4.10Build17548](Firmware/Unicore/um980/UM980_R4.10Build17548.pkg) | [Reference Commands Manual](Manuals/Unicore_Unicore-N4-Reference-Commands-Manual_V2_EN_R1.13.pdf) |
| UM980 | [R4.10Build20739](Firmware/Unicore/um980/UM980_R4.10Build20739.pkg) | |
| UM980 | [R4.10Build25621](Firmware/Unicore/um980/UM980_R4.10Build25621.pkg) | [RU Notes](Firmware/Unicore/um980/UM980_R4.10Build25621%20RU.txt) |
| UM981-02 AUTO | [GSP10598](Firmware/Unicore/um981/UM981-02_AUTO_GSP10598.pkg) | |
| UM981-02 SLANT | [GSP11767](Firmware/Unicore/um981/UM981-02_SLANT_GSP11767.pkg) | |
| UM982 | [R4.10Build18975](Firmware/Unicore/UM982/UM982_R4.10Build18975.pkg) | [Release Notes](Firmware/Unicore/UM982/UM982_R4.10Build18975%20Release%20Notes.jpg) |

### [NovAtel](Firmware/NovAtel/)
| Модель | Прошивка | Документация |
|--------|----------|--------------|
| OEM719 | [v7.10.02 (.shex)](Firmware/NovAtel/OEM719/OM7MR1002RN0000.shex) | [What's New](Firmware/NovAtel/OEM719/WhatsNew_71002.pdf) \| [Commands Manual](Manuals/NovAtel_OEM7_Commands_Logs_Manual.pdf) |

### [ComNav](Firmware/ComNav/)
| Модель | Прошивка | Документация |
|--------|----------|--------------|
| K8 | [v630A4](Firmware/ComNav/K8/blue_update_K8_630A4.bin) | [Release Notes](Firmware/ComNav/K8/ComNav%20GNSS%20Firmware%20v630A4%20Release%20Notes.pdf) \| [Reference Manual](Manuals/ComNav_OEM_Board_Reference_Manual_V3.1.pdf) |

## 🛠 Использование

1. Найдите нужную прошивку в таблице выше или в папке `Firmware/`.
2. Ознакомьтесь с документацией (Release Notes / Reference Manual) для получения информации о изменениях и ограничениях.
3. Используйте фирменное ПО производителя для прошивки устройства.

### Рекомендуемое ПО
- **u-blox**: u-center
- **Septentrio**: SEPTENTRIO Configuration Tool (SCT)
- **NovAtel**: NovAtel Configuration Tool / Span Navigator
- **Unicore**: U-Monitor / U-Center
- **ComNav**: ComNav configuration tool

## ⚠️ Важные замечания

- Убедитесь в совместимости версии прошивки с вашей моделью приёмника.
- Перед обновлением рекомендуется создать резервную копию настроек устройства.
- Прошивки предоставлены «как есть» без каких-либо гарантий.
- Обновление прошивки может аннулировать гарантию производителя.

## 📝 Лицензирование

Прошивки подпадают под условия лицензионных соглашений соответствующих производителей. Используйте их в соответствии с политиками лицензирования.
