
# esp32s3-storage

这是一款基于ESP32S3的移动存储产品的PCB板，这个开源硬件项目使用开源软件KiCad8打开esp32s3-storage.kicad<sub>pro文件来浏览和修改</sub>。项目基于GPLv3，本项目不提供任何保证，但允许任意修改，但需要保持开源义务。欢迎大家提Issue或PR。

本项目使用了两个需要引入的元器件。第一个是micro-sd的封装文件new-micro-sd-socket-taobao-9-pin.kicad<sub>mod</sub>，位于项目目录中，使用footprint editor导入该文件，创建的库名是imported-footprint，footprint名字是new-micro-sd-socket-taobao-9-pin。另一个元器件是ESP32S3，通过安装espressif-kicad-addon插件获得该元器件。通过乐鑫[kicad-libraries](https://github.com/espressif/kicad-libraries)项目页面下载插件包，再打开KiCad8的Plugin and Content Manager工具，点击Install from File&#x2026;，选中下载好的插件文件，安装插件。安装好后会在Installed Tab页看到Espressif Libary。

