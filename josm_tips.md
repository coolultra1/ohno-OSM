*`Preferences` → `OSM Data` → `Draw inactive layers in other color`*
Checked by default, this will grey out map objects on inactive layers.
Unchecking will let you see these objects on the active layer.
Example use - download osm task manager grid as background layer.

Click on a node to select it, `Shift` + click to add to selection, `Ctrl` + click to toggle it in selection, `Ctrl-Shift` to rotate selection, `Ctrl-Alt` to scale selection.

The continuous download plugin automatically downloads the area when you pan to a new area.

Creating a way with Draw building (`B`) while holding `Alt` will create a perfectly rectangular way without any tags.

When dragging a node, hold `Ctrl` to automatically merge it with nearby nodes.

`[` in the todo plugin will skip the current item but leave it in the todo list and go to the next.

`Alt-1/2/…` will toggle if an imagery layer is visible, with 1 being the bottom layer.

When merging or deleting nodes/ways you can use `Ctrl-Alt-D` to download the referrers before making the changes.
That will solve issues with other elements that are connected to these nodes/ways.

Selecting multiple POIs and pressing `L` will line them all in a row.

The `Tab` key will hide/show the docked window panels, but not the undocked panels.

The tilde (`~`) key will reorder the imagery layers.

The `]` key will Mark an item in the todo list plugin and zoom to the next item.

Searching for `node:connection < way[building]` (using MapCSS selector syntax) will find buildings that are connected.

Clicking on an item in the selection dialog and pressing `Ctrl-C` will copy its type and id - eg. `way 12345678`.
The reverse works too! Copying `way 12345678` and pressing paste in JOSM will paste a copy of the way if you have it downloaded in your current data.

In the Map Paint Styles Dialog - right click on a style - some have style settings for extra effects.

In Draw mode, holding the `Alt` key while clicking the mouse will start a new way from the last node.

In Draw mode, holding the `Shift` key while clicking the mouse will start a new way at your mouse position.

In Draw mode, holding the `Ctrl` key while clicking the mouse will prevent added nodes from being glued to other objects/nodes.

Holding the `Alt` key when drag selecting will select the entire object(s) of any node(s) in the selection area.

Left click drag will make a selection rectangle; you can move that rectangle outline by adding a right mouse click without releasing the left click and dragging.

For overlapping objects, middle click the object will cycle objects in a small popup (or `Alt` left click to cycle without popup).

Double left clicking inside an area or multipolygon will select the it. Good if you are zoomed out and are not able to click on the edge or have overlapping ways.

To get perfect pentagon hexagon or octagon (for example, if creating gazebos)  draw a 5, 6 or 8 sided way, then press `O`, *`Tools` → `Align Nodes in a Circle`*.

If you have programable buttons on your mouse, set them to your most used shortcuts. Examples: `Q`, `]`, `Del`, `Ctrl-Z`.

In extrude mode, double click on an existing way to create a new node at that point. This gives fine grained control on what you extrude.

The building tool plugin allows you to add/change the tags used, so instead of `building=yes`, you could do `building=house` or `leisure=swimming_pool` if you plan to add many rectangular pools.
Go to *`Data` → `Set building size and shape` → `Advanced…`*.

Select 2 nodes on a way, then select 1 or more other ways, press `Q` and the ways will square corners and align to the 2 selected nodes.

Pressing `Q` on a way will square the corners (orthogonalize).
After squared, you can click on a node in the way and press `Shift-Q` to undo that node.
This can be useful if a mostly rectangular way has a diagonal section.

`Shift` click or `Shift` double-click on a recently used tag in the tag dialog will add it without closing the dialog.
Double-click on recently used tag in the tag dialog will add it and close the dialog.

`Ctrl-J` will let you enter Lat/Long to jump to a map location, or copy a url using the current cursor Lat/Long.

`Shift-R` Applies tags from last selected object to the current selected object(s).  

`Shift-C` can create circle arcs in 3 different ways
- `Shift-C` makes an arc from the last 3 nodes in the way. In draw mode lets you draw curves and let you continue seamlessly.
- selecting any three nodes, `Shift-C` creates an arc between them.
- selecting any three nodes on a way, and the way, `Shift-C` will change the way between the nodes into an arc and proportionally fill in any nodes.

When in angle-snapping mode (press `A` when in draw mode to enable angle snapping), hold `Ctrl` and move your mouse over another way segment.
Angle snapping will now run relative to that way, making it easy to draw parallel or perpendicular ways.

If you want to edit something in JOSM without the risk of touching a boundary, select the boundary and press `Ctrl-Shift-P` to purge it from the downloaded data and not edit it.

Using *`File` Upload selection...* will allow you to upload the selected objects and minimize the uploads bounding box to that selection.
