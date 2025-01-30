.. _sec-posmarker:

Your location
=============
Your location is displayed on the :ref:`map <sec-maps>` with the position marker:

.. figure:: ../_static/posmarker.png
   :height: 150px
   :width: 150px
   :alt: Positiemarker Topo GPS

   *The position marker*

If you are standing still, the position marker points in the direction in which you point your device.
If you are moving, the position marker points in the direction in which you are moving.

The arrow in the status bar indicates that the location services are currently in use. This can cause faster battery consumption than usual. Therefore pay attention to the battery level when using Topo GPS.

The default position marker icon is red, you can :ref:`change it to another color <ss-settings-posmarker>` via :ref:`Menu <sec-menu>` > More > Settings > Styles > Position. This might to increase the visibility of the position marker ont the map.

To center the map on your location, tap the center button on the left hand side of the :ref:`dashboard <sec-dashboard>`.

<APPLE>
Recommended iOS Settings
------------------------
To enable location access for Topo GPS, first make sure that iOS Settings > Privacy > Location Services is enabled. Then in the
same screen give Topo GPS access to precise location while using the app. Or go to iOS Settings > Topo GPS. 

It is also recommended to go to iOS Settings > Privacy > Location Services > Scroll to bottom > System and 
enable the settings 'Compass calibration' and 'Movement and distance calibration'.
</APPLE>

<ANDROID>
Recommended Android Settings
----------------------------
To enable location access for Topo GPS, first go in the Android settings app to Apps > Topo GPS > Permissions.
Here enable the location permission. And enable 'Use precise location' as well.

For best performance with recording routes it is recommended to enable notifications in Apps > Topo GPS > Permissions > Notifications 
for the Topo GPS route recorder. Also 'Allow background battery usage' in Apps > Topo GPS > App battery usage.
</ANDROID>

.. _ss-current-location-screen:

Current location screen
-----------------------
If you tap the :ref:`position marker <sec-posmarker>`, the current location screen will appear. 
You can also open this screen by pressing long on the :ref:`position button <ss-position-button>` on the :ref:`dashboard <sec-dashboard>`.

The current location screen shows details of your current location. In the current location screen you can also save your current location
into a waypoint and export your current location with the buttons in the bottom toolbar. An example of the current location screen is displayed below:

.. figure:: ../_static/current_position.jpg
   :height: 568px
   :width: 320px
   :alt: Current location screeen Topo GPS

   *The current location screen (top part).*
      
In the location information screen you find subsequently the following information:

- *Map*: A map of the surroundings of your current location. You can also zoom and move this map.
<APPLE>
- *Coordinates*: The coordinates of your current location in various formats. You can change the displayed coordinate systems by tapping on the '>' on the right hand side. If you press long on a pair of coordinates you can choose for Copy or Share the coordinates in textual format. You can also choose here 'Speak out' to speak out the coordinates in the language of your device or in English. Speak out could a very useful option if you have to communicate clearly coordinates over an audio connection like a phone. There will be a smaller possibility for errors that reading out the cooordinates by yourself.
</APPLE>
<ANDROID>
- *Coordinates*: The coordinates of your current location in various formats. You can change the displayed coordinate systems by tapping on the more icon on the top of the screen. You can tap long on the coordinates to select and copy it.
</ANDROID>
- *Address*: The approximate address of your location. If you move this address will be updated automatically. If you press long on the address you can select and share it. If you press 'Edit' you can disabled automatic lookup of addresses in the current location screen.
- *Location accuracy*: The accuracy of the location determination. This accuracy means that your true location has a high probability of being inside a circle with a radius equal to the accuracy. If the GPS signal is good the location accuracy is 5 m or less.
- *Altitude*: The current altitude of the device above the WGS84 geoid with the accuracy.
- *Speed*: The current speed of the device.
- *Course*: The direction which respect to the true north in which the device is moving.
- *Device heading*: The direction with respect to the true north in which the device is pointing.
- *Timestamp*: The exact time at which the displayed location was obtained.
- *Magnetic declination*: This is the angle between the magnetic north pole and true north pole (geographic north). If the magnetic north lies east of the true north, the declination is positive. If the magnetic north lies west of the true north, the declination is negative.
If you read of a direction from a magnetic compass it is always relative to the magnetic north. To obtain the direction relative to the true north you have to add the magnetic declination to the reading of the magnetic compass. The magnetic north pole changes location over time, therefore the magnetic declination varies in time and from position to position.


Changing current location screen
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
<APPLE>
By tapping 'Edit' on the top right of the current location screen you can edit the order of the elements appearing in the current location screen. 

By dragging the handles on the right hand side the order of the elements can be modified. 

By tapping 'Displayed coordinate types' the :ref:`displayed coordinate types can be set <sec-settings-coordinates>` so that only coordinate systems which are of interest to you are displayed.
</APPLE>
<ANDROID>
By tapping 'More > Displayed coordinates types', the :ref:`displayed coordinate types can be set <sec-settings-coordinates>` so that only coordinate systems which are of interest to you are displayed.
</ANDROID>

.. _ss-current-location-save:

Saving current location
~~~~~~~~~~~~~~~~~~~~~~~
By tapping ‘Save’ in the bottom right of the current location screen you can save your current position as a :ref:`waypoint <sec-wp>`. The waypoint will be given a title based on settings which you can change by tapping 'Edit > Waypoint title' in the current location screen.
The automatic waypoint title can be set to either:

- *Time*: The current time
- *Date and time*: The current date and time
- *Number (next: ..)*: A number. If you press 'Reset' it will be reset to 1. This setting is useful if you want to save your location several times and number the waypoints.

If you press 'Save' your current position will be saved immediately as a waypoint and added to the map. A pop-up will show that the waypoint was saved successfully as you can see in the figure below:

.. figure:: ../_static/current_position_save.jpg
   :height: 568px
   :width: 320px
   :alt: Saving current location as waypoint Topo GPS

   *Saving your current location as a waypoint.* 

<APPLE>
.. _ss-current-location-create:

Creating waypoint on current location
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
By tapping 'Create waypoint' in the bottom toolbar of the current location screen you can create a waypoint at the current location. The difference between tapping 'Save' is that it is slower, but now a waypoint creation screen will pop-up in which you can enter the title, description and change the icon. This is the same screen which appears when :ref:`creating a waypoint from the map <ss-waypoint-create-map>`.
</APPLE>

Sharing current location
~~~~~~~~~~~~~~~~~~~~~~~~
<APPLE>
By pressing 'Share' on the bottom left of the current location screen you can share your location. 
</APPLE>
<ANDROID>
By pressing the 'Share' icon in the top right of the current location screen you can share your location. 
</ANDROID>
An export pop-up will appear exactly as what happens when :ref:`exporting waypoints <ss-waypoints-exporting>`.



<APPLE>
Current location quick actions
------------------------------
If you press long on the position marker icon, a quick actions screen will appear.

.. figure:: ../_static/current_position_quick.jpg
   :height: 568px
   :width: 320px
   :alt: Current location quick actions Topo GPS

   *The quick actions for your current location.* 

In the quick actions screen for the current location you can choose to view the details, to share your current location, to create a waypoint at your current location, or to save the current location as a waypoint.   
</APPLE>
