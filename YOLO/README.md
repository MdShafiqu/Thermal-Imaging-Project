<details open>
<summary>Install</summary>

Clone repo and install [requirements.txt](https://github.com/ultralytics/yolov5/blob/master/requirements.txt) in a
[**Python>=3.7.0**](https://www.python.org/) environment, including
[**PyTorch>=1.7**](https://pytorch.org/get-started/locally/).

```bash
git clone or download
cd YOLO
pip install -r requirements.txt  # install

Download dataset https://gla-my.sharepoint.com/:u:/g/personal/mdshafiqul_islam_glasgow_ac_uk/EX5c6qu2sK5BtT7yT57-qJgBrpH8KiaOh-bU12EJpO1Vtw?e=zv8aDT

Dowlond best weight: https://gla-my.sharepoint.com/:u:/g/personal/mdshafiqul_islam_glasgow_ac_uk/EaUI4QI1hvtFjAER4pQ8HXsBG4pzW403xbJ7f4zrmTkluA?e=ss3uYG

python train.py  --epochs 100 --batch-size 16 --data data.yaml --weights '' --cfg yolov5s.yaml --workers 0

python detect.py --weights C:/Users/shafi/YOLO/runs/train/exp/weights/best.pt --img 416 --conf 0.6 --source C:/Users/shafi/YOLO/test/images/1. #from image
  
python obfuscate.py --weights C:/Users/shafi/YOLO/runs/train/exp/weights/best.pt --img 416 --conf 0.5 --source C:/Users/shafi/YOLO/test/video/2.avi # from video

python obfuscate.py --weights C:/Users/shafi/YOLO/runs/train/exp/weights/best.pt --img 416 --conf 0.5 --source 0 #real-time from camera
  


```

</details>






https://user-images.githubusercontent.com/22468194/182390119-9202d81a-ac3e-40dd-83c0-727d1ea548fb.mp4

