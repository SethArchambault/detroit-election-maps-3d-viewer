This is just a test!

Place this folder side by side with detroit-election-maps like so:

```
mkdir some_folder
cd some_folder
git clone git@github.com:pjsier/michigan-primary-election-maps-2026.git
git clone https://github.com/SethArchambault/detroit-election-maps-3d-viewer.git
cd detroit-election-maps-3d-viewer
```

You'll probably have to update permissions for this file.
```
sudo chmod 755 3d_viewer
```

Then you can run and see the detroit election maps in 3d
```
./3d_viewer
```

Move around with the mouse and WASD keys

Press Space to look at a precinct (really a bounding box around a precinct).

Press Escape to fiddle with settings.

Try loading a different shader style, or tweaking shader settings.

Try switching between data fields, and adjusting elements.

Check out detroit-election-maps.cfg to see how things are configured, though editing this might break things.






