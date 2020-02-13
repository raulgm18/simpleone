# simpleone

https://raulgm18.github.io/leaflet-maps-with-google-sheets/


<iframe width="600" height="371" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vT5IJXYa2BUPGEF8GtxxY0qj6ECZi_QEoUYZc6bYUiToL57id3lNYPyLSSuv6uVg9hUejF758RE_k0N/pubchart?oid=592911189&amp;format=interactive"></iframe>

<iframe width="600" height="371" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTKrRwlsrG4jiEPevBH9F6Qig1gA4kEA58U0aU1tCgK4Rk6WmDxPeWairsUNco4VH1e9eRNif42jNjV/pubchart?oid=557199677&amp;format=interactive"></iframe>

<iframe src="https://www.google.com/maps/d/u/0/embed?mid=1PGldItuxs5SHDJMLxfCS_nlgbxM" width="640" height="480"></iframe>





google-doc-url.js

var map = L.map('map').setView([51.505, -0.09], 13);

L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', { attribution: '© OpenStreetMap contributors' }).addTo(map);

L.marker([51.5, -0.09]).addTo(map) .bindPopup('A pretty CSS3 popup.
Easily customizable.') .openPopup();

