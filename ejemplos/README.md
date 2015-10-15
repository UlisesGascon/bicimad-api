# Ejemplos

Los ejemplos están listos para funcionar, no es necesario realizar ajustes.


### Geolocalización

En [este ejemplo](nearest.html) la idea principal es poder usar [Geolocation de html5](http://www.w3schools.com/html/html5_geolocation.asp) para saber donde estamos y posterior mente hacer una petición a la API con esos datos.

La respuesta de la API se muestra en un [Google Map](https://developers.google.com/maps/). La [chincheta](img/pin.png) representa el usurio, y las [bicicletas](img/bike.png) las diversas estaciones. *Nota: al pinchar en los iconos podemos ver los detalles (lon, lat, nombre, calle, distancia relativa, bicis libres...)*

La precisión varia según el sistema usado por el cliente.  Las conexiones más precisas por orden de precisión son GPS, Wifi, Ethernet...

**Imágenes**

Los iconos utilizados en la aplicación son de Freepick.

- [Bicicleta](http://www.flaticon.com/free-icon/bike-zone-signal_34665)
- [Chincheta](http://www.flaticon.com/free-icon/push-pin_69667#term=pin&page=1&position=45)

**Dependencias**

- [Google Maps](https://developers.google.com/maps/documentation/javascript/)
- [Geolocation HTML5 (Compatibilidad)](http://caniuse.com/#feat=geolocation)

**Capturas**

![usuario detalles](/img/gmaps_bicimad_geolocation.png)

![estación detalles](/img/gmaps_bicimad_station.png)


### Detalles de las estaciones

En [este ejemplo](locations.html) la idea principal es poder usar [dataTables](http://datatables.net/) para poder jugar con los datos ofrecidos por la API.

**Dependencias**

- [Jquery](https://jquery.com/)
- [DataTables](http://datatables.net/)

**Capturas**

![dataTables detalles](/img/dataTable_locations.png)