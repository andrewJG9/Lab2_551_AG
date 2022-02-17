this app creates a map of the city of calgary using Leaflet functions and geojson features.
When opened, it shows a organized cluster of all the building permit locations in calgary. If you click
on a marker, it will show metadata such as issue date, contractor name and address. The date time picker widget 
filters the building permits by issue date and updates the map. I created my own function for filtering the date time
of the permits, however it seems to have issues when it comes to the null issueddate values, even though it is set to return false
for null dates. 