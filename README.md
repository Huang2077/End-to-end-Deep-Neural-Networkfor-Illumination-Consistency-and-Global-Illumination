# End-to-end-Deep-Neural-Networkfor-Illumination-Consistency-and-Global-Illumination
# Author
Jingtao Huang and Takashi Komuro/ Graduate School of Science And Engineering, Saitama University
# Abstract
 In order to achieve illumination consistency and global illumination in augmented reality (AR), we propose a method of performing illumination estimation and rendering computation simultaneously using end-to-end deep neural
networks. The proposed networks can implicitly estimate the illumination information from the background environment scene in AR, and can generate natural reflections and shadows
for the virtual objects by using geometric information of the virtual objects and the estimated illumination information. We created two different scenes to train the networks with Unreal Engine 4: 
a static simple scene and a dynamic complex scene. Two datasets were rendered. In the simple training scene,
realistic reflections and shadows of a metal virtual object were
generated. In the complex scene, realistic dynamic shadows
of the virtual object were generated successfully, but the
generation of metal reflections failed. As a result, illumination
consistency was achieved in both the simple scene and the
complex scene. Global illumination was achieved only in the
simple scene.
