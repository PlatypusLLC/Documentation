Quick Start
===========

Following this guide will help you get the boat running and into the water as quickly as possible. 
It is not meant to provide detailed explanations. For that, look through the other sections of the manual.


Safety
------

Battery
^^^^^^^

The Lutra uses a large Lithium Polymer (LiPo) battery. Any large battery can be an electric shock and fire hazard
if it is not handled with proper care.

Do not tamper with the internal wiring in the boat aside from inserting and removing the battery.

LiPo batteries may become a fire hazard if they become "puffy" or are struck with significant force.
A LiPo battery is normally stiff - if you squeeze it, it feels stiff, and it does not feel puffy.
If you have run the battery below a recommended minimum voltage, it can expand, becoming puffy.
If this occurs, do NOT charge or reuse the battery! 
Store it in a flame resistant area (a LiPo storage bag is recommended!).
It is very unlikely that it will catch fire by itself, but it can catch fire if struck with enough force.

To prevent a "puffy" battery, do not drain the battery below a safe value. The green 4-cell 16,000 mAh
batteries should not be drained below 14 V. Make sure the battery is fully charged before you deploy the boat
and keep an eye on the voltage displayed on the tablet during deployment.

Propellers
^^^^^^^^^^

The Lutra uses fairly powerful motors to spin propellers. While we use plastic propellers to decrease the damage
they might cause, spinning plastic propellers are still a hazard. While on land, 
always make sure the propellers are clear. Never touch the propellers while the boat is turned on.


Setting Up
----------

Learn how to assemble the equipment you just received.

Lutra Prop
^^^^^^^^^^

Take out phone, charge phone. 
Attach USB-C adapter to USB-female to USB-mini adapter. (or do we now have a direct USB-mini to USB-C cable now?)
Ziptie down USB cable (should already be done, right?)
Make sure velcro is on back of phone and front wall of front compartment.

Attach propellers if not attached.

Plug in battery, turn on boat, listen for pump
Make sure that water is flowing in the cooling tubes in the back compartment.

Lutra Air
^^^^^^^^^

Deal with USB cables the same way as Lutra prop.

Attach fan, plug in servo cable to s0 socket, plug three-pin in next to fan.

Sensors
^^^^^^^

Sensor cables are meant to pass through the vertical tube in the front of the boat.
Sensors are mounted on the bottom of the boat.

Small cylindrical sensors are held down with the acrylic bracket. 
Remove the bolts and bracket, place the sensors, then replace the bracket and bolts.


Lowrance HDS
""""""""""""

Install transducer and head unit. Plug in power cable to sX socket. 
Be careful not to crush the transducer that will stick out.
When you deploy the boat, make sure to straighten the transducer so it is parallel with the boat hull again.

Before Deploying
----------------

Here are the steps you should take the before deploying the boat.
|
* Charge LiPo batteries
.. image:: ../images/charge_battery.gif
|
* Charge phone and tablet
* Download maps in table app (navigate to area of interest, zoom in and out in vector and satellite style to cache the map data)
* Create and upload any sets of waypoints if you don't want to create them in the tablet app during deployment
  (Recommended for complex waterway geography, such as a winding stream or ponds with many small branches)

Starting and Launching the Boat
-------------------------------
|
.. image:: images/insert_battery_big.gif
|
Controlling the Boat
--------------------

Two ways to control the boat, manually drive it and use autonomy to follow a series of waypoints.
You can create polygonal regions to automatically generate waypoints that completely cover an area of interest.

Manual Tele-Operation
^^^^^^^^^^^^^^^^^^^^^

We recommend using the autonomy whenever possible. This requires a GPS lock. If the boat is deployed
in an urban environment, it may be difficult to get a GPS lock (or multi-pathing may occur, causing the
GPS lock to be totally incorrect and misleading). In a narrow body of water like a stream, even if you
have a GPS lock, the possible error in the position could cause the boat to drive into the shore.

There are two ways to tele-operate the boat.

Tablet Thumb-Stick
""""""""""""""""""

Recommend placing thumb down in the center and rolling it rather than sliding around.
That way you can easily return to center and apply smaller changes.

Radio Control Module
""""""""""""""""""""

Requires extra equipment.
RC module plugs in like a sensor. Comes with a large RC transmitter.
Flip the override switch to take control away from the phone in the boat.

Waypoints
^^^^^^^^^

The boat will move in a more-or-less straight line from its current position to the next waypoint.
Once it arrives in the proximity of a waypoint, it either stops (if it has no more waypoints)
or it moves on toward the next waypoint.

Regions
^^^^^^^

Recommended for covering an area of interest.
Instead of manually setting up every single waypoint, select a polygon that covers an area.
The waypoints that represent a path through that area will be automatically generated for you.
When you press and hold, instead of a waypoint, you lay down a corner (vertex) of the polygon.
Choose transect width (distance between parallel paths, units are meters) and hit the re-generate button.
Lawnmower is always aligned with cardinal directions.
Spiral is recommended.
Polygons are always convex - try making a U-shape of vertices and notice how the app won't let you.
You will need to break up a non-convex region into separate chunks so that each one is convex.

Alternatively you could manually prepare

Saving and Loading Waypoints
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

