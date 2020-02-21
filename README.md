# Face-landmarks-detection-benchmark
Face landmarks(fiducial points) detection evaluation.

Name| Rot. | Exp. | Lang | Doc.
------------------ | --- | --- | --- | ---
[Stasm](http://www.milbo.users.sonic.net/stasm/)|no|no|C|yes
[CLM-framework](https://github.com/TadasBaltrusaitis/CLM-framework)|?|?|?|?
[Dlib](http://dlib.net/)|?|?|?|?


Metric: 
~~~
"The average point-to-point Euclidean error normalized by the inter-ocular distance (measured as the Euclidean distance between the outer corners of the eyes)"
http://ibug.doc.ic.ac.uk/media/uploads/competitions/compute_error.m

"RMSE is very common and is a suitable general-purpose error metric. Compared to the Mean Absolute Error, RMSE punishes large errors"
https://www.kaggle.com/c/facial-keypoints-detection/details/evaluation
~~~

To look at:
~~~
Kaggle Facial Keypoints Detection
https://github.com/mrgloom/Kaggle-Facial-Keypoints-Detection-Solutions



Explicit shape regression
https://github.com/delphifirst/FaceX
https://github.com/soundsilence/FaceAlignment
http://phg1024.github.io/CSCE625/

https://github.com/ci2cv/face-analysis-sdk  (http://face.ci2cv.net/)
https://github.com/uricamic/flandmark
http://cmp.felk.cvut.cz/~uricamic/flandmark/
http://cmp.felk.cvut.cz/~uricamic/clandmark/
https://github.com/uricamic/clandmark
https://github.com/dnouri/kfkd-tutorial
https://github.com/FaceDetect/jointCascade_py
https://github.com/zhusz/CVPR15-CFSS
http://ibug.doc.ic.ac.uk/resources/fiducial-facial-point-detector-20052007/
http://ibug.doc.ic.ac.uk/resources/facial-point-detector-2010/
https://github.com/kylemcdonald/FaceTracker
http://www.cl.cam.ac.uk/research/rainbow/projects/clmz/
Coarse-to-Fine Auto-Encoder Networks (CFAN) for Real-Time Face Alignment
http://vipl.ict.ac.cn/resources/codes
http://ibug.doc.ic.ac.uk/resources/drmf-matlab-code-cvpr-2013/

Supervised Descent Method
https://github.com/RoboPai/sdm

ASM/AAM
http://www.milbo.users.sonic.net/stasm/
https://github.com/cxcxcxcx/asmlib-opencv
http://uomasm.sourceforge.net/
https://github.com/greatyao/aamlibrary
https://github.com/greatyao/asmlibrary
https://github.com/jiapei100/VOSM

https://github.com/ShiqiYu/libfacedetection

Shape regression
https://github.com/GentleZhu/Face_Alignment

constrained local models
https://github.com/TadasBaltrusaitis/CLM-framework

"One Millisecond Face Alignment with an Ensemble of Regression Trees"
http://blog.dlib.net/2014/08/real-time-face-pose-estimation.html
http://www.csc.kth.se/~vahidk/face_ert.html

http://www.ics.uci.edu/~xzhu/face/
https://github.com/TadasBaltrusaitis/CLM-framework


https://github.com/yulequan/face-alignment-in-3000fps
https://github.com/jwyang/face-alignment
https://github.com/jwyang/face-alignment-cpp

https://github.com/AndrejMaris/facefit

Joint Cascade Face Detection and Alignment
https://github.com/luoyetx/JDA

https://github.com/donghoonlee04/cGPRT

https://github.com/ChrisYang/RCPR

https://github.com/TadasBaltrusaitis/OpenFace

Supervised Descent Method (SDM) for Face Alignment
https://github.com/tntrung/impSDM
https://github.com/patrikhuber/superviseddescent

Not sure 
https://github.com/elador/FeatureDetection
https://github.com/t0nyren/kbdetect
https://github.com/YuvalNirkin/find_face_landmarks

Mobile:
https://github.com/gicheonkang/Fast-Face


Deep learning:
http://mmlab.ie.cuhk.edu.hk/projects/TCDCN.html
http://mmlab.ie.cuhk.edu.hk/archive/CNN_FacePoint.htm
https://github.com/zhzhanp/TCDCN-face-alignment
https://github.com/RiweiChen/DeepFace
https://github.com/OAID/mtcnn
Theano
https://github.com/SinaHonari/RCN
https://github.com/cowpig/deep_keypoints
https://github.com/MarekKowalski/DeepAlignmentNetwork
Caffe
https://github.com/ralpguler/DenseReg
https://github.com/kuangliu/pycaffe-mtcnn
https://github.com/ishay2b/VanillaCNN (http://www.openu.ac.il/home/hassner/projects/tcnn_landmarks/)
https://github.com/luoyetx/deep-landmark
https://github.com/qiexing/caffe-regression
https://github.com/pminmin/caffe_landmark
https://github.com/feixuan090803/CNN-Face-Point-Detection
https://github.com/qiexing/face-landmark-localization
https://github.com/kpzhang93/MTCNN_face_detection_alignment
https://github.com/ZhiwenShao/Dense-Landmark-Detection
https://github.com/xipeng13/recurrent-face-alignment
https://github.com/blankWorld/MTCNN-Accelerate-Onet
https://github.com/lsy17096535/face-landmark
https://github.com/BobLiu20/FacialLandmark_Caffe
https://github.com/CongWeilin/mtcnn-caffe
https://github.com/wywu/LAB
TensorFlow
https://github.com/trigeorgis/mdm
https://github.com/flyingzhao/tfTCDCN
https://github.com/fengju514/Face-Pose-Net
https://github.com/AITTSMD/MTCNN-Tensorflow
https://github.com/YadiraF/PRNet
https://github.com/yinguobing/cnn-facial-landmark
https://github.com/610265158/face_landmark
https://github.com/papulke/face-of-art
https://github.com/TheSouthFrog/stylealign
https://github.com/guoqiangqi/PFLD
Chainer
https://github.com/takiyu/hyperface
Torch
https://github.com/1adrianb/binary-face-alignment
https://github.com/1adrianb/2D-and-3D-face-alignment
https://github.com/TencentYoutuResearch/FaceAlignment-FHR
MXNet
https://kpzhang93.github.io/MTCNN_face_detection_alignment/
https://github.com/pangyupo/mxnet_mtcnn_face_detection
https://github.com/Seanlinx/mtcnn
PyTorch
https://github.com/1adrianb/face-alignment
https://github.com/D-X-Y/SAN
https://github.com/oawiles/FAb-Net
https://github.com/nicehuster/cpm-facial-landmarks
https://github.com/victimsnino/pose-simple-baselines-demo.pytorch
https://github.com/FunkyKoki/Look_At_Boundary_PyTorch
https://github.com/D-X-Y/landmark-detection
https://github.com/HRNet/HRNet-Facial-Landmark-Detection
https://github.com/protossw512/AdaptiveWingLoss
https://github.com/ideask/A-Practical-Facial-Landmark-Detector
https://github.com/justusschock/shapenet
https://github.com/LeiJiangJNU/DAMDNet
https://github.com/LeiJiangJNU/R3FA
https://github.com/polarisZhao/PFLD-pytorch
https://github.com/tomguluson92/PRNet_PyTorch
https://github.com/ElvishElvis/68-Retinaface-Pytorch-version
MatConvNet
https://github.com/FengZhenhua/Wing-Loss


Tracker
https://github.com/cheind/dest

FANN:
https://github.com/olddocks/facialkeypoints

Javascript:
https://github.com/auduno/clmtrackr

Seems to be commercialized, closed source and not publicly available to download, not worth considering it:
http://www.humansensing.cs.cmu.edu/intraface/

Too simple algorithm, not worth considering it:
https://github.com/sdcoca/facex
~~~

Other(blog posts, SO, etc.):
~~~
http://www.researchgate.net/post/Which_facial_landmark_detection_tracking_software_is_publically_available_for_research
http://www.learnopencv.com/facial-landmark-detection/
~~~

TO LOOK AT:
~~~
https://github.com/luoyetx/face-alignment-presentation
~~~

Facial points datasets:

Name| N images| N points |N individuals | Lighting | Age | Race| $ | Auth.
------------------ | --- | --- | --- | --- | --- | --- | --- | ---
[MUCT](http://www.milbo.org/muct/)|3755|76|624|yes|yes|yes|no|no

~~~
http://www.milbo.org/muct/other-databases.html
[LFPW](http://neerajkumar.org/databases/lfpw/)|1432|29|
[HELEN](http://www.ifp.illinois.edu/~vuongle2/helen/)|2330|192
[AFW](https://www.ics.uci.edu/~xzhu/face/ http://www.cs.cmu.edu/~deva/papers/face/index.html)|?|?
[AFLW](https://www.tugraz.at/institute/icg/research/team-bischof/lrs/downloads/aflw/)|?|?
[IBUG]()|?|68 (http://ibug.doc.ic.ac.uk/resources/300-W/)
[XM2VTS](http://www.ee.surrey.ac.uk/CVSSP/xm2vtsdb/)|?|?
[ATVS](http://atvs.ii.uam.es/atvs/scfacedb_landmarks.html)|?|?|yes
[CACD](http://bcsiriuschen.github.io/CARC/)
[MUG](http://mug.ee.auth.gr/fed/)
[UMDFace](http://umdfaces.io/)
[WFLW](https://wywu.github.io/projects/LAB/WFLW.html)
[COFW](http://www.vision.caltech.edu/xpburgos/ICCV13/)
[Robust-FEC-CNN](https://github.com/LynnHo/Facial-Landmarks-of-Face-Datasets)
~~~

Landmark annotation tools:
~~~
https://github.com/menpo/menpo http://www.menpo.org
https://github.com/menpo/landmarker.io
https://github.com/luigivieira/Facial-Landmarks-Annotation-Tool
https://github.com/NaturalIntelligence/imglab
~~~

Pose estimation related:
~~~
https://github.com/wangzheallen/awesome-human-pose-estimation
https://github.com/CMU-Perceptual-Computing-Lab/openpose
https://github.com/shihenw/convolutional-pose-machines-release
https://github.com/1adrianb/binary-human-pose-estimation
https://github.com/bearpaw/PyraNet
https://github.com/eldar/deepcut-cnn
https://github.com/michalfaber/keras_Realtime_Multi-Person_Pose_Estimation
https://github.com/bazilas/matconvnet-deepReg
https://github.com/shihenw/convolutional-pose-machines-release
https://github.com/DavexPro/pytorch-pose-estimation
https://github.com/MVIG-SJTU/AlphaPose
https://github.com/eldar/pose-tensorflow
https://adrianbulat.com/human-pose-estimation
https://github.com/AlexEMG/DeepLabCut
https://github.com/edvardHua/PoseEstimationForMobile
https://github.com/facebookresearch/DetectAndTrack
https://github.com/tensorboy/pytorch_Realtime_Multi-Person_Pose_Estimation/
https://github.com/tucan9389/PoseEstimation-CoreML
https://github.com/cbsudux/awesome-human-pose-estimation
https://github.com/Daniil-Osokin/lightweight-human-pose-estimation.pytorch
https://github.com/liuziwei7/fashion-landmarks
https://github.com/vita-epfl/openpifpaf [PyTorch]
https://github.com/microsoft/human-pose-estimation.pytorch [PyTorch]
https://github.com/leoxiaobin/deep-high-resolution-net.pytorch [PyTorch]
~~~

Papers:
~~~
"A comparative study of face landmarking techniques"
http://www.busim.ee.boun.edu.tr/~sankur/SankurFolder/Jour_JIVP_Landmarking.pdf
"Supervised Descent Method and its Applications to Face Alignment"
http://www.ri.cmu.edu/pub_files/2013/5/main.pdf
"Deep Convolutional Network Cascade for Facial Point Detection"
http://mmlab.ie.cuhk.edu.hk/archive/CNN/data/CNN_FacePoint.pdf
"One Millisecond Face Alignment with an Ensemble of Regression Trees" by Vahid Kazemi and Josephine Sullivan, CVPR 2014
http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Kazemi_One_Millisecond_Face_2014_CVPR_paper.pdf
~~~

Other cool benchmarks:
~~~
https://github.com/soumith/convnet-benchmarks
https://github.com/ducha-aiki/caffenet-benchmark
https://github.com/DeepMark/deepmark
https://github.com/erikbern/ann-benchmarks
https://github.com/andrewssobral/bgslibrary
https://github.com/gnebehay/VOTR
https://bitbucket.org/rodrigob/doppia
https://github.com/foolwood/benchmark_results
https://github.com/davidstutz/superpixel-benchmark
~~~
