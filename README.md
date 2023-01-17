# crack
# First install the python

gitclone 

cd crack

git clone https://github.com/WongKinYiu/yolov7


cd yolov7


pip install -r requirements.txt

cd ..

python yolov7/detect.py --weights best.pt --conf 0.1 --source Wall Crack .mp4

python yolov7/detect.py --weights best.pt --conf 0.1 --source 0