[Show using the save and load waypoints buttons, naming a set of waypoints etc.]

[add the stuff that you put in the email to Lasse for manually creating and uploading waypoints]

Extracting Data
---------------

Pulling logs off the phone.
Uploading logs to the Platypus website?
Pulling data off of Lowrance HDS sdcard and 

Storing the Boat
----------------

Clean off outside of boat. Dry it off.
Open up compartments, let it air out. Avoid getting any water droplets inside.



|
|
|

quick screenshots (<= 1 page)
1. the boat
2. the tablet application icon, tablet application buttons chart
3. the phone application icon (phone application buttons chart?)

the quick start guide
1. Charge all batteries beforehand. Best to do it overnight.
2. Cache the maps of your intended area on the tablet control application. To do this, connect the tablet to the internet and turn on the tablet control application and navigate the map to deployment area. The app automatically caches maps as it loads them into view. [link to the page where we describe the tablet app for more details]
3. Gather your equipment: the boat, the tablet, the phone, the battery, any sensors.
4. Travel to your launch point.
5. Turn on the tablet and phone. Launch Google Maps on the phone, to start the process of getting a GPS fix. Also, turn the phone in broad, slow figure eights for 10 seconds to cause the orientation sensors to recalibrate.
6. Launch the Platypus tablet and phone applications.
7. Elevate the boat such that the props are off the ground and can spin without touching anything.
8. Plug in any sensors to the appropriate 8-pin connectors on the top of the eboard.
9. Plug the battery into the boat and hit the white button on the eboard. The LED should blink red. If the LED doesn't light up, press the white button twice quickly to cycle the eboard power. The LED should then blink red.![alt text][insert_battery]
10. Turning the power on to the eboard will cause the wifi router in the boat 
to boot up. After about a minute, a WiFi network (typically with "Platypus" in the name) will appear to wireless devices. Connect the tablet and the phone to the boat's network. [wifi passwords?] 
11. If you have a Lowrance unit, turn it on now and set up the options. Keep in mind that the Lowrance requires the boat to be powered at all times, or it will shut off.
12. Plug the phone into the arduino on the eboard with the USB cable. If the phone application is on the screen, the LED should blink green.
13. Press and briefly hold the big red button on the phone screen to start the application. The ESC's should beep and the LED should turn a solid green. The button on the phone should also turn green.
14. Verify that the phone server's boat type matches the type of boat you have. Swipe to the right on the phone to pull up some options. Scroll down until you see the boat type and make sure it is correct. If not, press on it and select the proper type. Swipe to the left to bring up the big button screen again.
15. Swipe to the left on the phone to pull up the manual motor control interface. This is just like the thumbstick control on the tablet, but may be more sensitive, so be gentle with it. Using the control, check that the motors turn the correct direction for forward, left, right, and reverse.
16. Swipe to the right to return to the screen with the big button. Note the IP address at the top. 
17. In the tablet application, press the connect button. In the window that pops up, enter the phone's IP address. Leave the other options with their default settings. If the tablet successfully connects to the phone, the red bar at the top of the tablet application will turn green.
18. Press the center button and zoom in until the boat's green arrow icon appears clearly.
19. Use the thumb stick to test the motor direction again, just like you did with the phone application.
20. Put the phone into the front compartment, pushing it onto the wall with velcro, keeping the USB cord to the starboard (right side when looking from the back of the boat to the front) side.
21. Turn the phone screen OFF.
22. Close the front plate and lock it down with the white tabs. Make sure that the USB cable is entirely inside the compartment and not stuck on the rim. If any of the tabs is very hard to turn, this may be a sign that the USB cable is wedged there. This MUST be done properly to protect the electronics from water!
23. Place the boat into the water, pushing it slightly away from the shore to avoid damaging the propellers.
24. Set the home location for the boat [directions]
25. TYPICAL TABLET USE DIRECTIONS, possibly link to another page. e.g. saving and loading waypoints, adjusting region transects, etc.
26. While you are using the boat, make sure the voltage doesn't go below X volts. A good rule of thumb is bringing the boat back once it reaches 15 volts while the boat isn't drawing current.
27. Once you are done or the battery needs to be changed, bring the boat back to the shore. Avoid damaging the propellers. Make sure you don't have any autonomy set up that you might accidentally reactivate by touching the tablet screen.
28. Open the front compartment. Make sure that any water that may have splashed over the top of the boat does not drip into the compartment or onto the inside of the plate near the eboard.
29. Press the white button on the eboard and unplug the battery.
30. Pull the phone out of the compartment. Turn the screen back on and press and hold the large button for 1 second. After you let go, the button should turn red again.
31. Close the front compartment again. Make sure both compartment plates are secure, as you are about to transport the boat again.
31. Kill the tablet application.
32. Pack up all your equipment and return.
33. Copy the files from the phone [directions]
34. Load the log file into Platypus online software.
35. If you had a Lowrance bathymetry unit, extract data from Lowrance and use Biobase.
36. Air out the compartments and remove pressure from the o-ring.
37. Remove the battery. If you plan to use the boat again in the near future, charge the battery.
38. Charge the tablet and phone. [Need them to connect either to internet to get usage info?]


[insert_battery]: images/insert_battery_big.gif
