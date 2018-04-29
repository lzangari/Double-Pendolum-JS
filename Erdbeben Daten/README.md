# Erbeben Visualisation 
Dieses Programm visualisiert Erdbebendaten aus dem USGS, indem ich den Breitengrad, den Längengrad und das Ausmaß von Erdbeben mit p5.js abbilde.

Das Kartenbild wird aus mapbox.js gezogen, und die mathematischen Daten zeigen den Breitengrad, den Längengrad und den Längengrad von x, y über Web Mercator.



# p5.js
Um JavaScript Files ind dem Browser schnell ausfüren zu können, rate ich p5.js zu benutzen (open source intuitive library for JavaScript)
 https://p5js.org/
 
 + Download : https://github.com/processing/p5.js-editor/releases
 + Programm extraieren und ausführuen. Danach die Gwünschte .js datei öffnen und "Play" drücken.
 
 # Erdbeben daten
 Die Daten wurden von der U.S. Geological Survey Seite genommen und sind in cvs Format. 

 Um die Daten Zeitraum der daten zu ändern einfach den Link zum gewünschten Zeitraum kopieren und in zeile 21 ändern.
 
 ```javascript
earthquakes = loadStrings('https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_day.csv');
