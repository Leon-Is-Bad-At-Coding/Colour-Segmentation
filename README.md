# Colour-Segmentation
![Webp net-gifmaker](https://user-images.githubusercontent.com/84482670/136640509-c3555461-186d-4658-8af8-176aa6667b17.gif)

This project is about seperating colours in an image into larger groups.
Colour segmentation is useful because grouping the colours into larger chunks of colours makes it a lot simpler and easier to analyze. The chunks of colour are better at representing the RGB values rather than tiny pixels.
1. Choose a number of clusters.
2. Choose a some points to be centroids.
3. Assign all points to the nearest centroid.
4. Calculate new centroid locations based on clusters.

Clustering result changes each iteration because the centroids are being recalculated every time.
You should stop the algorithm when the error graph is at its lowest. The error how different your image is to the original.
