On your PS4:

- Go to `Settings` and then `Network`
    
- Select `Set Up Internet connection` and choose `Use a LAN Cable`
    
- Choose `Custom` setup and choose `PPPoE` for `IP Address Settings`
    
- Enter anything for `PPPoE User ID` and `PPPoE Password`
    
- Choose `Automatic` for `DNS Settings` and `MTU Settings`
    
- Choose `Do Not Use` for `Proxy Server`
    
- Now, simultaneously press the 'X' button on your controller on `Test Internet Connection` and 'Enter' on your keyboard (on the computer you have your Python script ready to run).
    

ALWAYS wait for the console to show the message "Cannot connect to network: (NW-31274-7)" before trying this PPPOE injection again.

If the exploit fails or the PS4 crashes, you can skip the internet setup and simply click on `Test Internet Connection`. Kill the `pppwn.py` script and run it again on your computer, and then click on `Test Internet Connection` on your PS4: always simultaneously.

If the exploit works, you should see an output similar to below, and you should see `Cannot connect to network.` followed by `PPPwned` printed on your PS4, or the other way around.

https://github.com/TheOfficialFloW/PPPwn  
  
Static connection.  
GoldHen plugged in on startup.  
Laptop 1 second before PS4.  