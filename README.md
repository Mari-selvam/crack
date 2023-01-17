# Steps to detect wall crack on live cam.

git clone https://github.com/Mari-selvam/crack.git

cd crack

git clone https://github.com/WongKinYiu/yolov7


cd yolov7


pip install -r requirements.txt

cd ..

# detect the video

python yolov7/detect.py --weights crack.pt --conf 0.1 --source Wall_Crack .mp4

# output ('runs/train/exp/output.mp4')

# using Live webcam

python yolov7/detect.py --weights crack.pt --conf 0.1 --source 0
