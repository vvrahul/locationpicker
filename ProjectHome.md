The Location Picker allows people to easily find a location and save the longitude and latitude to a form text input.

The main starting point will usually be for a user to search for an address using the input field and search button which is automatically added. A small map then pops up below the input field where the user can drag a marker to fine tune the position. All the while the text input is updated with a latitude and longitude string.

Location Picker currently utilises jQuery and Google Maps.

Usage is as simple as:

```
<script type="text/javascript" src='http://maps.google.com/maps/api/js?sensor=false'></script>
<script type='text/javascript' src='http://ajax.googleapis.com/ajax/libs/jquery/1.4.2/jquery.min.js'></script>
<script type='text/javascript' src='jquery.locationpicker.js'></script>
<script type="text/javascript">
    jQuery(document).ready(function(){
        jQuery('input.lnglat').locationPicker();
    });
</script>
```