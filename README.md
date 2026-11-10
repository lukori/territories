# to boldly go · טריטוריות

A 3D version of the Miro board "to boldly go - טריטוריות". The clusters float above a dotted Miro-style floor.

- **X axis:** דיגיטלי ↔ פיזי
- **Y axis:** מחקרי ↔ יישומי
- **Z axis:** משחקי (playfulness). The colour sets each cluster's height: yellow is lowest, then orange, then red.

Live: https://lukori.github.io/territories/

## Controls
- Drag to pan. Use the wheel or a pinch to zoom.
- Shift + drag, a right-drag or the rotate tool orbits the view.
- The 2D button gives the flat top view, like Miro. The 3D button goes back to the angled view.
- Tap a card to enlarge it and open its link.

## Tuned values (in `index.html`)
- Cluster heights (`PLAY`): yellow 70, orange 380, red 700. Before these were 120 / 330 / 560.
- The "משחקי ↑" label sits at z=1800 and the pole is 1780 tall. The label is outlined, at the same size as the axis labels.
- Axis labels lie flat in the 2D view. They stand up, perpendicular to the floor and facing the camera, when the pitch is over 35° or the yaw is over 50°.

The images were cropped from screenshots of the Miro board, so they are not full resolution.
