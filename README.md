### Dolly Zoom Effect

Here I implemented Dolly Zoom effect used by cinema - makers to create a sensation of vertigo, a \falling-away-from-oneself feeling".
This is done by moving the camera away from the object and increasing the focal length which reduce the FOV and creates the effect.

Here is the gif of the matplotlib plot that was generated in the code:

![Matlab program showing gif of dolly zoom effect](./resources/DollyZoom.gif)


Run run_dolly_zoom.m to see visualize it.

Files explanation:

  - The code compute_focal_length.m computes the focal lenght such that the green object in front has the same height in the image when the camera is moved back.
  - The code compute_f_pos.m computes the focal length and the position of the camera such that the object in front has the same height in the image and the blue object behind it becomes half it's size.
  - The code project_objects.m render synthetic image using given camera focal length and camera position
