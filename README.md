# Fred's Fourier Factory (F^3)
a.k.a. Jacob's Jeneric Jenerator (J^3)

## Datasheets / manuals / documentation

* [STM32H7 series][stm32h7-home] microcontrollers
  - [Datasheet (H743)][h743-datasheet] (231 pages)
  - [Reference manual (H743, H750, and H753)][reference-manual] (3247 pages :scream:) 
  - [Programming manual (F7/H7)][programming-manual] (252 pages) 
* NUCLEO demo/eval/prototyping boards
  - [Schematics](doc/nucleo/nucleo144-schematics-from-um1974.pdf) (for 144-pin MCU versions)
  - [NUCLEO-H743ZI][nucleo-H743ZI]
* Example of using STM32 DMA with GPIO port:
  - [AN4666][an4666-pdf] *Parallel synchronous transmission using GPIO and DMA*
  - [X-CUBE-PARAL-COM][x-home] ([direct download][x-direct])
  
## Software download link(s)

* [STM32Cube initialization code generator](https://www.st.com/en/development-tools/stm32cubemx.html)
* [System Workbench for STM32: free IDE on Windows, Linux and OS X](https://www.st.com/en/development-tools/sw4stm32.html)
* [STM32 Flash loader demonstrator (UM0462)](https://www.st.com/content/st_com/en/products/development-tools/software-development-tools/stm32-software-development-tools/stm32-programmers/flasher-stm32.html)

## Development environment setup notes

Eclipse (AC6 SW4STM32) uses absolute paths in some of its project files (e.g. `.cproject`). There are (at least) two ways to work around this:

* Recreate / re-import the project on each machine
* Set the environment variable `F3_HOME` equal to the base folder of the project (root of git repository)

[stm32h7-home]: https://www.st.com/en/microcontrollers/stm32h743-753.html?querycriteria=productId=LN2033
[h743-datasheet]: https://www.st.com/resource/en/datasheet/stm32h743bi.pdf
[reference-manual]: https://www.st.com/content/ccc/resource/technical/document/reference_manual/group0/c9/a3/76/fa/55/46/45/fa/DM00314099/files/DM00314099.pdf/jcr:content/translations/en.DM00314099.pdf
[programming-manual]: https://www.st.com/content/ccc/resource/technical/document/programming_manual/group0/78/47/33/dd/30/37/4c/66/DM00237416/files/DM00237416.pdf/jcr:content/translations/en.DM00237416.pdf

[nucleo-H743ZI]: https://www.st.com/en/evaluation-tools/nucleo-h743zi.html

[an4666-pdf]: https://www.st.com/content/ccc/resource/technical/document/application_note/7a/88/df/e3/d3/36/40/29/DM00169730.pdf/files/DM00169730.pdf/jcr:content/translations/en.DM00169730.pdf
[x-home]: https://www.st.com/content/st_com/en/products/embedded-software/mcu-mpu-embedded-software/stm32-embedded-software/stm32cube-expansion-packages/x-cube-paral-com.html
[x-direct]: https://my.st.com/content/ccc/resource/technical/software/firmware/7c/88/26/9a/29/c1/46/2c/x-cube-paral-com.zip/files/x-cube-paral-com.zip/jcr:content/translations/en.x-cube-paral-com.zip
