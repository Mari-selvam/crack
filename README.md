# Steps to detect wall crack on live cam.

Step: 1
git clone https://github.com/Mari-selvam/crack.git

Step: 2
cd crack

Step: 3
wget "" -o crack.pt

Step: 4
git clone https://github.com/WongKinYiu/yolov7

Step: 5
cd yolov7

Step: 6
pip install -r requirements.txt

Step: 7
cd ..

# detect the video

Step: 8
python yolov7/detect.py --weights crack.pt --conf 0.1 --source Wall_Crack .mp4

=> output ('runs/train/exp/output.mp4')

# using Live webcam

Step: 9
python yolov7/detect.py --weights crack.pt --conf 0.1 --source 0
