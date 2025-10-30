.. _ss-waypoint-search:

Searching waypoints
===================

In the waypoints screen (Menu > Waypoints) you can search waypoints by :ref:`entering keywords in the search bar <ss-waypoint-search-keywords>`, and by :ref:`applying filters <ss-waypoint-filter>`. Furthermore you can :ref:`sort the waypoints <ss-waypoint-sort>` in various ways.


.. _ss-waypoint-search-keywords:

Searching waypoints with keywords
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
If you enter a keyword in the search bar in the waypoins screen, only waypoints will be shown which have the keyword in its title, description, street, town, province, two character iso country code, or zip code. Search is case insensitive.  If you search in a folder, also all search results in descendant folders will be displayed. If a :ref:`filter <ss-waypoint-filter>` is applied, the search will restrict itself to the filtered waypoints.

Below an example is shown in which 'stone' was entered in the search bar. Only the 'Stonehenge' waypoint is shown.

.. figure:: ../_static/waypoint-search1.png
   :height: 568px
   :width: 320px
   :alt: Waypoint sorting Topo GPS
  
   *Searching waypoints with the keyword 'stone'.*


Sorting waypoints
~~~~~~~~~~~~~~~~~
Below the folder/filter bar, the current sort method is displayed in the middle. If you tap the sort button you can change the current sort method between:

<APPLE>- *Customizable order*: The waypoints are sorted in customizable order. If you did not change the order manually, the most recent added waypoints are on top.</APPLE>
<ANDROID>- *Last added on top*: The most recent added waypoints are on top.</ANDROID>
- *Closest on top*: The waypoints are sorted according to their distance to your current location, the closest waypoint is on top.
- *Closest to center map on top*: The waypoints are sorted according to their distance to the current center of the map, the closest waypoint is on top.
- *Newest on top*: The waypoints are sorted according to their creation time, the newest is on top.
- *Oldest on top*: The waypoints are sorted according to their creation time, the oldest is on top.
- *Most recently updated on top*: The waypoints are sorted according to the time at which they were last changed, the waypoint that was changed most recently is on top.
- *Least recently updated on top*: The waypoints are sorted according to the time at which they were last changed, the waypoint that was changed the longest ago is on top.
- *Alphabetically*: The waypoints are sorted in alphabetical order.
- *Reverse alphabetically*: The waypoints are sorted in reversed alphabetical order.

.. figure:: ../_static/waypoint-search2.png
   :height: 568px
   :width: 320px
   :alt: Waypoint sorting Topo GPS
  
   *Sorting waypoints on distance to current location.*

.. _ss-waypoint-filter:

Filtering waypoints
~~~~~~~~~~~~~~~~~~~
It is possible to filter waypoints on location and on the kind of icon. To enable a filter, tap the filter button in the waypoints screen. If the filter is enabled, the filter button has a blue background, as in the figure below. If the filter is disabled, it has a normal appearance.

.. figure:: ../_static/waypoint-search3.png
   :height: 568px
   :width: 320px
   :alt: Waypoint enabled filter Topo GPS
  
   *A filter is enabled.*
   
In the figure above you see an example of an enabled filter. Below the navigation bar a description of the currently active filter is displayed. Here the waypoints are filtered on location, only waypoints within 10 km of the current location are shown.
If you tap the filter description you can modify the current filter. To disable the filter, tap on the filter button.

.. _ss-waypoint-filter-location:

Filtering on location
---------------------
To filter the waypoints on location, tap the filter button to enable the filter. Then tap the filter description to modify the current filter. 
The following screen will be shown in which you can change the current filter:

.. figure:: ../_static/waypoint-search4.png
   :height: 568px
   :width: 320px
   :alt: Waypoint filter modifying Topo GPS
  
   *Modifying a filter.*

In the section 'Waypoint location' you can change the properties of the location filter. In the example above it is set to 'All waypoints within 10 km of your current location'. The slider can be moved to determine the maximal distance of shown waypoints to a specific point.
Above the slider, the location of the location filter is displayed. 
If you tap it, you could change it to:

- *Everywhere*: There is no filtering on location.
- *Current location*: Only waypoints within a certain distance of the current location are shown.
- *Within selected area*: A map will be shown, which you can move and zoom to the desired area. Only waypoints in the shown area on the map are shown in the waypoints screen.
- *Visible part of map*: Only waypoints that are within the bounds of the currently visible part of the main map are shown in the waypoints screen. In constrast to the 'Within selected area' filter, this is a dynamic filter. It changes if you change the position of the map in the main screen.
- *Custom location*: If you enter a custom location or coordinates only waypoints within a certain distance of the entered location are shown.


If you choose 'Within selected area', a map with a gray overlay will be shown as in the figure below:

.. figure:: ../_static/waypoint-search7.png
   :height: 568px
   :width: 320px
   :alt: Waypoint search Topo GPS
  
   *Setting a 'Within selected area' filter.*

The gray overlay area indicates the area the filtered waypoints must be located in. You can resize the overlay by holding one finger and moving up-down or left-right, and you can zoom, rotate and move the map to change the selected area.

If this filter is applied, only waypoints in the selected area in the 'Edit filter' screen will be shown in the waypoint screen as in the example below:

.. figure:: ../_static/waypoint-search8.png
   :height: 568px
   :width: 320px
   :alt: Waypoint search Topo GPS
  
   *Only waypoints within a selected area are shown.*


To view all waypoints in a certain area, it is also possible to :ref:`select part of the main map <ss-map-select>` and tap 'Waypoints' in the pop-up.

.. _ss-waypoint-filter-icon:

Filtering on icon
-----------------
To filter the waypoints on icon, tap the filter button in the waypoints screen to enable a filter. 
Then tap the filter description to modify the current filter. Then in the bottom of the filter edit screen, enable filtering on icon:

.. figure:: ../_static/waypoint-search5.png
   :height: 568px
   :width: 320px
   :alt: Waypoint search Topo GPS
  
   *Filtering on icon is enabled.*

In the figure above, filtering on icon is enabled. The icon was set to 'Ancient monument'. To modify this specific icon, tap on the icon. Then the :ref:`waypoint icons screen <ss-waypoint-icons>` will be opened from which you can select another icon.

When applying a filtering on icon, only waypoints with a specific icon will be shown in the waypoints screen, as in the figure below. There you see only waypoints with the 'Ancient monument' icon. To indicate that an icon filter is active, the icon on which is filtered is displayed below the search bar left of the filter description.

.. figure:: ../_static/waypoint-search6.png
   :height: 568px
   :width: 320px
   :alt: Waypoint search Topo GPS
  
   *Filtering waypoints on 'Ancient monument' icon.*

   
