**PeopleFisher**

**A mesh based positioning and messaging application , that is completelely offline and is free to use without any installation cost.**

**Working of the App:- https://www.youtube.com/watch?v=ptAid6plkws**

**Introduction**

The PeopleFisher application was designed to work under the harshest of conditions and in the remotest of the locations and these things are usually common during disasters.

**Tech Stack**
Android - Used to create the mobile application. Heavily focusses on WifiP2p.
AZURE database - Used to sync the messages sent to an online server (Under development)
AZURE blob - Used to upload the apk file.

**Tips for using the app:**
**Follow these tips to avoid errors:**
**1.** *Since peer to peer connection is a resource intensive task, 
        once the send message button is pressed, the user has to wait till the phone has attempted to send the messae to all           the nearby peers(usually a minut or two)* 
        
        
        **This is a LIMITATION of the ANDROID device, and not the APPLICATION.**
        
        
**2.**  *If the app choses not to respond, please switch off the wifi, and the application and try again.*

**3.**   *Trilateration is currently not supported on all the android devices so please use the Trilateration button with                 utmost caution.*

**4.Send button :**  *runs a for loop through the peers in range, and sends messages to them
                  takes time to implement due to device limitation so please be patient and do not spam the send button.*
                  
**5.Trilateration button:**  *this is similar but instead it requests data from the client , which is further used to calculate                               the latiude longitude of the user this is also a slow process due to device limitation so please                               do not spam the trilateration button.*
