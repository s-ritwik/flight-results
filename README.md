# Flight Results

Interactive results from three real flights of GNSS-denied visual positioning. Each camera frame is matched to satellite imagery, and the resulting fixes are fused with visual-inertial odometry.

- **Frame from flight camera**: the frame used for each match.
- **Overlay of map accuracy**: the frame laid on the satellite map where the match placed it. The slider sets its opacity.
- **Map**: the GPS track and the visual fixes over the whole flight.
- **3D view**: GPS, fused, VIO and VPS tracks, with the full-flight error against GPS.

Use the bottom bar to play or scrub through a flight, and the picker at the top to switch flights. Drag to pan the maps, ctrl + scroll (or pinch) to zoom, and drag the 3D view to orbit it.

## Run locally

It is a static site:

```
python3 -m http.server 8000
```

Then open http://localhost:8000.
