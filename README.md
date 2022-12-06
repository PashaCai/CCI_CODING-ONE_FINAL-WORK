# CCI_Coding-One_Final-Work_Rui Cai
<h2>CCI_Coding One_Final Work</h2>

<h3>LINK TO Demonstration Video https://youtu.be/lcCC4DGMA5I</h3>

Due to the use of GIT LFS to upload large files, please click into Final_Work.zip to download, the file size is 810mb.

This project is a 3d interactive project based on the first semester of code study, based on three.js.

The project is based on the concepts of 'vapour waves' and 'dream cores', creating a realistic yet unrealistic scene through the combination of sky, ocean and plaster figures. 

I love the ethereal ambience of the real sky swirling to the music and the water reflecting the figures of the plaster statues, giving a real but false sense of absurdity. Sometimes there is no need to worry about the line between dream and reality, life is just a dream after all.

I have always wanted to try my hand at making something like this, but as I have no coding skills from my undergraduate degree in graphic design, I took the opportunity to study the various functions of three.js for my final assignment and combined it with blender modelling to create this interactive scene.

The project is based on html and is detailed using css code and js.
The project uses three.js as a dependency library, using the controller, water surface, GltfLoder, DRACOloder and RGBELoder from three.js respectively.
An attempt was also made to use this in conjunction with GLSL, but this did not work due to technical issues. Finally the whole project was wrapped in parcel and uploaded to github with git lfs.

In this project I used scene creation and created a sky material sphere, then placed the camera in the sphere, inverted the sphere material, placed the sky inside the sphere, created a video texture for the sphere and created a dynamic sky with 'mouse move' as the interaction method.

The water surface was then created using the three.js dependency library and a ripple texture was added to the water surface. The models prepared in blender were then loaded using GTFLoder and DRACOLoder.

Finally HDR environment textures were added to the overall scene and lighting was added. To complement the scene, background music was added using the html5 <audio> element and looped using the function().

The viewer can use the mouse to move the scene around to see different angles while enjoying the project, while the mouse wheel can also control the distance of the camera for close up or long distance viewing. Meanwhile outside the sphere is another view thanks to the HDR texture.

This project is the first time I have used code to create a virtual world, and I think there are still a lot of things I need to learn, especially the use of GLSL and three.js together. Also becoming more proficient in using three.js and learning more ways to interact with it is something I want to learn in the future.
