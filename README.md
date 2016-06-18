# newmaps

Metro celebrated the new Expo Line with a revised [rail system map](https://media.metro.net/riding_metro/maps/images/rail_map.pdf). That means another round of map updates for metro.net, the kiosks, the Go Metro Mobile App, and the Station Guide.

As we We move towards a more dynamic platform we will need dynamic mapping. This project will provide a framework for these maps.

The index.html page uses [d3.js](https://d3js.org) to parse the data.json file and draw a few stops. Check out the code and open index.html in a browser. You will see this:

![preview](https://www.evernote.com/l/ADOJGmjoSJdOHa0p9qlAuEGwajpi0G3YoPgB/image.png)

## Blue skies

1. fully responsive (check!)
2. interactive: click on station names to see bus connections and station amenities
3. real-time: show system alerts and vehicle positions
