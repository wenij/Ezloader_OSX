This code base on Apple Sample code "Ezloader Example"

add as follow things.

hex value support on vender and product

add more option

option

-v Original Vender ID

-p Original Product ID

-V New Vendor ID

-P New Product ID

-F chip is EZ-USB FX2 CY7C68013A

-n No USB firmware or not wait new USB Device 

-d demon mode

-r raw binary file

-f filename

tested at AN2131 and CY7C68013A

examples

Download sigrok firmware to FX2 module

% Ezload  -v 0x04b4 -p 0x8613 -n -F -r -f fx2lafw-saleae-logic.fw

