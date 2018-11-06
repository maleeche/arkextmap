# Ark Extinction Interactive Map

## Instructions
1. Navigate to https://maleeche.github.io/arkextmap

2. Clicking anywhere on the map will display a popup displaying the current Lat,Lng position.

3. You can zoom in/out using your mouse scroll wheel.

4. The "Bases" layer should be active by default, but you can turn on/off other layers by
clicking the layers icon in the top right corner of the map window.

5. You can add additional map data points to the "markers.csv" file by following this format:
Lat,Lng,group,popup

Example:
40,42,crystal,This is a crystal node

The above example places a marker at Lat 40, Lng 42, adds it to the crystal layer group,
and links a popup to it with the text "This is a crystal patch".

If no popup text is provided, the popup text will simply show the Lat and Lng of the marker.

6. Layer groups must be typed exactly as they are shown below.
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
