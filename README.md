# AVR_Wuploader
Smart uploader for avr-family controllers

This uploader will purpose for simpler flashing microcontrollers by net  
without any manipulatioon by operator on offline

This code intends for bootloader proccessor-sector  
**We main principe:**
1. We compile code on pc
2. Send signal for device by any protocol, tftp as example
3. Device receiver compiled binary-file by tftp (way doesn't matter, it may by WiFi/Ethernet)
4. Bootloader beguns to executing code

P.S: Nowadays project on test-point, it means that I'm foundings correct way to associate
based bootloader functional with the above 
