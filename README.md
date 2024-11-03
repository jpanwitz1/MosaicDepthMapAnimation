# MosaicDepthMapAnimation
3D animation for mosaic image displays that uses a depth map to extrude individual mosaic tiles

LA Photo Party sells a live-event photo mosaic software that allows all photos taken at an event (whether by our team or by guests who wish to text or tag their own photos to the mosaic). These photos are then printed out as stickers for guests to place on a large mosaic board—aided by a column and row grid with corresponding tag printed on the photo sticker—or broadcast live to a custom URL and displayed on large screens at the event.  

These live video mosaics were designed with very simplistic animations by the developer, but I wanted to incorporate more dramatic GPU-accelerated 3D animations to the live displays.  I came up with the idea to integrate depth map extrusions of the individual images using any greyscale image (this could be easily sourced or created by our software users to customize their animations with a minimal learning curve) along with a pre-configured perspective shift animation to enhance the perceived depth of the 3D extrusion animation.

I created this three.js project as a proof-of-concept. The actual program would have used the generated mosaic image, the number of images in x and y, and the user created depth map as inputs. I have included a video showing the animation in action as well as the depth map image used in this specific animation.
