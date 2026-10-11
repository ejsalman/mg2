# minigame 2
## Devlog

1. I didn't encounter any issues while writing my code, so when I was fixing Step 2, I got a syntax 
   error. This is because the condition for the if-statement was missing the parenthesis.

2. _spriteRenderer.color = new Color(r, 0.2f, 0.2f);
   This code runs after the if-else statements, and plugs in the value of r to change the RGB value of the prop after each iteration where it's hit with the spell. I believe the period (.) is used so that the Color(r,g,b) function is able to be applied to _spriteRenderer. The "new" I think is used to let the game know that the RGB value is different from the one it was assigned before.