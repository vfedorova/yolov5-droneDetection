# yolov5-droneDetection
Implementation of Yolov5 Object detection Model: https://github.com/ultralytics/yolov5

on custom dataset with drone images, dataset created with roboflow, 

full description is here: https://blog.roboflow.com/how-to-train-yolov5-on-a-custom-dataset/.




Model1 is trained with 100 epochs about 3 hours on Google Colab GPU with follow hyperparameters (runs/train/exp/weights/best1.pt): 

!python train.py --img 416 --batch 16 --epochs 100 --data {dataset.location}/data.yaml --weights yolov5s.pt --cache



Model2 is trained with 10 epochs on Colab GPU (runs/train/exp/weights/best.pt):

!python train.py --img 416 --batch 16 --epochs 10 --data {dataset.location}/data.yaml --weights yolov5s.pt --cache




