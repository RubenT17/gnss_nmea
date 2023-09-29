# GNSS NMEA DECODER
NMEA messages decoder for ring buffer. Microcontrollers are compatible.

## ✒️ &nbsp; Author 
* **Rubén Torres Bermúdez** - [RubenT17](https://github.com/RubenT17)


## ⚙️ &nbsp; How to use

```
#include "gnss_nmea.h"

gnss_nmea_rmc_sentence_t rmc;
gnss_nmea_gga_sentence_t gga;
gnss_nmea_t gnss = {&rmc, &gga};

gnss_nmea_GetData(gnss_ring, message_pos_ini, message_pos_end, &gnss);
```

## 📄 &nbsp; License

This project is licensed under the General Public License - see the LICENSE.md file for details

## ❓ &nbsp; Where to ask questions 

| Type                            | Platforms                               |
| ------------------------------- | --------------------------------------- |
| 🚨 **Bug Reports**              | [GitHub Issue Tracker](https://github.com/RubenT17/gnss_nmea/issues)                 |
| 🎁 **Feature Requests & Ideas** | [GitHub Issue Tracker](https://github.com/RubenT17/gnss_nmea/issues)                 |
