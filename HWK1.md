## Hello Neighbor 

I choose Hello Neighbor because my wife and I volunteer with the organization mentoring a refugee family that arrived to Pittsburgh just prior to the pandemic in 2020. We have enjoyed spending time them, learning the Afghan culture, and sharing traditions. We have taken the family to Phipps Conservatory, played board games, learned how to cook Afghan food, and spent many hours drinking tea and talking. 

__ From the "About us Page on Hello Neighbor's Website:  

### Our Mission

Hello Neighbor works to improve the lives of recently resettled refugee and immigrant families by matching them with dedicated neighbors to guide and support them in their new lives.

### Our Vision

Hello Neighbor envisions a welcoming, inclusive, and vibrant Pittsburgh and America, whose newest neighbors can realize their dreams of success and prosperity. We aspire to see communities where everyone is valued for their diverse perspectives and are empowered to rebuild their lives with dignity and respect __

[Click on Hello Neighbor Website Link to Learn More!](https://www.helloneighbor.io/about)

## Creating a Color Palette

I chose a picture from Hello Neighbor's webpage that encapsulated not on the mission of Hello Neighbor but also the central colors of the Hello Neighbor logo which are more pastel greens and blues. I also wanted a few colors like black or greys to have for background and to highlight man made features in a subtle way. 

![picture](Pictures/HelloNeighbor_Pic.jpg)

![Palette](Pictures/HelloNeighbor_ColorPalette.jpg)

## Hello Neighbor Map

<html>
  <head>
    <title>Hello Neighbor</title>
    <meta name="viewport" content="initial-scale=1.0, user-scalable=no">
    <meta charset="utf-8">
    <style>
      /* Always set the map height explicitly to define the size of the div
       * element that contains the map. */
      #map {
        height: 100%;
      }
      /* Optional: Makes the sample page fill the window. */
      html, body {
        height: 100%;
        margin: 0;
        padding: 0;
      }
    </style>
  </head>
  <body>
    <div id="map"></div>
    <script>
      function initMap() {
        // Styles a map in custom mode.
        var map = new google.maps.Map(document.getElementById('map'), {
          center: {lat: 40.4583498, lng: -80.079528},  // Setting the center to Pittsburgh, change as you like
          zoom: 15,  // Setting a zoom scale for Pittsburgh
          styles:    // Add JSON from Map Style Wizard below this line... 
      
      [
  {
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#ebe3cd"
      }
    ]
  },
  {
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#523735"
      }
    ]
  },
  {
    "elementType": "labels.text.stroke",
    "stylers": [
      {
        "color": "#f5f1e6"
      }
    ]
  },
  {
    "featureType": "administrative",
    "stylers": [
      {
        "color": "#2c2e1c"
      },
      {
        "saturation": -45
      },
      {
        "lightness": -30
      },
      {
        "weight": 1
      }
    ]
  },
  {
    "featureType": "administrative",
    "elementType": "geometry.stroke",
    "stylers": [
      {
        "color": "#c9b2a6"
      }
    ]
  },
  {
    "featureType": "administrative",
    "elementType": "labels.text.stroke",
    "stylers": [
      {
        "color": "#ffffff"
      }
    ]
  },
  {
    "featureType": "administrative.land_parcel",
    "elementType": "geometry.stroke",
    "stylers": [
      {
        "color": "#dcd2be"
      }
    ]
  },
  {
    "featureType": "administrative.land_parcel",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#ae9e90"
      }
    ]
  },
  {
    "featureType": "landscape",
    "stylers": [
      {
        "color": "#708534"
      }
    ]
  },
  {
    "featureType": "landscape.natural",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#dfd2ae"
      }
    ]
  },
  {
    "featureType": "poi",
    "stylers": [
      {
        "color": "#6bb6cb"
      },
      {
        "weight": 4.5
      }
    ]
  },
  {
    "featureType": "poi",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#dfd2ae"
      }
    ]
  },
  {
    "featureType": "poi",
    "elementType": "labels.text",
    "stylers": [
      {
        "color": "#6bb6cb"
      }
    ]
  },
  {
    "featureType": "poi",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#6bb6cb"
      }
    ]
  },
  {
    "featureType": "poi",
    "elementType": "labels.text.stroke",
    "stylers": [
      {
        "color": "#ffffff"
      },
      {
        "saturation": -55
      },
      {
        "lightness": -5
      },
      {
        "weight": 1.5
      }
    ]
  },
  {
    "featureType": "poi.park",
    "elementType": "geometry.fill",
    "stylers": [
      {
        "color": "#a5b076"
      }
    ]
  },
  {
    "featureType": "poi.park",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#447530"
      }
    ]
  },
  {
    "featureType": "road",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#f5f1e6"
      }
    ]
  },
  {
    "featureType": "road.arterial",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#fdfcf8"
      }
    ]
  },
  {
    "featureType": "road.highway",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#f8c967"
      }
    ]
  },
  {
    "featureType": "road.highway",
    "elementType": "geometry.stroke",
    "stylers": [
      {
        "color": "#dacfc8"
      }
    ]
  },
  {
    "featureType": "road.highway.controlled_access",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#e98d58"
      }
    ]
  },
  {
    "featureType": "road.highway.controlled_access",
    "elementType": "geometry.stroke",
    "stylers": [
      {
        "color": "#db8555"
      }
    ]
  },
  {
    "featureType": "road.local",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#806b63"
      }
    ]
  },
  {
    "featureType": "transit.line",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#dfd2ae"
      }
    ]
  },
  {
    "featureType": "transit.line",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#8f7d77"
      }
    ]
  },
  {
    "featureType": "transit.line",
    "elementType": "labels.text.stroke",
    "stylers": [
      {
        "color": "#ebe3cd"
      }
    ]
  },
  {
    "featureType": "transit.station",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#dfd2ae"
      }
    ]
  },
  {
    "featureType": "water",
    "stylers": [
      {
        "color": "#6bb6cb"
      }
    ]
  },
  {
    "featureType": "water",
    "elementType": "geometry.fill",
    "stylers": [
      {
        "color": "#6bb6cb"
      }
    ]
  },
  {
    "featureType": "water",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#92998d"
      }
    ]
  }
]


// ..and here's the end of JSON from Style Wizard          
        });
      }
// Don't forget your API Key below vv
    </script>
    <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyDQ3oWa5ZpbHbUzZHwJB3Fl4ftxVojVNrM&callback=initMap"
    async defer></script>
  </body>
</html>
