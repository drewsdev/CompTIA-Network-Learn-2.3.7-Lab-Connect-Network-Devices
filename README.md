# CompTIA-Network-Learn-2.3.7-Lab-Connect-Network-Devices
## CompTIA CertMaster Learn v9.1

In this lab, your task is to connect the switch in the Networking Closet on Floor 1 with the switch in Networking Closet 2 on Floor 2 through the fiber patch panels in each networking closet. Use the following information to identify the necessary connections:

* Connect the appropriate fiber cable to switches through the fiber patch panels.  
* For the patch panel on Floor 1:  
  * Port 3 is transmit (Tx).  
  * Port 4 is receive (Rx).  
* For the patch panel on Floor 2:  
  * Port 1 is transmit (Tx).  
  * Port 2 is receive (Rx).  
* Use the color coding on the end of fiber optic cables to identify which end is Tx and which is Rx.  
  * Connector A (white or red) is Tx.  
  * Connector B (black) is Rx.  
* Plug the switch on Floor 2 into a bank 1 critical load outlet on the UPS.  
* Verify that the connection was made by checking the internet connection on any Floor 2 computer.

![Floor1](/Screenshot_1.png)
![Floor2](/Screenshot_2.png)
![Critical Power](/Screenshot_3.png)

Explanation  
While completing this lab, use the following information:

* SC connectors have square connectors that are pushed in to connect.  
![White](/fiber-t-sc-simplex-white-top.jpg)
![Black](/fiber-t-sc-simplex-black-top.jpg)
* LC connectors have both connectors linked together.  
![Blue](/fiber-lc-top-blue.jpg)

Complete this lab as follows:

1. Install the SFP Transceiver (LC) in the networking closet on Floor 1.  
 a. Under Shelf, expand the Adapters.  
 b. Drag the SFP Transceiver (LC) to the SFP 2 port on the switch.  
2. Connect the fiber cable to the switch.  
 a. Under Shelf, expand Cables.  
 b. Select Cable, Fiber, SC to LC.  
 c. From the Selected Component pane:  
  * Drag Connector, Fiber, Duplex LC Multi-mode, Male to the SFP LC port (plugged into SFP2) on the switch.  
  * Drag the Fiber Optic SC Connector (A) to port 3 on the fiber patch panel.  
  * Drag the Fiber Optic SC Connector (B) to port 4 on the fiber patch panel.  
3. Access the networking closet on floor 2.  
 a. From the top left, select Floor 1.  
 b. Under Building A, select Floor 2.  
 c. Under Networking Closet 2, select Hardware.  
4. Connect the fiber cable to switches on Floor 2.  
 a. Under Shelf, expand Adapters.  
 b. Drag SFP Transceiver (LC) to an open SFP port on the switch.  
 c. Under Shelf, expand Cables.  
 d. Select Cable, Fiber, SC to LC.  
 e. From the Selected Component pane:  
  * Drag the Connector, Fiber, Duplex LC, Multi-mode, Male to the SFP port.  
  * Drag the Fiber Optic SC Connector (A) to port 1 on the fiber patch panel.  
  * Drag the Fiber Optic SC Connector (B) to port 2 on the fiber patch panel.  
5. Plug the switch on Floor 2 into a bank 1 critical load outlet on the UPS.  
 a. Above the rack, select Back to switch to the back view of the rack.  
 b. Under Shelf, select AC Power Cable.  
 c. From the Select Connector pane:  
  * Drag AC Power Connector (Female) to the AC port on the back of the switch.  
  * Drag the AC Power Connector (Male) to an open bank 1 critical load outlet.  
 d. Above the rack, select Front to switch to the front view and confirm that the network switch has power.  
6. Verify that there is an internet connection for any Floor 2 computer.  
 a. From the top left, select Floor 2.  
 b. Select any of the computers on Floor 2.  
 c. Right-click Start and then select Settings.  
 d. Select Network & Internet.  
The image shown should indicate a connection to the internet.
