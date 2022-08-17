# YSE Address formatter

## address_trim_by_postcode

This is more specialized than the name gives away!   This is originally used for Yale Campus,
could be used for any corporate or hyperlocal setup.   When display space is at a premium, street address
may be enough.   But within the same city, the city name still makes sense where 100 Main Street could 
be on either side of a town border, etc.  Postcode allows for that granularity.


## address_trim_by_homecountry

Takes away the country from the address display.  Used when the assumption is that almost every
address will repeat the country designation, but you want to print the country when it is not the
same as the site origin.

## TODO
- need to get the form working!  hardcoding is not OK.
-  $homecountries_to_match = array("US");
-  $postals_to_match = array("06510", "06511", "06515", "06519");
