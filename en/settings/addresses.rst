.. _sec-settings-addresses:

Addresses
=========

In the section 'Addresses' of the :ref:`settings <ss-settings>` you can determine whether addresses of points are looked up automatically.

If you enable the setting 'Find automatically' addresses of locations can be looked up if necessary. To find the address of a location you need an internet connection.<APPLE>
The Topo GPS app is using the `MKReverseGeocodingRequest service from Apple <https://developer.apple.com/documentation/mapkit/mkreversegeocodingrequest>`_ for this.
</APPLE>
<ANDROID>
The Topo GPS app is using the `Android Geocode <https://developer.android.com/reference/android/location/Geocoder>`_ for this.
</ANDROID>

Addresses are used in the :ref:`waypoint details screen <ss-waypoint-details>` and in the :ref:`current location screen <ss-current-location-screen>` to show the address of a waypoint and of your current location.

If you want a high level of privacy, you might want to disable this feature, in order to prevent network requests containing your location or the location of your points.

