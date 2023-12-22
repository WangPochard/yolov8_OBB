"# yolov8_OBB" 
---

### Yolo Enviroment setting
conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia  

pip install ultralytics --no-deps  


---
### Paddle OCR  
The OCR labeling data is programmed in C Sharp.  
I utilize RotateRect to detect the *MESSAGE* in image data and save it.  
Paddle OCR takes some time to recognize the *WORD*.  
I aim to reduce time costs.  
And I have achieved it.  
This model excels in identifying patterns and features within this particular case by Python.  
