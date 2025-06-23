# Library for the ESP32 CAN Bus Controller (ESP32-CAN)

## Features

* Support the CAN Controller built in to the ESP32, all that is required is a CAN Transceiver (Required to actually be usable) or use the Lilygo CAN485 board (https://www.aliexpress.com/item/1005003624034092.html)
* CAN Messages send and receive 
* Various Bus speeds
* Standard and Extended Frames
* CAN Message Filter
* Modified to support DIY-Battery-BMS
* Fast timeout on send so it doesn't block the running application


## Third Party Components

- ESPCan Driver 
  - Base CAN Driver from [Thomas Barth](https://github.com/ThomasBarth/ESP32-CAN-Driver) and [Nayar Systems](https://github.com/nayarsystems/ESP32-CAN-Driver)
  - General [Component CAN Driver Pack](https://github.com/ESP32DE/ESP32-CAN-Driver/tree/Component_CAN_Driver_Pack)
