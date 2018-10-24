MALEECHE'S JANKY ARK MAP
-------------------------------------------------------------------------------

1. Launch the program by double clicking the file "ark_ab_map.html"

2. The program will launch in your default browser (tested with firefox and chrome)

3. Click the "Load Map Data" button.

4. Navigate to the "Data" folder in this directory, and select the file "markers.csv"

5. The "Bases" layer should be active by default, but you can turn on/off other layers by
clicking the layers icon in the top right corner of the map window.

6. You can add additional map data points to the "markers.csv" file by following this format:
Lat,Lng,group,popup

Example:
40,42,crystal,This is a crystal patch

The above example places a marker at Lat 40, Lng 42, adds it to the crystal layer group,
and links a popup to it with the text "This is a crystal patch".

If no popup text is provided, the popup text will simply show the Lat and Lng of the marker.

7. Layer groups must be typed exactly as they are shown below.
The list of layer groups currently availabe are:

crystal
metal
metal_rich
obsidian
silica
oil_rock
black_pearl
polymer
element_ore
keratin
gem_blue
gem_green
gem_red
bases
chargeNodes
rockDrakeEggs