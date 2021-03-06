# USB_Laptop_Keyboard_Controller
 This repo contains all the files that are needed to make a USB keyboard from an old laptop keyboard.

 See the YouTube video at https://www.youtube.com/watch?v=Z1PheqSNNP8
 
 See the "Instructable" at https://www.instructables.com/id/How-to-Make-a-USB-Laptop-Keyboard-Controller/

 All files and folders are listed below:
 
 Instructable Laptop Keyboard Conversion to USB.pdf contains the text and pictures from the Instructable.
 
 Keyboard_Scanner.brd  EagleCad circuit board file for Teensy LC or 3.2. 
 
 Keyboard_Scanner_LT.brd EagleCad file same as above with 2 bit Level Translator for touchpad Clock and Data
     
 Blank_Key_Lists Folder
 
     Keyboard_with_number_pad.txt     Lists all keys on a keyboard with a number pad. 
     
     Keyboard_without_number_pad.txt  Lists all keys on a keyboard without a number pad. 
     
 Teensy_Continuity_Tester Folder
 
     Matrix_Decoder_LC.ino        Teensyduino file for Teensy LC continuity tester. 
     
     Matrix_Decoder_3p2.ino       Teensyduino file for Teensy 3.2 continuity tester.  
     
 Example_Touchpads Folder
 
     Touchpad_3p2.ino             Teensyduino file for Teensy 3.2 touchpad controller
     
     Touchpad_Info.pdf            PDF file describing the touchpad code
 
 Example_Keyboards Folder
 
     Instructions for Modifying the Teensyduino LC code.pdf     PDF file with LC instructions   
     
     Instructions for Modifying the Teensyduino 3p2 code.pdf    PDF file with 3.2 instructions 
     
     Laptop_Keyboard      A separate Folder for each laptop keyboard, containing the following:
     
          Text file with FPC pin connections. The results from running the Matrix_decoder code.
          
          PDF file with key matrix table and any additional information. 
          
          Teensyduino code that makes a simple homebrew USB keyboard routine.
          
 Each of the Laptop Keyboards listed below have been tested and documented in their own folder:
*  Dell Inspiron 1525 - Keyboard Part Number D9K01
*  Dell Latitude 131L - Keyboard Part Number V-0511BIAS1-US
*  Dell Latitude X1 - Keyboard Part Number 0M6607
*  Dell Latitude D630 - Keyboard Part Number DP/N 0DR160
*  HP Compaq Presario 2100 - Keyboard Part Number AEKT1TPU011
*  HP Compaq Presario V4000 - Keyboard Part Number NSK-H3L01
*  HP Pavilion DV9000 - Keyboard Part number AEAT5U00110
*  Sony Vaio PCG-K25 - Keyboard Part Number KFRMBA151B
*  Sony Vaio VPCCW - Keyboard Part Number 148754321
*  Sony Vaio VPCEA - Keyboard part number A-1765-621-A
*  Sony Vaio VPCEB4 – Keyboard part number A-1766-425-A
*  Lenovo ThinkPad T61 - Keyboard part number 42T3177 (Teensy 3p2 and Teensy LC folders)
