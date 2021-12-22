# ACG-Group-Project
Final project for Advanced Computer Graphics course


## Introduction
Our group has decided to render a simple detective themed scene for our nal project. As we
are a group of three with limited background in game design, web design, and otherwise interactive
computing, we have decided to keep our tasks focused to the scope of this course. That is, each of
us will contribute to this project by rendering one component of the scene. The detective scene will
include three basic components, all three dimensional in nature. Each of these components can stand
alone and be rendered by an individual group member regardless of the state of the other components.
Thus, we avoid pipelining halts.

## Task Allocation
The first component is a textured surface, chosen to be crumpled paper. The paper may include
elements of text, which can be noise-generated, but the focus will be to sample noise to produce an
uneven three-dimensional surface (not just a two-dimensional skin). Perhaps the paper will even 
utter
lightly with some wind. The techniques required to render the paper may include noise sampling,
signed distance functions and ray tracing. This component will be handled by Xiaotian Yang.
The second component is some noise-related motion, chosen to be a smoking cigar. The cigar may
also be textured to look more realistic, but the focus is on animating the smoke using noise-generated
motion. Additional interactions may be introduced, such as the smoke path being altered by some
wind. The techniques required to render the cigar and smoke may include noise sampling, ray tracing
and matrix transformations in time. This component will be handled by Erich Doclaf.
The third component is warped glass, chosen to be a magnifying glass. The magnifying glass may
have some texture, such as a metallic rim and leather handle, but the focus is on creating the glass
surface and warping eect. If possible, the glass may even show some faint re
ection of the surrounding
room. The techniques required to render the magnifying glass include ray tracing, lighting techniques
and matrix transforms in space. This component will be handled by Akirabha Chanuntranont.

## Final Scene
In the nal product, these components will be put together to make a scene reminiscent of a
detective's desk. That is, these components will likely be layered and will ideally interact with each
other. For example, the magnifying glass will magnify the creases and texts of the paper, and the cigar
smoke will dance whistfully in the air, possibly curling around the edges of the other components.
After we have completed a minimum working product, we may seek to include further details, such
as wood texturing for the desk. To emphasize the idea that all components can work together, the
stage of the nal scene will rotate steadily in time, so each component will eventually overlap another
and some interaction (either correct layering of objects or correct magnication of objects) will take
place. Hopefully, we will have an interactive component where the user can move around the camera
and choose arbitrary lighting.
