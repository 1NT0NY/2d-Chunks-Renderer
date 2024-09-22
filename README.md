# 2d-Chunks-Renderer
2d-Chunks Renderer by 1NT0NY

![Zrzut ekranu 2024-09-22 115855](https://github.com/user-attachments/assets/677ca32e-ff13-4cf1-874e-c7244b5deeb3)

When a player with a connected camera doesn't see any sprites that are outside the camera boundaries, they are deactivated.
But as soon as he moves in any direction, these deactivated sprites, will activate 0.4 hundredths of a second in advance before the player really sees them,
the same works the other way when the player leaves some sprites they will deactivate only after 0.4 seconds as well.
In addition, I added a periodic check by the script for newly added sprites, so that it won't happen that when I add many new objects with sprites they will be missed.
The script has a list through which I can manually add objects, but it exists so in addition, the script itself collects every object that has a “Sprite Renderer”.

