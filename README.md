P5.JS

1) Blood.  
This output uses noise to move a red ellipse smoothly around the canvas. I layered transparent red ellipses around it to create a blurred, smudged effect, like blood. Because the marks stay on the canvas as the ellipse moves, it leaves behind a red stain looking trail

2) Eyes.  
uses If statements to translate across its X axis and within the boundaries of the canvas. Used random() and thought to do it with two ellipses and make it creepy looking, with the translucent eye trail effect and color choice

3) Solar System 
The first idea that I had with translating was how similar it was to planets and stuff orbiting things, so using that logic I gave each planet its own origin and that made it revolve around something else. Like the moon rotates around the middle of the earth where its origin is, earth and mars have their origins off screen so they rotate on a much larger orbit mimicking their orbit around the sun which isn’t shown. I also made things like the basic clouds on the Earth orbit within the earth to look more realistic. This one was a lot of playing with numbers to get the speed and arc right


Touch Designer

1) Dot.  
This one uses two noise chops to make the dot move around, and feedback loops that play with the opacity to leave a trail by leaving less-opaque copies of the circle behind as it’s translated all around

2) RGBlob.  
Used absTime on translateZ to animate a Noise SOP that warps a bezier sphere SOP. the sphere also has a attribute create SOP to make the shadows more realistic and make the 3D more believable

3) Blood Smear.  
I created something similar in p5.js and wanted to compare the process. This one uses LFO and Math CHOPs to move a circle around. The X and Y change values at different speeds, and off sync, which helped me understand the difference between doing it that way, and using Noise instead. The level and blur TOPs add the sort of smudgy red trail, but I do prefer how it turned out on p5.js
