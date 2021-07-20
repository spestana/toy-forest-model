# toy-forest-model

A **forest, snow, remote sensing, python, art project for fun** and to help visualize the impacts of view angle, sun angle, and/or shadows on image brightness (whether in visible or infrared wavelengths).


<img src="model.jpg" width="300" />

* The wooden "snow" base is about 14 cm square, painted white. 

* The "trees" are made of wooden pegs glued in place and painted dark green. 

* The trees protrude about 1 cm above the base.


<img src="animation_bw.gif" width="200" />

Black and while photos of the forest model from various angles.

As the view angle increases, we see more of the sides of the trees which in turn block our the lighter snow surface. This decreases the mean and median brightness value that the camera sees.

<img src="histograms.png" />

But why is there an apparent peak around ~10 degrees from nadir? It is likely due to the incoming angle of ambient lighting casting longer shadows when I held the model at "nadir" than the shadows (or lack of shadows) when held at ~10 degrees. This was not a rigorous experiment. 

<img src="viewangles.png" />

---
