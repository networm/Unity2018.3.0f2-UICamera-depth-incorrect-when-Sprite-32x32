# Unity2018.3.0f2-UICamera-depth-incorrect-when-Sprite-32x32

Open TestBackground.unity and play, you will find camera and white
background is flickering.
The depth of CanvasCamera is higher than depth of MainCamera, it should
be that white background is full of screen.

Change Max Size from 32 to 64 in Android settings of Background.png will
fix this problem. And change Max Size from 64 to 32 will reproduce this
problem.

