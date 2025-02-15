# SD_CARD
TÜRKÇE
Bu çalışmada, STM32F407VGT6 mikroişlemcisine SPI protokolü üzerinden bağlanan bir SD kart modülünün projesi bulunmaktadır.
IOC dosyası üzerinden ilgili pinoutlar verildikten sonra clock ayarlanır. Ardından Middleware kısmı üzerinden FATFS protokolü aktifleştirilir.
Tek seferlik veri yazma ve okuma üzerine kurulmuştur. while döngüsü içerisinde sonsuz kez okuma ve yazma yapılabilir.


ENGLISH
In this study, there is a project of an SD card module connected to the STM32F407VGT6 microprocessor via SPI protocol.
After the relevant pinouts are given via the IOC file, the clock is set. Then the FATFS protocol is activated via the Middleware section.
It is based on one-time data writing and reading. You can read and write infinitely many times in a while loop.
