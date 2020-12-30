# UNICT Underwater Background Modeling

The underwater benchmark dataset consists of 14 videos categorized into seven different classes representing complex challenges in the background modeling:
* “Blurred” sequences aim at evaluating how low-contrast images may affect the algorithms’ performance. This is particularly important for all those approaches that use textures in the background/foreground modeling process.
* “Complex Background” sequences show cases where background is characterized by complex textures and aim at assessing how approaches not using textures perform.
* “Crowded” sequences aim at evaluating algorithm performance with many occluding objects.
* “Dynamic Background” and “Luminosity Changes” videos include, respectively, by background objects movements (e.g. plant movements due to the marine currents) and transient and abrupt luminosity changes, and aim at evaluating the methods' capabilities of filtering out potential false positives.
* “Camouflage Foreground Objects” sequences are included for evaluating the effects of camouflage.
* “Hybrid” sequences, finally, show a combination of the above conditions.

The ground truth on the underwater video dataset was hand-labeled using the PERLa (see references) tool. For each video about 30 images were annotated and are provided as binary masks. In total more than 3500 objects were labeled. Please note that in the ground truth there are masks which are completely black, and are meant to assess performance when only background moving objects are present in the scene.


### Download dataset

Link to dataset files: https://tinyurl.com/UNICT-Underwater-Bkg-Modeling

### Citation

If you use this dataset, please cite the following works:

> I. Kavasidis, S. Palazzo, R. Di Salvo, D. Giordano, C. Spampinato, _An Innovative Web-Based Collaborative Platform for Video Annotation_, Multimedia Tools and Applications, pp. 1-20, 2013.

> C. Spampinato, S. Palazzo, I. Kavasidis, _A texton-based kernel density estimation approach for background modeling under extreme conditions_, Computer Vision and Image Understanding, vol. 122, pp. 74-83, 2014.
