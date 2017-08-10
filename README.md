Face Alignment
===

> This is a demo of detecting and aligning faces in an image.
Alignment is a process of rotating a face to a vertically straight orientation, should the original face image is tilted.

#### Setup:
1. Run `pip install -r requirements.txt`
2. Download and extract shape predictor 68 landmarks at this [link](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2).
3. Place the extracted predictor in the root directory of this project.
4. Find some images with faces, tiled if possible.

#### Run:
```bash
python app.py \<image input\> \<image output\>
```

##### Dependencies:
- [dlib](http://dlib.net/)
- [opencv-python](http://docs.opencv.org/3.0-beta/doc/py_tutorials/py_tutorials.html)
