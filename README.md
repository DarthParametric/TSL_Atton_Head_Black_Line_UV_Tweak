# [TSL] Atton Head UV Tweak for Black Line Issue
This is a slightly tweaked version of Atton's head model that adjusts the UVs to reduce/eliminate the "black line" issue. This can happen on some systems due to the engine utilising deprecated OpenGL calls that can cause black lines along any UV seams at the very edge of a texture. The issue is most prominent in the center of faces due to both K1 and TSL using mirrored face UVs to maximise pixel density in their low resolution textures.

Further information can be found here - https://deadlystream.com/topic/5632-black-line-in-middle-of-face
