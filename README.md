# Face-landmarks-detection-benchmark
Face landmarks(fiducial points) detection evaluation.

Attention! It's comparision of specific implementations, not algorithms by itself, so if you know how to improve results let me know.


Name| Rot. | Exp. | Lang | Doc.
------------------ | --- | --- | --- | ---
[Stasm](http://www.milbo.users.sonic.net/stasm/)|no|no|C|yes
[CLM-framework](https://github.com/TadasBaltrusaitis/CLM-framework)|?|?|?|?
[Dlib](http://dlib.net/)|?|?|?|?


TODO:
~~~
Choose metric and protocol of testing.
~~~

To look at:
~~~
https://github.com/delphifirst/FaceX
https://github.com/ci2cv/face-analysis-sdk
https://github.com/uricamic/flandmark
http://cmp.felk.cvut.cz/~uricamic/flandmark/
http://cmp.felk.cvut.cz/~uricamic/clandmark/
https://github.com/dnouri/kfkd-tutorial
https://github.com/FaceDetect/jointCascade_py
https://github.com/zhusz/CVPR15-CFSS
http://mmlab.ie.cuhk.edu.hk/archive/CNN_FacePoint.htm
http://mmlab.ie.cuhk.edu.hk/projects/TCDCN.html
http://ibug.doc.ic.ac.uk/resources/fiducial-facial-point-detector-20052007/
http://ibug.doc.ic.ac.uk/resources/facial-point-detector-2010/
ASM/AAM
http://www.milbo.users.sonic.net/stasm/
https://github.com/cxcxcxcx/asmlib-opencv
check if it detects points or only align face
https://github.com/jwyang/face-alignment
https://github.com/soundsilence/FaceAlignment
constrained local models
https://github.com/TadasBaltrusaitis/CLM-framework

"One Millisecond Face Alignment with an Ensemble of Regression Trees"
http://blog.dlib.net/2014/08/real-time-face-pose-estimation.html
http://www.csc.kth.se/~vahidk/face_ert.html

http://www.ics.uci.edu/~xzhu/face/
https://github.com/TadasBaltrusaitis/CLM-framework

Deep learning:
https://github.com/olddocks/caffe-facialkp

Kaggle:
https://www.kaggle.com/c/facial-keypoints-detection/data

Javascript:
https://github.com/auduno/clmtrackr

Too simple algorithm, not worth considering it:
https://github.com/sdcoca/facex
~~~

Facial points datasets:

Name| N images| N points |Lighting | Age | Ethnicity| $ | Auth.
------------------ | --- | --- | --- | --- | --- | --- | --- 
[MUCT](http://www.milbo.org/muct/)|3755|76|yes|yes|yes|no|no
[LFPW](http://neerajkumar.org/databases/lfpw/)|1432|29|
[HELEN](http://www.ifp.illinois.edu/~vuongle2/helen/)|2330|192
[AFW]()|?|?
[AFLW](https://lrs.icg.tugraz.at/research/aflw/)|?|?
[IBUG]()|?|68
[PUT]()|?|?
[XM2VTS](http://www.ee.surrey.ac.uk/CVSSP/xm2vtsdb/)|?|?
[ATVS](http://atvs.ii.uam.es/scfacedb_landmarks.html)|?|?|yes

